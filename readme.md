# Simple Golang Chat Server

## Description
This is a simple chat server written in Go. It allows multiple clients to connect and send messages to each other in real-time.

## Installation

### Prerequisites
- Go 1.x
- A working Go environment

### Steps
1. Clone the repository: `git clone https://github.com/wust-lzy/golang-chat-server`
2. Navigate to the project directory: `cd golang-chat-server`
3. Build the server: `go build`

## Usage
Start the server by running the executable: `./chat-server`

Clients can connect to the server using a WebSocket connection on the "/ws/12345" endpoint.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)