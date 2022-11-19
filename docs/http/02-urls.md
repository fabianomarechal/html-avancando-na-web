## URLs and Resources

Apps uses URLs to easy access

### URL Syntax
{scheme}://{user}:{password}@{host}:{port}/{path};{params}?{query}#{frag}

    - scheme: Protocol to be used. Case Insensitive. [http, ftp, rstp, smtp, ...]
    - user: username [ optional, in some cases will required to access a resource]
    - password: password [ optional, in some cases required to access a resource. used after username and separated by a colon ':']
    - host: hostname or dotted ip of the server
    - port: Port number in wich server is listening. [optional, Default: 80]
    - path: Local name for resource in server
    - params: Name/Value pairs used in some schemes to input parameters. [optional, separated from the rest of url by semicolons ';' ]
    - query: used in some schemes to pass parameters to an application. [optional, separated from the rest of url by '?' ]
    - frag: Name for a piece or part of resource. [optional, is not passed to the server, is used internally in client. Separated by the '#' ]

### Shady Characters
URLs needs to be portable. Uniform names to be transfered across diferent protocols. Ex: smtp strips * character, invisible characters as spaces could to be confused to humans. Because this, URLs names use **_safe characters_**

By the way in some cases users needs transmit binary character in URLs. Because this URLs uses **_character escape_** to encode unsafe characters.

### Character Restrictions

[ Reserved characters ](https://en.wikipedia.org/wiki/Percent-encoding#Reserved_characters)

    - % escape for encoded characters
    - / delimiting path segments
    - . path component
    - .. path component
    - \# fragment delimiter
    - ? query-string delimiter
    - ; params delimiter
    - : delimit the scheme, user/password, and host/port
    - $ , +
    - @ & = special meaning in some schemes
    - { } | \ ^ ~ [ ] ‘ unsafe handling by various transport agents
    - < > " Unsafe
    - 0x00–0x1F, 0x7F characters within these hex ranges fall within the nonprintable section of the US-ASCII set
    - \> 0x7F characters whose hex values fall

### Another interesting things
[Purl - Persistent Uniform resource locators](https://purl.archive.org/help)