Real Time Chat Application

This is a real time chat app built with react, nodejs and socket.io. This project features a login,register and chat page where you can chat with your contacts. Your contact will be able to see the message that you send in real time without page refresh.

Steps to run the app:

Once you have cloned the app,

```
cd server && npm install
cd ..
cd public && npm install
cd ..
```

To run frontend and backend simultaneously :

```
npm i -g concurrently 
concurrently "cd server && npm start" "cd public && npm start"
```

Login/Register and start chatting!





