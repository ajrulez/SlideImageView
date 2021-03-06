SlideImageView
==============

Simple and convenient library that allows you to slide images through a view.

[![DevLight](https://lh4.googleusercontent.com/-9btnRFp_eVo/V5cfwZsBpMI/AAAAAAAAC4E/s4NGoezKhpAVdVofAoez1QWpzK5Na8_cQCL0B/w147-h20-no/devlight-badge.png)](http://devlight.com.ua)

[![Android](https://img.shields.io/badge/platform-android-brightgreen.svg?style=flat&label=Platform)](https://github.com/DevLight-Mobile-Agency)
[![Download](https://api.bintray.com/packages/gigamole/maven/slideimageview/images/download.svg)](https://bintray.com/gigamole/maven/slideimageview/_latestVersion)
[![Crates.io](https://img.shields.io/crates/l/rustc-serialize.svg?maxAge=2592000&label=License)](https://github.com/DevLight-Mobile-Agency/SlideImageView/blob/master/LICENSE.txt)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/0b467adb674e42a088ef2802901979be)](https://www.codacy.com/app/gigamole53/SlideImageView?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=DevLight-Mobile-Agency/SlideImageView&amp;utm_campaign=Badge_Grade)

![](https://lh5.googleusercontent.com/-2BiBFz-OW_s/VU_EPv33XMI/AAAAAAAAAcc/nGie_kBoZQ8/w244-h368-no/siv.gif)

You can check the sample app [here](https://github.com/DevLight-Mobile-Agency/SlideImageView/tree/master/app).

Download
------------

You can download a `.jar` from GitHub's [releases page](https://github.com/DevLight-Mobile-Agency/SlideImageView/releases).

Or use Gradle jCenter:
```groovy
dependencies {
    repositories {
        mavenCentral()
        maven {
            url  'http://dl.bintray.com/gigamole/maven/'
        }
    }
    compile 'com.github.gigamole.slideimageview:library:+'
}
```

Or Gradle Maven Central:

```groovy
compile 'com.github.gigamole.slideimageview:library:1.1.4'
```

Or Maven:

```groovy
<dependency>
    <groupId>com.github.gigamole.slideimageview</groupId>
    <artifactId>library</artifactId>
    <version>1.1.4</version>
    <type>aar</type>
</dependency>
```

Android SDK Version
=========
SlideImageView requires a minimum sdk version of 8.

Sample
========

<b>Parameters</b>

You can set such parameters as:

 - source
 - axis (`HORIZONTAL` | `VERTICAL`)
 - rate

<b>Init</b>

Check out in code init:

```java
SlideImageView slideImageView = (SlideImageView) findViewById(R.id.img_horizontal_slide);
slideImageView.setSource(R.drawable.wide_background);
slideImageView.setRate(0.3f);
slideImageView.setAxis(SlideImageView.Axis.HORIZONTAL);
```

And XML init:

```xml
<com.gigamole.slideimageview.lib.SlideImageView
    android:id="@+id/img_vertical_slide"
    android:layout_width="match_parent"
    android:layout_height="0dp"
    android:layout_weight="1"
    slide:source="@drawable/long_background"
    slide:axis="vertical"/>
```

Getting Help
======

To report a specific problem or feature request, [open a new issue on Github](https://github.com/DevLight-Mobile-Agency/SlideImageView/issues/new).

License
======
Apache 2.0 and MIT. See [LICENSE](https://github.com/DevLight-Mobile-Agency/SlideImageView/blob/master/LICENSE.txt) file for details.

Author
=======

Made in [DevLight Mobile Agency](https://github.com/DevLight-Mobile-Agency)

Created by [Basil Miller](https://github.com/GIGAMOLE) - [@gigamole](mailto:gigamole53@gmail.com)

Support
=======

If you'd like to support future development and new product features, please make a payments on Gratipay and Beerpay or become a patron on Patreon.

[![Gratipay](https://img.shields.io/gratipay/user/gigamole.svg?maxAge=2592000)](https://gratipay.com/~GIGAMOLE/)
[![Beerpay](https://beerpay.io/DevLight-Mobile-Agency/SlideImageView/badge.svg?style=flat)](https://beerpay.io/DevLight-Mobile-Agency/SlideImageView)
[![Patreon](https://lh5.googleusercontent.com/-lXI_oKp5724/V58ysdDtxHI/AAAAAAAAC7s/g91W_YT2SM0Q_VaIhDAMmoe-jHPP3ijJwCL0B/w140-h20-no/patreon-badge.png)](https://www.patreon.com/gigamole)

Also, if you use this library in applications that are available on Google Play, please report it to us or author.

Thanks in advance.