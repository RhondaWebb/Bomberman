Multiplayer Bomberman
=========

This project is coded in 4 days for company internal competition.

We used [libGDX](http://libgdx.badlogicgames.com) for OpenGL ES on Android, [libgdx stagebuilder](https://github.com/peakgames/libgdx-stagebuilder) which is opensource project, and AppWarp (appwarp.shephertz.com) for multiplayer server

I reminisce the days playing Super Mario, Kung fu, Marble Madnes, and even the Double Dribble. We develop the project coded Bomberman game for you! 

Bomberman was the first in a long-running series of games. The goal was to plant bombs within mazes and use the explosions, which filled the maze corridors with flame, to destroy monsters and open up new paths. See some power-ups [here](https://essaydoc.com ) in  addition. Get the Bomberman to run faster and played it on your own desktop! 

Below are the set-ups.


Running Project
------

Download App Warp Java SDK from http://www.shephertz.com/downloads/appwarp-downloads.php and extract files.

Add App Warp Client dependency to your local maven repository by running below command

```java
mvn install:install-file -Dfile=App42MultiPlayerGamingSDK.jar -DgroupId=com.shephertz.app42.gaming -DartifactId=multiplayer-client -Dversion=1.5.2 -Dpackaging=jar
```

Then, clone https://github.com/peakgames/libgdx-stagebuilder project and run below command

```java
mvn install -Dmaven.test.skip
```

After then, you can open the project by IntelliJ or Eclipse and run BombermanDesktop
If you want to run on device, connect your device and run below command
```java
mvn clean install -Pandroid
```

![Lobby Screen](https://raw.githubusercontent.com/firstthumb/Bomberman/mvn_repo/screenshots/1.png "Lobby Screen")
![Waiting Game Start](https://raw.githubusercontent.com/firstthumb/Bomberman/mvn_repo/screenshots/2.png "Waiting Game Start")
![Game Screen](https://raw.githubusercontent.com/firstthumb/Bomberman/mvn_repo/screenshots/3.png "Game Screen")
![Game Controller Selection](https://raw.githubusercontent.com/firstthumb/Bomberman/mvn_repo/screenshots/4.png "Game Controller Selection")
