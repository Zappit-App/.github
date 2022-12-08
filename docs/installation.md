# Installation

Please note that **all** services must be running for the app to work properly.

## Prerequisites

-   At least 1GB RAM dedicated only for the app
-   5GB For the main app (excluding files uploaded by the users)
-   Node.js 18.12.1
-   UNIX based system (Mac, Linux or WSL)
-   MongoDB Server
-   Redis Server

## Website

-   First we need to clone the repository:

```bash
git clone https://github.com/Zappit-App/website.git
```

-   Our app already comes with an example `.env` file, you only need to duplicate it and name it `.env.local`, and you will need to change the values accordingly.

-   Run the following command to create the directory for the user uploaded media: (Temporal, since a media management microservice is being created)

```bash
mkdir -p data/avatars
```

-   Then you can run the server using the following command:

```bash
npm run start
```

This will automatically build the client and server side for you, after that the server will start using the environment variables you declared.

<br />

# Chat

-   Clone the repository:

```bash
git clone https://github.com/Zappit-App/chat.git
```

-   As before, we need to set out environment variables, the repository comes with an example `.env` file to create your own

-   Run the server
``` bash
npm run start
```