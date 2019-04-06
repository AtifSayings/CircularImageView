# CircularImageView
[![](https://jitpack.io/v/mohammadatif/CircularImageView.svg)](https://jitpack.io/#mohammadatif/CircularImageView)


CircularImageView to show your images in Circular Shape.
* min SDK 16 (Android Jellybean 4.1)
* written in Java

A lightweight and fully customizable library to show your images in Circular Form

## Installation

Add this into your root build.gradle file:

```java
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
```
Add the dependency to your module build.gradle:
```java
dependencies {
	        implementation 'com.github.mohammadatif:CircularImageView:1.0.0'
}
```
## Usage
```xml
<com.blogspot.atifsoftwares.circularimageview.CircularImageView
        android:layout_width="250dp"
        android:layout_height="250dp"
        android:layout_centerHorizontal="true"
        android:layout_centerVertical="true"
        android:src="@drawable/firebase_logo"
        app:c_background_color="@color/colorPrimary"
        app:c_border="true"
        app:c_border_color="#AFA5A5"
        app:c_border_width="10dp"
        app:c_shadow="true"
        app:c_shadow_color="#000"
        app:c_shadow_gravity="end"
        app:c_shadow_radius="5dp" />
```
