---
category: 'Order Interface'
title: 'Buttons'

layout: nil
---

Buttons im User Interface, sollen sich in Form nicht unterscheiden. Der Button soll speziell für Touch Interface designet sein.


<button class="order-order-button">Abbrechen</button><br>
<code>button {
	font-family: 'Palanquin', sans-serif;
	font-weight: 700;
	font-size: 18px;
	border:none;
	margin:10px;
	padding:25px;
}
</code>
<code>.order .orderlist cancel-button {
	color:#4D4D4D;
	background-color:#E6E6E6;
	box-shadow: 2px 2px 5px rgba(0,0,0,0.3);
</code>
<code>.order .orderlist .cancel-button:hover, .order .orderlist .cancel-button:active {
	background-color:#F0F0F0;
	box-shadow: none;
}
</code>


<button class="order-send-button">Abschicken</button><br>
<code>.order .orderlist send-button {
	color:#ffffff;
	background-color:#177FB2;
	box-shadow: 2px 2px 5px rgba(0,0,0,0.3);
}
</code>
<code>.order .orderlist .send-button:hover, .order .orderlist .send-button:active {
	background-color:#1988BF;
	padding:25px;
	border:none;
	box-shadow: none;
}
</code>