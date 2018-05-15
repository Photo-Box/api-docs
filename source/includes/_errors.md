# Errors

PhotoBox uses the following error codes:

Error Code | Meaning
---------- | -------
400 | Bad Request -- Your request is invalid.
401 | Unauthorized -- Your API key is wrong.
403 | Forbidden -- You don't have permission to use this endpoint.
404 | Not Found -- The specified resource could not be found.
500 | Internal Server Error -- We had a problem with our server. Try again later.
503 | Service Unavailable -- We're temporarily offline for maintenance. Please try again later.

## Error Types
Error Type | Status Code | Meaning
---------- | ----------- | -------
1 | 401 - Unauthorized | Bad Auth -- Invalid Authentication.
2 | 401 - Unauthorized | Bad Perms -- You are missing permissions to use the endpoint.
3 | 400 - Bad Request | Invalid Schema -- The POST body is formatted wrong.
4 | 400 - Bad Request | Invalid File Type -- A resource you gave responded with the wrong type of content.
5 | 400 - Bad Request | Resource Error -- A resource you gave has errored.
1000 | 400 - Bad Request | Invalid Body -- The POST body is formatted wrong.
1001 | 500 - Internal Server Error | Image Process Error -- The image process has errored while processing the request.