
simplinnovation
Microsoft Office 2016 Activator ⚡
Microsoft Office 2016 Activator is a simple command line script project to activate Microsoft Office 2016 (Standard & Professional Plus) using KMS server. It's totally free & you don't need to install any tools/software.
office_2016

Create the Activator File 📋
Basically we will create & use our own simple batch file (.cmd) which can access the KMS server to activate Microsoft Office products. To get started, open your text/code editor (e.g Notepad, WordPad, Visual Studio Code, etc.), write the codes below & save it as .cmd file. Or you can simply download my Activator.cmd from this repo.

@echo off
title Microsoft Office 2016 Activator - simpLINnovation&cls&echo.&echo ****************************************************************************&echo Microsoft Office 2016 Activator for FREE without any software!&echo Lintang Wisesa&echo simpLINnovation(c)2018 &echo.&echo.****************************************************************************&echo.&echo #This project is using KMS server.&echo.&echo #Supported products:&echo - Microsoft Office Standard 2016&echo - Microsoft Office Professional Plus 2016&echo.&(if exist "%ProgramFiles%\Microsoft Office\Office16\ospp.vbs" cd /d "%ProgramFiles%\Microsoft Office\Office16")&(if exist "%ProgramFiles(x86)%\Microsoft Office\Office16\ospp.vbs" cd /d "%ProgramFiles(x86)%\Microsoft Office\Office16")&(for /f %%x in ('dir /b ..\root\Licenses16\proplusvl_kms*.xrm-ms') do cscript ospp.vbs /inslic:"..\root\Licenses16\%%x" >nul)&(for /f %%x in ('dir /b ..\root\Licenses16\proplusvl_mak*.xrm-ms') do cscript ospp.vbs /inslic:"..\root\Licenses16\%%x" >nul)&echo.&echo ****************************************************************************&echo Activating your Microsoft Office...&echo.&cscript //nologo ospp.vbs /unpkey:WFG99 >nul&cscript //nologo ospp.vbs /unpkey:DRTFM >nul&cscript //nologo ospp.vbs /unpkey:BTDRB >nul&cscript //nologo ospp.vbs /unpkey:CPQVG >nul&cscript //nologo ospp.vbs /inpkey:XQNVK-8JYDB-WJ9W3-YJ8YR-WFG99 >nul&set i=1
:server
if %i%==1 set KMS_Sev=kms7.MSGuides.com
if %i%==2 set KMS_Sev=kms8.MSGuides.com
if %i%==3 set KMS_Sev=kms9.MSGuides.com
if %i%==4 goto notsupported
cscript //nologo ospp.vbs /sethst:%KMS_Sev% >nul&echo ****************************************************************************&echo.
cscript //nologo ospp.vbs /act | find /i "successful" && (echo.&echo ****************************************************************************&echo.&echo #Facebook: https://www.facebook.com/lintangbagus&echo #Twitter: https://twitter.com/Lintang_Wisesa&echo #GitHub: https://github.com/LintangWisesa&echo #Youtube: https://www.youtube.com/user/lintangbagus&echo #Contact me at lintangwisesa@ymail.com&echo.&echo ****************************************************************************&echo.&choice /n /c YN /m "Done. Wanna see my project on YouTube [y/n]?" & if errorlevel 2 exit) || (echo The connection to my KMS server failed! Trying to connect to another one... & echo Please wait... & echo. & echo. & set /a i+=1 & goto server)
explorer "https://www.youtube.com/user/lintangbagus"&goto halt
:notsupported
echo.&echo ***************************************************************************=&echo Sorry! Your version is not supported.&echo Please try installing the latest version!
:halt
pause
Make sure your internet connection is good enough, then open the file: right click & choose Open as Administrator. Automatically it will access KMS server to activate your Microsoft Office 2016. Wait until its processing done.

screenshot

If everything goes well, now your Microsoft Office 2016 is activated. On the last line, you can type n to exit from the terminal, or type y to see my projects on YouTube. Enjoy! 😎

