# Aerial-Updater
This works with https://github.com/JohnCoates/Aerial
# Important
* This is  CURRENTLY not a AUTO UPDATER, it is a Workflow that when run will update Aerial to the latest version.
* Aerial updater is also in Beta Testing for Auto Update install Aerial Updater 1.1 Beta1 [here](https://github.com/NightRaider73/Aerial-Updater/releases/download/1.1/Aerial.Auto.Update.zip)
* We are currently working on a Auto Update feature in the future.
# Set up
1) Install [here](https://github.com/NightRaider73/Aerial-Updater/releases/download/1.0/Update.Aerial.zip).
2) Next move the file to your Desktop (Or somewere you can't forget about it).
3) Every week or so just double click the Workflow and it will auto update Aerial for you.
Simple and that, Thank you for installing!
# How it works:
1) It runs a simple Ruby script: `brew cask update`, which will update Brew Cask (Aerial can't be updated if Brew Cask is not).
2) Then it runs the Ruby script to update all Brew Cask installed packages: `brew cask upgrade`.
3) Workflow setup:
(Right here thanks)

We appriciate all Issues and Pull requests.
