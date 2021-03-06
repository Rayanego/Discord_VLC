# Discord_VLC


## Description :
A program that allows you to play a video and control it (play/pause) by adding or removing discord reactions to a message. It can be useful when watching a movie with friends with shared screen so that they can pause if they need to (that's how i had the idea ).  
When you start the program the discord bot will send a message with informations about the video, then add a reaction to pause it.



## Features

* Gets informations about the video 
    * (Title, Duration, Resolution)
* Play and Pause the video
* Command to see how much time is left
 
 
## To do
* Add volume control
* Moving in the timeline
    * forward and backward reactions
* Add a GUI so that you can still control your video without discord


 ## Built with 
 * [discord.py](https://discordpy.readthedocs.io/en/stable/)
 * [libVLC](https://www.olivieraubert.net/vlc/python-ctypes/doc/)


## How to use 


### Clone the repository
```bash
$ git clone https://github.com/Rayanego/Discord_VLC.git
```

### Installing requirements
 ```bash
 python -m pip install -r requirements.txt
 ```
 
### Accessing your video
* Put your file in the same folder as main.py
### Edit main.py
* Enter your file name in the source variable (line 16) 
    * e.g :
    ```py
    source = "Paprika.mp4"
    ```
 * enter your channel id in the discord_channel variable (line 60)
 * enter your token in the token variable (line 150) 
* Save
### Run the code and enjoy
 
 ***
  ## Demo

  ### Play and pause by adding and removing reaction
![play / pause gif](https://i.imgur.com/LYcwYcN.gif)

  ### Command to get how much time is left

![uptime command](https://i.imgur.com/NmKdXf6.png)

