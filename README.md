<div align="center">

## Awsome Color Sheet\!


</div>

### Description

Makes a cool color sheet for using on the making of webpages
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[theMayor](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/themayor.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__2-57.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/themayor-awsome-color-sheet__2-2437/archive/master.zip)





### Source Code

```
<html>
<head>
<title>
color sheet
</title>
</head>
<body bgcolor="black">
<center>
<table cellspacing=0>
<script language="javascript">
<!-- This was wrote by kc. If you use this please email me :)-->
var colors= new Array()
colors[0]="FF"
colors[1]="CC"
colors[2]="99"
colors[3]="66"
colors[4]="33"
colors[5]="00"
for (var x=0;x<=5;x=x+1)
 {
 document.write("<tr>")
 for (var y=0;y<=5;y=y+1)
  {
   for (var z=0;z<=5;z=z+1)
   {
   var c=""
   c="#"+colors[x]+""+colors[y]+""+colors[z]+""
   document.write("<td bgcolor=\""+c+"\">"+c+"</td>")
   }
 document.write("</tr>")
  }
}
</script>
</table>
</body>
</html>
```

