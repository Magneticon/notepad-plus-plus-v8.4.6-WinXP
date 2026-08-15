Notepad++ for Windows XP / Windows Server 2003
===================

Ported version of Notepad++ v8.4.6 to Windows XP & Windows XP x64.

Changes were made in main executable notepad++.exe to disable custom file dialog and dark theme implementation, which were incompatible with Windows XP. Following the modifications and recompiling with old VS 2017 (v141) platform toolset, the Notepad++ was made working on Windows XP again.

NOTE: This version has missing toolbar under Windows XP. It is working in Windows 10, but not on XP. Despite of my attempts of updating src\WinControls\ToolBar\ToolBar.cpp & ToolBar.h and porting of the same from last XP version of Notepad++ (v7.9.2), I am not able to make the toolbar code to work under Windows XP. It might be fixed eventually, once I will find a way to make it working. However, the rest of the program seems to be working well, as I use it daily on my Windows XP x64 without stumbling on any other issues so far;-)

**Notepad++ v.8.4.6 in Windows XP:**

<img width="1920" height="1080" alt="WXP_X86" src="https://github.com/user-attachments/assets/c160fd23-e278-4827-86c7-56ebb3c867df" />

**Notepad++ v.8.4.6 in Windows XP x64:**

<img width="1920" height="1080" alt="WXP_X64" src="https://github.com/user-attachments/assets/cb8b227d-2012-4d18-80d9-a8b1d883d9c6" />
