# loginDemo

<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@drawable/icon"
    tools:context=".Login">

    <TextView
        android:id="@+id/textView"
        android:layout_width="270dp"
        android:layout_height="85dp"
        android:gravity="center"
        android:text="LOGIN"
        android:textColor="#040404"
        android:textSize="50sp"
        android:textStyle="bold"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintVertical_bias="0.14999998" />

    <androidx.constraintlayout.widget.ConstraintLayout

        android:id="@+id/frameLayout"
        android:layout_width="342dp"
        android:layout_height="217dp"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/textView"
        app:layout_constraintVertical_bias="0.20999998">

        <EditText
            android:id="@+id/editTextTextPersonName2"
            android:layout_width="277dp"
            android:layout_height="40dp"
            android:ems="10"
            android:hint="@string/username"
            android:inputType="textPersonName"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toTopOf="parent"
            app:layout_constraintVertical_bias="0.120000005" />

        <EditText
            android:id="@+id/editTextTextPassword"
            android:layout_width="277dp"
            android:layout_height="40dp"
            android:ems="10"
            android:hint="@string/password"
            android:inputType="textPassword"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toBottomOf="@+id/editTextTextPersonName2"
            app:layout_constraintVertical_bias="0.110000014" />

        <Button
            android:id="@+id/button4"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Button"
            app:layout_constraintBottom_toBottomOf="parent"
            app:layout_constraintEnd_toEndOf="parent"
            app:layout_constraintStart_toStartOf="parent"
            app:layout_constraintTop_toBottomOf="@+id/editTextTextPassword" />

    </androidx.constraintlayout.widget.ConstraintLayout>

    <Button
        android:id="@+id/button2"
        android:layout_width="170dp"
        android:layout_height="50dp"
        android:backgroundTint="#C9E6CA"
        android:hint="@string/Forgetpassword"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintHorizontal_bias="0.871"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toBottomOf="@+id/frameLayout"
        app:layout_constraintVertical_bias="0.0" />

</androidx.constraintlayout.widget.ConstraintLayout>
