# fsharp-gtk-sample

To find Gtk from an FSI session on OS X you will have to add the following lines to your Mono config (```/Library/Frameworks/Mono.framework/Versions/Current/etc/mono/config```)

```
<dllmap dll="libgtk-win32-2.0-0.dll" target="/Library/Frameworks/Mono.framework/Versions/Current/lib/libgtk-quartz-2.0.0.dylib" />
<dllmap dll="libglib-2.0-0.dll" target="/Library/Frameworks/Mono.framework/Versions/Current/lib/libglib-2.0.0.dylib" />
<dllmap dll="libgobject-2.0-0.dll" target="/Library/Frameworks/Mono.framework/Versions/Current/lib/libgobject-2.0.0.dylib" />
<dllmap dll="libgdk_pixbuf-2.0-0.dll" target="/Library/Frameworks/Mono.framework/Versions/Current/lib/libgdk_pixbuf-2.0.0.dylib" />
<dllmap dll="libgio-2.0-0.dll" target="/Library/Frameworks/Mono.framework/Versions/Current/lib/libgio-2.0.0.dylib" />
<dllmap dll="libgtk-3-0.dll" target="/Library/Frameworks/Mono.framework/Versions/Current/lib/libgtk-quartz-2.0.0.dylib" />
```
