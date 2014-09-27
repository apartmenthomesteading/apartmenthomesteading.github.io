---
layout: article
title:  "Compost Calculator"
date:   2014-09-27
categories: composting
image:
  feature: compost-feature.jpg
  teaser: compost-teaser.jpg
  thumb: compost-teaser.jpg
  creditlink: https://flic.kr/p/7Sbyv9
  credit: Lindsay
excerpt: "Calculate how much brown and green waste you can use to get a 30 C:N ratio in your compost bin."
ads: false
comments: true
featured: true
---

<SCRIPT LANGUAGE="Javascript">
<!--Begin Hiding

function  cItem(materialName,LbCuYd,percentH2O,percentN,CNRatio,percentLignin,percentCellWall,percentC,percentCAvail,CNAvailable)
{
this.materialName = materialName;
this.LbCuYd = LbCuYd;
this.percentH2O = percentH2O;
this.percentN = percentN;
this.CNRatio = CNRatio;
this.percentLignin = percentLignin;
this.percentCellWall = percentCellWall;
this.percentC = percentC;
this.percentCAvail = percentCAvail;
this.CNAvailable = CNAvailable;
}
//recordID,materialName,LbCuYd,percentH2O,percentN,CNRatio,percentLignin,percentCellWall,percentC,percentCAvail,CNAvailable
var aryCharacteristics = new Array();
aryCharacteristics[0] = new cItem("None",0,0,0,0,0,0,0,0,0);
aryCharacteristics[1] = new cItem("Laying Hen Manure",1479,69,8,6,3.4,3.4,48,47.7762096178409,5.97202620223012);
aryCharacteristics[2] = new cItem("Poultry Manure",1150,53,5.35,10,2,38,53.5,51.6374092559243,9.65185236941993);
aryCharacteristics[3] = new cItem("Vegetable Waste",1585,87,3.2,12,6,45,38.4000015258789,34.751319890372,10.8597873039178);
aryCharacteristics[4] = new cItem("Swine Manure",1620,80,3.1,14,2.2,40.5,43.3999977111816,41.6686542163803,13.4415017736328);
aryCharacteristics[5] = new cItem("Food Waste",1500,69,2.5,15,0.4,40,37.5,37.0955599806548,14.8382239922619);
aryCharacteristics[6] = new cItem("Dairy Cow Manure",1458,80,3,15,8.5,57.1,45,37.930246703768,12.6434155679227);
aryCharacteristics[7] = new cItem("Sheep Manure",1755,69,2.7,16,6,45,43.2000007629395,39.0952340136102,14.4797160456161);
aryCharacteristics[8] = new cItem("Grass (compacted)",650,82,3.4,17,6,45,57.8000030517578,52.3079769765749,15.3846986792282);
aryCharacteristics[9] = new cItem("Grass (loose)",300,82,3.4,17,6,45,57.8000030517578,52.3079769765749,15.3846986792282);
aryCharacteristics[10] = new cItem("Cattle Manure",1458,81,2.4,19,6,45,45.6000022888184,41.267192801346,17.194662983973);
aryCharacteristics[11] = new cItem("Coffee Grounds",1500,80,2,20,15,74,40,27.4593994972738,13.7296997486369);
aryCharacteristics[12] = new cItem("Horse Manure",1620,72,1.6,30,6,45,48,43.4391481368484,27.1494671809717);
aryCharacteristics[13] = new cItem("Leaves Fresh",300,65,1.3,40,6.5,31.5,52,48.3244247914861,37.1726358184735);
aryCharacteristics[14] = new cItem("Fruit Waste",1580,80,1.4,40,13.4,52.7,56,44.5238675756728,31.8027630956498);
aryCharacteristics[15] = new cItem("Leaves loose-dry",100,15,0.9,54,8,50,48.5999984741211,42.2151305910957,46.9057018993498);
aryCharacteristics[16] = new cItem("Leaves compact-wet",500,38,0.9,54,8,50,48.5999984741211,42.2151305910957,46.9057018993498);
aryCharacteristics[17] = new cItem("Straw Wheat",227,12,0.4,80,14,85,32,21.0648819390762,52.6622040629626);
aryCharacteristics[18] = new cItem("Newsprint",225,5.5,0.34,115.5,20.9,97,39.2700004577637,18.5045633603836,54.4251857815998);
aryCharacteristics[19] = new cItem("Office Paper",300,20,0.2,150,4,91,30,25.764296951096,128.82148283589);
aryCharacteristics[20] = new cItem("Cardboard",259,8,0.1,563,12,92,56.2999992370605,37.778709382554,377.787088196074);
aryCharacteristics[21] = new cItem("Wood Chips Softwood",400,40,0.09,641,28,95,57.6900024414063,20.3768853005642,226.409827676217);

var xLbWet;
var xLbWet1;
var xLbWet2;
var xLbWet3;
var xLbWet4;
var xVolume;
var xLbCuYd;
var xpH2O;
var xpH2O1;
var xpH2O2;
var xpH2O3;
var xpH2O4;
var xLbDry;
var xLbDry1;
var xLbDry2;
var xLbDry3;
var xLbDry4;
var xCAvail;
var xCAvail1;
var xCAvail2;
var xCAvail3;
var xCAvail4;
var xpN;
var xpN1;
var xpN2;
var xpN3;
var xpN4;
var xLbC;
var xLbC1;
var xLbC2;
var xLbC3;
var xLbC4;
var xLbN;
var xLbN1;
var xLbN2;
var xLbN3;
var xLbN4;
var xCN;
var xCN1;
var xCN2;
var xCN3;
var xCN4;
var xTotalC;
var xTotalN;
var xtotalCN;
var xMaterialName_1 = ""
var xMaterialName_2 = ""
var xMaterialName_3 = ""
var xMaterialName_4 = ""
var xVolume_1 = ""
var xVolume_2 = ""
var xVolume_3 = ""
var xVolume_4 = ""
var xResultText = ""

function getValues(indexNum,MNum)
{
// fLbWet_1 fpH20_1 fLbDry_1 fpCAvail_1 fpN_1 fLbC_1 fLbN_1 fCN_1
// LbCuYd percentH2O percentN CNRatio percentLignin percentCellWall percentC percentCAvail CNAvailable

switch (MNum) {
	case 1:
		xVolume = document.CompostCalc.fVolume_1.value;
		xMaterialName_1 = aryCharacteristics[indexNum].materialName;
		xVolume_1 = xVolume
		break;
	case 2:
		xVolume = document.CompostCalc.fVolume_2.value;
		xMaterialName_2 = aryCharacteristics[indexNum].materialName;
		xVolume_2 = xVolume
		break;
	case 3:
		xVolume = document.CompostCalc.fVolume_3.value;
		xMaterialName_3 = aryCharacteristics[indexNum].materialName;
		xVolume_3 = xVolume
		break;
	case 4:
		xVolume = document.CompostCalc.fVolume_4.value;
		xMaterialName_4 = aryCharacteristics[indexNum].materialName;
		xVolume_4 = xVolume
		break;
}



xLbWet=(aryCharacteristics[indexNum].LbCuYd/27) * xVolume;
switch (MNum) {
	case 1:
		xLbWeb1 = xLbWet;
		document.CompostCalc.fLbWet_1.value = Math.round(100*xLbWet)/100;
		break;
	case 2:
		xLbWeb2 = xLbWet;
		document.CompostCalc.fLbWet_2.value = Math.round(100*xLbWet)/100;
		break;
	case 3:
		xLbWeb3 = xLbWet;
		document.CompostCalc.fLbWet_3.value = Math.round(100*xLbWet)/100;
		break;
	case 4:
		xLbWeb4 = xLbWet;
		document.CompostCalc.fLbWet_4.value = Math.round(100*xLbWet)/100;
		break;
}

xpH2O=(aryCharacteristics[indexNum].percentH2O);

switch (MNum) {
	case 1:
		xpH2O1 = xpH2O;
		document.CompostCalc.fpH20_1.value = Math.round(100*xpH2O)/100;
		break;
	case 2:
		xpH2O2 = xpH2O;
		document.CompostCalc.fpH20_2.value = Math.round(100*xpH2O)/100;
		break;
	case 3:
		xpH2O3 = xpH2O;
		document.CompostCalc.fpH20_3.value = Math.round(100*xpH2O)/100;
		break;
	case 4:
		xpH2O4 = xpH2O;
		document.CompostCalc.fpH20_4.value = Math.round(100*xpH2O)/100;
		break;
}

xLbCuYd = aryCharacteristics[indexNum].LbCuYd;

xLbDry = ((xLbCuYd * xVolume)/27) - ((xLbCuYd * xVolume*xpH2O*.01)/27);

switch (MNum) {
	case 1:
		xLbDry1 = xLbDry;
		document.CompostCalc.fLbDry_1.value = Math.round(100*xLbDry)/100;
		break;
	case 2:
		xLbDry2 = xLbDry;
		document.CompostCalc.fLbDry_2.value = Math.round(100*xLbDry)/100;
		break;
	case 3:
		xLbDry3 = xLbDry;
		document.CompostCalc.fLbDry_3.value = Math.round(100*xLbDry)/100;
		break;
	case 4:
		xLbDry4 = xLbDry;
		document.CompostCalc.fLbDry_4.value = Math.round(100*xLbDry)/100;
		break;
}

xCAvail = (aryCharacteristics[indexNum].percentCAvail);

switch (MNum) {
	case 1:
		xCAvail1 = xCAvail;
		document.CompostCalc.fpCAvail_1.value = Math.round(100*xCAvail)/100;
		break;
	case 2:
		xCAvail2 = xCAvail;
		document.CompostCalc.fpCAvail_2.value = Math.round(100*xCAvail)/100;
		break;
	case 3:
		xCAvail3 = xCAvail;
		document.CompostCalc.fpCAvail_3.value = Math.round(100*xCAvail)/100;
		break;
	case 4:
		xCAvail4 = xCAvail;
		document.CompostCalc.fpCAvail_4.value = Math.round(100*xCAvail)/100;
		break;
}

xpN = (aryCharacteristics[indexNum].percentN);

switch (MNum) {
	case 1:
		xpN1 = xpN;
		document.CompostCalc.fpN_1.value = Math.round(100*xpN)/100;
		break;
	case 2:
		xpN2 = xpN;
		document.CompostCalc.fpN_2.value = Math.round(100*xpN)/100;
		break;
	case 3:
		xpN3 = xpN;
		document.CompostCalc.fpN_3.value = Math.round(100*xpN)/100;
		break;
	case 4:
		xpN4 = xpN;
		document.CompostCalc.fpN_4.value = Math.round(100*xpN)/100;
		break;
}

xLbC =
( (( ((xLbCuYd*xVolume)/27)-((xLbCuYd*xVolume*xpH2O*.01)/27) ))*xCAvail*.01 );

switch (MNum) {
	case 1:
		xLbC1 = xLbC;
		document.CompostCalc.fLbC_1.value = Math.round(100*xLbC)/100;
		break;
	case 2:
		xLbC2 = xLbC;
		document.CompostCalc.fLbC_2.value = Math.round(100*xLbC)/100;
		break;
	case 3:
		xLbC3 = xLbC;
		document.CompostCalc.fLbC_3.value = Math.round(100*xLbC)/100;
		break;
	case 4:
		xLbC4 = xLbC;
		document.CompostCalc.fLbC_4.value = Math.round(100*xLbC)/100;
		break;
}

xLbN =
( (( ((xLbCuYd*xVolume)/27)-((xLbCuYd*xVolume*xpH2O*.01)/27) ))*xpN*.01 );

switch (MNum) {
	case 1:
		xLbN1 = xLbN;
		document.CompostCalc.fLbN_1.value = Math.round(100*xLbN)/100;
		break;
	case 2:
		xLbN2 = xLbN;
		document.CompostCalc.fLbN_2.value = Math.round(100*xLbN)/100;
		break;
	case 3:
		xLbN3 = xLbN;
		document.CompostCalc.fLbN_3.value = Math.round(100*xLbN)/100;
		break;
	case 4:
		xLbN4 = xLbN;
		document.CompostCalc.fLbN_4.value = Math.round(100*xLbN)/100;
		break;
}

xCN = (aryCharacteristics[indexNum].CNAvailable);

switch (MNum) {
	case 1:
		xCN1 = xCN;
		document.CompostCalc.fCN_1.value = Math.round(100*xCN)/100;
		break;
	case 2:
		xCN2 = xCN;
		document.CompostCalc.fCN_2.value = Math.round(100*xCN)/100;
		break;
	case 3:
		xCN3 = xCN;
		document.CompostCalc.fCN_3.value = Math.round(100*xCN)/100;
		break;
	case 4:
		xCN4 = xCN;
		document.CompostCalc.fCN_4.value = Math.round(100*xCN)/100;
		break;
}
xTotalC = 0
	if (isNaN(parseFloat(xLbC1)))
		xTotalC = xTotalC;
	else
		xTotalC = xTotalC + xLbC1;

	if (isNaN(parseFloat(xLbC2)))
		xTotalC = xTotalC;
	else
		xTotalC = xTotalC + xLbC2;

	if (isNaN(parseFloat(xLbC3)))
		xTotalC = xTotalC;
	else
		xTotalC = xTotalC + xLbC3;

	if (isNaN(parseFloat(xLbC4)))
		xTotalC = xTotalC;
	else
		xTotalC = xTotalC + xLbC4;

	document.CompostCalc.fTotalLbC.value = Math.round(100*xTotalC)/100;

xTotalN = 0
	if (isNaN(parseFloat(xLbN1)))
		xTotalN = xTotalN;
	else
		xTotalN = xTotalN + xLbN1;

	if (isNaN(parseFloat(xLbN2)))
		xTotalN = xTotalN;
	else
		xTotalN = xTotalN + xLbN2;

	if (isNaN(parseFloat(xLbN3)))
		xTotalN = xTotalN;
	else
		xTotalN = xTotalN + xLbN3;

	if (isNaN(parseFloat(xLbN4)))
		xTotalN = xTotalN;
	else
		xTotalN = xTotalN + xLbN4;

	document.CompostCalc.fTotalLbN.value = Math.round(100*xTotalN)/100;

xtotalCN = Math.round(100*(xTotalC/xTotalN))/100;
if (isNaN(xtotalCN))
document.CompostCalc.fTotalCN.value = "";
else
document.CompostCalc.fTotalCN.value = xtotalCN;

xResultText = "";
/*
if (xMaterialName_1 == "None" || xVolume_1 == 0){
	xResultText = xResultText;
	}
else (xResultText.length == 0) {
	xResultText = xResultText + xVolume_1 + " part " + xMaterialName_1 + "";
	}
else (xResultText.length != 0) {
	xResultText = xResultText + ", " xVolume_1 + " part " + xMaterialName_1 + "";
	}
*/
if (xMaterialName_1 == "None" || xVolume_1 == 0){
	xResultText = xResultText;
	}
else {
	xResultText = xResultText + xVolume_1 + " part(s) " + xMaterialName_1 + "";
	}

if (xMaterialName_2 == "None" || xVolume_2 == 0){
	xResultText = xResultText;
	}
else {
	if (xResultText == ""){
	xResultText = xResultText + xVolume_2 + " part(s) " + xMaterialName_2 + "";
	}
	else {
	xResultText = xResultText + "\n" + xVolume_2 + " part(s) " + xMaterialName_2;
	}
	}

if (xMaterialName_3 == "None" || xVolume_3 == 0){
	xResultText = xResultText;
	}
else {
	if (xResultText == ""){
	xResultText = xResultText + xVolume_3 + " part(s) " + xMaterialName_3 + "";
	}
	else {
	xResultText = xResultText + "\n" + xVolume_3 + " part(s) " + xMaterialName_3;
	}
	}

if (xMaterialName_4 == "None" || xVolume_4 == 0){
	xResultText = xResultText;
	}
else {
	if (xResultText == ""){
	xResultText = xResultText + xVolume_4 + " part(s) " + xMaterialName_4 + "";
	}
	else {
	xResultText = xResultText + "\n" + xVolume_4 + " part(s) " + xMaterialName_4;
	}
	}


/*
if (xMaterialName_3 == "None" || xVolume_3 == 0){
	xResultText = xResultText;
	}
else {
	xResultText = xResultText + xVolume_3 + " part " + xMaterialName_3 + "";
	}
if (xMaterialName_4 == "None" || xVolume_4 == 0){
	xResultText = xResultText;
	}
else {
	xResultText = xResultText + xVolume_4 + " part " + xMaterialName_4 + "";
	}
*/
if (isNaN(xtotalCN)) {
	xResultText = "";
	}
else {
	xResultText = "For a total C:N Ratio of " + Math.round(xtotalCN) + ":1 mix " + "\n" + xResultText;
	}
//xMaterialName_4.length == 0 || 
//isNaN(xVolume_1) || 
// + ", " +xMaterialName_2 + ", " +xMaterialName_3 + ", " +xMaterialName_4;
document.CompostCalc.fResultText.value = xResultText;

}

function fillSelect(intSelected)
{
	var i;
	for (i = 0; i < aryCharacteristics.length; i++)
	{
		//	<option value="1" SELECTED></option>
		//	<option value="2"></option>
		document.write ("<option value=\"");
		document.write (i);
		if (i != intSelected)
		{
			document.write ("\">");
		}
		else
		{
			
			document.write ("\" selected>");
		}
		document.write (aryCharacteristics[i].materialName +" "+ Math.round(aryCharacteristics[i].CNAvailable) +":1");
		document.write ("</option>")
	
	}
}
//document.write (i+","+aryCharacteristics[i].materialName +","+ Math.round(aryCharacteristics[i].CNAvailable) +":1<br>");
//{

<!-- done hiding from old browsers -->
</script>

<small>This calculator was originally created by [Klickitat County](http://klickitatcounty.org/solidwaste/fileshtml/organics/compostCalcAbout.htm). All calculations and code belong to them.</small>

Choose a material. Enter a cubic foot measurement. Press TAB. The Total C:N ratio for your recipe will appear.
<br><br>
<b>Aim for a TOTAL C:N RATIO of 30.</b> (25-30 is good. 20-40 is OK.)
<br><br>

<form action="" method="post" name="CompostCalc">

<table width="540" border="0" cellspacing="1" cellpadding="0">
<tr align="center">
<td width="100" valign="bottom" id="eightpt">
<strong>Material</strong>
</td><td width="50" valign="bottom" id="eightpt">
<strong>CuFt</strong>
</td><td width="50" valign="bottom" id="eightpt">
LbWet
</td><td width="50" valign="bottom" id="eightpt">
%H2O
</td><td width="50" valign="bottom" id="eightpt">
available<br>%C
</td><td width="50" valign="bottom" id="eightpt">
%N
</td><td width="50" valign="bottom" id="eightpt">
available<br>Lb C
</td><td width="50" valign="bottom" id="eightpt">
Lb N
</td><td width="50" valign="bottom" id="eightpt">
available<br>C:N
</td>
</tr>
<tr><td width="100" align="right" id="eightpt">
<script language="JavaScript">
document.write ("<select name=\"fMaterial_1\" size=\"1\" onChange=\"getValues(fMaterial_1.selectedIndex,1)\">");
fillSelect(0);
document.write ("</select>");
<!-- done hiding from old browsers -->
</script>
</td><td id="eightpt">
<input type="text" name="fVolume_1" value="0" size="5" maxlength="12" onChange="getValues(fMaterial_1.selectedIndex,1)">
</td><td id="eightpt">
<input type="text" name="fLbWet_1" size="5" maxlength="12" readonly>
</td><td id="eightpt">
<input type="text" name="fpH20_1" size="5" maxlength="12" readonly>
<input type="Hidden" name="fLbDry_1" value="">
</td>
<td id="eightpt">
<input type="text" name="fpCAvail_1" size="5" maxlength="12" readonly>
</td><td id="eightpt">
<input type="text" name="fpN_1" size="5" maxlength="12" readonly>
</td><td id="eightpt">
<input type="text" name="fLbC_1" size="5" maxlength="12" readonly>
</td><td id="eightpt">
<input type="text" name="fLbN_1" size="5" maxlength="12" readonly>
</td><td id="eightpt">
<input type="text" name="fCN_1" size="5" maxlength="12" readonly>
</td></tr>

<tr><td width="100" align="right" id="eightpt">
<script language="JavaScript">
<!-- hide this script tag's contents from old browsers
document.write ("<select name=\"fMaterial_2\" size=\"1\" onChange=\"getValues(fMaterial_2.selectedIndex,2)\">");
fillSelect(0);
document.write ("</select>");
<!-- done hiding from old browsers -->
</script>
</td><td id="eightpt">
<input type="text" name="fVolume_2" value="0" size="5" maxlength="12" onChange="getValues(fMaterial_2.selectedIndex,2)">
</td><td id="eightpt">
<input type="text" name="fLbWet_2" size="5" maxlength="12" readonly>
</td><td id="eightpt">
<input type="text" name="fpH20_2" size="5" maxlength="12" readonly>
<input type="Hidden" name="fLbDry_2" value="">
</td>
<td id="eightpt">
<input type="text" name="fpCAvail_2" size="5" maxlength="12" readonly>
</td><td id="eightpt">
<input type="text" name="fpN_2" size="5" maxlength="12" readonly>
</td><td id="eightpt">
<input type="text" name="fLbC_2" size="5" maxlength="12" readonly>
</td><td id="eightpt">
<input type="text" name="fLbN_2" size="5" maxlength="12" readonly>
</td><td id="eightpt">
<input type="text" name="fCN_2" size="5" maxlength="12" readonly>
</td></tr>

<tr><td width="100" align="right" id="eightpt">
<script language="JavaScript">
<!-- hide this script tag's contents from old browsers
document.write ("<select name=\"fMaterial_3\" size=\"1\" onChange=\"getValues(fMaterial_3.selectedIndex,3)\">");
fillSelect(0);
document.write ("</select>");
<!-- done hiding from old browsers -->
</script>
</td><td id="eightpt">
<input type="text" name="fVolume_3" value="0" size="5" maxlength="12" onChange="getValues(fMaterial_3.selectedIndex,3)">
</td><td id="eightpt">
<input type="text" name="fLbWet_3" size="5" maxlength="12" readonly>
</td><td id="eightpt">
<input type="text" name="fpH20_3" size="5" maxlength="12" readonly>
<input type="Hidden" name="fLbDry_3" value="">
</td>
<td id="eightpt">
<input type="text" name="fpCAvail_3" size="5" maxlength="12" readonly>
</td><td id="eightpt">
<input type="text" name="fpN_3" size="5" maxlength="12" readonly>
</td><td id="eightpt">
<input type="text" name="fLbC_3" size="5" maxlength="12" readonly>
</td><td id="eightpt">
<input type="text" name="fLbN_3" size="5" maxlength="12" readonly>
</td><td id="eightpt">
<input type="text" name="fCN_3" size="5" maxlength="12" readonly>
</td></tr>

<tr><td width="100" align="right" id="eightpt">
<script language="JavaScript">
<!-- hide this script tag's contents from old browsers
document.write ("<select name=\"fMaterial_4\" size=\"1\" onChange=\"getValues(fMaterial_4.selectedIndex,4)\">");
fillSelect(0);
document.write ("</select>");
<!-- done hiding from old browsers -->
</script>
</td><td id="eightpt">
<input type="text" name="fVolume_4" value="0" size="5" maxlength="12" onChange="getValues(fMaterial_4.selectedIndex,4)">
</td><td id="eightpt">
<input type="text" name="fLbWet_4" size="5" maxlength="12" readonly>
</td><td id="eightpt">
<input type="text" name="fpH20_4" size="5" maxlength="12" readonly>
<input type="Hidden" name="fLbDry_4" value="">
</td>
<td id="eightpt">
<input type="text" name="fpCAvail_4" size="5" maxlength="12" readonly>
</td><td id="eightpt">
<input type="text" name="fpN_4" size="5" maxlength="12" readonly>
</td><td id="eightpt">
<input type="text" name="fLbC_4" size="5" maxlength="12" readonly>
</td><td id="eightpt">
<input type="text" name="fLbN_4" size="5" maxlength="12" readonly>
</td><td id="eightpt">
<input type="text" name="fCN_4" size="5" maxlength="12" readonly>
</td></tr>
<tr align="center">
<td>
&nbsp;
</td><td id="eightpt">
&nbsp;
</td><td id="eightpt">
&nbsp;
</td><td id="eightpt">
&nbsp;
</td><td id="eightpt">
&nbsp;
</td><td align="right" id="eightpt">
<b>TOTALS:</b>
</td><td id="eightpt">
<input type="text" name="fTotalLbC" size="5" readonly>
</td><td id="eightpt">
<input type="text" name="fTotalLbN" size="5" readonly>
</td><td id="eightpt">
<input type="text" name="fTotalCN" size="5" readonly>
</td>
</tr>
<tr align="center">
<td colspan="9" id="eightpt">
<textarea cols="60" rows="5" name="fResultText" wrap="soft"></textarea>
</td>
</tr>
</table>
</form>
<div id="default10"><div id="mlr5"><div id="mlr5">
<small>This calculator was originally created by <a href="http://klickitatcounty.org/solidwaste/fileshtml/organics/compostCalcAbout.htm">Klickitat County</a>. All calculations and code belong to them.</small>
<br><br>
</div></div></div>