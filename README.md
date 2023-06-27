html
<!DOCTYPE html>
<html>
<head>
 <meta charset="utf-8">
 <title>Chat Website</title>
 <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
 <header>
  <h1>Chat Website</h1>
  <nav>
   <ul>
    <li><a href="#">Home</a></li>
    <li><a href="#">Chat</a></li>
    <li><a href="#">Video Chat</a></li>
    <li><a href="#">About</a></li>
   </ul>
  </nav>
 </header>
 <main>
  <section id="chat">
   <h2>Chat</h2>
   <div id="chat-window">
    <div class="message">
     <div class="from">User 1:</div>
     <div class="message-content">Hello, how are you?</div>
    </div>
    <div class="message">
     <div class="from">User 2:</div>
     <div class="message-content">I'm fine, thanks. How about you?</div>
    </div>
   </div>
   <form id="chat-form">
    <input type="text" id="chat-input" placeholder="Type your message here">
    <buttontype="submit">Send</button>
   </form>
  </section>
  <section id="video-chat">
   <h2>Video Chat</h2>
   <div id="video-chat-window">
    <div id="local-video"></div>
    <div id="remote-video"></div>
   </div>
   <button id="start-call">Start Call</button>
   <button id="end-call">End Call</button>
  </section>
 </main>
 <footer>
  <p>&copy; 2023 Chat Website</p>
 </footer>
 <script src="app.js"></script>
</body>
</html>
