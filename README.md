#DebugView



Debug View is a simple implementation of method swizzling to add red borders over each view for Debugging.

##Installation


1 - Download the proj and copy "UIView+Debug.h" & "UIView+Debug.m" in your project
2 - Add the following import in your [project-name]-prefix.pch file
      #import "UIView+Debug.h"
      
      
###If you want to debug a single controller or view

Simply import the "UIView+Debug.h" into that controller or view class

##Examples 

*Note: The examples are generated by randomly creating UIViews*

![Screenshot 1](./screenshot1.png)

![Screenshot 2](./screenshot2.png)

##Or you could try code injection

![Phone.app after code injection](./screenshot3.png)

![Game center after code injection](./screenshot4.png)
