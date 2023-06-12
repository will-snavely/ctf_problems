# Radool's Realm, Level 2

Turn on all of the achievements to get the flag! To play, you must have a 
recent version of Java installed, and then:

1. Extract the level2 zip file. You will find a game client jar (`level2.jar`), a save file (`savelvl2.rr`), 
a snippet of the vulnerable server code (`Level2Server.java`), and a configuration file (`server.conf`).

2. Run the game server jar from the parent directory (e.g. in a separate terminal or in the background).

```
java -jar server.jar 2 3147
```

3. Run the game client jar.

```
java -jar level2.jar
```
