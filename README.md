This will get a Cisco's Fantasy Medieval RPG [Dragonfyre] server running in a docker container.

You will need to download the "CARPG_Dragonfyre_V2F_Beta_Serv.zip" file from CurseForge and put it in a folder called /modpacks.

This server allocates 16GB RAM to the server (it takes a LOT to run this game) as well as sets a high timeout threshold as one of the mods dumps a ton of data into the characters upon first launch and caused them to time out. The RAM usage and timeout can be adjusted on line 11 of the docker-compose file. These numbers seem to work for me.

Make sure you are running:

    Minecraft 1.20.1
    Dragonfyre 2F Beta

If there are any differences, the player won't be able to connect. There are a lot of error messages when this server loads. I'm assuming it's just the nature of the beast with it. The game severely lags when trying to open chests, but that's most likely due to the abundance of mods and the missing values of said mods.
