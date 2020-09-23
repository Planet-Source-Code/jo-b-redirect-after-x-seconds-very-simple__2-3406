<div align="center">

## Redirect after X seconds «VERY SIMPLE»


</div>

### Description

This code is very simple to understand, implement, and use. I was browsing this website when I found this code (http://www.planetsourcecode.com/vb/scripts/ShowCode.asp?txtCodeId=91&lngWId=2). My next tought was how could I apply that to a normal redirection? It's simple check this out..
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Jo B](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/jo-b.md)
**Level**          |Beginner
**User Rating**    |5.0 (25 globes from 5 users)
**Compatibility**  |
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__2-68.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/jo-b-redirect-after-x-seconds-very-simple__2-3406/archive/master.zip)





### Source Code

```
...
<form action="http://www.planetsourcecode.com" name="myform"></form>
<script language="Javascript">
setTimeout('document.myform.submit()',5000);
</script>
...
(Note: 5000 = 5 seconds)
```

