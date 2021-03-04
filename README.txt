<html>
<head>
    <meta charset="UTF-8">
    <title>ORDER FOODS</title>
</head>
<body>
<h1>Order Form</h1>
<h3>What would you like to buy?</h3>
<form>
    <select nam="Combo">
        <option value="ComboA">Combo A</option>
        <option value="ComboB">Combo B (+  0.5$)</option>
        <option value="ComboC">Combo C (+  0.5$)</option>
    </select>
</form>
<h3>How many would you like to order</h3>
<form>
    <label><input name="combo1"value="cost"type="checkbox"/> <b>1 - $10 </b> </label> </br>
    <label><input name="combo2" value="cost" type="checkbox" /> <b>2 - $20 </b> </label> </br>
    <label><input name="combo3" value="cost" type="checkbox"/> <b> 3 - $25 </b> </label>
</form>
<h3> <b>Name</b> <span style="color: red"> *</span> </h3>
<label><input type="text" name="hodem" placeholder="FistName"</label>
<label><input type="text"name="ho"placeholder="LastName"</label>
<h3>Email</h3>
<form>
    <label><input type="email"name="mail"placeholder="Email"</label>
</form>
<h3>Phone Number</h3>
<label><input type="text"name="phonenumber1" size="5"</label> -
<label><input type="text" name="phonenumber2"size="5"</label> -
<label><input type="text" name="phonenumber3"size="5"</label>
</br>
<p><label><input type="button" name="submit" value="Submit"</label></p>

</body>
</html>