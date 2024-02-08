# Chat Application

[Take tour of Chat Application](https://www.loom.com/share/4946fb24a6604234800641eae0a3ab4b)

<!-- toc -->

- [Features](#features)

- [Requirements](#requirements)

- [Usage](#usage)

- [Env Variables](#env-variables)

- [Install Dependencies (frontend & backend)](#install-dependencies-frontend--backend)

- [Run](#run)

- [Build & Deploy](#build--deploy)

<!-- tocstop -->

## Features

- Chat App

- Send Emoji

- Create users to begin chat

## Installation Guide

### Requirements

- [Nodejs](https://nodejs.org/en/download)

- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)

Both should be installed and make sure mongodb is running.

## Usage

- Create a MongoDB database and obtain your `MongoDB URI` - [MongoDB Atlas](https://www.mongodb.com/cloud/atlas/register)

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

### Install Dependencies (frontend & backend)

Now install the dependencies

```shell

cd  server

yarn

cd  ..

cd  client

yarn

```

### Env Variables

Rename the `.env.example` file to `.env` and add the following

```

PORT = 5000

MONGO_URI = your mongodb uri

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

## Build & Deploy

```

# Create frontend prod build

cd frontend

npm run build

```
