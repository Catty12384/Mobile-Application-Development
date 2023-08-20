# Ex.No:1 To create a HelloWorld Activity using all lifecycles methods to display messages.

AIM:

    To create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio.

EQUIPMENTS REQUIRED:

    Latest Version Android Studio

ALGORITHM:

    Step 1: Open Android Stdio and then click on File -> New -> New project.
    
    Step 2: Then type the Application name as HelloWorld and click Next. 
    
    Step 3: Then select the Minimum SDK as shown below and click Next.
    
    Step 4: Then select the Empty Activity and click Next. Finally click Finish.
    
    Step 5: Design layout in activity_main.xml.
    
    Step 6: Display message give in MainActivity file.
    
    Step 7: Save and run the application.

PROGRAM:

      <?xml version="1.0" encoding="utf-8"?>
      <androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
        xmlns:app="http://schemas.android.com/apk/res-auto"
        xmlns:tools="http://schemas.android.com/tools"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        tools:context=".MainActivity">

        <TextView
          android:id="@+id/textView"
          android:layout_width="wrap_content"
          android:layout_height="wrap_content"
          android:text="HELLO WORLD!"
          android:textSize="40sp"
          android:textStyle="bold"
          app:layout_constraintBottom_toBottomOf="parent"
          app:layout_constraintEnd_toEndOf="parent"
          app:layout_constraintStart_toStartOf="parent"
          app:layout_constraintTop_toTopOf="parent" />
      </androidx.constraintlayout.widget.ConstraintLayout>

OUTPUT

  ![hello world](https://github.com/Catty12384/Mobile-Application-Development/assets/120629225/20e7abe7-b0b5-43ae-b5a3-6e2f2ddf5f64)



RESULT

    Thus a Simple Android Application create a HelloWorld Activity using all lifecycles methods to display messages using Android Studio is developed and executed successfully.
