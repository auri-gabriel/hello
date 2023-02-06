# Hello Web Server

Note: This project was completed as part of the guided exercises in Chapter 20 of The Rust Programming Language Book. The objective of the project was to reinforce the concepts learned in the book.


This is a simple multithreaded web server implemented in Rust. The server listens on IP address `127.0.0.1` and port `7878`, and uses a thread pool to handle incoming requests.

## Features
- Supports GET requests to the root endpoint (`/`), which returns the contents of `hello.html`
- Supports GET requests to the `/sleep` endpoint, which returns the contents of `hello.html` after sleeping for 5 seconds
- Returns a 404 NOT FOUND response for any other type of request, along with the contents of `404.html`

## Usage

To run the server, simply compile and execute the program using a terminal or command prompt.

``$ cargo run``

## Requirements

- Rust compiler and development environment

## Contributing

Feel free to fork the project and make any changes you'd like. Pull requests are welcome!
