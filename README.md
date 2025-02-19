This is a prototype for a mobile game that I created called Rebase. You can [play the online prototype here](http://danfischer87.github.com/game-off-2012/index.html). The final mobile version is currently available in the android app store for free here:  [Rebase for Android](https://play.google.com/store/apps/details?id=com.fischfro.rebase). It will be available for iOS very soon.

Rebase is a challenging puzzle game that tests your spatial awareness skills and ability to strategize and think ahead. Use four types of moves (rebase, reset, remove, and cherry-pick) to untangle these messy dots into a straight line. The goal of the game is simple; get your messy dots on the right to have the same yellow line as the straight line on the left, your goal line.

I was always getting asked by my coworkers to help them with their merges and I realized that no one else saw Git the way I did. I'm a visual person and always saw my commits as it is displayed in gitx but my coworkers weren't visualizing the commands they were using and their effects on their commit trees same way I did. If I asked them "You're doing a rebase of this branch on to this. What will your commit tree look like?" I'm not sure many of them could have drawn it out. This is what inspired me to make the game Rebase. I wanted everyone to be able to untangle their git commits visually and see using git as fun puzzle rather than a necessary nuisance. The moves in this game are the actual git commands (except for "remove"), my favorite being rebase. Sometimes it can get pretty crazy untangling that mess, and using rebase helps to keep things organized and in a straight line. In addition to helping developers visualize git commands I wanted everyone, developers, and non-developers alike, to be able to have fun untangling branches of dots. That’s all Rebase and git really are, fun and challenging puzzles. To do this I simplified the git commands in my game a little. You're not really on a branch but you have some effects of being on the yellow line branch. I also had to make some compromises as to how the rebase would work when you cannot be on any other branch. I also added remove, which is possible in git but doesn't have a specific command that I know of.

Level 7 in the prototype is really hard if you guys want a challenge.

Also excuse the bugginess of the prototype. If you want to really play the game without bugs you should play the mobile version.

Here are some screenshots of the final product: 

![](https://lh3.ggpht.com/ETr5YlWLLfhzbDALwQd5stcfpyACirr4iJL5_n1APVLxnBYPp6Jv4N1mcwHBGCgo2Vg=w705)


![](https://lh3.ggpht.com/Zlo0TUcilKRVt6wUU-kEB_Fs7RQQZvMB8Noq5t_fijsWrNEYi4ixnsK1UxOveb1Ewso)
![](https://lh3.ggpht.com/c3izXWl8GVlhQ9F2mvSrtawRXnJ5aA5CiyXLyloPcgUIkuIVajVT7_aaRrPVK5oPvb4)