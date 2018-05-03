# android_study
code pieces

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <ImageView
        android:src="@drawable/androidparty"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:scaleType="centerCrop"/>

    <TextView
        android:id="@+id/text1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:textSize="35sp"
        android:fontFamily="sans-serif-light"
        android:textColor="#FFEB3B"
        android:text="Happy Birthday, Nusha!"
        android:padding="20dp"/>

    <TextView
        android:id="@+id/text2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_alignParentRight="true"
        android:textSize="35sp"
        android:fontFamily="sans-serif-light"
        android:textColor="#FFEB3B"
        android:text="Love you, Julia!"
        android:padding="20dp"/>

</RelativeLayout>
