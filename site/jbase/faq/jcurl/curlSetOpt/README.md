# curlSetOpt

<PageHeader />

Set a specific libcurl option for the current ***curlHandle***.

## Syntax

***result_code*** = **curlSetOpt**(***curlHandle***, ***option***, ***param***)

where:

| Variable | Type | Description |
|--|--|--|
***result_code*** | integer | result code
***curlHandle*** | var | a [jCURL](./../README.md) handle generated by [curlInit](./../curlInit/README.md)
***option*** | integer | ***libcurl*** option
***param*** | string | value to set option

## Example

```
INCLUDE JBCCURL.h
rc = curlInit(curlHandle)
rc = curlSetOpt(curlHandle, CURLOPT_TIMEOUT, 5)
IF rc EQ CURLE_OK THEN
    errors = curlLastError(curlHandle)
END
```

Click here [$ftp class](../#ftpclass-jabba) for a practical use of curlSetOpt.

The available options is driven by [libcurl](https://curl.haxx.se/libcurl/c/curl_easy_setopt.html).

The following are equated in JBCCURL.h

|Option Name|Actual Value|
|--|--|
|CURLOPT_FILE|10001|
|CURLOPT_URL|10002|
|CURLOPT_PORT|00003|
|CURLOPT_PROXY|10004|
|CURLOPT_USERPWD|10005|
|CURLOPT_PROXYUSERPWD|10006|
|CURLOPT_RANGE|10007|
|CURLOPT_INFILE|10009|
|CURLOPT_ERRORBUFFER|10010|
|CURLOPT_WRITEFUNCTION|20011|
|CURLOPT_READFUNCTION|20012|
|CURLOPT_TIMEOUT|00013|
|CURLOPT_INFILESIZE|00014|
|CURLOPT_POSTFIELDS|10015|
|CURLOPT_REFERER|10016|
|CURLOPT_FTPPORT|10017|
|CURLOPT_USERAGENT|10018|
|CURLOPT_LOW_SPEED_LIMIT|00019|
|CURLOPT_LOW_SPEED_TIME|00020|
|CURLOPT_RESUME_FROM|00021|
|CURLOPT_COOKIE|10022|
|CURLOPT_HTTPHEADER|10023|
|CURLOPT_HTTPPOST|10024|
|CURLOPT_SSLCERT|10025|
|CURLOPT_SSLCERTPASSWD|10026|
|CURLOPT_SSLKEYPASSWD|10026|
|CURLOPT_CRLF|00027|
|CURLOPT_QUOTE|10028|
|CURLOPT_WRITEHEADER|10029|
|CURLOPT_COOKIEFILE|10031|
|CURLOPT_SSLVERSION|00032|
|CURLOPT_TIMECONDITION|00033|
|CURLOPT_TIMEVALUE|00034|
|CURLOPT_CUSTOMREQUEST|10036|
|CURLOPT_STDERR|10037|
|CURLOPT_POSTQUOTE|10039|
|CURLOPT_WRITEINFO|10040|
|CURLOPT_VERBOSE|00041|
|CURLOPT_HEADER|00042|
|CURLOPT_NOPROGRESS|00043|
|CURLOPT_NOBODY|00044|
|CURLOPT_FAILONERROR|00045|
|CURLOPT_UPLOAD|00046|
|CURLOPT_POST|00047|
|CURLOPT_FTPLISTONLY|00048|
|CURLOPT_FTPAPPEND|00050|
|CURLOPT_NETRC|00051|
|CURLOPT_FOLLOWLOCATION|00052|
|CURLOPT_TRANSFERTEXT|00053|
|CURLOPT_PUT|00054|
|CURLOPT_PROGRESSFUNCTION|20056|
|CURLOPT_PROGRESSDATA|10057|
|CURLOPT_AUTOREFERER|00058|
|CURLOPT_PROXYPORT|00059|
|CURLOPT_POSTFIELDSIZE|00060|
|CURLOPT_HTTPPROXYTUNNEL|00061|
|CURLOPT_INTERFACE|10062|
|CURLOPT_KRB4LEVEL|10063|
|CURLOPT_SSL_VERIFYPEER|00064|
|CURLOPT_CAINFO|10065|
|CURLOPT_MAXREDIRS|00068|
|CURLOPT_FILETIME|00069|
|CURLOPT_TELNETOPTIONS|10070|
|CURLOPT_MAXCONNECTS|00071|
|CURLOPT_CLOSEPOLICY|00072|
|CURLOPT_FRESH_CONNECT|00074|
|CURLOPT_FORBID_REUSE|00075|
|CURLOPT_RANDOM_FILE|10076|
|CURLOPT_EGDSOCKET|10077|
|CURLOPT_CONNECTTIMEOUT|00078|
|CURLOPT_HEADERFUNCTION|20079|
|CURLOPT_HTTPGET|00080|
|CURLOPT_SSL_VERIFYHOST|00081|
|CURLOPT_COOKIEJAR|10082|
|CURLOPT_SSL_CIPHER_LIST|10083|
|CURLOPT_HTTP_VERSION|00084|
|CURLOPT_FTP_USE_EPSV|00085|
|CURLOPT_SSLCERTTYPE|10086|
|CURLOPT_SSLKEY|10087|
|CURLOPT_SSLKEYTYPE|10088|
|CURLOPT_SSLENGINE|10089|
|CURLOPT_SSLENGINE_DEFAULT|00090|
|CURLOPT_DNS_CACHE_TIMEOUT|00092|
|CURLOPT_PREQUOTE|10093|
|CURLOPT_DEBUGFUNCTION|20094|
|CURLOPT_DEBUGDATA|10095|
|CURLOPT_COOKIESESSION|00096|
|CURLOPT_CAPATH|10097|
|CURLOPT_BUFFERSIZE|00098|
|CURLOPT_NOSIGNAL|00099|
|CURLOPT_SHARE|10100|
|CURLOPT_PROXYTYPE|00101|
|CURLOPT_ENCODING|10102|
|CURLOPT_PRIVATE|10103|
|CURLOPT_HTTP200ALIASES|10104|
|CURLOPT_UNRESTRICTED_AUTH|00105|
|CURLOPT_FTP_USE_EPRT|00106|
|CURLOPT_HTTPAUTH|00107|
|CURLOPT_SSL_CTX_FUNCTION|20108|
|CURLOPT_SSL_CTX_DATA|10109|
|CURLOPT_FTP_CREATE_MISSING_DIRS|00110|
|CURLOPT_PROXYAUTH|00111|
|CURLOPT_FTP_RESPONSE_TIMEOUT|00112|
|CURLOPT_IPRESOLVE|00113|
|CURLOPT_MAXFILESIZE|00114|
|CURLOPT_INFILESIZE_LARGE|30115|
|CURLOPT_RESUME_FROM_LARGE|30116|
|CURLOPT_MAXFILESIZE_LARGE|30117|
|CURLOPT_NETRC_FILE|10118|
|CURLOPT_FTP_SSL|00119|
|CURLOPT_POSTFIELDSIZE_LARGE|30120|
|CURLOPT_TCP_NODELAY|00121|
|CURLOPT_SOURCE_USERPWD|10123|
|CURLOPT_SOURCE_PREQUOTE|10127|
|CURLOPT_SOURCE_POSTQUOTE|10128|
|CURLOPT_FTPSSLAUTH|00129|
|CURLOPT_IOCTLFUNCTION|20130|
|CURLOPT_IOCTLDATA|10131|
|CURLOPT_SOURCE_URL|10132|
|CURLOPT_SOURCE_QUOTE|10133|
|CURLOPT_FTP_ACCOUNT|10134|
|CURLOPT_COOKIELIST|10135|
|CURLOPT_IGNORE_CONTENT_LENGTH|00136|
|CURLOPT_FTP_SKIP_PASV_IP|00137|
|CURLOPT_FTP_FILEMETHOD|00138|
|CURLOPT_LOCALPORT|00139|
|CURLOPT_LOCALPORTRANGE|00140|
|CURLOPT_CONNECT_ONLY|00141|
|CURLOPT_CONV_FROM_NETWORK_FUNCTION|20142|
|CURLOPT_CONV_TO_NETWORK_FUNCTION|20143|
|CURLOPT_CONV_FROM_UTF8_FUNCTION|20144|
|CURLOPT_MAX_SEND_SPEED_LARGE|30145|
|CURLOPT_MAX_RECV_SPEED_LARGE|30146|
|CURLOPT_FTP_ALTERNATIVE_TO_USER|10147|
|CURLOPT_CRLFILE|10169|
|CURLOPT_PROTOCOLS|00181|
|CURLOPT_REDIR_PROTOCOLS|00182|
|CURLOPT_GSSAPI_DELEGATION|00210|

Back to [jCurl.](./../README.md)

<PageFooter />