# Radool's Realm, Level 0

Turn on all of the achievements to get the flag! To play, you must have a 
recent version of Java installed, and then:

1. Extract the level0 zip file. You will find a game client jar (`level0.jar`), a save file (`savelvl0.rr`), 
a snippet of the vulnerable server code (`Level0Server.java`), and a configuration file (`server.conf`).

2. Run the game server jar from the parent directory (e.g. in a separate terminal or in the background).

```
java -jar server.jar 0 3145
```

3. Run the game client jar.

```
java -jar level0.jar
```
