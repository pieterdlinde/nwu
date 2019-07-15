## NWU - Potchefstroom

This is a simple AR implementation using Vuforia and Unity

# Setup Vuforia

First thing first -> Go to the official Vuforia website [Vuforia](https://developer.vuforia.com/) and create a new account

Using Vuforia in developer mode is free for X (a lot) amount of times. [t/c] -> [Pricing](https://library.vuforia.com/content/vuforia-library/en/articles/FAQ/Pricing-and-Deployment-Plans.html)

### Create a new Vuforia License

![Screenshot](https://github.com/pieterdlinde/nwu/blob/master/NWUImages/Screenshot%202019-07-15%20at%2011.13.03.png)

### Create a new Vuforia Target Manager

![Screenshot](https://github.com/pieterdlinde/nwu/blob/master/NWUImages/Screenshot%202019-07-15%20at%2011.20.54.png)

### Download the Vuforia database

# Install Unity

Go to the official Unity website [Unity](https://unity3d.com/get-unity/download) and download the developer version

### Create a new Project

![Screenshot](https://github.com/pieterdlinde/nwu/blob/master/NWUImages/Screenshot%202019-07-15%20at%2011.21.22.png)

### Change the platform to an Android Device

Go to build settings.

![Screenshot](https://github.com/pieterdlinde/nwu/blob/master/NWUImages/Screenshot%202019-07-15%20at%2011.30.44.png)

Click on the android icon on the left side.

![Screenshot](https://github.com/pieterdlinde/nwu/blob/master/NWUImages/Screenshot%202019-07-15%20at%2011.35.42.png)

Click on the 'Player Setting' button and change the bottom radio button to true.
 -- Vuforia Augmented Reality Support
![Screenshot](https://github.com/pieterdlinde/nwu/blob/master/NWUImages/Screenshot%202019-07-15%20at%2011.36.07.png)

Click Swith platform

### Import the Vuforia Database

Go to the package and add the downloaded package from Vuforia
![Screenshot](https://github.com/pieterdlinde/nwu/blob/master/NWUImages/Screenshot%202019-07-15%20at%2011.41.43.png)

Import

![Screenshot](https://github.com/pieterdlinde/nwu/blob/master/NWUImages/Screenshot%202019-07-15%20at%2011.42.42.png)

### Delete the default main Camera

![Screenshot](https://github.com/pieterdlinde/nwu/blob/master/NWUImages/Screenshot%202019-07-15%20at%2011.43.01.png)

### Add the Vuforia AR Camera

![Screenshot](https://github.com/pieterdlinde/nwu/blob/master/NWUImages/Screenshot%202019-07-15%20at%2011.43.10.png)

Remember to add the license key (Found on the vuforia website) in the vuforia setting

![Screenshot](https://github.com/pieterdlinde/nwu/blob/master/NWUImages/Screenshot%202019-07-15%20at%2011.59.13.png)

### Add the Vuforia Image

![Screenshot](https://github.com/pieterdlinde/nwu/blob/master/NWUImages/Screenshot%202019-07-15%20at%2011.55.55.png)

### Import the Unity Asset

Go to the Unity Asset Store and download the asset -> Stylized Earth

![Screenshot](https://github.com/pieterdlinde/nwu/blob/master/NWUImages/Screenshot%202019-07-15%20at%2011.57.34.png)


### Drag and Drop the lowpoly_earth_prefab file into the ImageTarget

### Drag and Drop the EarthSpinScript file into the lowpoly_earth_prefab


### Drag and Drop the EarthSpinScript file into the lowpoly_earth_prefab

### Boom you are done.  Press Run and Test









