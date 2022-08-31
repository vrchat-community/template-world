# VRChat World Project Template

This repo makes it easy to start a new VRChat World project!

<details>
<summary>

## I Wanna Go Fast
If you don't care about using source control and just want to make something quick:

</summary>

1. [Download this Zip](https://github.com/vrchat-community/template-world/archive/refs/heads/main.zip) and unpack it somewhere.
2. Go to "3. Open the Project" below.

</details>

<details>
<summary>

## I Want To Use Source Control
This template is set up to easily make your own GitHub projects, and we highly recommend you take this route.

</summary>

## 1. Make Your Own GitHub Project

Press [![Use This Template](https://user-images.githubusercontent.com/737888/185467681-e5fdb099-d99f-454b-8d9e-0760e5a6e588.png)](https://github.com/vrchat-community/template-world/generate)
to start a new GitHub project, and follow the directions there. This is an optional step but gets you started with using GitHub for source control so you'll always have a backup.

## 2. Clone or Download the Project

If you're not ready to use git yet, you can download a zip of your project by pressing the "Code" button and then "Download Zip".

If you're familiar with git, use your favorite client or the command line to clone your repository.

</details>

<details>
<summary>

## 3. Open the Project

</summary>

Use Unity 2019.4.31.f1 to open the project. Press "OK" on the dialog that offers to download the required VRChat packages.

![image](https://user-images.githubusercontent.com/737888/185468226-33492169-c1f5-4b27-b5c4-83febb5e6e66.png)

</details>

<details>
<summary>

## 4. Load the Example World

</summary>

Find the "VRChat SDK" item in the menu bar at the top of the Unity Editor window, press it to open, then choose "Samples > UdonExampleScene".

![samples-udonexample-scene](https://user-images.githubusercontent.com/737888/186485286-2758cec3-ec89-4598-a451-9fa12fa27616.png)


Once the scene opens, choose "File > Save As..." and give the scene a new name.

Then modify the scene however you'd like - you learn about all the examples in [the UdonExampleScene](https://docs.vrchat.com/docs/udon-example-scene) or learn about [Getting Started with Udon](https://docs.vrchat.com/docs/getting-started-with-udon).

</details>

<details>
<summary>

## 5. Test Your World

</summary>

When you're ready to try out your World, find and choose the menu item "VRChat SDK > Show Control Panel".
* Sign into your VRChat Account in the "Authentication" tab.
* Switch to the "Builder" tab and choose "Build & Test".
* After a quick build process, VRChat should open up in your test world!
* If you have any issues making a test world, check out [our docs on Using Build & Test](https://docs.vrchat.com/docs/using-build-test).

</details>

<details>
<summary>

## 6. Publish Your World

</summary>

When you're ready to publish your World so you can use it regularly:
* Return to the VRChat SDK Control Panel in your Unity Project
* Switch to the "Builder" tab and press "Build and Publish for Windows".
* This will build your World and add some publishing options to your Game window.
* Fill out the fields "World Name", "Description" and "Sharing", and check the terms box "the above information is accurate...".
* Press "Upload".

Return to VRChat - open the "Worlds" menu, then scroll down to the section named "Mine". Choose your world from the list and press "Go" to check it out!

</details>
