# LAN Chat Application

## Project Overview
LAN Chat Application is a beginner-level Computer Networks project developed using Python and Flask-SocketIO. It allows multiple users connected to the same local Wi-Fi network to communicate through real-time messaging.

## Features
- Real-time messaging
- Multiple users can join the chat
- Simple user-friendly interface
- Live connection status
- Instant message updates
- Supports communication over a local network

## Technologies Used
- Python
- Flask
- Flask-SocketIO
- HTML
- CSS
- JavaScript
- Socket.IO

## Project Structure

```text
LANChat/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── templates/
│   └── index.html
│
└── static/
    └── style.css
```

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/LAN-Chat-Application.git
```

### 2. Open the project folder

```bash
cd LAN-Chat-Application
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

For Windows PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

## Run the Application

```bash
python app.py
```

Open your browser:

```text
http://127.0.0.1:5003
```

## How to Use

1. Start the Flask server.
2. Open the application in your browser.
3. Enter your username.
4. Type a message.
5. Click the Send button.
6. Messages will appear in the chat window.

## Test with Two Devices

1. Connect both devices to the same Wi-Fi network.
2. Run the application on your computer.
3. Open PowerShell and type `ipconfig`.
4. Find your computer's IPv4 address.
5. On the second device, open:

```text
http://YOUR_LOCAL_IP:5003
```

6. Enter a username and exchange messages.

Make sure Windows Firewall allows Python connections on private networks.

## Networking Concepts
- Local Area Network (LAN)
- IP Addressing
- Client-server communication
- WebSocket communication
- Real-time data transmission
- Network connectivity

## Learning Objectives
- Understand how devices communicate over a LAN.
- Learn basic client-server architecture.
- Understand real-time communication using Socket.IO.
- Develop a Python-based networking application.

## Author
Bharanidharan

## License
This project is created for educational purposes.
