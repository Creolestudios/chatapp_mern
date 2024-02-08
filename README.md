
# Chat Application

[Take tour of Chat Application](https://www.loom.com/share/4946fb24a6604234800641eae0a3ab4b)

## Installation Guide

  

### Requirements

- [Nodejs](https://nodejs.org/en/download)

- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)

  

Both should be installed and make sure mongodb is running.

  

```shell

git  clone  https://github.com/Creolestudios/chatapp_mern.git

cd  chatapp_mern

```

Now rename env files from .env.example to .env

```shell

cd  server

mv  .env.example  .env

cd  ..

```

  

Now install the dependencies

```shell

cd  server

yarn

cd  ..

cd  client

yarn

```

We are almost done, Now just start the development server.

  

For Frontend.

```shell

cd  client

yarn  start

```

For Backend.

  

Open another terminal in folder, Also make sure mongodb is running in background.

```shell

cd  server

yarn  start

```

  

Done! Now open localhost:3000 in your browser.