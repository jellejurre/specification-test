# deleteFileVersion

## Request
`delete https://vrchat.com/api/1/file/undefined/1`

| Header | Value |
| ------ | ----- |
| user-agent | `specification-test/@<unstable> https://github.com/vrchatapi/specification-test/issues/new` |
| cookie | `auth=<redacted>; twoFactorAuth=<redacted>` |


## Response
`404 Not Found`

| Header | Value |
| ------ | ----- |
| access-control-allow-credentials | `true` |
| cache-control | `private, no-cache` |
| connection | `keep-alive` |
| content-type | `application/json; charset=utf-8` |
| pragma | `no-cache` |
| server | `cloudflare` |
| transfer-encoding | `chunked` |
| vary | `Authorization, Accept-Encoding` |
| x-frame-options | `deny` |

```jsonc
{
  /**
   * Unexpected property.
   *
   * @schema File
   * @keyword additionalProperties
   *
   * #/additionalProperties
   * #/error
   */
  "error": {
    "message": "File not found",
    "status_code": 404
  }
}
```
