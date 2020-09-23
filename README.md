<div align="center">

## \[ A1 Code \] Simple Scroll Text


</div>

### Description

This code is the simplest form of Scrolling Text. It uses a Timer controle to make a label scroll. No consideration is required for screen cordinates or size or any other thing. Have a look at this simple scroll text application and Please do rate it :) I am watching from sachinweb@hotmail.com
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Sachin Mehra \(Delhi\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/sachin-mehra-delhi.md)
**Level**          |Beginner
**User Rating**    |4.3 (125 globes from 29 users)
**Compatibility**  |VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Custom Controls/ Forms/  Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/custom-controls-forms-menus__1-4.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/sachin-mehra-delhi-a1-code-simple-scroll-text__1-34901/archive/master.zip)





### Source Code

```
Form1 (starts)
 ======================
Private Sub Form_Load()
Label1.Caption = "Hi all, I am Sachin "
Timer1.Enabled = True
Timer1.Interval = 300
End Sub
Private Sub Timer1_Timer()
Dim str As String
str = Form1.Label1.Caption
str = Mid$(str, 2, Len(str)) + Left(str, 1)
Form1.Label1.Caption = str
End Sub
=================================
Form1 (Ends)
```

