# Frontend - Trivia API

## Getting Setup

> _tip_: this frontend is designed to work with [Flask-based Backend](../backend) so it will not load successfully.

### Installing Dependencies

1. **Installing Node and NPM**
   This project depends on Nodejs and Node Package Manager (NPM). Before continuing, you must download and install Node (the download includes NPM) from [https://nodejs.com/en/download](https://nodejs.org/en/download/).

2. **Installing project dependencies**
   This project uses NPM to manage software dependencies. NPM Relies on the package.json file located in the `frontend` directory of this repository. After cloning, open your terminal and run:

```bash
npm install
```

### Running Your Frontend in Dev Mode

The frontend app was built using create-react-app. In order to run the app in development mode use `npm start`. You can change the script in the `package.json` file.

Create a ```.env``` file in the frontend root directory, that is
```frontend/.env``` and within the file add the line 
```REACT_APP_BASE_URL=http://127.0.0.1:5000``` you can change the
```REACT_APP_BASE_URL``` to fit your backend url and port if you aren't
using the default.

Open [http://localhost:3000](http://localhost:3000) to view it in the browser. The page will reload if you make edits.

```bash
npm start
```
---