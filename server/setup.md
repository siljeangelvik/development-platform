# Setup 
## Step by Step


### Project Setup GitHub 
1. Create repository in GitHub Browser
2. Copy **GitHub CLI** link
3. Open `terminal` and **cd** into projects-folder
4. Paste **GitHub CLI** link inside projects-folder
5. Provide correct passphrase for you key

### Project Setup Server
1. Go to newly cloned repo using terminal: `cd development_platform`
2. Create new folder: `mkdir server`
3. Go to new folder: `cd server`
4. From **server** folder, run scripts:
5. `npm init -y`
6. `npm install express`
7. `npm install unirest`
8. `npm install -g nodemon`

### Project Setup Text Editor
1. Open **server** folder in text editor 
2. Create a new file: `app.js`
3. Add this code to the new `app.js` file: 
<pre>const express = require('express')
const app = express()
const port = 3000

app.get('/', (req, res) => {
res.send('Hello World!')
})

app.listen(port, () => {
console.log(`Example app listening at http://localhost:${port}`)
})</pre>

4. Run the app with command: `node app.js`
5. Commit and push 

**( Everything is working perfectly so far! )**



### Project Setup