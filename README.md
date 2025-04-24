# Hello, I'm Furock

## About me
I'm curently a software tester (I develop automated API tests in java and groovy against a backend) and like to implement some things also in my free time

## Projects

|Project|State|Started|Description|Technologies|
|-------|-----|-------|-----------|------------|
|[AutoClicker](https://github.com/Furock/AutoClicker)|Finished\*|2025|Self-explanatory|java, swing for ui, gradle, vscode|
|[FileServer](https://github.com/Furock/FileServer)|Finished\*|2025|(Local) Web Server to share files within the network|python, html, js, flask, vscode|
|[TextFieldWebSocket](https://github.com/Furock/TextFieldWebSocket)|Finished\*|2025|(Local) Web(socket) server to edit a text field simultaneously from multiple devices within the network|python, html, js, FastAPI, uvicorn, vscode|
|[YT-DL-ChromeExt](https://github.com/Furock/YT-DL-ChromeExt)|Ongoing|2023|Google Chrome Extension for YT-DLP|Chrome API, html, js, python, vscode|
|[CircleFlowers](https://github.com/Furock/CircleFlowers)|Frozen|2023|HTML Canvas Experiment with colored circles|html, js|

Finished\* = works, but release package still has to be attached

## Project Details
<details> 
<summary>AutoClicker | finished</summary>
  
### Motivation

I liked clicker games and there this automation makes sense. Besides a friend of mine was unsatisfied with her downloaded autoclicker.
    
### About the program

It has a minimal UI (photo is coming soon), and it's more for technical users than non-technical users:
You can set the time between pressing the click button and releasing it and the time waited between two clicks. 
The Background: Everyone has different hardware and it's difficult to guarantee x clicks per second. Instead you can control finer settings and also use an integrated test how many clicks per seconds there are 
  
### Further Potential

* better UI
* using C/C++ for better performance
* make clicks/s settable
</details>

<details> 
<summary>FileServer | finished</summary>

### Motivation

I had files on several devices in the same network and wanted to gather them on one device, without them needing to leave the private local network and without USB sticks or bluetooth.

### About the program

(photo is coming soon)

### Further Potential

* creating folders on the server
* deleting files on the server
</details>
<details>
<summary>TextFieldWebSocket | finished</summary>

### Motivation

I was interested in how one could establish a connection that sends data in real time and WebSockets were an answer.

### About the program

The program starts a server and when multiple devices visit it with a browser, they can write in the same test area
(photo coming soon)

### Further Potential

* Not just writing in a text area but editing the same file
* Have the cursor in the text area at different locations at different devices (currently they are in the same place)

</details>

<details>
  <summary>YT-DL-ChromeExt | ongoing</summary>

  ### Motivation

  In 2023 I was asked if it was possible to run yt-dl (which you can easily download on linux as cli) as a chrome extension on windows 7. To find a way how this was possible became my motivation

  ### History / How it works
  
  1. At the end of 2023 I started to implement the extension part without yt-dl. For yt-dl I had the idea of using a linux container, which might seem to be a good idea but wasn't that simple on windows 7.
  2. Then I put the project on ice because it wasn't urgent and there was some private stuff going on.
  3. 2025 I continued the project and found out that you can install yt-dl on windows with python. Yet the current python versions don't run on windows 7. After a bit of research I found the python version (3.8.10) and the version of yt-dl's dependency ffmpeg that run also on windows 7 and it worked

  ### About the program

  (photo coming soon)

  ### Current Status

  The first version of the program works but still is insecure and too quiet (you don't know what the program is doing)
  Current goal is making the program more secure and more verbose. So you know when the program started and ended and some steps in between.
  
</details>

<details>
  <summary>CircleFlowers | frozen</summary>

  ### Motivation
  
  I just wanted to experiment with HTML Canvas

  ### About it
  
  (photo coming soon)
  In the meantime you can have a look yourself (but be warned that it is buggy)
  https://furock.github.io/CircleFlowers/

  ### Current State

  Frozen. I do not work on it currently and I do not plan to do so in the near future.
  It is somewhat buggy (when you change the settings and does not apply instantly but only if some certain other settings are changed)
  My last work was to try to automate tests for this html but this is also frozen (and not online)

</details>
  
## Future Ideas

<details>
  <summary>Ideas</summary>
  
  * Not using this markdown readme as kind of portfolio because you can't nest these collapsibles well enough
  * Writing a program to read the hard drives (goal: understand how hard drives store data and maybe to be able to restore deleted data)
  * Writing a game where you can collect and train spells (with the feeling of the anime frieren). I know that is going to be big, so maybe start with a MVP, like: 1 village, 10 spells, 10 quests
  * Founding the genre bot-enic gaming: Games that offer an API with the purpose that the players develop gaming clients/ manipulate the game 
  
</details>

<!--
**Furock/Furock** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
