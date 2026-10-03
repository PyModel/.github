# Apple signing

Shared Developer ID signing setup for PyModel macOS apps. The five secrets are
PyModel organization secrets (private repositories on the Free plan need their
own copies with the same names).

```yaml
- uses: PyModel/.github/apple-signing@<commit sha>
  with:
    certificate-p12: ${{ secrets.MAC_CSC_LINK }}
    certificate-password: ${{ secrets.MAC_CSC_KEY_PASSWORD }}
    api-key-p8: ${{ secrets.APPLE_API_KEY_P8 }}
    api-key-id: ${{ secrets.APPLE_API_KEY_ID }}
    api-issuer: ${{ secrets.APPLE_API_ISSUER }}
```

Then sign with `codesign --sign "$CODE_SIGN_IDENTITY" --options runtime --timestamp`
and notarize with `xcrun notarytool submit --key "$APPLE_API_KEY" --key-id
"$APPLE_API_KEY_ID" --issuer "$APPLE_API_ISSUER" --wait`. Each app keeps its own
bundle ID (`com.pymodel.<app>`).
