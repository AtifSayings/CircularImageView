# CircularImageView
[![](https://jitpack.io/v/mohammadatif/CircularImageView.svg)](https://jitpack.io/#mohammadatif/CircularImageView)

[![license](https://img.shields.io/github/license/DAVFoundation/captain-n3m0.svg?style=flat-square)](https://github.com/AtifSayings/CircularImageView/blob/master/license.txt)

CircularImageView to show your images in Circular Shape.
* min SDK 16 (Android Jellybean 4.1)
* written in Java

A lightweight and fully customizable library to show your images in Circular Form

## Screenshots
<div align="center">
    <img src="https://github.com/mohammadatif/CircularImageView/blob/master/screenshots/screen1.png" width="300px"</img> 
    <img src="https://github.com/mohammadatif/CircularImageView/blob/master/screenshots/screen2.png" width="300px"</img> 
</div>

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
### Using XML Layout
```xml
<com.blogspot.atifsoftwares.circularimageview.CircularImageView
        android:id="@+id/imageView"
        android:layout_width="200dp"
        android:layout_height="200dp"
        android:layout_centerHorizontal="true"
        android:src="@drawable/profile_pic"
        app:c_background_color="@color/colorPrimary"
        app:c_border="true"
        app:c_border_color="#4A97E4"
        app:c_border_width="5.5dp"
        app:c_shadow="true"
        app:c_shadow_color="#000"
        app:c_shadow_gravity="end"
        app:c_shadow_radius="5.5" />
```
### Programatically
```java
CircularImageView circularImageView = findViewById(R.id.imageView);
circularImageView.setImageResource(R.drawable.profile_pic);
circularImageView.setBackgroundColor(getResources().getColor(R.color.colorPrimary));
circularImageView.setBorderWidth(5);
circularImageView.setBorderWidth(10);
circularImageView.setBorderColor(getResources().getColor(R.color.colorPrimaryDark));
circularImageView.setShadowGravity(CircularImageView.ShadowGravity.BOTTOM);
circularImageView.setShadowRadius(9);
```
## Usage
MIT License

Copyright (c) 2020 Atif Pervaiz

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
