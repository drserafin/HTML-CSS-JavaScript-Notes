### What is JavaScript?

JavaScript is a high-level, dynamic programming language mainly used for creating interactive effects within web browsers. It is a core technology of the World Wide Web, alongside HTML and CSS, enabling developers to create dynamic and interactive content on websites, such as animations, form validations, and responsive user interfaces.

### Coding JavaScript in Visual Studio Code

You can write and run JavaScript code in Visual Studio Code (VS Code) just like you do with C++. To do this, you need to install Node.js:

**Node.js** is a free, open-source, cross-platform JavaScript runtime environment that allows developers to build servers, web applications, command-line tools, and scripts.

1. **Install Node.js**: Download and install Node.js from [nodejs.org](https://nodejs.org).

2. **Verify Installation**: Open your terminal and run:
   ```bash
   node -v
   npm -v
```

You should see version numbers for both node and npm, e.g.:
```bash
v18.17.0
9.6.0
```
If you encounter issues, check YouTube tutorials or ask for help from ChatGPT.

## Creating a New Node.js Project

1. Initalize a project:

```bash
mkdir my-node-project
cd my-node-project
npm init
```
This command creates a package.json file that manages your project's dependencies, scripts, and metadata.

2. Install Packages:

```bash
npm install express
```

`express` is a popular framework for building web applications and APIS with Node.js

3. `Write and Rune Code`: Create a new JavaScript file (e.g, `app.js`) and write your code. Run your code using Node.js:

```bash
node app.js
```
## Understanding package.json and Express

package.json: This JSON file contains metadata about your project, such as its name, version, description, entry point (usually index.js), and dependencies.

Express Framework:

* Middleware Support: Middleware functions process requests, modify data, or handle responses. Examples include user authentication, data parsing, or request logging.
* Routing: Express simplifies setting up routes for different URLs or HTTP methods (GET, POST, etc.).
* Server Creation: Express provides a higher-level API to set up and manage a web server without dealing with low-level server code directly.

