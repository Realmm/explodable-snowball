# explodable-snowball
Exploding Snowball Minecraft Plugin - An example first plugin to create in Minecraft

Download JDK 17 here:
https://www.oracle.com/nz/java/technologies/downloads/#java17

Download BuildTools 1.20.1 here (and then run it with `java -jar BuildTools.jar --rev 1.20.1` to generate the 1.20.1 spigot server jar, then copy this jar into a separate `/server` directory, this is your new server)
https://www.spigotmc.org/wiki/buildtools/

Download IntellijIDEA here:
https://www.jetbrains.com/idea/download

`git clone git@github.com:Realmm/explodable-snowball.git`

Then run 
`java -jar <server jar>` (after running BuildTools and getting the server jar)
to start the server

Note:
Build the plugin and put it into the `/plugins` directory on your server after running your server at least once to generate the files/folders for your server

To build the plugin, run `mvn clean install` or just install the plugin in IntellijIDEA with the Maven module by clicking the `install` button, then 
clicking the `green play arrow`, you will find your .jar to copy into the `/plugins` directory inside the `/target` directory


