**Real-Time Chat Application**

This project is a realtime chat application where users can join chat rooms, exchange messages in realtime, and have a smooth and interactive chat experience. Built with HTML, CSS, SpringBoot, and Java WebSocket.

**Features**

- Join chat rooms and exchange messages in real-time.
- User authentication to choose a unique username before joining a chat roo m.
- Display who sent each message and timestamp each message.
- Create new chat rooms and join existing ones.
- Responsive design to accommodate different screen sizes.

**Prerequisites**

- Java Development Kit (JDK) 8 or higher
- Maven
- JavaScript

**How to Run**

**Backend (SpringBoot)**

1\. **Run the SpringBoot application:**

The backend server will start and run on http://localhost:8080.

**Frontend**

1. **Navigate to the** src/main/resources/static **directory:**
1. **Open** index.html **in your browser:**

   You can also use a live server extension if you’re using VS Code or a similar editor.

**Configuration**

- Ensure that the WebSocket endpoint /ws is correctly configured in the bac kend.
- The WebSocket messages are handled at /topic/public.

**Usage**

1. **Open the application in your browser:**
- http://localhost:8080
2. **Enter a unique username:**
- You’ll be taken to the chat room interface.
![username](https://github.com/user-attachments/assets/409d15a6-70c6-4700-be69-4dc51768ed44)


3. **Join a chat room:**
- You can join chat room .
4. **Start chatting:**
- Type your message in the input field and hit send.
- Messages will be displayed in real-time.
![Screenshot 2024-12-13 231310](https://github.com/user-attachments/assets/7689885e-330d-436c-bd52-25d917f040c6)

**Additional Notes**

- Pay attention to security, especially regarding user authentication and data validation.
- Handle cases where users disconnect or join the chat.
- Basic text formatting (bold, italics, links) is supported in chat messages.


