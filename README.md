# Basic-AndroidStudio
### Program:
```
Developed by: Manoj Guna Sundar Tella.
Register No: 212221240026.
```
#### MainActiviity.java
```
package com.example.project1;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.widget.Toast;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        Toast toast=Toast.makeText(getApplicationContext(),"OnCreate Executed",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onStart(){
        super.onStart();
        Toast toast=Toast.makeText(getApplicationContext(),"OnStart Executed",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onResume(){
        super.onResume();
        Toast toast=Toast.makeText(getApplicationContext(),"OnResume Executed",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onPause(){
        super.onPause();
        Toast toast=Toast.makeText(getApplicationContext(),"OnPause Executed",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onStop(){
        super.onStop();
        Toast toast=Toast.makeText(getApplicationContext(),"OnStop Executed",Toast.LENGTH_LONG);
        toast.show();
    }

    protected void onDestroy(){
        super.onDestroy();
        Toast toast=Toast.makeText(getApplicationContext(),"OnDestroy Executed",Toast.LENGTH_LONG);
        toast.show();
    }
    protected void onRestart(){
        super.onRestart();
        Toast toast=Toast.makeText(getApplicationContext(),"OnRestart Executed",Toast.LENGTH_LONG);
        toast.show();
    }
}


```
#### activity_main.xml
```
<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World!"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

</androidx.constraintlayout.widget.ConstraintLayout>
```
### Output:
![p1](https://user-images.githubusercontent.com/94883876/190643858-3d4b2a0a-a259-44f0-9b03-a7135f0fd035.jpg)
![p2](https://user-images.githubusercontent.com/94883876/190643878-af59d916-5c34-4709-8146-67c29cdaab1b.jpg)
![p3](https://user-images.githubusercontent.com/94883876/190643929-f6fd23f1-3335-4a88-ad12-b3fb60ba3ae6.jpg)
![p4](https://user-images.githubusercontent.com/94883876/190643947-b34eb5bf-4b3d-431b-bf72-5fac8c78230d.jpg)
![p5](https://user-images.githubusercontent.com/94883876/190643962-6e27b61e-1592-488b-b740-92fa86692835.jpg)
![p6](https://user-images.githubusercontent.com/94883876/190643981-77686250-9a9e-4eb2-8b31-30a7c4352df2.jpg)
![p7](https://user-images.githubusercontent.com/94883876/190644009-4c580282-89b4-429d-87cf-b6d41dfccf8c.jpg)


### Result:
Therefore a program is return to develop a program to detect the various life cycles of an activity. The program is successfully executed.
