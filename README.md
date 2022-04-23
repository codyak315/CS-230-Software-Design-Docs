# CS-230
Software Design Documentation

Briefly summarize The Gaming Room client and their software requirements. Who was the client? What type of software did they want you to design?

The Gaming Room is looking to develop a web-based game application that serves multiple platforms based on their current game "Draw It or Lose It".

What did you do particularly well in developing this documentation?

Providing options to achieve the goal, and explaining the rationale behind them. The Gaming Room wants their game to be cross platform, but as it currently exists is only available on Android. What this means is that their game is written in Java, so either a solution needs to be compatible with Java, or if not that needs be addressed up front otherwise there is no game to serve to their audience. 

What about the process of working through a design document did you find helpful when developing the code?

It can be easy to implement code that you would want to do, whether or not it falls in line with what the client wants in the first place. For instance The Gaming Room's game server follows a singleton pattern to ensure only one instance of a game exists in memory at any given time; it would be easy to code it otherwise, either to save time on the programming or simply because the programmer doesn't think the amount of resources being used would call for a singleton. 

If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?

In the confines of the assignment I wouldn't change much. I stand by my reccomendations and outline of the pro's and con's of the listed operating systems. Outside the confines I would suggest using a cloud provider, as with little work you could take their android application which is written in java and have it hosted on AWS, Azure, or GCP without having to re-write the game to make it multi-platform. 

How did you interpret the user’s needs and implement them into your software design? Why is it so important to consider the user’s needs when designing?

A big part for me when thinking about the user's needs came down to accessibilty. Services and functions mean nothing if they will never get used. This is a big part of why I recommended Windows as opposed to Linux, because while in good hands Linux would be cheaper, provide potentially greater security, and perform just as well it requires a higher level of expertise that is not common that could put The Gaming Room in a less than desireable situation that could require them to seek even further outside help costing them more money to keep their application operational. 

How did you approach designing software? What techniques or strategies would you use in the future to analyze and design a similar software application?

In the world of programming I believe one of the most invaluable skills you can have is converting a casual conversation into an actionable task. The client may have an idea of what they want, but converting that idea into a series of goals with the finish-line being the finished application is no easy feat. Not only does this serve the programmer by helping them become organized but it doesn't matter how good your program is if it is not what the client wanted, which stresses again the importance of attention to detail. 
