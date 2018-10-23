# Aerial-Updater
This works with https://github.com/JohnCoates/Aerial
## Important
* This is  currently not a auto updater, it is a Workflow that when run will update Aerial to the latest version.
* Aerial updater is also in beta testing for Auto Update install Aerial Updater 1.1 Beta 1 [here](https://github.com/NightRaider73/Aerial-Updater/releases/download/v1.1beta1/Aerial.Auto.Update.zip).
* We are currently working on a Auto Update feature in the future.
## Set up
1) Install [here](https://github.com/NightRaider73/Aerial-Updater/releases/download/v1.0/Update.Aerial.zip).
2) Next move the file to your Desktop (Or somewere you can't forget about it).
3) Every week or so just double click the Workflow and it will auto update Aerial for you.
Simple as that, Thank you for installing!
## How it works:
1) It runs a simple Ruby script: `brew cask update`, which will update Brew Cask (Aerial can't be updated if Brew Cask is not).
2) Then it runs the Ruby script to update all Brew Cask installed packages: `brew cask upgrade`.
3) Workflow setup:

![screen shot 2018-10-22 at 1 52 22 pm](https://user-images.githubusercontent.com/44180668/47318751-be405a80-d601-11e8-8081-2cb6ce7adb5a.png)

## Community
- **Found a bug?** [Open an issue](https://github.com/NightRaider73/Aerial-Updater/issues/new). Try to be as specific as possible.
- **Have a feature request?** [Open an issue](https://github.com/NightRaider73/Aerial-Updater/issues/new). Tell us why this feature would be useful, and why you and others would want it.

## Contribute
We appreciate all pull requests.
