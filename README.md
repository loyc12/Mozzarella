# Mozzarella

Mozzarella modpack for Minecraft 1.18.2 (Fabric 0.14.8)

PS : (It is recommended you have at least 12G of ram on your PC to run this modpack)

How to install this modpack :

- Have minecraft JAVA EDITION installed on your PC
- Download the Mozzarella folder (extract from the zip file if needed)
- Run the fabric installer (.exe file)
- Install the MC version 1.18.2 with the loader version 0.14.8 (create profile option turned on)
- Open the minecraft launcher and go to the Installations tab (2nd one)
- Click on the newly created installation of fabric 1.18.2
- (Optional) change the name of the installation to Mozzarella
- Create a subdirectory on your .minecraft called Mozzarella
- click on more options and paste the JVM arguments bellow;

-Xmx7G -Xms1G -XX:+UnlockExperimentalVMOptions -XX:+UseG1GC -XX:G1NewSizePercent=6 -XX:G1ReservePercent=6 -XX:MaxGCPauseMillis=10 -XX:G1HeapRegionSize=32M -XX:ParallelGCThreads=12 -XX:SoftRefLRUPolicyMSPerMB=10000 -Dsun.rmi.dgc.server.gcInterval=2147483648

- (Optional) You can change the 7 in "-Xmx7G" to any number between 5 and 10 to give minecraft more or less allowed ram usage
- Save and launch the installation
- Once at the title screen, close the game
- Reopen the minecraft launcher and go back to the Installations tab
- Open the Mozzarella directory you just created with the folder button to the right
- In this directory, slide in the "config", "mods" and "shaderpacks" folders from the repo
- In the "mods" folder, slide in the files from the "mods (clientside)" folder
- Close the file explorer and launch the Mozarella Installation again
- If everything has been done correctly, the bottom left corner of the minecraft title screen should say "Minecraft 1.18.2/Fabric (397 Mods)"

Additional information :

This modpack is in its beta phase, and while it is currently mostly stable, bugs and issues are still to be expected. If you find any, please communicate them to us so we can try to resolve them.

We are currently testing this modpack on a server (the adress was given to select participants), so you're welcomed to join us, assuming you<ve been given the IP and can act like decent people online.

Pregenerating chunks with Chunky is highly recommended, especially for multiplayer worlds.
