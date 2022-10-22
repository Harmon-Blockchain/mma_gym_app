This is a beta social/MMA education app built with Next.js that we are developing for mixed martial arts gyms and plan to eventually roll out remote personal training sessions.

First check if you have node and npm on your device already with both seperate commands:

node -v
npm -v

If you do not have them installed follow along below-

You can install the node version manager "nvm" with:

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.2/install.sh | bash


Then you are ready to setup and install node.js and npm, the node package manager with the following two seperate commmands:

nvm install 16
node --version

If you see a response such as "Now using node v16.0.6 (npm v12.14.5)" then you have installed node properly.  With node installed you should be able to write either:

nvm install npm

or

npm install -g npm

With that out of the way, lets no use the following commands to get up and running:

npm init
npm install next, react, react-dom, express

Once the basic packages are installed locally you should be able to run the command "next dev" to get your browser to pop the application up @ localhost://3000
