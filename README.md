# Java - Starting game development using LibGDX

Hello and great that you have decided to start coding games using Java. This guide/tutorial will introduce you into the most important basics for 2D and 3D gaming and help you understand the concepts. Please not that this guide is not a place to learn Java itself, this guide expect a good knowledge of Java itself. So if you are net yet familiar with concepts as loops, methods, classes, constructors, packages, inheritance, polymorphism, etc ... I suggest you start with improving your overall knowledge of Java itself.

To help us in developing our code this guide will use a framework, **libGDX** (https://libgdx.com), so we don't have to learn raw OpenGL but can access the functionality more easily. If you want to learn more how rendering realy works or how you can access all features at its core, you better look for a native OpenGL guide. Another reason why libGDX is a good choice, is that it provides cross-platform access and easily lets us guild an executable JAR for Windows, Linux or Mac, port application as runnable website and even a mobile application for Android or iOS.

However since development for iOS is not free and exporting the application as a website is not out-of-the-box, we will focus on this guide for an application that runs through a JAR and Android app.

This guide, and most assets used in it, is largely based on the wiki pages of libGDX itself (https://libgdx.com/wiki/). So all credits to them, I have just updated, rearranged or extended the code where needed to meet the latest libGDX and JDK version that was used in this guide. They also have great community who can help should you have any problems while using the framework.

At the end of each chapter you will be able to find the full code source in the guide, but also a link to the complete project at that point so you can run that should your code not match. Keep in mind that this guide is by no means a full tutorial on all possibilities but it will merely demonstrate the principles. It is up to you to grasp these and then expand your knowledge by experimenting on your own.

Have fun exploring game development.

Thumbkin

## Repository

This repository contains the following structure:

- Tutorials: Folder containing all materials per chapter of the tutorial
  - Assets: the assets used in the chapter
  - Sourcecode: A folder containing ONLY the java classes used for the chapter
  - Projectfiles: Contains a zip of the project when starting the chapter and a zip when finished with the chapter
  - Builds: contains an executable JAR and apk for the chapter

- [libGDX-tutorial.md](./libGDX-tutorial.md): the tutorial to teach you about libGDX
- [README.md](./README.md): this readme
