Real-Time Chat System with Upvote Mechanism

A real-time chat application built with Node.js and raw WebSockets, featuring an admin-controlled room system, message upvoting, and an intelligent message escalation flow.

📌 Key Features
 Admin Controls

Create new chat rooms.
Configure:
room_name: Custom title for the chat session.
start_time: Timestamp marking when chat begins.
is_open: Boolean flag to control if users can join.
cool_down_time: Optional pause between messages.
 User Interaction

Join an available chat room.
Send real-time messages via WebSocket.
React to messages by upvoting.
🔺 Message Upvote System

If a message gets 3+ upvotes, it is highlighted or moved to a separate "Popular" section.
If a message hits 10+ upvotes, it triggers a real-time alert to the admin for immediate attention.



Project Structure :-

 real-time-chat-app/
├── 📦 public/              # HTML/JS frontend
│   └── index.html
├── 📦 server/
│   └── app.js              # WebSocket & server logic
├── 📄 README.md            # You're reading it!
├── 📄 package.json
└── 📄 .env                 # Configs (if needed)

