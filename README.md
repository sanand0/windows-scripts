Windows Scripting
=================

On the whole, it's best to stick to C#. Most code samples are in C#. Keep a
[cheat sheet](http://www.digilife.be/quickreferences/QRC/Core%20CSharp%20and%20.NET%20Quick%20Reference.pdf)
handy.

The C# compiler is at `C:\Windows\Microsoft.NET\Framework\v...\csc.exe`.

There are different technologies that Windows uses for GUI applications.
WinForms is the old way. WPF is the new way. WinForms is simpler, and we'll go
with that. [Ref](http://www.wpf-tutorial.com/about-wpf/wpf-vs-winforms/).

Here are the sample apps:

- [Tray app](tray-app.cs) that adds a system tray icon for the app
