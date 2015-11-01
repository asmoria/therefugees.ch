+++
title = "Kontakt"
[menu.main]
weight = 1000
name = "Kontakt"
+++

<h2>Schick uns eine Nachricht</h2>
<form action="//formspree.io/projekt.refugees@gmail.com" method="POST">
	<label for="name">Name:</label>
    <input type="text" name="name">
	<label for="email">E-Mail:</label>
    <input type="email" name="_replyto">
	<label for="content">Nachricht:</label>
	<textarea name="content" rows="10" cols="50"></textarea>
    <input type="submit" value="Abschicken">
	<input type="hidden" name="_next" value="http://therefugees.ch/message-sent" />
</form>
