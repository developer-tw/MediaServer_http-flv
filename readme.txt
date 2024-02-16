1.
git clone https://github.com/illuspas/Node-Media-Server.git
cd Node-Media-Server
npm install

2. cd bin
node app.js

3. 
click index.html

4. run
ffmpeg -re -i demo_zybridhome.mp4 -c copy -f flv rtmp://localhost/live/mark

5. input "mark" in browser
