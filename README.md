
# Report
Replaced TextView with WebView.
Instantiated WebView object in OnCreate() and used it to change settings.

Added file access permissions to be able to display the internal web page.
> myWebView.getSettings().setAllowFileAccess(true);

The folder "assets" could not be found. Needed to change to "android_asset" which is the type of the
folder.

Enabled external and internal web pages by url and file location.

![](external.png)
![](internal.png)
