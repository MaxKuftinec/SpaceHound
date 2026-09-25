# SpaceHound

**An AI agent that investigates disk usage and helps you reclaim storage safely**

## Why SpaceHound?

I use Windows, and at one point my disk was almost completely full. After some investigation, I discovered that Docker was taking up a huge amount of space. Uninstalling it freed nearly **50% of my disk**

Six months later, I'm facing the same problem again. My drive is almost full, with only around 20 GB remaining

The first time I solved the problem was interesting: I used **Cursor's AI agent**, which was originally meant to help me write code, to run commands on my machine and investigate what was consuming all that storage

That gave me an idea:

> What if there were an AI agent specifically designed to investigate your computer and tell you where all your storage went?

That's the purpose of **SpaceHound**

A lot of people probably have dozens, or even hundreds of gigabytes being consumed by things they don't fully understand: application caches, old development environments, temporary files, abandoned Docker images, package caches, logs, leftover application data, and more
* What is taking up the most space
* What each file, folder, cache, or application data is used for
* Whether it is likely worth keeping
* What can safely be cleaned up
* How much space can potentially be reclaimed

Eventually, SpaceHound should also be able to clean up unnecessary files automatically, with user consent of course 🤓
