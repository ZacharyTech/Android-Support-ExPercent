## Android-Support-ExPercent ##

- 该库基于[Android Support Percent](https://developer.android.com/intl/zh-cn/tools/support-library/features.html#percent)扩展，增加PercentLinearLayout。

![](http://i.imgur.com/ZgphQUH.png)

### User
	compile 'cc.zachary:android-support-expercent:1.0.0'

### Example

	<android.support.percent.PercentLinearLayout
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:orientation="horizontal"
        app:layout_heightPercent="20%">

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:background="#ff0066"
            android:gravity="center"
            app:layout_widthPercent="40%" />

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="match_parent"
            android:background="#339966"
            android:gravity="center"
            app:layout_widthPercent="60%" />
    </android.support.percent.PercentLinearLayout>