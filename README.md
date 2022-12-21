![Release](https://jitpack.io/v/YusufbekIbragimov/LottieSwipeRefreshLayout.svg)
 
# LottieSwipeRefreshLayout

To get a Git project into your build:

## Step 1. Add the JitPack repository to your build file
Add it in your root build.gradle at the end of repositories:
```
allprojects {
   repositories {
     ..
     maven { url 'https://jitpack.io'}
     ..
  }
}
```
## Step 2. Add the dependency Gradle:

```
//Swipe Refresh Layout
implementation 'com.github.YusufbekIbragimov:LottieSwipeRefreshLayout:#latest_version'
```

## Step 3. Example to add xml code
```
<uz.yusufbekibragimov.testapp.lib.LottiePullToRefreshLayout 
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/collapseToolBar"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    app:max_offset_top="300dp"
    app:pull_to_refresh_lottieFile="@raw/main_screen_anim"
    app:trigger_offset_top="150dp">

    <androidx.recyclerview.widget.RecyclerView
        android:id="@+id/nestedView"
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        app:layout_type="content"
        tools:itemCount="3"
        tools:listitem="@layout/item_design" />

</uz.yusufbekibragimov.testapp.lib.LottiePullToRefreshLayout>
```
## Step 4. Warning !!!
You have to use only one RecyclerView in LottieSwipeRefreshLayout.
## Step 4. Result
![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/83059102/191929944-65174114-3543-42c1-aa6f-db1b88675a08.gif)

## You can set orientaion type
![ezgif com-gif-maker](https://user-images.githubusercontent.com/83059102/191929986-8d139851-e91b-408d-b9bb-dada36166bab.gif)



For bugs, feature requests, and discussion, please use GitHub Issues. For general questions ONLY, please contact via Telegram.
