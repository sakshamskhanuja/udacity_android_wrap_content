## Wrap Content

### About

The application shows a single ```TextView``` having both its ```layout_width``` and ```layout_height``` set to ```wrap_content```.

```xml
<?xml version="1.0" encoding="utf-8"?>
<TextView xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:background="@color/color_text_background"
    android:text="@string/description"
    android:textColor="@color/color_text"
    tools:context=".MainActivity" />
```

The size of this ```TextView``` adjusts accordingly to its content.

### Screenshots

| Device      | Virtual | OS        | API | Orientation                                                                                                         |
|-------------|---------|-----------|-----|---------------------------------------------------------------------------------------------------------------------|
| Pixel 6 Pro | Yes     | Android Q | 29  | [Portrait](https://user-images.githubusercontent.com/122201501/224528542-49dfca93-fe23-4ab2-92a5-85c3b093936e.png)  |
| Pixel 6 Pro | Yes     | Android Q | 29  | [Landscape](https://user-images.githubusercontent.com/122201501/224528545-ece35f87-48d7-4b0a-9d04-4f7aabc71916.png) |
