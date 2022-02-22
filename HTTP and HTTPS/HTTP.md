Familiarize myself with HTTP (2/16/22)
    -Notes-
                    METHODS
        GET - Retrieves data from the server
        POST - Submits data to the server
        PUT - Update data already on the server
        DELETE - Deletes data from the server

        Headers convey messages to and from the server. 
        -----------------------------------------------
        REQUEST ----
            Method: GET - Path: / - Protocol: HTTP/1.1
        Headers ----
        i.e. - Host: developer.mozilla.org
                Accept-Language: fr
        RESPONSE ----
            Protocol: HTTP/1.1 Status Code : 200 (good) status message : OK (functioning properly)
        Headers ----
            Server: Apache
            Last-Modified: Tues, 01 Dec 2009 20:13:00 GMT
            Content-Length: 29769
            Content-Type: text/html
        -----------------------------------------------
    HTTP is stateless but cookies and sessions help provide state.


Mozilla Reference Reading
    https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview


Helpful Videos
    -->Traversy Media HTTP Crash Course (In Javascript)
    https://www.youtube.com/watch?v=iYM2zFP3Zn0&t=1904s
    -->What is HTTP
    https://www.youtube.com/watch?v=SzSXHv8RKdM&t=425s