# Authentication

<aside class="notice">
The examples below will use the key <code>123456abcxyz</code>.
When using these examples please replace them before using.
</aside>

The value of the `Authorization` header would look like this `123456abcxyz`

All endpoints will use this base for all requests:
`api.photobox.pw/v1/`

```shell
# With shell, you can just pass the correct header with each request
curl "api_endpoint_here"
  -H "Authorization: 123456abcxyz"
```