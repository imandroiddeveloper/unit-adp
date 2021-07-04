# Unit-adp
This Android Lib provide you new Unit - asp(Scale). This scale unit supporting to multiple android screen size.

# How to use
* Need to add in root gradle file as following :
```gradle 
allprojects {
     repositories {
	maven { url 'https://jitpack.io' }
	}
   }
```
* In your app module gradle file just need to add the dependency
```gradle 
dependencies 
   {
     implementation 'com.github.ImAndroidDeveloper:Unit-adp:1.0.0'
   }
```
* You need to create layout for 320.480 layout xml.
```xml
<android.support.v7.widget.AppCompatTextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="@string/app_name"
        android:fontFamily="serif"
        android:textColor="@color/purple_500"
        android:textSize="@dimen/_22adp"></android.support.v7.widget.AppCompatTextView>

<ImageView
        android:layout_width="@dimen/_75adp"
        android:layout_height="@dimen/_75adp"
        android:layout_margin="@dimen/_10adp"
        android:backgroundTint="@color/purple_700"
        android:background="@drawable/ic_baseline_clean_hands_24">
    </ImageView>
   ```
# Screenshots

 <p float="left">
    <img src="/NexusOne.png">
    <img src="/NexusS.png" >
  <img src="/Phone.png" >
  <img src="/Table_Phone.png" >
</p>


