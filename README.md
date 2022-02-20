# Vue Youtube Video Browser 


This is a simple application build with the help of Vue.js and bootstrap. Here, the user can search top 5 youtube videos by entering the name
of the video the user wants to search for and then presss the ENTER key. After this, the user will be displayed with top 5 videos based on that search and then the user can simply play a youtube video by simply clicking on it.

<br />

NOTE :- You need to press ENTER in order to see the search result.

<br />

# Installing the application in Local Environment


In order to run the application, we first need to have "vue-cli" installed in your system. TO install "vue-cli", open command prompt and enter the following command and then press ENTER

```
npm install -g @vue/cli
```

After you have successfully installed vue-cli, you then need to clone this repository in your local system. After you have cloned the repo, open command prompt inside that folder where all the files of this projects are present, and then run

```
npm i
```

This will install the necessary node_modules of the project.

<br />

# Running the Application in local environment


In order to run this application locally in the system, open command prompt inside the folder where all the files of this project is present, and then run

```
npm run serve
```

This command will now start a development server. After the development server starts running successfully, you will get a localhost url. You just need to copy that url and paste it in browser to open the website.

# Important Note

When you will open this website and search for something, then there is a chance that you will not get any search result. Now, there can be two possible reasons for it =>


a) You don't have any stable internet connection. <br />
b) The API which is being used in this application to search for youtube videos i.e. `YouTube Data API v3` has reached its daily limit and is down for that particular day. 

<br />

To know more about `YouTube Data API v3`, visit https://developers.google.com/youtube/v3/getting-started





