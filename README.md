# lightning-SMP
hey soft, all you have to do is create 1 terminal instance per server, THEN
run 
``` bash
cd [insert server name here] && java -jar server.jar
```
the lobby is now a Leaf server (Paper fork) on 1.21.11, while the rest of the servers (survival, lifesteal, schoolSMP) run 26.2, so start it the same way as the others
```bash
cd Lobby && java -jar server.jar
```
(folder is `Lobby` with a capital L, and swap `server.jar` for whatever the Leaf jar is actually named)
it is just as simple as that, alr?

| server | software | version |
| --- | --- | --- |
| Lobby | Leaf | 1.21.11 |
| survival | Paper | 26.2 |
| lifesteal | Paper | 26.2 |
| schoolSMP | Paper | 26.2 |
| velocity | Velocity | proxy |
| auth | NanoLimbo | limbo |

btw velocity doesnt need a lot of RAM so you really only need to do 
```bash
cd velocity && java -Xms512m -Xmx2G -jar server.jar
```
# YOU ARE A GOAT!