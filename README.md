# Android-Circle-ImageView
<img src="https://www.androdocs.com/files/uploads/large/android-circle-imageview-with-border-using-kotlin-cover-1566392360.jpg"/>
<p>Read the tutorial on creating Android Circle ImageView <a href ="https://www.androdocs.com/tutorials/android-circle-imageview-with-border-using-kotlin.html" target="_blank"><b>here</b></a></p>
<h3>Step 1. Add the JitPack repository to your build file</h3>
<p>Add it in your root <strong>build.gradle</strong> at the end of repositories:</p>
<pre>allprojects {
	repositories {
		...
		maven { url 'https://jitpack.io' }
	}
}</pre>
<p>&nbsp;</p>
<h3>Step 2. Add the dependency</h3>
<pre>dependencies {
        implementation 'com.github.androdocs:Android-Circle-ImageView:0.1.0'
}</pre>
<p>&nbsp;</p>
<h3>Step 3. Add Circle ImageView in your XML Layout</h3>
<pre>&lt;com.androdocs.circleimagelibrary.CircleImageView
            android:layout_width="200dp"
            android:layout_height="200dp"
            android:src="@drawable/shajib"
            app:border_width="10dp"
            app:border_color="#000000"
    /&gt;</pre>
<p>&nbsp;</p>
