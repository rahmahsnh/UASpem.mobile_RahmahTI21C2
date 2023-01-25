<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:paddingBottom="@dimen/activity_vertical_margin"
    android:paddingTop="@dimen/activity_vertical_margin"
    android:paddingRight="@dimen/activity_horizontal_margin"
    android:paddingLeft="@dimen/activity_horizontal_margin">

    <Button
        android:id="@+id/buttonScan"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="SCAN"
        android:layout_alignParentBottom="true"/>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="150dp"
        android:orientation="vertical"
        android:layout_alignParentTop="true"
        android:layout_centerVertical="true">

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Nama" />

        <TextView
            android:id="@+id/textViewNama"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="RAHMAH HASANAH"
            android:textAppearance="@style/TextAppearance.AppCompat.Large" />

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Kelas" />

        <TextView
            android:id="@+id/textViewKelas"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="TI 21 C2"
            android:textAppearance="@style/TextAppearance.AppCompat.Large"/>

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="NIM" />

        <TextView
            android:id="@+id/textViewNIM"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="312110512"
            android:textAppearance="@style/TextAppearance.AppCompat.Large"/>

    </LinearLayout>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="20dp"
        android:layout_alignParentStart="true"
        android:layout_alignParentBottom="false"
        android:layout_centerInParent="true"
        android:layout_marginStart="35dp"
        android:layout_marginTop="360dp"
        android:layout_marginEnd="35dp">

        <TextView
            android:id="@+id/textViewMAP"
            android:layout_width="70dp"
            android:layout_height="wrap_content"
            android:text="Map"
            android:textAlignment="center"></TextView>

        <TextView
            android:id="@+id/textViewKontak"
            android:layout_width="70dp"
            android:layout_height="wrap_content"
            android:text="Kontak"
            android:textAlignment="center"></TextView>

        <TextView
            android:id="@+id/textViewEmail"
            android:layout_width="70dp"
            android:layout_height="wrap_content"
            android:text="Email"
            android:textAlignment="center"></TextView>

        <TextView
            android:id="@+id/textViewWebsite"
            android:layout_width="70dp"
            android:layout_height="wrap_content"
            android:text="Website"
            android:textAlignment="center"></TextView>
    </LinearLayout>

    <LinearLayout
        android:layout_width="70dp"
        android:layout_height="60dp"
        android:layout_alignParentStart="true"
        android:layout_alignParentBottom="true"
        android:layout_centerHorizontal="true"
        android:layout_marginStart="35dp"
        android:layout_marginEnd="35dp"
        android:layout_marginBottom="200dp">

        <ImageButton
            android:id="@+id/imageButton1"
            style="@android:style/Widget.ImageButton"
            android:layout_width="70dp"
            android:layout_height="60dp"
            android:onClick="Map"
            android:layout_weight="1"
            app:srcCompat="@drawable/map"
            tools:ignore="DuplicateIds,DuplicateSpeakableTextCheck"/>
    </LinearLayout>

    <LinearLayout
        android:layout_width="70dp"
        android:layout_height="60dp"
        android:layout_alignParentStart="true"
        android:layout_alignParentBottom="true"
        android:layout_centerHorizontal="true"
        android:layout_marginStart="105dp"
        android:layout_marginEnd="0dp"
        android:layout_marginBottom="200dp">

        <ImageButton
            android:id="@+id/imageButton2"
            style="@android:style/Widget.ImageButton"
            android:layout_width="70dp"
            android:layout_height="60dp"
            android:onClick="Kontak"
            android:layout_weight="1"
            app:srcCompat="@drawable/call"
            tools:ignore="DuplicateIds,DuplicateSpeakableTextCheck"/>
    </LinearLayout>

    <LinearLayout
        android:layout_width="70dp"
        android:layout_height="60dp"
        android:layout_alignParentStart="true"
        android:layout_alignParentBottom="true"
        android:layout_centerHorizontal="true"
        android:layout_marginStart="175dp"
        android:layout_marginEnd="0dp"
        android:layout_marginBottom="200dp">
        
        
![mobile 1](https://user-images.githubusercontent.com/116366904/214574410-2cd96f35-f450-4e28-b1cd-8ff81354212e.JPG)

        <ImageButton
            android:id="@+id/imageButton3"
            style="@android:style/Widget.ImageButton"
            android:layout_width="70dp"
            android:layout_height="60dp"
            android:onClick="Email"
            android:layout_weight="1"
            app:srcCompat="@drawable/mail"
            tools:ignore="DuplicatIds,DuplicateSpeakableTextCheck"/>
    </LinearLayout>

    <LinearLayout
        android:layout_width="70dp"
        android:layout_height="60dp"
        android:layout_alignParentStart="true"
        android:layout_alignParentBottom="true"
        android:layout_centerHorizontal="true"
        android:layout_marginStart="245dp"
        android:layout_marginEnd="0dp"
        android:layout_marginBottom="200dp">

        <ImageButton
            android:id="@+id/imageButton4"
            android:layout_width="70dp"
            android:layout_height="60dp"
            android:onClick="Website"
            app:srcCompat="@drawable/web_view"
            android:layout_weight="1"
            tools:ignore="DuplicateIds,DuplicateSpeakableTextCheck"/>
    </LinearLayout>

    <LinearLayout
        android:layout_width="280dp"
        android:layout_height="70dp"
        android:layout_alignParentStart="true"
        android:layout_alignParentBottom="true"
        android:layout_centerHorizontal="true"
        android:layout_marginStart="35dp"
        android:layout_marginBottom="86dp">

        <TextView
            android:id="@+id/textView"
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:layout_marginEnd="0dp"
            android:layout_marginBottom="0dp"
            android:layout_weight="@integer/material_motion_duration_long_1"
            android:text="Gunakan Tombol SCAN untuk men-Scan Kode QR"
            android:textAlignment="center"
            android:textAppearance="@style/TextAppearance.AppCompat.Large" />
    </LinearLayout>

    <LinearLayout
        android:layout_width="330dp"
        android:layout_height="70dp"
        android:layout_alignParentStart="true"
        android:layout_alignParentTop="true"
        android:layout_centerHorizontal="true"
        android:layout_marginStart="14dp"
        android:layout_marginEnd="14dp"
        android:layout_marginTop="188dp" >

        <TextView
            android:id="@+id/textView2"
            android:layout_width="wrap_content"
            android:layout_height="70dp"
            android:layout_weight="1"
            android:textAlignment="center"
            android:text="Berbagai macam Kode QR seperti Map, Kontak, Email, Website, dll dimungkinkan dapat di- Scan melalui Aplikasi ini." />
    </LinearLayout>
  

</RelativeLayout>
