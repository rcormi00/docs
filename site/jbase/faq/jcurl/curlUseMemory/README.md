# curlUseMemory

<PageHeader />

This function is typically used to reset the ***curlHandle*** if [curlUseFile](./../curlUseFile#heading) was previously used.

## Syntax

***result_code*** = **curlUseMemory**(***curlHandle***)

where:

| Variable | Type | Description |
|--|--|--|
***result_code*** | integer | result code
***curlHandle*** | var | a [jCURL](./../README.md) handle generated by [curlInit](./../curlinit/README.md)

## Example

```
INCLUDE JBCCURL.h
rc = curlInit(curlHandle)

... perform curl operations with curlHandle

rc = curlUseMemory(curlHandle)
rc = curlExec(curlHandle, result, headers)
...
```

Click here [$ftp class](../jftp/ftpclass-jabba/README.md) for a practical use of curlUseMemory.

see also [curlUseVar](./../curlUseVar/README.md) and [curlUseFile](./../curlUseFile/README.md)

Back to [jCurl.](./../README.md)

<PageFooter />