# codejs-in-action
This is my practise for Node.js!

ConEmu

Run
  node server.js

Error
npm install -g mime
npm install mime
npm install -g mime
(not sure what happened)
npm install -g socket.io
(again)

You need to install Express locally into the context of your application (node_modules folder):

$ npm install express

The reason for this is that applications always look in their local context for any dependencies. The global installation is only for setting up system-wide available binaries, such as unit test runners or bootstrappers or things like that.

With Express, when you install it globally, you get an express binary that can bootstrap an application for you. For more information, type

$ express --help

So, to answer your final question: YES, you need to install it without -g.