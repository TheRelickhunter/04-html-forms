<div style="border:solid;padding:10px;">
<span style="float:left;border:solid 1px;">Author: Andrea Zappa </span>
<span style="border:solid 1px;float:right;">
Exercise 04-html-forms
</span><br>
</div>

In this exercise demonstrate how the forms works.
We can say that forms gives the user all the tools to interact with the webpage and the other side, the server which implements the logic to elaborate information. So that enable the user to input and collect information using controls like textboxes, checkboxes, selections and so on and send the data to the server.

What we are gonna see here is a simple form which simulate a contest where there's candidates which are choosen after collecting data from users.

---
### ```<form>```
this is the pillar element that constitute the form
> ```<form action="" method="post">```

<p>Inside this element controls can be added like textboxes, checkboxes, selections etc so that will be rendered properly on screen. </p>

- ```action``` this attribute refers to the endpoint where data will be sended and processed, like server-side scripts included in dynamic web pages, or services trough the web.
- ```method``` indicate the mode by which data would be sended
> ```method="POST"```

data will be enclosed into the body of the request.
- More secure than GET; information is never visible in the URL query string or in the server logs
- Has a much larger limit on the amount of data that can be sent
- Can send text data as well as binary data (uploading a file)
- Not possible to bookmark the page with the query

> ```method="GET"```

- Data sent by the GET method is displayed in the URL
- It is possible to bookmark the page with specific query string values
- Not suitable for passing sensitive information such as the username and password
- The length of the URL is limited
  
