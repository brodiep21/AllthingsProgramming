REST API /Learn API's better 2/17/22
    -Notes-
    -------------------------------------------
    # GET /users/defunkt
    $ curl https://api.github.com/users/defunkt
    -------------------------------------------
    $ curl -i https://api.github.com/users/defunkt THE -i FLAG includes the headers which includes content type, in this case application/json. i.e. 
    ---->
    {
        "login": "defunkt",   
        "id": 2,
        "node_id": "MDQ6VXNlcjI=",
        "avatar_url": "https://avatars.githubusercontent.com/u/2?v=4",
        "gravatar_id": "",
        "url": "https://api.github.com/users/defunkt",
        "html_url": "https://github.com/defunkt",
    }
 
 Any headers beginning with x- are customer headers, and are not included in the HTTP spec. For Example ->
    X-GitHub-Media-Type has a value of github.v3. This lets us know the media type for the response.Media types have helped us version our output in API v3

                        POSTMAN
Learn what you want to do, before you push it into code.              


    HTTP Methods
        Create ----> Post
        Read ----> Get
        Update ----> Put    
        Delete ----> Delete
Reading and Help
    Github Docs on Rest API -->
    https://docs.github.com/en/rest  

Videos
    IBM Cloud Rest API explanation
    https://www.youtube.com/watch?v=lsMQRaeKNDk
