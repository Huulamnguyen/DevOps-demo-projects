## 2. Deplpoy Node App with Digital Ocean 
### Demo Project:
- Create a server and deploy Node application on Digital Ocean

### Techology used:
- Digital Ocean, Linux, Node, npm

### Project Description:
- Setup and configure a server on Digital Ocean
- Create and configure a new Linuz user on the Droplet (security best practices)
- Deplpoy and run a node application on Doplet

### Source:
- Module 5: Cloud & Infrastructure as Service Basics with DigitalOcean

### Steps:
- Pack my app into a zip file `npm pack`
- On Digital Ocean,
    - Create a new droplet
    - Set up ssh public key
    - Create and assign firewall rules to the droplet
    - Access the server by `ssh -i ~/id_rsa root@{server-ip-address}`
    - Install Node and npm on the server `apt install -y nodejs npm`
        - Check if nodejs is installed `node -v`
        - check if npm is installed `npm -v`
    - Copy app zip file and package.json to the droplet (server):
        - `scp -i ~/id_rsa app/bootcamp-node-project-1.0.0.tgz root@{server-ip-address}:/root`
        - `scp -i ~/id_rsa app/package.json root@{server-ip-address}:/root`
    - Login to droplet (server):
        - `ssh -i ~/id_rsa root@{server-ip-address}`
        - Unpack the node-project file: `tar zxvf bootcamp-node-project-1.0.0.tgz`
        - Change into unpacked directory called "package": `cd package`
        - Install dependencies: `npm install`
        - Run application: `node server.js`
