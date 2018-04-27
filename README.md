# RCeFramework
/\*/\\\ <br/>
 (C) 2006-2018 RCe.Framework I.S.Zirinskiy, E.Y.Shapovalova, A.A.Chekmarev <br/>
\\*\// <br/>
<br/>
Consists of 3 classic structure elements: <br/>
# Js<br/>
:position->showAll<br/>
:position->elementView<br/>
:action->upadateElement(<br/>
	[<br/>
	url:url<br/>
	]<br/>
);<br/>
# Css<br/>
/*<br/>
window <br/>
	{<br/>
	{<br/>
*/<br/>
window header<br/>
	{<br/>
	}<br/>
window element.card<br/>
	{<br/>
	}<br/>
window section<br/>
	{<br/>
	}<br/>
window section form<br/>
	{<br/>
	}<br/>
window section form element<br/>
	{<br/>
	}<br/>
window section div.body.volume<br/>
	{<br/>
	}<br/>
# layout<br/>
<window class="flex-full"><br/>
	<header></header><br/>
	<element class="card" url="///"><br/>
		<header></header><br/>
	</element><br/>
</window><br/>
<br/>
:position->elementView<br/>
<window class="flex-full"><br/>
	<header></header><br/>
	<section><br/>
		<form class="header controls"><br/>
			<element url="///"></element><br/>
		</form><br/>
		<div class="body volume"><br/>
		</div><br/>
	</section><br/>
</window><br/>
<br/>
