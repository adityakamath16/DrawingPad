# DrawingPad


## Android Open-source app for developers to directly add a Drawing pad to their Android app.


## Features:

 - Directly add an drawing pad to your Android app
 - Use any color to draw on the drawing pad
 - The Thickness of the Drawing can be selected as per your interest
 - More features will be added soon :-)
 
 
## Demonstration
|Demo DrawingPad|
|:---:|
|![Alt Text](https://firebasestorage.googleapis.com/v0/b/github--images.appspot.com/o/DrawingPad%2FDrawingpadoptimized.gif?alt=media&token=d8b2611a-b9bb-4ea0-97b2-ef1c956a3a1a)|

 ## Clone Repository
 ```
  https://github.com/adityakamath16/DrawingPad.git    
 ```
 
 ## XML Usage
 ```xml
 <com.args.drawingapp.DrawingView
        android:id="@+id/drawing_view"
        android:layout_margin="5dp"
        android:layout_weight="1"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"/>
     
 ```
 
 ## Kotlin Usage
 ```Kotlin
    //for setting the size of the brush (as of now 20 is the default)
    drawing_view.setSizeForBrush(20.toFloat())

         
    //for adding custom color to the brush (add the colour tag directly to colorTag)
    drawing_view.setColor(colorTag)

 ``` 
 
 ### Make the Drawing Pad more Interactable
          
Implement more functionalities:

```XML file

          //Add the below line into your XML file and create a drawale file
          android:background="@drawable/background_drawing_view_layout"

  ``` 

```drawable

          //Implement this in your drawable file with the name "background_drawing_view_layout"
          <shape xmlns:android="http://schemas.android.com/apk/res/android"
                        android:shape="rectangle">
                  <solid android:color="#FFFFFF"/>
                  <stroke android:width="0.5dp"
                        android:color="#9AA2AF"/>

  ``` 

 
 License
 -------
 
     Copyright 2020 adityakamath16
 
     Licensed under the Apache License, Version 2.0 (the "License");
     you may not use this file except in compliance with the License.
     You may obtain a copy of the License at
 
        http://www.apache.org/licenses/LICENSE-2.0
 
     Unless required by applicable law or agreed to in writing, software
     distributed under the License is distributed on an "AS IS" BASIS,
     WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
     See the License for the specific language governing permissions and
     limitations under the License.
