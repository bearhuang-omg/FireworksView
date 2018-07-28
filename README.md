# FireworksView
```

        my_edittext = findViewById(R.id.my_edittext);
        fire_view = findViewById(R.id.fire_view);
        fire_view.bindEditText(my_edittext);

```
```
<?xml version="1.0" encoding="utf-8"?>
<android.support.constraint.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
   >
    <EditText
        android:id="@+id/my_edittext"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Hello World!"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintLeft_toLeftOf="parent"
        app:layout_constraintRight_toRightOf="parent"
        app:layout_constraintTop_toTopOf="parent" />
    <com.ssy.fireworkstextview.FireWorkView
        android:id="@+id/fire_view"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        ></com.ssy.fireworkstextview.FireWorkView>

</android.support.constraint.ConstraintLayout>
```
