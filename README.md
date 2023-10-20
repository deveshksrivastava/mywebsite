## Upload Websie on the GitHub?
1. Create Github account with new repositority to host? Make it public. and click add read me file.> create reposiotry?
2. GO to Add file and clieck upload file Drag all the folder and files. IMP : it should have index.html -> commit changes.
3. Go to Setting -> pages -> change branch from none to main > refresh page > you can see the link.


## If you want to publish react applicatoin, follow below 3 stpes
1. gh-pages : npm add gh-pages
2. add below in package.json file
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build",
3. npm run deploy
