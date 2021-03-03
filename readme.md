# Notepad

This is my part of a bigger project, which I developed during my studies at Warsaw University of Technology. Here I share only my part of this project, which is the client app for collaborative notepad. The most interesting thing about this project is representing data as CRDT (Conflict-free replicated data type). You can view algorithms that I wrote to make all changes independent in **Notepad.java** file. Basically each character gets its own unique ID which also indicates position in the text.

This was originally written in a client-server architecture, but because I share here only my part, I made a couple of changes for my client app, and it can run now as a server. So now it's more like a peer-to-peer connection. Only one client and one server can run at once. I did it only for you to look, how it works. If you run it from cmd (`java -jar Client.jar` or `./Client.exe`) you can see all changes (with generated IDs) and the messages that are received and sended. That can help to understand those algorithms.

Please visit [my website](www.mmakos.pl/programming/notepad) to learn more about this project, and to see other things I do.

![Notepad window](http://www.mmakos.pl/storage/2021/02/Screenshot-2021-02-27-223629.png)
![Connect window](http://www.mmakos.pl/storage/2021/02/Screenshot-2021-02-27-224801.png)
