## HTTP Messages
    - Start Line
    - Headers
    -Entity Body

### Methods
- GET
- POST
- PUT
- DELETE
- OPTIONS
- TRACE
- HEAD

### Status Codes
- 100-199: Informational
- 200-299: Success
- 300-399: Redirection
- 400-499: Client Error
- 500-599: Server Error

### Headers
#### General
    1. Connection
    2. Date
    3. MIME-Version
    4. Trailer
    5. Transfer-Encoding
    6. Upgrade
    7. Via
    8. Cache-Control
    9. Pragma

#### Request
##### Request Informational Headers
    1. Client-Ip
    2. From
    3. Host
    4. Referer
    5. UA-Color
    6. UA-Cpu
    7. UA-Disp
    8. UA-Os
    9. UA-Pixels
    10. User-Agent

##### Accept Headers
    11. Accept
    12. Accept-Charset
    13. Accept-Encoding
    14. Accept-Language
    15. TE

##### Conditional request headers
    16. Expect 
    17. If-Match 
    18. If-Modified-Since 
    19. If-None-Match 
    20. If-Range 
    21. If-Unmodified-Since 
    
##### Request Security Headers
    22. Authorization
    23. Cookie
    24. Cookie2

##### Proxy Request Headers
    25. Max-Forwards
    26. Proxy-Authorization
    27. Proxy-Connection

#### Response
##### Response informational headers
    1. Age
    2. Public
    3. Retry-After
    4. Server
    5. Title
    6. Warning

##### Negotiation Headers
    1. Accept-Ranges
    2. Vary

##### Response Security Headers
    1. Proxy-Authenticate
    2. Set-Cookie
    3. Set-Cookie2
    4. WWW-Authenticate

#### Entity

##### Entity informational headers
    1. Allow
    2. Location

##### Content headers
    1. Content-Base
    2. Content-Encoding
    3. Content-Language
    4. Content-Length
    5. Content-Location
    6. Content-MD5
    7. Content-Range
    8. Content-Type

##### Entity caching headers
    1. ETag
    2. Expires
    3. Last-Modified
