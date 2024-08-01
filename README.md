# Project Overview

This project will use the responses of an LLM (in this case, ChatGPT) to control parameters within an Strudel livecoding editor.

1. **Node Server**: A backend server built with Node.js that interacts with the ChatGPT API. It handles API requests and responses, serving as the intermediary between the web page and the ChatGPT service.

2. **Web Page**: A frontend interface that displays the responses from the ChatGPT API. It also includes a Strudel editor, which allows users to update parameters and interact with the API dynamically.

## Node Server

The Node server is responsible for:
- Making API calls to ChatGPT.
- Processing and formatting the responses.
- Serving the responses to the web page.

## Web Page

The web page provides:
- A user-friendly interface to interact with the ChatGPT API.
- Display of API responses.
- A Strudel editor for updating parameters and sending requests to the Node server.

## Getting Started

### Prerequisites

- Node.js installed on your machine.
- Access to the ChatGPT API.

### Installation

1. Clone the repository:
    ```sh
    git clone <repository-url>
    ```
2. Navigate to the project directory:
    ```sh
    cd <project-directory>
    ```
3. Install the dependencies:
    ```sh
    npm install
    ```

### Running the Project

1. Start the Node server:
    ```sh
    npm start
    ```
2. Open the web page in your browser:
    ```sh
    open http://localhost:3000
    ```

## Usage

- Use the web page to send requests to the ChatGPT API.
- View and interact with the responses.
- Update parameters using the Strudel editor.

## Contributing

Feel free to submit issues or pull requests. Contributions are welcome!

## License

This project is licensed under the MIT License.