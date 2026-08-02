# NatBoot | Notifications on launch

**NatBoot** is a simple and lightweight submod for Just Natsuki which allows for random Notifications to appear on your desktop depending on Natsuki's Affinity.


> [!NOTE]
> This submod would've never been made if it wasn't for Zombie_B and Zhaumbie, thank you to both of them for the motivation to start making submods :heart:
>
> But anyways, This submod was brought to you by Singularity (aka. Me)

> [!IMPORTANT]
> Unless you have the [Remote Notifications for Just Natsuki](https://github.com/Zombie-Bdev/Remote-Notifications-for-Just-Natsuki/tree/main) mod by [Zombie_B](https://github.com/Zombie-Bdev) installed, this mod only works on Windows. (At least I think so, I don't have anyone to test.)
> 
> This is an unofficial submod for Just Natsuki, a mod for Doki Doki Literature Club.
> It is not affiliated with Team Salvato in any way.
> And it is not affiliated with the Just Natsuki Team in any way either.
>
> As of version 1.1.0, You can now toggle the notifications on and off via the in-game settings (Specifically, the Activity notifications)
>
> Please remember to always back up your persistent file, which can be found in ```%APPDATA%\RenPy\JustNatsuki```

# Preview:

## Windows Preview:

<img width="800" height="427" alt="ezgif-580cf8c1196c73e3" src="https://github.com/user-attachments/assets/c5406f71-38f2-49bd-8e15-17d62f1ce6b4" />

## Ntfy Preview:

<img width="418" height="930" alt="ezgif-5850a2703b3307a4" src="https://github.com/user-attachments/assets/2445303b-1f40-46ed-9a19-3795e3821c96" />

# How does this mod work?

This submod has priority of 1 when launching the game, which basically means, it is one of the first thing that launches when loading Just Natsuki, which then, the script gets Natsuki's Affinity level using the vanilla functions isLove, isNormal and etc.
Using that, random messages are selected accordingly to Natsuki's Affinity, and the script then uses a function to translate [player] and the emoticons, which, after doing that, uses the vanilla function jn_activity.notifyPopup to send the notification to your desktop.
And if the script detects that you have [Remote Notifications for Just Natsuki](https://github.com/Zombie-Bdev/Remote-Notifications-for-Just-Natsuki/tree/main) installed, it also sends a message there too!

# Installation.

> [!IMPORTANT]
> To install the mod, there are 2 different methods.
>
> Method 1:
> You can go to ```C:\Program Files (x86)\Steam\steamapps\common\Doki Doki Literature Club```, where you can then head into the ```game``` folder where you need to create a folder named ```submods``` and put the .rpy file there.
>
> Method 2: Go to your steam library and right click on Doki Doki Literature Club. Press Manage then Browse local files. Which you can then go in the ```game``` folder, create a folder named ```submods``` and put the .rpy file there.
>
> Why do you need a folder? If you don't create a folder, a red warning will appear every time you launch Just Natsuki at the top left of your screen. It's harmless, but annoying.
