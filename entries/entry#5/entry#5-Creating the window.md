<h1>Java API-Independent-Study</h1>
<p>Learning to make a game out of Java for the next 9 week, the third week, I watch a Youtube series on how to make a game in Java.</p>

<h2>Watching YouTube Videos: RealTutsGML, trying to make a window for a game.</h2>

<p>After watching the RealTutsGML first video, I learn a lot of interesting mechanic on Eclipse and the Java language. This is a basic format for creating a Java game. This tutorial explained by the YouTuber is the main program to set up the game to make it work. As working with this program, I realize that I had some trouble understanding some of the basic functionality of the code. As a result of this, I asked my partners for assistance with learning the code.</p>

<ol>

<li>Class: Window</li>

<p>To understand the Window class code, I made an adjustment on how I understand the code.</p>

<p>On line 10, the serial number stated allows the code to run a specific function and is only shown to the owner.</p>

<p>On line 12 to 13, the window class is initialized as width, height, String, Game inside it parameter. The JFrame is then collected into a new JFrame where the title params are.</p>

<p>On line 15 to 17, the difference is as followed: setPreferredSize allows the dimension to be set as preferred, the setMaximumSize maximize the window size, the setMinimumSize makes the window smallest size.</p>

<p>On line 19 to 24, the JFrame will close after being exited, this starts after the program is closed. The setResizeable allows the frame to be false as it will not change the window size. The setLocationRelativeTo params are null to where it is located on the screen. The game is added and the visibility of the window is set as true. Finally, the game would then start, calling the Game class/</p>

![What Game Object Code should look like.](image-window.jpg)


<li>Class: Game</li>

<p>To understand the Game class code, I made an adjustment on how I understand the code.</p>

<p>On line 34 to 37, it will not return the value when the game is started. The thread is being created as new when it is started and the game will return true if the game is running.</p>

<p>On line 40 to 45, it will not return the value when the game is stopped. As the code run through a try, the thread is joined together and if it's not able to run, it will return false. When the code is a catch, it shall print out the e trace statement.</p>

<p>On line 49 to 74, this code allows the game to run with FPS and known to be popularly used by the game developer. The code will not return the value as it will run.</p>

<p>As the system time is run by nana time, then it will be minus to the total last time. The amount of tick is equal to how much the monitor refresh rate is such as 60 frames per second to have a smooth game. The tick would be divided from one billion to the tick of 60 FPS. The time for delta is equal to 0 as follows when the timer is minus to the system current millis in time.</p>

<p>Line 57 to 62 is confusing but on line 64 to 74m the code runs if the while statement runs. It would render the game and render the frames as it adds up.</p>

<p>On line 68 to 74, the system runs to the timmer when it is greater then 1000, the timer would equal to or add up to 1000. The system would print out the following FPS counter to the frames on the windows. The frames would be equal to 0 as a replacement. Finally, the game would stop line 49 to 71, then it will run again.</p>

![What Game Object Code should look like.](image-game1.jpg)

<p>On line 77 to 98, the game would not return the value of the tick. The game would also not return the value of the render method. Within the render method, the BufferStrategy also the FPS to be max out so it will not crash the system, console or computer. The buffering strategy must equal to 3 as going above 3 will most likely crash the system.</p>

<p>The Graphics of g is minus by what it draws from its graphics. The color would set the background of the window to be black as it will make the screen from white to black. The Graphics would be disposed of the buffer strategy would show. The value of main will not return but it will create a new game every time.</p>

![What Game Object Code should look like.](image-game2.jpg)

</ol>


<h2>Takeaway</h2>

<ol>

<li>If you can not understand the code, ask for help from a partner or a fellow colleague who is working on similar interest as you.</li>

<p>Working on this project is harder then I thought, although it is much easier working with a partner, I still tend to struggle in specific or most area at best. But as long as you have someone to talk about what kind of struggle you have with your code or just trying to understanding it. You won't need to be stressed out. A good advice they gave me was to reread and try to understand your own preference, then compare that with what others say about the code. You can still tinker with your preference if it still helps you in the long run.</p>

</ol>