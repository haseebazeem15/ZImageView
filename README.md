# ZImageView
ZImageView is simple touchable and zoomable imageView with all gestures detections. Zoom-in &amp; Zoom-out functionality implemented.

## Minimum API LEVEL
GifImageView is compatible with API LEVEL 21 or above.

## Installation

1) Use [jitpack](https://jitpack.io) in your build.gradle file to install GifImageView.

```bash
allprojects {
 repositories {
   maven { url 'https://jitpack.io' }
 }
}
```
## Gradle
```bash
dependencies {
  implementation 'com.github.haseebazeem15:ZImageView:1.0'
}
```

## Usage

Create this ZImageView element in your layout xml file:

```java
  <com.haseebazeem.zimageview.ZImageView
      android:layout_width="wrap_content"
      android:layout_height="wrap_content"
      android:src="@mipmap/ic_launcher"
      android:id="@+id/z_image"
  />
```
Inflate ZImageView programmatically using:
```java

ZImageView zImageView;

zImageView = (ZImageView) findViewById(R.id.z_image);
zImageView.setImageResource(YOUR_RESOURCE);
zImageView.setImageBitmap(YOUR_BITMAP);
zImageView.setImageDrawable(YOUR_DRAWABLE);
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
