# GasFutsal

Tugas Pemrograman Mobile - Pertemuan 7

<hr>

Nama : Andriansyah <br>
Nim : 312010011 <br>
Kelas : TI.20.C1

<hr>

## Praktikum Android Studio

Soal :  Membuat Design User Interface dengan menggunakan Android Studio dari hasil storyboard

**1. Membuat Halaman Splashcreen**

code xml :

```
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".SplashScreenActivity">
    <ImageView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:src="@drawable/elipse"
        android:layout_centerVertical="true"
        android:layout_centerHorizontal="true"
        android:contentDescription="Logo Applikasi" />


    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="Gas Futsal"
        android:textColor="@color/white"
        android:textSize="36sp"
        android:gravity="center"
        android:layout_centerHorizontal="true"
        android:layout_centerVertical="true"
        android:fontFamily="@font/baumans_egular"/>

</RelativeLayout>
```

![image](https://user-images.githubusercontent.com/73049521/236671419-043e4d19-22eb-483a-94d5-cbd1490b6798.png)

**2. Membuat Halaman Log in**

Berikut saya lampirkan code xml nya:
```
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="@color/purple"
    android:orientation="vertical"
    android:padding="50dp"
    tools:context=".MainActivity">
    
    <ImageView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_marginBottom="30dp"
        android:layout_gravity="center_horizontal"
        android:src="@drawable/logo"/>

    <TextView
        android:id="@+id/textView"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="Login"
        android:textColor="@color/white"
        android:textSize="32sp"
        android:fontFamily="@font/poppins_semibold"
        android:gravity="center"
        android:layout_marginBottom="30dp"/>

    <EditText
        android:layout_width="match_parent"
        android:layout_height="50dp"
        android:background="@drawable/form_shape"
        android:hint="Email Address"
        android:drawableLeft="@drawable/baseline_email_24"
        android:padding="10dp"
        android:drawablePadding="10dp"
        android:textColorHint="#A69F9F"
        android:fontFamily="@font/poppins_regular"
        android:drawableTint="@color/ijo"
        android:textSize="16dp"/>

    <EditText
        android:layout_width="match_parent"
        android:layout_height="50dp"
        android:background="@drawable/form_shape"
        android:hint="Password"
        android:textColorHint="#A69F9F"
        android:fontFamily="@font/poppins_regular"
        android:textSize="16dp"
        android:layout_marginTop="10dp"
        android:drawableLeft="@drawable/baseline_lock_24"
        android:drawableTint="@color/ijo"
        android:padding="10dp"
        android:drawablePadding="10dp"/>



    <Button
        android:layout_width="wrap_content"
        android:layout_height="50dp"
        android:text="Log In"
        android:layout_gravity="center_horizontal"
        android:backgroundTint="@color/ijo"
        android:width="320dp"
        android:textColor="@color/white"
        android:textSize="16dp"
        android:fontFamily="@font/poppins_bold"
        android:layout_marginTop="20dp"
        android:textAllCaps="false"
        android:elevation="12dp"/>


</LinearLayout>


```

Preview Gambar :

![image](https://user-images.githubusercontent.com/73049521/236671595-a5e88c51-c00f-4bfd-955d-2c0dab9358d6.png)

**3. Membuat Halaman Home**

Untuk source code pada bagian ini bisa diakses di C:\Users\Infinix X1\AndroidStudioProjects\GasFutsal\app\src\main\res\layout

![image](https://github.com/Andriansyah00/GasFutsal/assets/73049521/460ff1d4-e965-48c1-9030-ea5ff0ff4f25)

