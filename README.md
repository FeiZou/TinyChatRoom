# TinyChatRoom
Using Java Socket API and thread framework to implement a Tiny ChatRoom

Download Client.java and Host.java in src file. Compile them in terminal first:
- javac Host.java
- javac Client.java

Run the Host.java file:
- java Host
Should see following:
Usage: java MultiThreadChatServerSync <portNumber>
Now using port number=2222

Open a new window of terminal and run Client.java:
- java Client
The system will ask your name. And to quit the chat room enter /quit, everyone the the chat room shall see a message notice.

The default Client is set by 10, so we could run 10 Client in the same time.
