group members: naf

expansion of the story game lab and the most recent lab(?), a 2 player fully client side game that is inspired by BUCKSHOT ROULETTE by Klubnika

how the project will be used: upon the first client running, a wait message will appear that waits for the second client to connect. once the second client connects, both clients write in their name and the game starts. clients can write text to input actions (i.e ITEM to view items, SELF to shoot self, OTHER to shoot the other client).

technical stuff:
will be using semaphores to check when 2 clients are running the program at one time and start the game
pipes and shared memory will be used between clients to share data
signals will be used when a player abruptly quits etc. to send a message to the other client about the leaving.


