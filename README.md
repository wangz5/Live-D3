# ng-D3

**ng-D3** is a kickstart project to build real-time D3 chart components using angular and WebSockets.

#Download
You can either download the whole project by clicking "Download ZIP" button on top-right side or can clone the repository to your local via cmd :
```
git clone https://github.com/veercg/ng-D3.git
```

#Installation
Step 1. Downlaod and install Node.js (If you already have node installed, you can skip this step.) 
        [**Download Node.js**](https://nodejs.org/en/download/)
        
Step 2. **Installing server dependencies** Go to the local folder where you have cloned the repository via command prompt and type:
  ```
  npm install
  ```
Step 3. **Installing client dependencies** Go inside the '/public' folder via command prompt and type:
  ```
  npm install
  ```
Step 4. Now you can go back to local folder where you have the file 'server.js' and run the node server by typing:
  ```
  node server.js
  ```
Step 5. If you are able to see : "listening on *:3000" in your command prompt, you have installed the project successfully. 

#Usage
Now you can open your browser and open these two links in your two different tabs:
```
http://localhost:3000/dashboard.html
http://localhost:3000/user.html
```
Woah! I am able to see D3 charts in Dashboard page. Cool!
Now you can add data to your D3 Charts in real-time by entering data in user.html page.
Try it! :)

# License
MIT
