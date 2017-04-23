
# WHAT IS IT:

This project is made using Java based GUI and facebook restFB API to enable the user to post any facebook posts through the GUI
application and retrieve and delete the posts posted by the user using the post ID.


# RestFB API:


Restfb is an open source software .It's a facebook API that provides the programmer to get access to facebook website through accessTokens and by using that the user can perform different publish actions like posting , uploading,updating ,deleting etc.

# NOTE :

1.To get the access token go to https://developers.facebook.com/ and create your own app. Go to tools&supports->GraphAPIExplorer->Get Token->Get user access Token -> check all ->get access Token .Then copy the accessToken and now you have it and can use in the Application. 


2.After downloading and opening the project in NetBeans(you can use another one as well) , go to Libraries ,right click on Libraries, Click Add JAR/Folder , go to the directory where you have downloaded the project and look for jar file of restfb (e.g restfb-2.0.0-rc.2) and open it. Then restfb will be added to your libraries and you can use it.


# REFERENCES :


https://developers.facebook.com/

http://restfb.com/


# Problems (May Be Faced):

1.Use of RestFb allows the user to delete only those posts which were posted from the app.

2.The access Token may get expired after some instance of time . So you may have to regenerate accessToken whenever you run it. 
