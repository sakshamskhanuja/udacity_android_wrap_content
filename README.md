## Wrap Content

### About

The application shows a single ```TextView``` having both its ```layout_width``` and ```layout_height``` set to ```wrap_content```.

```xml
<?xml version="1.0" encoding="utf-8"?>
<TextView xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:background="@android:color/darker_gray"
    android:text="@string/description"
    android:textColor="@android:color/black"
    tools:context=".MainActivity" />
```

The size of this ```TextView``` adjusts accordingly to its content.

### Screenshots

| Device      | Virtual | OS        | API | Orientation                                                                                                         |
|-------------|---------|-----------|-----|---------------------------------------------------------------------------------------------------------------------|
| Pixel 6 Pro | Yes     | Android Q | 29  | [Portrait](https://user-images.githubusercontent.com/122201501/223959729-92038e5a-55a7-4c4f-acd1-f3380ea42b85.png)  |
| Pixel 6 Pro | Yes     | Android Q | 29  | [Landscape](https://user-images.githubusercontent.com/122201501/223959731-25e2b652-9dcf-4301-bc5a-ad736b082f71.png) |
