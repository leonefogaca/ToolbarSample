# Toolbar Sample #


----------


##Screenshot
<img src="../master/screenshots/screenshot.png"/>

	<android.support.v7.widget.Toolbar xmlns:android="http://schemas.android.com/apk/res/android"
	    xmlns:app="http://schemas.android.com/apk/res-auto"
	    app:theme="@style/ActionBarThemeOverlay"
	    app:popupTheme="@style/ActionBarPopupThemeOverlay"
	    android:id="@+id/toolbar_actionbar"
	    android:background="?colorPrimary"
	    app:titleTextAppearance="@style/ActionBar.TitleText"
	    app:contentInsetStart="56dp"
	    app:subtitle="SubTitle"
	    app:subtitleTextAppearance="@style/ActionBar.SubTitleText"
	    app:navigationIcon="@drawable/abc_ic_menu_copy_mtrl_am_alpha"
	    android:layout_width="match_parent"
	    android:layout_height="?actionBarSize" />


Style <br />
Base application theme.

    <style name="AppTheme" parent="Theme.AppCompat.Light.NoActionBar">
        <!-- Customize your theme here. -->
        <item name="colorPrimary">#3f51b5</item>
        <item name="colorPrimaryDark">#3f51b5</item>
        <item name="android:colorAccent">#e91e63</item>
    </style>

Toolbar Theme

	<style name="ActionBarThemeOverlay" parent="">
	        <!--<item name="android:textColorPrimary">#fff</item>-->
	        <!--Left icon color-->
	        <item name="colorControlNormal">#fff</item>
	        <!--Left icon hightlight color-->
	        <item name="colorControlHighlight">#3fff</item>
	    </style>

Toolbar Popupmenu Theme
	
	<style name="ActionBarPopupThemeOverlay" parent="ThemeOverlay.AppCompat.Light" />
	

Toolbar TitleTextAppearance
	
	<style name="ActionBar.TitleText" parent="TextAppearance.AppCompat.Widget.ActionBar.Title">
	        <!--Title Color & Size-->
	        <item name="android:textColor">#fff</item>
	        <item name="android:textSize">18sp</item>
	    </style>
	
Toolbar SubtitleTextAppearance

	    <style name="ActionBar.SubTitleText" parent="TextAppearance.AppCompat.Widget.ActionBar.Subtitle">
			<!--Subtitle color & size-->
	        <item name="android:textColor">#fff</item>
	        <item name="android:textSize">12sp</item>
	    </style>