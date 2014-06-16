#Assignment II


##Clumsy Bird
This particular open source project is inspired from the very famous *Flappy Bird* , which is a side scrolling mobile game featuring 2D retro style graphics.The objective is to direct a flying bird,which moves continuously to the right, 
between each coming set of pipes without colliding with them,which otherwise ends the game.If the screen is not tapped the bird falls due to gravity.The player is scored on the number of pipes the bird successfully passes through.Since this game was removed it inspired so many developers to develop it, Just because it was an open source project,It got a lot of visibility from all over the world.**Clumsy Bird** is a clone of *Flappy Bird* Played in similar manner.


**Clumsy Bird**  took two days to develop, since it is being inspired from *Flappy Bird* ,It gained popularity soon Flappy Bird was being removed from web.
One thing that gave him so many stars on github (400 stars in a week) was the post on [Hacker News](http://news.ycombinator.com/item?id=7206155 "Hacker News").
The official game website is having average of 3k access per day and more than 180k views already. They had 6 contributors on the official repo that helped fix a lot of issues and some bugs.

The Game was made with a fabulous game framework called MelonJS, which is recommended to all game developers that needs to make fast and high quality games.MelonJS is an open source HTML5 based community game engine, released under the MIT license, that you can join, but that you can also modify or extend in any way to fit your needs.

Feature list :


* A fresh and lightweight 2D sprite-based engine.
* Standalone library( does not rely on anything else, except an HTML5) capable browser
* Compatible with all browsers(Chrome,Safari,Firefox,Opera,IE)
* Multiple Audio Channel Support
* Basic physics and collision mechanisms
* Basic vector Math
* Transition effects
* Object Pooling
* Basic animation management.
* Mouse and touch device support
* Some basic GUI elements.

This particular project is a sheer motivation to game developers aspirants that they didn't need to spend hundreds of dollars buying pre-made game clones.Only free tools have been used to develop this particular game.

* VIM for text editing
* Audacity for sound effects and music
* google images
* google Fonts

To contribute to the **clumsy Bird** we just need to fork it and pull request.



------------------------------------------------------------------------------------

#My Tracks
##My tracks for Android

Records your runs, bike rides, or any other activity and view your live data with My Tracks.

My tracks lets you:

*Record your path,speed,distance and elevation.
*View live data while you do outdoor activity
*Annotate your path with text and photos while you record.
*Hear voice announcements about your progress.
*Share your tracks with friends and family through Google Drive.
*Export your tracks to Google Drive, Google Maps, Google Fusion Tables, Google Spreadsheets or external storage.
*Connect third-party biometric sensors, like a heart rate monitor,to MY Tracks for more data.

There is a user forum where in people who have downloaded and installed the app have made comments, it can be accessed at [User Forum]("https://productforums.google.com/forum/#!categories/maps/mytracks").


For My Tracks Android development ,Eclipse is used for IDE, Mercurial for source control. Even TortoiseHg , a graphical tool for Mercurial is recommended.

*Mercurial uses python(versions 2.4 through 2.7). Most ready-to-run mercurial distributions include Python or use the python that comes with your operating system.When building from source you should confirm that an appropriate Python version is available.


Programmers contributing to My Tracks 
*Start with [DevelopmentProcess](https://code.google.com/p/mytracks/wiki/DevelopmentProcess)
*Use mytracks-dev@googlegroups.com discussion group
*Before starting with any work its better to email the discussion group on your proposal.

The only Way to keep the code consistent is to have a very strict style guide.My Track Code roughly follows Sun java Style guide.


------------------------------------------------------------------------------------

#HYSTRIX 

Hystrix is a latency and fault tolerance library designed to isolate points of access to remote systems, services and 3rd party libraries, stop cascading failure and enable resilience in complex distributed systems where failure is inevitable.

Hystrix evolved out of resilience engineering work that the Netflix API team began in 2011. Over the course of 2012, Hystrix continued to evolve and mature, eventually leading to adoption across many teams within Netflix. Today tens of billions of thread-isolated and hundreds of billions of semaphore-isolated calls are executed via Hystrix every day at Netflix and a dramatic improvement in uptime and resilience has been achieved through its use.

##Purpose of Hystrix

*Give protection from and control over latency and failure from dependencies (typically accessed over network) accessed via 3rd party client libraries.
*Stop cascading failures in a complex distributed system.
*Fail fast and rapidly recover.
*Fallback and gracefully degrade when possible.
*Enable near real-time monitoring, alerting and operational control.


Applications in complex distributed architectures have dozens of dependencies, each of which will inevitably fail to some point.If not isolated from these external failures, the host application is at risk of being taken down with them.

Even when all dependencies are performing eel the aggregate impact of even 0.01% downtime on each dozens of services equates to potentially hours a month of downtime.

With high volume traffic a single backend dependency becoming latent can cause all resources to become saturated in seconds on all servers.
Network connections fail or degrade. Services and servers fail or become slow. New libraries or service deployments change behavior or performance characteristics. Client libraries have bugs.

All of these represent failure and latency that needs to be isolated and managed so a single dependency failing can't take down an entire application or system.


In addition to Hystrix examples, the following are additional examples from complete end to end applications using many key components from Netflix OSS stack:
*Flux Capacitor,
*Netflix Recipes -RSS Reader


Hystrix supports the modification or addition of behavior using plugin implementations.


