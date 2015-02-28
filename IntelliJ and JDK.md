Follow these instructions to install the basic software you will need to write programs in Java. You will use the _IntelliJ IDE_ and the _Java7 JDK_.

**Local dowload links:**
- [IntelliJ IDEA 14 CE](http://192.168.1.28:8000/ideaIC-14.0.3.dmg)
- [Oracle Java7 JDK](http://192.168.1.28:8000/jdk-7u75-macosx-x64.dmg)

**Google Drive download links:**
- [IntelliJ IDEA 14 CE](https://drive.google.com/file/d/0B8ga0y5taeMYWWJiSG5adzR2MUk/view?usp=sharing)
- [Oracle Java7 JDK](https://drive.google.com/file/d/0B8ga0y5taeMYUHBnX0NYSHBGaTg/view?usp=sharing)



Installing IntelliJ
==
IntelliJ is an **IDE**, or Integrated Development Environment.  An IDE makes programming much easier by providing a visual tool for writing, managing, running, and debugging your code.  We will use IntelliJ version 14.

To install IntelliJ:

1. Go to the [IntelliJ download page](https://www.jetbrains.com/idea/download/).
2. Select the `Download Community` button on the right, to download the free version of the program.  You will download a file named `ideaIC-14.0.3.dmg`.
3. Once it's finished downloading it, click on it. When the window opens, drag the IntelliJ icon to the Applications folder.
4. Drag the `IntelliJ IDEA 14 CE` drive icon from your desktop to the trash can.

Test that you can open IntelliJ by opening Spotlight (press `⌘-Space`) and typing the first few  letters of IntelliJ.

Installing the JDK
==
The **JDK** is the Java Development Kit, which contains the tools you need to compile and run Java programs.  There are multiple versions of Java; in this course, we will use version 7, otherwise known as **Java7**.  Make sure you are using Java7, and not Java6 or Java8.

To install the Java7 JDK:

1. Go to the [Oracle Java7 JDK page](http://www.oracle.com/technetwork/java/javase/downloads/jdk7-downloads-1880260.html)
1. Accept the license agreement.
1. Download `jdk-7u75-macosx-x64.dmg`.
1. Double-click on the .dmg once it downloads. This will mount the .dmg file as a drive on your computer.
1. When the .dmg mounts, a new window will open. Double-click on the .pkg package file in the window that comes up.
1. In the installer, click `OK`, then `Install`.
1. It will prompt you for your login password.
1. When it's done, find the `jdk update 75` drive icon on your desktop and drop it on the trash.  This unmounts the .dmg file.

Installing the JDK in IntelliJ
--
You'll have to set up the JDK in IntelliJ before you can use it.  You only have to do this once.

1. In the lower right click on `Configure > Project Defaults > Project Structure`.
1. In the second column, click the plus button at the top and select `JDK`.
1. A file dialog box will open.  In the top-middle, dropdown box, select `Macintosh HD`.
1. Navigate to `Library > Java > JavaVirtualMachines`.
1. There should be an entry named `jdk1.7.0_75.jdk`.  Select (single-click) this and press the `Choose` button in the lower-right.
1. Click `OK`.

Creating an IntelliJ project
==
IntelliJ organizes your work into _projects_.  In IntelliJ, you'll always work on one project at a time.  To test that you have installed IntelliJ and the JDK correctly, we'll create a simple Java project, and you'll create your first Java program.

1. Click `Create New Project`.
1. Make Sure `Java` is selected in the left column.
1. In the `Project SDK` box, there should be a `1.7` entry with version 1.7.0_75.  (If this is not there, please ask for help.)
1. Click `Next`.
2. Check the `Create project from template`. Select `Command Line App` and hit `Next`.  (A "command line" app is one that you run from the terminal.)
3. Give your project the name "helloworld". For the base package, use `nyc.c4q.(username).helloworld` where (username) is your GitHub username.  

IntelliJ creates the project for you.  In fact, it writes most of the Java code for you!  You'll see a file named `Main.java` that contains the skeleton of your first program.  Find the line that says,

    // write your code here

and delete the entire line. Replace it with this line, typed exactly as it appears below (including punctuation).

    System.out.println("Hello, world!");

Press `⌘-S`
to save. 

Now run it!  Select `Run > Run Main` from the menu.  IntelliJ compiles your program and then executes it.  A box appears at the bottom and your program prints out the line "Hello, world!".

Congratulations, you've written your first Java program!
