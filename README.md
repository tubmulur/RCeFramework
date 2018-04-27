# RCeFramework
/*/\\<br/>
 (C) 2006-2018 RCe.Framework I.S.Zirinskiy, E.Y.Shapovalova, A.A.Chekmarev<br/>
\*\//<br/>
<br/>
Consists of 3 classic structure elements:<br/>
#Js<br/>
:position->showAll<br/>
:position->elementView<br/>
:action->upadateElement(<br/>
	[<br/>
	url:url<br/>
	]<br/>
);<br/>
#Css
/*
window 
	{
	{
*/
window header
	{
	}
window element.card
	{
	}

window section
	{
	}
window section form
	{
	}
window section form element
	{
	}
window section div.body.volume
	{
	}
#layout
<window class="flex-full">
	<header></header>
	<element class="card" url="///">
		<header></header>
	</element>
</window>

:position->elementView
<window class="flex-full">
	<header></header>
	<section>
		<form class="header controls">
			<element url="///"></element>
		</form>
		<div class="body volume">
		</div>
	</section>
</window>
