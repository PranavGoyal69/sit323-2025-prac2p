# SIT323-2025-Prac2P

This project is a simple Node.js web server using the Express framework to serve an HTML page.

## 🚀 Project Overview
This task is part of the SIT323 unit to practice Node.js and prepare for building microservices. The web server serves a basic HTML page.

## 🛠️ Installation Instructions

### Prerequisites
Ensure the following tools are installed on your computer:
- [Node.js](https://nodejs.org)
- [Git](https://git-scm.com)
- [Visual Studio Code](https://code.visualstudio.com)

### Steps to Set Up the Project
1. **Clone the Repository**
```bash
git clone https://github.com/PranavGoyal69/sit323-2025-prac2p.git
cd sit323-2025-prac2p
```

2. **Install Dependencies**
```bash
npm install
```

3. **Run the Server**
```bash
node server.js
```

4. **View the Web Page**
Open your browser and navigate to:
```
http://localhost:3000
```

## 📂 Project Structure
```
sit323-2025-prac2p/
├── public/
│   └── index.html       # The HTML page served by the server
├── server.js            # Node.js server file
├── package.json         # Project metadata and dependencies
└── README.md            # Project documentation
```

## 📄 Code Overview
- **`server.js`**: Sets up the Express server and serves the HTML page.
- **`public/index.html`**: A simple HTML file served when accessing the root URL.

## ⚡ Example Output
Once the server is running, visiting `http://localhost:3000` should display:

> **Welcome to my Node.js Web Server!**
>
> This is a simple HTML page served using Express.js.

## 💡 Troubleshooting
- If `npm install` fails, ensure Node.js is correctly installed.
- If the server doesn't start, ensure port 3000 is free or change the port in `server.js`.


## 📚 References
- [Node.js Official Site](https://nodejs.org)
- [Express.js Documentation](https://expressjs.com)
- [Git Documentation](https://git-scm.com)

---

