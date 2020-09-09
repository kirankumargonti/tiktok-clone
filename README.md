# TikTok Clone With MERN ( MongoDB Express React Node)

#### **Live Project: https://tiktok-clone-mern-b8cd7.web.app/**

<br />

## Demo Picture

[![Snapshot](https://res.cloudinary.com/kirankumargonti/image/upload/v1599666065/GituHub/Screenshot_171_eol2yx.png)](https://tiktok-clone-mern-b8cd7.web.app)
<br/>

## Project Setup

    ## Quick Start

    # Clone the application
    $ git clone https://github.com/kirankumargonti/tiktok-clone.git

    # Install dependencies
    $ npm install

    # Serve on localhost:5000
    $ npm run dev

### 1. Backend

- [MongoDB Atlas](https://docs.atlas.mongodb.com/getting-started/)

  - [Create an Atlas Account.](https://docs.atlas.mongodb.com/tutorial/create-atlas-account/)
  - [Deploy a Free Tier Cluster.](https://docs.atlas.mongodb.com/tutorial/deploy-free-tier-cluster/)
  - [Whitelist Your Connection IP Address.](https://docs.atlas.mongodb.com/tutorial/whitelist-connection-ip-address/)
  - [Create a Database User for Your Cluster.](https://docs.atlas.mongodb.com/tutorial/create-mongodb-user-for-cluster/)
  - **[Connect to Your Cluster.](https://docs.atlas.mongodb.com/tutorial/connect-to-your-cluster/)**

- Add your own MongoURI key to your application
  - Navigate to **`tiktok-backend`** directory and add your own cluster MongoURI key to
    - `tiktok-backend/config/default.json`
    - Example MongoURI key 👇
    ```mongodb+srv://<username>":<password>@clustername.mongodb.net/test?retryWrites=true&w=majority```

<br />

- Deploying to Heroku

    - **[Getting Started on Heroku with Node.js](https://devcenter.heroku.com/articles/getting-started-with-nodejs)**

    - Copy the hosting url and Naviagte to to frontend 
<br/>

### 2. Frontend

- Naviagte to **```axios.js file```** which is located in 
**```tiktok```** directory
- **```src/Components/axios.js```**
- update baseURL with your heroku application url
<br/>

        # Install dependencies
        $ npm install

        # Serve on localhost:3000
        $ npm start

        # Build for production
        $ npm run build


<br />

- **Frontend deployment at firebase**
    - [ Create a Firebase Project](https://firebase.google.com/docs/web/setup)

<br />

    # Install firebase tools
    $ npm install -g firebase-tools

    # Login to firebase
    $ firebase login

    # Initialize your firebase project
    $ firebase init

    # Important Steps
        - Use an existing project
        - What do you want to use as  your public directory?
          build
        - Configure as a single-page app 
          (rewrite all urls to /index.html)? Yes
        - File build/index.html already exists. Overwrite? No

    # Deploy to firebase
    $ firebase deploy


## For more information refer firebase docs
https://firebase.google.com/docs
