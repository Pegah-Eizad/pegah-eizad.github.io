---
layout: post
title: SOFTWARE DEVELOPEMENT — Prioritizing speed over maintainability loses the race
author: Pegah Eizadkhah
date: '2020-06-18 14:35:23 +0530'
category:
        - maintainability

summary: Investing the time in maintainable code produces better results for everyone.
thumbnail: code-maintainability-blog.jpeg
---

We’ve heard it time and time again, the tail of the Tortoise and the Hare. Just as commonly heard, is developers cutting corners in terms of code maintainability and saying rather proudly: “I’ll just do [this], it’ll take me like two seconds” ….Aaaand a few furious clicks of the keyboard later, the seventh circle of hell has opened:

Spaghetti code, gigantic files, confusing variable names, lack of **separation of concerns**, folders within folder that make simple importing a path-ologocal nightmare (get it?), and worse of all… the Duct tape upon Duct tape upon Duct tape that is holding this app together is making debugging unnecessarily difficult, time consuming, frustrating, and costing you or your clients lots of MONEY.

Having to add new features on top of this? Hiring new developers just to reduce the number of bugs and getting them acclimated to this mess? Most likely you can’t hire juniors because they won’t be able to make sense of it. Spend double on a senior dev who will soon leave the project? Terrible client meetings? Good luck!

And just like that, two seconds turns into two months…and you have lost — a client, or valuable business time, but most importantly, you’ve lost in doing right by your staff (developers) in failing to teach them how to create great software. And chances are, if bad habits aren’t corrected, you will lose your next project too.

Slow and steady wins the race — some good development habits to stick by:

1. *Start clean*- practice **separation of concerns** when it comes to app architecture and folder structure (see below points).

2. App Architecture — practice **separation of concerns** — Don’t make the Frontend do the API work, don’t make the Backend do what needs to be part of the Frontend… and so on… this requires some thought and perhaps discussions with different teams.

3. *Folder structure* — the importance of folder structure is often neglected. However, it is a key organization feature for understanding component hierarchy and for visualizing it as well. Projects that neglect good folder structure are often a mess. **Separation of concerns** applies to folder structure as well… (e.x. get rid of unnecessary folders within folders).

4. *Tests* — if you’re not unit testing, then what are you doing?! Testing enforces clean code, clean code enforces passing tests, need I say more?

5. *Naming* — for both file and variable names, keep it short, sweet, and to the point. Think if a new dev joined the project, could they make sense of the code or folders based on the names?

6. *Strict code reviews* — Make sure your developers aren’t so stressed for time that they are auto-approving everything. Code reviews count, big time! Your developers should hold each other accountable for all of the above points: **separation of concerns**, code architecture, folder structure, naming, and tests (don’t just make sure they exist, make sure they pass!).

Cutting corners around these critical things in your software development practice means hindering projects and digging a hole in your codebase that you can’t climb out of. Invest the time in implementing these and it’s a win: for your clients, your money, and most importantly, your team — built to succeed over and over.