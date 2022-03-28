<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@drawable/ui"
    tools:context=".MainActivity">

    <ImageView
        android:id="@+id/imageView"
        android:layout_width="285dp"
        android:layout_height="159dp"
        android:layout_marginTop="144dp"
        android:layout_marginEnd="60dp"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:srcCompat="@drawable/me" />

    <TextView
        android:id="@+id/textView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="96dp"
        android:layout_marginTop="56dp"
        android:fontFamily="sans-serif-black"
        android:text="Welcome, Amr"
        android:textAlignment="center"
        android:textColor="@color/color1"
        android:textSize="35sp"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/imageView" />

    <TextView
        android:id="@+id/textView2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginStart="68dp"
        android:layout_marginTop="36dp"
        android:fontFamily="sans-serif-medium"
        android:text=" Your Profile"
        android:textColor="@color/color1"
        android:textSize="50sp"
        android:textStyle="bold"

        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />
</androidx.constraintlayout.widget.ConstraintLayout>
