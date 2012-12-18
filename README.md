movie-search-application
========================

a simple ajax movie search application. Once you type in a movie name, it gonna hack imdb.com and find the results back,then users can see the movies and share them on facebook. Cause imdb.com is not allowed to usage of their images by other guy, so you may install Disable Http referer in other to show the images correctly. 

Once the user click the button, a java servlet gonna receive the request and send it to a Apache server. the server will use perl regex to get the first 5 results from imdb.com and send them back using json. After the java servlet get the results, it also send the json format results back to client. The jQuery code is responsible for showing the json info in a proper way. Then users can view the search results, and share a movie on facebook.

This is a homework of CSCI571 web technology.
