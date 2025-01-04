# 🔥Node.js 30+ Practical Problems🔥

<div align="center">
    <img src="./nodejs-frameworks.webp" alt="node.js logo image" />
</div>

Welcome to the **Node.js 30+ Practical Problems** repository! 🌟 This is a collection of practical challenges designed to help you learn and master Node.js by tackling real-world scenarios. Each problem is organized as a standalone submodule, making it easy to focus on one challenge at a time.

---

## 🚀 Repository Structure

```js
node.js-practical-problems/
├── README.md
├── 01-hello-world-node-problem/ (submodule)
├── 02-read-file-node-problem/ (submodule)
├── 03-write-file-node-problem/ (submodule)
└── ...
```

Each problem resides in its own repository and is added here as a submodule. This structure ensures modularity and flexibility for learning.

---

## 🛠️ How to Get Started

1. **Clone the Repository**

   ```bash
   git clone --recurse-submodules https://github.com/anirudha-8/node.js-practical-problems.git
   ```

   This will clone the main repository along with all the submodules.

2. **Initialize Submodules (if not cloned with recurse-submodules):**

   ```bash
   git submodule update --init --recursive
   ```

3. **Navigate to a Problem Directory:**

   ```bash
   cd problem-1-simple-server
   ```

4. **Follow the Instructions in Each Problem's README:**
   Each submodule repository contains its own `README.md` with problem-specific details.

---

## 📋 Problems List

| #   | Problem Name                      | Description                                     |
|-----|-----------------------------------|-------------------------------------------------|
| 1   | [hello world](https://github.com/anirudha-8/01-hello-world-node-problem.git) | Build a basic HTTP server. |
| 2   | [read file](https://github.com/anirudha-8/02-read-file-node-problem.git) | Node.js script that reads the content of a file. |
| 3   | [write file](https://github.com/anirudha-8/03-write-file-node-problem.git)  | Create a Node.js script that writes the string `"Hello, Node.js!"` to a file called `output.txt`. |
| 4 | [http server](https://github.com/anirudha-8/04-basic-http-server-node-problem.git) | Create a Node.js script that sets up an HTTP server. The server should respond with the message `"Hello, World!"` to any incoming request. |
| 5 | [command line arguments](https://github.com/anirudha-8/05-command-line-argument-node-problem.git) | Write a Node.js script that takes a name as a command-line argument and prints `"Hello, [name]!"` to the console. |
| 6 | [read directory content](https://github.com/anirudha-8/06-name-of-all-files-in-directory-node-problem.git) | Write a Node.js script that reads the content of a directory and prints the names of all files in it to the console. |
| 7 | [command line calculator](https://github.com/anirudha-8/07-simple-calculator-node-problem.git) | Write a Node.js script that functions as a command-line calculator. The script should take three arguments |
| 8 | [events emitter](https://github.com/anirudha-8/08-event-emitter-node-problem.git) | Create a Node.js script that demonstrates the use of the `EventEmitter` class from the `events` module. |
| 9 | [json file handling](https://github.com/anirudha-8/09-json-file-handling-node-problem.git) | Write a Node.js script that will reads the content of a JSON file and modifies a specific part of the data also writes the modified content back to the file. |
| 10 | [simple tcp server](https://github.com/anirudha-8/10-simple-tcp-server-node-problem.git) | Create a simple **TCP Server** using Node.js's `net` module.  |
| 11 | [simple express server](https://github.com/anirudha-8/11-simple-express-server-node-problem.git) | Create a simple `Express.js` server  |
| 12 | [express route parameter](https://github.com/anirudha-8/12-express-route-parameter-node-problem.git) | Create an **Express.js route** that, accepts a `username` as a route parameter and also responds with the message: **"Hello, [username]!"** where `[username]` is the value passed in the URL.  |
| 13 | [express query parameter](https://github.com/anirudha-8/13-express-query-parameter-node-problem.git) | Create an **Express.js route** that, accepts a query parameter `name`. And responds with the message: **"Hello, [name]!"** if the `name` query parameter is provided also if `name` is not provided then sends a default response. |
| 14 | [serve static files](https://github.com/anirudha-8/14-serve-static-files-node-problme.git) | Create an **Express.js server** that, serves static files from a directory named **`public`** and responds with the appropriate files when accessed through specific routes. |
| 15 | [express middleware](https://github.com/anirudha-8/15-express-middleware-node-problem.git) | Create an **Express.js middleware** that logs the **request method** and **URL** for each incoming request to the server. |
| 16 | [express form data submit](https://github.com/anirudha-8/16-express-form-submit-node-problem.git) | Create an Express server that, serves an HTML form, handles a **POST request** when the form is submitted and responds with the submitted form data in a structured format. |
| 17 | [express route for json respond](https://github.com/anirudha-8/17-express-route-json-respond-node-problem.git) | Create an Express route `/users` that responds to GET requests with a JSON object containing a list of users. Each user object should include the following fields. |
| 18 | [express custom error handling](https://github.com/anirudha-8/18-express-custom-error-handling-node-problem.git) | Create an Express application that returns a custom error message for invalid routes (routes that are not defined in the application). |
| ... | More to Come! | Stay tuned for additional challenges. |

---

## 🎯 Key Features

- 🌟 **Beginner to Advanced Problems**: Gradual progression from basics to complex tasks.
- 🧩 **Modular Structure**: Focus on one problem at a time.
- 📖 **Practical Approach**: Learn Node.js through hands-on projects.
- 🚀 **Real-World Scenarios**: Gain experience with practical use cases.

---

## 🤝 How to Contribute

We welcome contributions! Here’s how you can get involved:

1. Fork the repository.
2. Add your own Node.js problem as a new submodule.
3. Submit a pull request.

---

## ℹ️ About

This repository is a hands-on resource for learning Node.js through practice. Whether you're just starting out or looking to enhance your skills, these challenges are perfect for you.

**Happy Coding! 💻**
