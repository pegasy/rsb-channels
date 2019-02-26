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

Here's what you need to know to properly do those things, we will be looking at this snip as an example (https://www.youtube.com/watch?v=dQw4w9WgXcQ)

You should see something like this, ![Roles snip](https://cdn.discordapp.com/attachments/465059517550428173/549808419251421184/unknown.png)

To add a role, you will be using this format.

```json
{
  "comment": "",
  "id": "",
  "emoji": "",
  "desc": ""
}
```

after filling it out, it should look something like this

```json
{
  "comment": "Test",
  "id": "373982567600488459",
  "emoji": "<:test:549809152818675753>",
  "desc": "Example"
}
```

"Comment" is well, a comment so that the other mods know what the role being added is.

"ID" is the role itself, you can find the role id by simply saying "/roleinfo @role"
![role id](https://cdn.discordapp.com/attachments/465059517550428173/549816465575116802/unknown.png)

"Emoji" is found by putting a \ before the emote. 
[![Image from Gyazo](https://i.gyazo.com/43366b282997025f68ac5aa9de18bee3.gif)](https://gyazo.com/43366b282997025f68ac5aa9de18bee3)

"Desc" is just a description for roles that aren't self explanatory.

When adding a few lines for the role, make sure to add in a comma on the role above.
 ![adding role comma](https://cdn.discordapp.com/attachments/465059517550428173/549818678795829268/unknown.png)
