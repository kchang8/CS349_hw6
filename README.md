# CS349_hw6

In this assignment, you will start a new application, Chattrbox, and work with Node.js to build a
custom back-end. Complete the following:
1. Work through Chapter 15 (Introduction to Node.js) to set up the chattrbox/ directory and
create index.js.
2. Complete the Bronze Challenge: Creating a Custom Error Page from Chapter 15. Load the
page from app/error.html, and include the appropriate image from https://http.cat/.
3. Complete the Silver Challenge: Providing a MIME Type Dynamically from Chapter 15.
When you push this this homework assignment to GitHub, include the files you tested in your
app/ subdirectory.
4. Work through Chapter 16 (Real-Time Communication with WebSockets) to create
websockets-server.js, install wscat, and test the results.
5. Add a /topic command to the chat server to track what users are discussing in the chat. If
any user types a string like this: \
 ```/topic Chatting about WebSockets``` \
All connected users should receive this string: \
```*** Topic has changed to 'Chatting about WebSockets'``` \
Users who are not connected should not see this message (i.e., the /topic command should
not be saved in the array of previous messages to be sent to each user.)
Instead, the first message that newly connected users should receive is the current topic: \
```*** Topic is 'Chatting about WebSockets'``` \
Newly connected users should then receive all the previous messages.
6. Push the contents of your project to a new GitHub repository using a git client (e.g., the git
command-line client, GitHub desktop. Do not submit files using drag-and- drop onto the
repository web page, and do not push this assignment to the same repository as your previous
homework assignments. 
