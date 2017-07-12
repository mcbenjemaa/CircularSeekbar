# CircularSeekbar
[![](https://jitpack.io/v/medmedchiheb/CircularSeekbar.svg)](https://jitpack.io/#medmedchiheb/CircularSeekbar)

CircularSeekbar is a android library to create seekbars  

Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
  Step 2. Add the dependency
  
  	dependencies {
	        compile 'com.github.medmedchiheb:CircularSeekbar:1.0.1'
	}


Step 3.  add xml on your layout 

<octadev.circularseekbar.CircularSeekBar
                android:id="@+id/circularSeekBar1"
                android:layout_width="92dp"
                android:layout_centerInParent="true"
                app:progress="50"
                app:max="150"
                app:circle_color="#969696"
                app:circle_progress_color ="#fff"
                app:lock_enabled="false"
                app:pointer_alpha_ontouch="10"
                app:pointer_color="#fff"
                app:pointer_halo_color="@android:color/transparent"
                android:layout_height="92dp"
                />
                
  

