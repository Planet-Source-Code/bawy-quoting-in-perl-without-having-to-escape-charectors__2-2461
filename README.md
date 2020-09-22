<div align="center">

## Quoting in Perl without having to escape charectors


</div>

### Description

Allows strings to be used without having to escape the quotation symbols
 
### More Info
 
This is a complex mathematical algorithm, it should not be adjusted unless you know what you are doing.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Bawy](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/bawy.md)
**Level**          |Advanced
**User Rating**    |4.3 (26 globes from 6 users)
**Compatibility**  |Java \(JDK 1\.1\), Java \(JDK 1\.2\)
**Category**       |[Input/ Output](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/input-output__2-84.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/bawy-quoting-in-perl-without-having-to-escape-charectors__2-2461/archive/master.zip)





### Source Code

```
#!usr/bin/perl
print "content-type:text/HTML\n\n";
use LWP::Simple;
for($x=0;$x<515;$x++) {
if ($x==344) {
$sdc = qq(I can use "quotes" freely in here);
$sdc = $sdc."|";
$sdc .= $sdc.$sdc;
@sdc = split(/[|]/,$sdc);
print $sdc[2];
} else {
#This next line ensures that the code maintains copyright to PSC or it will not work
get 'http://www.planet-source-code.com';
@t5g[$x] = $x**612.461456;
} }
```

