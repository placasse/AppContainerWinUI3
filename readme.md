# Demonstration of embedding an application inside a WinUI 3 desktop application.

This is not yet working.
The child process open, move into the main window, it disappears!

Also, the IWindowNative trick is used to get a HWND of the application window.
However, in the example EmbeddedWindow.zip from Unity, they use the System.Windows.Forms.Control.Handle which refer not to the Window but to the Control itself.
Is it possible to get such an handle for a Microsoft.UI.Xaml.Controls.Control ?

## References

### Unity engine embed into a Windows Form application
```
https://docs.unity3d.com/uploads/Examples/EmbeddedWindow.zip
```

with documentation for calling a Unity application from command line

```
https://docs.unity3d.com/Manual/CommandLineArguments.html
```

### notepad.exe embed into a WPF application
```
https://www.codeproject.com/Tips/673701/Hosting-EXE-Applications-in-a-WPF-Window-Applicati
```

### microsoft-ui-xaml/issues
```
https://github.com/microsoft/microsoft-ui-xaml/issues/3411
```


