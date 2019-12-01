# BitmapShapes
A library to get different shapes of bitmap


Implmentattion:-

Add it in your root build.gradle at the end of repositories:

allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}

Add the dependency

dependencies {
	        implementation 'com.github.ani2498:BitmapShapes:0.10'
	}

Usage:- 

For ovalshape

final ImageView imageView = new OvalShape(context, width, height);
