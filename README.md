# rsb-channels

## Editing text channels

Open and edit the .md file for the channel you want to edit

The file gets split into seperate messages by the `---`  
Each section gets trimmed of any blank rows in the beginning and end of the section (message).  
Sections starting with `![` will be treated as an image only message (first image will be used, rest of section discarded).  

## Editing roles channels

First click on the roles.json file  
You will be directed to the edit page where you are able to add, delete, edit the file.  
![Image from Gyazo](https://i.gyazo.com/536d7f00cdf60fa4f963c12f66104845.gif)

 Here's what you need to know to properly do those things, we will be looking at this snip as an example
(https://www.youtube.com/watch?v=dQw4w9WgXcQ)

You should see something like this, ![Roles snip](https://cdn.discordapp.com/attachments/465059517550428173/549808419251421184/unknown.png)

To add a role, you will be using this format.
###      {
###         "comment": "xxxxx",
###         "id": "#######",
###         "emoji": "<:xxxx:#####>",
###         "desc": "xxxx"
###       }
