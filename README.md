<div align="center">

## Reference another form


</div>

### Description

This will show you how to reference another form in VB.net.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Gene Averett](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/gene-averett.md)
**Level**          |Beginner
**User Rating**    |4.5 (18 globes from 4 users)
**Compatibility**  |VB\.NET
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__10-33.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/gene-averett-reference-another-form__10-3/archive/master.zip)





### Source Code

```
Code on form1:
Dim Frm2 as Form2 = New Form2
''Under InitializeComponent
frm.Init(me)
Code on form2:
Dim frm1 as form1
Public Function Init(Byval frm as Form1)
  frm1 = frm
End Function
'Now you will be able to reference controls on both forms.
```

