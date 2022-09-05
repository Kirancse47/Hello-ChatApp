<h1>Hello! - ChatApp</h1>
<ul>
<li>It's a Realtime Chatting Application that provides an interface for multiple user chatting at the same time.</li>
<li>FrontEnd Technologies- HTML, CSS</li>
<li>BackEnd Technologies- JavaScript, Node.js</li>
<li>Used Socket.io module for a two-way connection between client and server.</li>
<li>FrontEnd includes a navigation bar, Chat window and a form submit button for sending the messages.</li>
<li>First of all stored all the DOM elements in a respectives JS variable.</li>
<li>Used Audio file (tone.mp3) which gives notification on receiving the messages.</li>
<li>Everytime a new user tries to join, first of all ask his/her name and let the server know.</li>
<li>If a new user joins, receive the event from the server using eventListner.</li>
<li>Receive message from server using receive function.</li>
<li>If a user leaves the chat, tell all the other users that this user has left the chat.</li>
<li>Server Side JavaScript will handle the Socket IO connections.</li>
<li>If a new user joins, let the other users connected with server know.</li>
<li>If someone sends the message, broadcast it to other people.</li>
<li>If someone leaves the chat, let others know.</li>
</ul>

# Process to run the app
<ol>
  <li> run <b>nodemon nodeserver/index.js</b>
  <li> Right click anywhere in the file <b>index.html</b> and from the menu that appears select <b> Open with Live server </b>
  <li> A instance of the application will appear in the browser. 
  <li> Copy the url from the address bar and open another instance in another tab or in incognito or on another browser.
</ol>

# Client 1: Kiran
![Screenshot (19)](https://user-images.githubusercontent.com/54286695/188331252-a4deee35-ea86-4949-9f87-069677e70eee.png)

# Client 2: Raja
![Screenshot (18)](https://user-images.githubusercontent.com/54286695/188331259-3422e502-eaeb-492d-a386-043fd873eace.png)
