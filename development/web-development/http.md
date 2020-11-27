---
description: HTTP - (Hypertext Transfer Protocol)
---

# HTTP

## Request

The request is a message 



## Methods

`GET`- Browser caches GET-requests

## HTTP/1.0

### Request

#### Request line

```text
# Method  Query string  Protocol version
HEAD / HTTP/1.0
```

#### Headers

```text
# key:value
User-Agent: Google Chrome
```

### Response

#### Status line

```text
# Protocol version  Status code  Message
HTTP/1.0 200 OK
```

#### Headers

```text
#key:value
Date: Sat, 18 Jan 2020 09:24:50 GMT
# Custom headers begins with the letter "X"
X-XSS-Protection: 0
```

## HTTP/1.1

This version extends HTTP/1.0 and adds **virtual hosts** and **keep-alive**.

## Request

```text
# Protocol version  Status code  Message
HTTP/1.0 200 OK
# Host which should be returned
host: google.com
```

