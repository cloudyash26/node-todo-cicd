# node-todo-cicd

Run these commandsin this directory /var/lib/jenkins/workspace/TODO-NODEJS-APP


`sudo apt install nodejs`


`sudo apt install npm`


`npm install`

`node app.js`

or Run by docker compose

test


-----------------------------------------------------------------------------------------------------------------------------
`RUN npm install`
This command in the dockerfile installs the dependencies specified in the package.json file.

`RUN npm run test`
This command in the dockerfile runs the test script defined in the package.json file.
-----------------------------------------------------------------------------------------------------------------------------
Troubleshooting:
Use this commands for permission denied related issues
`sudo usermod -aG docker ubuntu`
`sudo usermod -aG docker jenkins`


