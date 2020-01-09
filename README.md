# Side_Menu

1.) you have to add the libraries 

1.1) for animation

repositories {
      
        maven {
            url "https://jitpack.io"
        }
        }
        
 1.2) for animation
 
  implementation ('com.github.ozodrukh:CircularReveal:2.0.1@aar') {
        transitive = true;
    }
    
   1.3) for side menu
  implementation 'com.github.yalantis:Side-Menu.Android:1.0.1'

   
 2.) Style
 
  <style name="AppTheme" parent="Theme.AppCompat.Light.NoActionBar">
  
  
  3.) String values
  
    <string name="drawer_open">Open</string>
    <string name="drawer_close">Close</string>
    
 4) go to activity_main.xml
 
 https://github.com/btabur/Side_Menu/blob/master/activity_main.xml
 
 5) go to fragment_layout.xml
 
 https://github.com/btabur/Side_Menu/blob/master/fragment_layout.xml
 
 6)  create a java class
 
 https://github.com/btabur/Side_Menu/blob/master/ContentFragment
 
 7) go to MainActivity
 
 https://github.com/btabur/Side_Menu/blob/master/MainActivity
 
 
 
 
        
        
        
