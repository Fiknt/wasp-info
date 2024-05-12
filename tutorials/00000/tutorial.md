


### Downloads

WaspScripts are made to run on the legacy OSRS client which you can download [**here**](https://www.Runescape.com/downloads/oldschool.msi).

**Recommended install:** You can download Simba with the pre-installed Wasp Launcher from [**here**](https://github.com/torwent/wasp-setup/releases/latest/download/Simba-setup.exe). 
This is the recommended way to use WaspScripts and will be what's covered in this guide.

Optionally if you a developer and you know what you are doing Simba is an open-source program and you can find its release history on [**github**]https://github.com/Villavu/Simba/releases/).

### Installing Simba

**If you have an older installation of Simba** skip to the troubleshooting section at the bottom to uninstall before installing Simba.

**Now onto the installation procedure:**
Run the installer you downloaded in the previous step. 

Depending on where you placed your Simba.exe, the first time you run it you might get a warning from **Windows Defender SmartScreen** like this:
![warningimg](https://i.imgur.com/DBJtvgd.png)
Click "**More info**", and then "**Run anyway**" as shown in the image.

Once the installer finishes, you'll get the option to immediately launch Simba. Alternatively it will create a desktop shortcut & start menu folder and you can open it from there.

**Recommended:** Associate Simba scripts with Simba when asked upon opening Simba for the first time:
![associatescripts](https://i.imgur.com/uwZGAJb.png)

**Optional:** Disable console window in View, this is up to the individual but this is what I personally do.
![img04](https://i.imgur.com/WYOGoUx.png)

## Using the Wasp Launcher

Click the **green play ▶️ button twice** in order to launch the in-built WaspLauncher. 
![img05](https://i.imgur.com/hxAlnVU.png)

Click Discord login when asked to login, and authorize Wasp when Discord asks you to.
Copy the token given or click the 📝 icon, wasp launcher should read what you've copied but if not just paste it into the box in the WaspLauncher.
![tokenimg](https://i.imgur.com/K0AfzNy.png)

In the launcher you will find free scripts as well as scripts you've subscribed to, along with a handful of other useful features like auto-updating scripts & packages required to run Waspscripts.
![launcherimg](https://i.imgur.com/XB1XxzL.png)
PS. Scripts in yellow are premium scripts you're currently subscribed to.

**Recommended** Enable auto-updating in the top right of the Wasp Launcher to always stay up to date.
![updateimg](https://i.imgur.com/BRLTY5V.png)
If you choose to date manually you can do so with the update buttons, it will show when you are out of date when your versions are in red text like in the picture.

**Getting errors running a script?** Try hitting the re-install buttons on SRL-T and WaspLib, and if that didn't help check out the troubleshooting section at the bottom.


# Downloading and running a script:

Find a script you'd like to run, for this example we'll be using the Wasp Alcher. 

Hit the install button, then click open script. Remember to read the info about the scripts themselves on how to run them and their requirements.
![scriptexample](https://i.imgur.com/3Mh4i84.png)


Now you have to use target selector to target the Runescape client. Make sure you target Runescape like shown in the gif, incorrectly targetting will result in errors.
![targetselectorgif](https://i.imgur.com/Z1vTX7w.gif)

PS. You can do this at any point, and you only have to do it when you boot up Simba or if it asks you to re-target.

Once you've targetted you will see the current text in the output of Simba, the dimensions should be 765x503 (unless you have Windows display scaling enabled) and the classname should be SunAwtCanvas.
![img06](https://i.imgur.com/yBDpnnp.png)

You're almost done, now fill in your Runescape account info so the script can log back in after breaks and **CLICK ADD** to save your details.
![img07](https://i.imgur.com/PKnVWoC.png)

And that's it, you've completed the installation and you are ready to run the script assuming you've followed the scripts instructions. 

# A few additional settings (OPTIONAL)

Since I used the alcher as an example, I just want to quickly note that an item and a noted item has to be added separately to the alch list.
[!img08](https://i.imgur.com/GgoSQSQ.png)

Antiban features can easily be turned off and on in the antiban manager, you can also adjust when the script goes to sleep and for how long (**Sleep hour is a 24 hour time format**)
![img08](https://i.imgur.com/feo0ayC.png)

Turning off the HUD that covers the chatbox in some scripts, and disabling your ability to click the Runescape client (this will help against you misclicking and breaking the script)
![img09](https://i.imgur.com/QNTa6hH.png) 
For the HUD you can make it transparent or uncheck the HUD Report checkbox, and enabling Block Real Input will help against misclicks.

Adding your own worldlist.
![img10](https://i.imgur.com/xZqcxbX.png)
Enter each world separated by a comma and hit the Save button. PS: Pressing delete will delete all of your account info, not just the worlds.


--------------



# TLDR Guide

1. Download [WaspScripts setup](https://github.com/torwent/wasp-setup/releases/latest/download/Simba-setup.exe)
2. Run the installer, allow it if windows defender asks you to.
3. Click the  play ▶️  button twice to run the wasp launcher.
4. Click Discord login when asked to login, and authorize Wasp when Discord asks you to.
5. Copy the token given or click the 📝 icon, wasp launcher should read what you've copied but if not just paste it into the box.
6. Select a script, click open script. 
7. Use the target selector to target the **legacy** Runescape client, if you don't have this download it at the top of the guide.
8. Enter your account info, click add. 
9. Adjust script settings as needed and run it, you're done.


If you run into any problem, either read the whole guide or check the [faq section](https://waspscripts.com/faq)



--------------

# Troubleshooting

**Uninstalling:** To uninstall Simba simply use the uninstaller located in C:\Users\WindowsUser\AppData\Local\Simba (Replace WindowsUser with your user), after that you can delete the Simba folder.
![uninstall1](https://i.imgur.com/8SmGEvP.png)

**Running into errors:** Check the the [common errors](https://waspscripts.com/faq) page, or [join the discord](https://discord.com/invite/YMYUahmww9) and come to the help-chat channel so we can figure out your problem together.

