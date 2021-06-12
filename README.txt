Made By APTOTIC (Batch File Inside Winrar Req. to read)
===================================

=============================
Original Raw Code 4 Bat File
=============================
@echo off
title Aptotic Copier
mode 141,18
color 0a

echo                     =====================================================================================================
echo                     ======================================== Aptotic Copier =============================================
echo                     =====================================================================================================
echo                                         This will copy all files to Portable Drive, please hit enter...
pause




echo                     =====================================================================================================
echo                     ======================================== Aptotic Copier =============================================
echo                     =====================================================================================================
echo                                         This will copy all files to D Drive...

echo Checking Drive D:
#xcopy /h /i /c /k /e /r /y "C:\Windows\" "D:\Vic\Windows"
xcopy /h /i /c /k /e /r /y "C:\Users\" "D:\Vic\Users"
#xcopy /h /i /c /k /e /r /y "C:\Program Files\" "D:\Vic\Program Files"
#xcopy /h /i /c /k /e /r /y "C:\Program Files (x86)\" "D:\Vic\Program Files (x86)"
cls


echo                     =====================================================================================================
echo                     ======================================== Aptotic Copier =============================================
echo                     =====================================================================================================
echo                                         This will copy all files to E Drive...

echo Checking Drive E:
#xcopy /h /i /c /k /e /r /y "C:\Windows\" "E:\Vic\Windows"
xcopy /h /i /c /k /e /r /y "C:\Users\" "E:\Vic\Users"
#xcopy /h /i /c /k /e /r /y "C:\Program Files\" "E:\Vic\Program Files"
#xcopy /h /i /c /k /e /r /y "C:\Program Files (x86)\" "E:\Vic\Program Files (x86)"
cls



echo                     =====================================================================================================
echo                     ======================================== Aptotic Copier =============================================
echo                     =====================================================================================================
echo                                         This will copy all files to F Drive...

echo Checking Drive F:
#xcopy /h /i /c /k /e /r /y "C:\Windows\" "F:\Vic\Windows"
xcopy /h /i /c /k /e /r /y "C:\Users\" "F:\Vic\Users"
#xcopy /h /i /c /k /e /r /y "C:\Program Files\" "F:\Vic\Program Files"
#xcopy /h /i /c /k /e /r /y "C:\Program Files (x86)\" "F:\Vic\Program Files (x86)"
cls

echo                     =====================================================================================================
echo                     =========================================== FINISHED ================================================
echo                     ===================================================================================================== 
echo                                                          Copier has finished ....
pause