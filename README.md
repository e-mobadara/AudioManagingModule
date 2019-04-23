
# AudioManagingModule

AudioManagingModule is a module for managing multiple applications audio files. 

---

# Requirements

minSdkVersion 17+

compileSdkVersion 28

---
# How to


## Step1. Add the module to Your project


## Step2. Add the dependency

```
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```

## And In your build.gradle

```
dependencies {
	        implementation 'com.github.e-mobadara:AudioManagingModule:v0.0.1'
	}
```

## Step3.Move packages to your project.


## Step4.Change XML files so that it conforms your game style.


## Step5.Use The Module to get audio files 

```
  MediaPlayer audiofile= 
		moblibAudioFileManager.getRandomAudioFile(Context,Type,Langue) ;
```
---
