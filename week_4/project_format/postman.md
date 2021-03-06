### Using Postman
To begin using Postman go to their website (https://app.getpostman.com), sign up for an account, and then download an application from the dashboard. It is available as a chrome app but I prefer the Mac app.

For each request you need to choose a method from the method select on the left of them main section of postman.  Then key in the URL showing the path of your api.  
+ If you have params you can add the name of the param to the path (localhost:3000/snakes/:id) and then click on the Params button to enter the key value pair.
+ If you are posting you will probably need to enter 'Content-Type' as a header key and 'application/json' as the value when using the body-parser middleware.
+ When posting I enter the data as "raw" "text" in and then just key in a json object in the body area.
+ You can also click on import and go to the 'Past raw text' area and key in a curl statement and then Postman will fill out its form.

There are pictures below.

#### GET  
![GET](images/postman-get.png)

#### POST
![POST](images/postman-post.png)

#### showing raw json

![GET](images/postman-post-raw-json.png)

#### showing header content type
![GET](images/postman-post-header-content-type.png)

#### showing the use of params
![GET](images/postman-using-params.png)

#### showing the use of importing curl
![GET](images/postman-import-curl.png)
