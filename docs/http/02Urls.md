## URLs and Resources

    Apps uses URLs to easy access

### URL Syntax
    {{scheme}}://{{user}}:{{password}}@{{host}}:{{port}}/{{path}};{{params}}?{{query}}#{{frag}}

    - scheme: Protocol to be used [http, ftp, rstp, ...]
    - user: username [ optional, in some cases will required to access a resource]
    - password: password [ optional, in some cases required to access a resource. used after username and separated by a colon ':']
    - host: hostname or dotted ip of the server
    - port: Port number in wich server is listening. [optional, Default: 80]
    - path: Local name for resource in server
    - params: Name/Value pairs used in some schemes to input parameters. [optional, separated from the rest of url by semicolons ';' ]
    - query: used in some schemes to pass parameters to an application. [optional, separated from the rest of url by '?' ]
    - frag: Name for a piece or part of resource. [optional, is not passed to the server, is used internally in client. Separated by the '#' ]