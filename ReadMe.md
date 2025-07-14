## Microsoft Terminology

This file contains a selection of TBX files that contain Microsoft terminology downloaded from their [Globalization site](https://learn.microsoft.com/en-us/globalization/reference/microsoft-terminology#downloading-microsoft-terminology).

Direct Download: https://download.microsoft.com/download/b/2/d/b2db7a7c-8d33-47f3-b2c1-ee5e6445cf45/MicrosoftTermCollection.zip

The files have been adjusted in a way to be compatible for Weblate import by cutting of the third part of the triplet ID of the `termEntry` elements and adding a counter as the third part in order to discriminate between different entries with the same first two parts.

### Exmaple

```xml
<termEntry id="1_11444_11446">
```

changed to 

```xml
<termEntry id="1_11444_1">
```
