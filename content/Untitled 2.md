Install Node
Install Git
Clone Quartz Repo

[jackyzha0/quartz: 🌱 a fast, batteries-included static-site generator that transforms Markdown content into fully functional websites](https://github.com/jackyzha0/quartz)

[How to publish your notes for free with Quartz](https://www.youtube.com/watch?v=6s6DT1yN4dw&t=34s)


1. Open Bash

2. Go into parent directory
cd "C:\Users\anton\OneDrive\D&D\Scrolls"

3. git clone https://github.com/jackyzha0/quartz.git

4. change name of the quartz folder to what you want it to be
mv quartz "Your Name"

5. cd "Your Name" 
6. npm i
7. npx quartz create

8. git remote rm origin
9. git remote add origin https://github.com/lheaj/slate-waves.git

how it has to look, upstrem is the github repo from quarts and in origin it's ours.
anton@Antonio-Laptop MINGW64 ~/OneDrive/D&D/Wikis/Slate Waves (v4)

$ git remote -v
origin  https://github.com/antonioorsini/slate-waves.git (fetch)
origin  https://github.com/antonioorsini/slate-waves.git (push)
upstream        https://github.com/jackyzha0/quartz.git (fetch)
upstream        https://github.com/jackyzha0/quartz.git (push)

npx quartz sync --no-pull

npx quartz sync 