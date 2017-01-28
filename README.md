<!DOCTYPE html>
<html>
	<head>
		<title>HTML DEMO</title>
	</head>
    <body>
			<h1><strong>Please enter your details for our dating website!</strong></h1>
			<fieldset>
			<legend>Your face</legend>
			<label for="avatar">Your image:</label>
			<input type="file" id="avatar" name="avatar" required><br />Last name? <input name="lastName" type="text" /></fieldset>

			<fieldset><legend>Your General Details</legend> <form action="http://ihome.ust.hk/~rossiter/cgi­bin/show_everything.php">
  <label for="age">Your age:</label>
  <input type="number" min="0" max="99" step="1" value="18" name="age" required><br>
  <label for="birthday">Your birthday:</label>
  <input type="date" name="birthday"><br>
	Please indicate your intelligence level. <br>
 <input type="radio" name="iq" value="high">High <br>
 <input type="radio" name="iq" value="medium" checked>Medium <
 <input type="radio" name="iq" value="low">Low <br> <br>
 Please indicate your intelligence level. <br>
<input type="radio" name="iq" value="high">High <br>
<input type="radio" name="iq" value="medium" checked>Medium <
<input type="radio" name="iq" value="low">Low <br> <br>
  <label for="color">Your favorite color:</label>
  <input type="color" name="color"> <br>
  <label for="mood">Your mood:</label>
  Bad <input type="range" min="0" max="100" step="5" value="50" name="mood"> Good<br

</form></fieldset>

			<fieldset><legend>Your Indicators</legend>

					<label for="salary">Your salary:</label> Poor <input type="range" min="0" max="100" step="5" value="salary"> Rich <br /><label for="height">Your height:</label> Short <input type="range" min="0" max="100" step="5" value="height"> Tall <br></fieldset>


					<fieldset><legend>Your Contact Information</legend> Email <input name="youremail" type="text" /> <br />Mobile <input name="phonenumber" type="text" />
					<br />Your Address <input name="address" type="text" /></fieldset>
			<h1><br /> <input type="submit" value="Send" /></h1>
	</body>
</html>
