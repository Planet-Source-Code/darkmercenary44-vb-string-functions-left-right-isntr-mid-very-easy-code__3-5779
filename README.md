<div align="center">

## VB String Functions \(left, right, isntr, mid\) very easy code\.\.\.


</div>

### Description

I just started learning C++ and had to do some string parsing code for one of my classes. I couldn't figure out how to do it until later on, but I wrote these little functions to help those that learned in VB feel a little more at home in C++. At least when they deal with strings.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[DarkMercenary44](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/darkmercenary44.md)
**Level**          |Beginner
**User Rating**    |4.5 (18 globes from 4 users)
**Compatibility**  |C\+\+ \(general\), Microsoft Visual C\+\+, UNIX C\+\+
**Category**       |[Strings](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/strings__3-26.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/darkmercenary44-vb-string-functions-left-right-isntr-mid-very-easy-code__3-5779/archive/master.zip)





### Source Code


<p><font size="1"><font size="3">Pretty much just copy and paste these functions
in your file, I would've made a header file but don't know how yet.</font></font></p>
<p><font size="3" color="#FF0000">Note: Make sure you include the string.h or
just #include</font></p>
<p><font size="3" color="#0000FF">Function Prototypes:<br>
</font><font size="3">string mid( int, int, string);<br>
int instr( int, string, string );<br>
string sleft( string, int );<br>
string sright( string, int );</font></p>
<p><font size="3" color="#0000FF">Function Definitions:<br>
</font><font size="3">string mid( int posStart, int intLen, string strSearch )<br>
{<br>
return strSearch.substr(posStart, intLen);<br>
}<br>
<br>
int instr(int startPOS, string strSearch, string strFind)<br>
{<br>
//return strSearch.find(strFind);<br>
return strSearch.find(strFind, startPOS);<br>
}<br>
<br>
string sleft(string strSearch, int intLen)<br>
{<br>
return strSearch.substr(0, intLen);<br>
}<br>
<br>
string sright(string strSearch, int intLen)<br>
{<br>
return strSearch.substr(strSearch.length() - intLen, intLen);<br>
}</font></p>

