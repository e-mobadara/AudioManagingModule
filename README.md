
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

## Step3.Change XML files so that it conforms your game style.


## Step4.Use The Module to get audio files 

```
  MediaPlayer audiofile= 
		moblibAudioFileManager.getRandomAudioFile(Context,Type,Langue) ;
```
---
