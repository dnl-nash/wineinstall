This script sets up an accessible wineprefix with the following packages and configurations, using winetricks:
sapi, MS Speech API
dx8vb, MS dx8vb.dll from DirectX 8.1 runtime
vb2run, MS Visual Basic 2 runtime
vb3run, MS Visual Basic 3 runtime
vb4run, MS Visual Basic 4 runtime
vb6run, MS Visual Basic 6 runtime sp6
mfc42, Visual C++ 6 SP4 mfc42 library; part of vcrun6
autostart_winedbg=disabled, Prevent winedbg from launching when an unhandled exception occurs
nocrashdialog, Does not show crash dialog
usetakefocus=y, Allows proper keyboard/window handling for standalone window managers
videomemorysize=default, matches simulated and actual video memory size
comctl32ocx, MS comctl32.ocx and mscomctl.ocx, comctl32 wrappers for VB6
comdlg32ocx, Common Dialog ActiveX Control for VB6
msaa, MS Active Accessibility (oleacc.dll, oleaccrc.dll, msaatext.dll)
riched20, MS RichEdit Control 2.0 (riched20.dll)
riched30, MS RichEdit Control 3.0 (riched20.dll, msls31.dll)
richtx32, MS Rich TextBox Control 6.0
tabctl32, Microsoft Tabbed Dialog Control 6.0 (tabctl32.ocx)
urlmon, MS urlmon
dotnet40, MS .NET 4.0
dotnet45, MS .NET 4.5
win81, Simulates Windows 8.1 for applications which do OS Version Checks
NVDA screen reader and 32-bit espeak TTS
If $0 contains .nodesktop, wineboot will not be run during startup of a desktop session supporting xdg autostart spec
