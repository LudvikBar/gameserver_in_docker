# Tmodloader
## Work in progress
### This is a personal learning project meant for exploring and learning docker, the Tmodloader server files themself are downloaded from the official github and not created by me.


For those who don't know. TmodLoader is a version of Terraria that allows for custom and community made mods



## Step-by-step - Setup

### 1. 
Clone the repo with 
> git clone https://github.com/LudvikBar/gameserver_in_docker.git


### 2. 

**Go to the latest version of tModLoader, not pre-release: https://github.com/tModLoader/tModLoader/releases**

<span style="color:red; font-size:12px;">If You have another version of tmodloader you want to use, select it instead.</span>

**Just "tModLoader.zip" no other folders or files. Either download manualy or use wget.**

Inside the "tmodloaderServer" folder located in the base folder make a folder named exactly "ServerFiles". 

Put tModLoader.zip inside ServerFiles and unzip


For wget: On the main page, rightclick the "tModLoader.zip" and click "Copy Link Address"

In terminal write the following:
> wget (the link you copied)



### 3. 
Run the docker compose file with:
> docker compose up --build




### to be continued
