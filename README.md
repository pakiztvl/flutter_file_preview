# flutter_file_preview

PDF, Word, Excel, and PowerPoint Viewer For Flutter App

## Getting Started

This is '**Flutter**' Office document preview plugin.

Support local and online PDF、Word、Excel、PowerPoint etc. document preview

'Android' is used by [TBS] (https://x5.tencent.com/tbs/guide/sdkInit.html)
`iOS` is used WKWebView`

![demo](./screenshot/demo.gif)

##Usage method

pubspec.yaml

```
file_preview:
    git:
        url: git://github.com/aliyoge/flutter_file_preview.git
```
Use in the file

```
import 'package:flutter_file_preview/flutter_file_preview.dart';

# Preview online files
FlutterFilePreview.openFile("http://www.xxx.com/1245.pdf", title: 'Online PDF');

# Preview local files
FilePreview.openFile("/storage/emulated/0/Download/20180715.pdf", title: 'Local PDF');
```

## FAQ

For help getting started with Flutter, view our online
[documentation](https://flutter.io/).

For help on editing plugin code, view the [documentation](https://flutter.io/platform-plugins/#edit-code).
