# RN MenuBar for macOS sample Project

This is a sample project of a menu bar app on macOS using **react-native-macos**, if you want to create one yourself you can follow [these steps](https://ospfranco.github.io/post/2020/05/23/how-to-make-a-react-native-menu-bar-app-for-mac-os/)

![Image description](https://github.com/ospfranco/rn-macos-menubar-template/blob/master/assets/RNMENUBARAPP.JPG?raw=true)

## Caveats

Not all libraries have react-native-macos support, support is slowly being added but you might need to work around many limitations, .

**react-native-vector-icons** work fine if you follow the macOS steps, it has been linked already on this project, so you can use directly and I also added a "macos:install" command so you can do a pod install, but the pod installation is messed up in this version.

**react-navigation** also does not work, support is being added alebit slowly, you will have to make due with the old v2 branch that uses pure javascript.

**As time passes by this repo will become obsolete, the original steps on my blog should be enough for anyone trying to replicate it though, so it is now archived**
