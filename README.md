# YantraLauncher-Yogdan
This repository is for contributing code to be used in the Closed-Source Yantra Launcher for increasing Developement Speed, testing pre-release builds, and finding bugs faster. 🐛🚀

## Why this name 🤔
You Probably already know the reason behind the name of Yantra Launcher. Yeah right, **Yantra**_(yan·truh)_ means Device and so this Launcher is basically a minimal Launcher for your device. 📱

Now coming to **Yogdan** _(/yogadāna/ Sanskrit योगदान)_: **Yogdan means Your Contribution. This repo is created for contributing to the Yantra Launcher.🙌

## Back-Story 📖
First of all, thank you for all the love for Yantra Launcher. When I started this project, I didn't expect that there are people like me who really love these kind of apps. As time passed by, more and more people, including programmers, senior managers, gamers, Youtubers, etc., started using Yantra Launcher as their default Home Screen and we are still a rapidly growing family. ❤️

As the number of users increased, so did their likes and dislikes and feature requests. This is the best phase as we can get feedback and discuss the app from a wide variety of people who actually care about improving what they use daily.

But this has also led to a slightly increased load on me as a solo Developer, juggling between University, side-projects, internships, and other things. But thankfully we also have some members in the community who really love to contribute to the project using their Development Skills. That's when I decided to have ***a repo where users of the app can also help with the development of the app.***

## How to contribute? 🤝
Thank you once again for deciding to contribute to the app. I am really grateful to you all! 🙏❤️

Before we start, let's understand _how Yantra Launcher works..._

Each command you enter into the terminal is directly passed to a Command Handling function. This function is shown in [CommandHandling.kt file](CommandHandling.kt).
Every time something is printed to the terminal output, Yantra Launcher uses a custom `printToConsole` function as shown in [Output.kt file](Output.kt).

**Refer to the above 2 files before moving forward so you get an idea of how to use them in your functions.**

Moving forward, commands in Yantra Launcher are nothing but Kotlin functions. See [sendtext.kt](commands/sendText.kt) for the implementation of the `text` command in Yantra Launcher

- Now to contribute a new command from scratch, upload it in the [commands](/commands) directory like the sample command shown in [sendtext.kt](commands/sendText.kt) file.

- To improve an existing command that's available in the [commands](/commands) directory, simply open a pull request. 🛠️🔄

- To improve an existing command that's not found in the [commands](/commands) directory, open an issue and we will discuss it there if I can provide the code for the existing command.  💻🔧
