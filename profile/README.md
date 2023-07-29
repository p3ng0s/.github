P3NG0S
======
*A Linux ISO with my config and usefull built in software*

![icon](https://github.com/p3ng0s/.github/blob/main/favicon.png?raw=true)

The main objective was for me to have an comfortable environement I can deploy fast and mostly reliably.
I also was looking for a way to package all of my things in an effective way other than just a tar ball.
p3ng0s is exactly what this is trying to resolve for me. I would not recommend anyone using this as it is
very customised for my use and comes with a lot of forks of software that I spent years adding functionality
that I personnaly wished existed wich you trying this out might not agree with. Since a lot of what I use
in my environement is open source I did let myself go and added as many features in as I wanted over the years.
I am still making this available since thorught the years people have been seeing what I run on my laptop I
have had a lot of questions on the tools how to use them and this would be an easy way to test out an environement
like mine without spending 8 years testing out alternatives.

If you do not know me and just stumbled on this I have provided a few screenshots and I am making a wiki
explaining as much as possible on how this works I will also do blog posts about this while I work on it
and there will be full README's on each section later down the line for now I finally managed to package all
of this over the span of a week and will be adding more later. There will also be a link to the ISO farelly
soon expecting (1 month max from today: 29/06/2023).

## Screenshots
A lot of these screenshots are just things I would do on my laptop and are not really indicative on what
p3ng0s can or can't do.

### sample red team workflow
![red team workflow](https://github.com/p3ng0s/.github/blob/main/screenshots/red_team_dark.png?raw=true)
This is a screenshot of the desktop running bloodhound on the left and the Havoc C2 client on the right
with under the c2 client in the background conky where I have a cool todo list feature to know what tasks
to work on next

### sample reverse shell workfow
![shell_and_autocmd_worklow](https://github.com/p3ng0s/.github/blob/main/screenshots/exploit_windows.png?raw=true)
This is a screenshot of what a typicall reverse shell workflow would look like at the top of the desktop
you can see the terminal with a shell that would in theory be running on windows. In this case for the
screenshot I just used a netcat wine cmd.exe pipe to simulate the environement and at the bottom of the
screenshot you can see one of my custom dmenu scripts. With this script I basically have a shortcut /
rubber ducky equivalent on the go where some commands are just to much of a pain for me to remember like
dissabling defender so with this fancy menu I have a shortcut to automatically type that command in and
I just have to press enter :)

### sample messing around workflow
![shell_xmenu](https://github.com/p3ng0s/.github/blob/main/screenshots/terminal_webshortcuts.png?raw=true)
In this screenshot there is a display of what a typicall terminal looks like when I first launch one. I have
a few banners configured to always keep me entertained during my long hours of deep intensive work and this is
a great display of my amazing humour. To the right of the terminal window there is a little menu. This menu
is where I launch my main favourite apps. Sometimes I am just not bothered to use shortcuts and want to click
around for fun so by default if you click anywhere on the desktop this menu should appear and you can run
your main apps from there. I also have usefull web shortcuts like the wifi pineapple one since sometimes it's
hard to remember the IP address and the port for those things.

### sample file management and desktop workflow
![file_browser_tint2](https://github.com/p3ng0s/.github/blob/main/screenshots/ranger_tint2.png?raw=true)
No matter how much linux nerds bash on windows (me included) I dod think having a little GUI desktop thing
at the bottom of the screen to click around through things is kinda fun (like with xmenu) so there is a autocolapse
menu bar at the bottom to navigate through open apps and launch a secret app launcher. I had it autocolapse
since I like to utilise as much screen space as possible for work with as little distractions as possible.
The main open window is my file browser ranger wich I don't spend enough time using.

## Software with custom configs
Here is a quick list from the top of my head what I remember working on for the past 8 years:
| name | what I added |
| ---- | -------------|
| dwm  | autorun features, light mode (no autorun on start), spiral layout, taskbar, loads of shortcuts, better background features |
| st   | light mode shortcut, emoji support |
| conky | todo list, passive network host mapper, open ports list, live view of status of my websites |
| tint2 | a cool looking theme |
| rofi | an other cool looking theme based of some else |
| xmenu | different arguments parsing method to match dmenu |
| dmenu | center mode, count on number of elements, a lot of other patches I honestly dont remember |
| bash | vim focused environement, PS1 git prompt, useful shortcuts |
| vim  | support for my xss_bomb project, a lot of pluggins see my vim config this one would be to long other wise |
