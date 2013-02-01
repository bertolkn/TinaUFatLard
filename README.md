<!DOCtype html>
<html>
<head>
<title> MPG to KPL Converter! </title>
</head>
<center>
 
<center><b><FONT SIZE = +2 color="CC0000">MPG and KPL Converter</FONT></b><center><BR>
<BR>
 
<embed src="music1.m4a" autostart="true" hidden="true">
 

<body>
<form Name="HooDickey">
<input type="text" style="text-align: right" name="MPG" size="8" value="" onClick="this.value=''"> Miles/Gallon bitches
<input type="button" value="LEGGGO" onClick="ConvertMPGtoKPL();">
<input type="text" style="text-align: right" ID="multiply" name"KPL" size="8" value="" onCick="this.value=''"> Kilometers/Liter Mofo
</form>

<body background="https://retailcapital.com/wp-content/uploads/2012/09/roth_gas_station_large.jpg">
<BR>
<form Name="HooDickey2">
<input type="text" style="text-align: right" name="KPL" size="8" value="" onClick="this.value=''"> Kilometers/Liter bitches
<input type="button" value="LEGGGO" onClick="ConvertKPLtoMPG();">
<input type="text" style="text-align: right" ID="multiply2" name"MPG" size="8" value="" onCick="this.value=''"> Miles/Gallon Mofo
</form>

<script language="Javascript">
alert("Kerianne is a programming master. Click OK if you agree.")

function ConvertMPGtoKPL()
{
var MPG =document.HooDickey.MPG.value;
var KPL;
var toKPL =0.425144;


KPL = (parseInt(MPG) * toKPL).toFixed(3);

document.getElementById('multiply').value = KPL;
}

function ConvertKPLtoMPG()
{
var KPL =document.HooDickey2.KPL.value;
var MPG;
var toMPG =2.35215;


MPG = (parseInt(KPL) * toMPG).toFixed(3);

document.getElementById('multiply2').value = MPG;
}
</script>
</body>

</html>TinaUFatLard
============

Final Converter
