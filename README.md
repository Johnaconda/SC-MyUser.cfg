Hello There Ladies and Gentlemen, i got back to Star Citizen recently and noticed my average Frames in the game was not exactly good at any means ~10-30 fps on my current setup.
so i decided to make some optimizations that includes a user.cfg for the game config and visuals, Windows 10 debloat and a star citizen nvidia profile,
Setup:
Intel i7 6800k i belive stock clock speeds,
32gigs of ram ~3000mhz,
Nvidia Gtx 1080, overclocked to ~2000mhz
Os: Windows 10.

The Tools i have used are:
WinaeroTweaker for debloating
source: https://winaerotweaker.com/

uninstallView also for debloating
source: https://www.nirsoft.net/utils/uninstall_view.html

And Orbmu2k's NvidiaProfile Inspector for creating, importing and exporting a Star citizen Nvidia profile.
source: https://github.com/Orbmu2k/nvidiaProfileInspector

i also tried to unpark my cpu cores but that really dident matter much.
source: https://www.coderbag.com/programming-c/disable-cpu-core-parking-utility

i'm not really going into detail on what i have debloated but i have disabeled many Windows features that i decieded was not necessary and removed alot of "bloatware".
i highly recommend looking debloating up and you should also be aware that disableing some features may cause windows to stop functioning as intended, use at your own risk!!

what i am going into "detail" of though is the Nvidia profile and the user.cfg for Star Citizen.
most of the user.cfg commands are commented in the config and the settings i currently have is for the best visual quality i can achieve with decent to exelent ingame framerates at 1440p!

This user.cfg increased my fps by 20+ and still keeps the good visuals within the game.
There are some issues with it though:
1. The Lightning takes some time to actually take it's "form" in darker areas might be an eyeaddaption thingy, its like it slowly loads in
and sometimes there are bright spots/areas where the lights should not really be at the first place(missplacement of light sources maybe?)
2. There is some issues for me when you are close to planets and the thrusters on the ship starts to pick up dust clouds and that causes massive fps drops/sttuuuttters with bigger ships(c2-m2-a2).
There are a few settings that is useless nowdays, ill update them once i get a nice config.

Here are some example screenshots of User.cfg :

<img src="https://github.com/Johnaconda/SC-MyUser.cfg/blob/main/Screenshots/ScreenShot-2023-12-30_03-18-33-56F.jpg?raw=true" alt="Example2" title="Seraphim station">

And this is the most stressfull area in loreville i've found so far.
<img src="https://github.com/Johnaconda/SC-MyUser.cfg/blob/main/Screenshots/ScreenShot-2023-12-30_03-26-51-E59.jpg?raw=true" alt="Example2" title="Seraphim station">

<img src="https://github.com/Johnaconda/SC-MyUser.cfg/blob/main/Screenshots/ScreenShot-2023-12-30_03-09-27-242.jpg?raw=true" alt="Example1" title="Seraphim station">

<img src="https://github.com/Johnaconda/SC-MyUser.cfg/blob/main/Screenshots/ScreenShot-2023-12-30_03-39-57-CF2.jpg?raw=true" alt="Example3" title="Seraphim station">

<img src="https://github.com/Johnaconda/SC-MyUser.cfg/blob/main/Screenshots/ScreenShot-2023-12-30_03-53-45-1CB.jpg?raw=true" alt="Example4" title="Seraphim station">

And Credit for Isaard and his config, without it i would not have dived down this rabbit hole.
source: https://github.com/Isaard/Optimized-USER.cfg

As for the nvidia profile i turned basically everything off,fxaa,msaa and whatnots and enhanced the profile to performance i also belive i started Gsync for borderless window for smooother gameplay, 
the Nvidiaprofile inspector makes it possible to edit "hidden" 3d profile settings so i started to look deeper into this and this profile is what i have come up with so far and it has gained me 5-10 smoother fps.
i will continue to edit the configs untill i feel they are fit and im well aware that CIG is working on the new graphics settings wich will probably render this optimization useless in the future.

The User.cfg is the official tweak meanwhile the v2 is the one im currently using, editing and update as i see fit.