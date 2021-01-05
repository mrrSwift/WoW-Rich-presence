# WoW Rich presence

-------------------------------------
## How to change the status
Open the state.json file 
 **(Dont Change clientID)**
```json
"info":{
        "details":"<Hero's name>" ,
        "state": "<Class Name>",
       
       "largeImageText":"<Class Name>" ,
       
       "smallImageText": "<Faction>"
       
    }
    
```
  After changing the info forgive values, you must carefully change the zone values

**Use all words in lower case And use the underscore instead of space**

  ```json

"zone":{
        "largeImageKey":"demon_hunter" 
    },
    "class":{
        "smallImageKey":"alliance" 
    },
    "modeplay":{
        "waudoing":"idle",
        "where":"y"

  ```
```js
/*
largeImageKey:{
daeth_knight,
demon_hunter,
druid,
hunter,
mage,
monk,
paladin,
priest,
rogue,
shaman,
warlock,
warrior

}

-smallImageKey:{
alliance,
horde
}

-where:{
    y,
    x
}
*/
```

y= in game 
x= in menu

-------------------------------------
## Install

You can download the [release](https://github.com/amirzarei007/WoW-Rich-presence/releases/tag/1.0) file or follow the tutorial below 

 -Download and Install [node.js](https://nodejs.org/en/download/)
 
 -Download the file using the following command

```
git clone <link>
```

 -Use the following commands to go into the file and install the required libraries

```
cd <File location>

npm install

```


 -And after doing all the work and saving the information using the following command, you turn on the Bot 
 
``` 
node .
```
 
