>
chead>
<title>Simple Array Manipulation</title>
<head>
<body>
chl>Simple Array Manipulationc/hl>
<?php
I/ Initialize an array with some values
Sfruils = I"Aple", "Banana", "Cherry'I;
I/ Handle form submission to add a new fruit
if(S_SERVERIREQUEST_METHODI== POST" && ise(s_POST'ad_fnuit)1SnewFruit=S_POST'new_fruir):
if (!empty(SnewFruit))1
Sfruits(] =SnewFruit; // Add the new fruit to the array
I/ Display the current array
echo "<h2>Current Fruits:</h2>";
echo "<ul>";
foreach (Sfruits as Sfruit)1echo "<li>", htmlspecialchars(Sfruit)."</lis";
echo "</ul>":
1>
<h2>Add a New Fruit</h2>
<form method="post">
<input type=text" name="new_fruit"placcholder="Enter new fruit” required>
(input type"submit" name-"add_fruit'" value'"Add Fruit"!
</form>
<body>
</html>
  OUTPUI
localhost/array1.php
Simple Array Manipulation
Current Fruits:
Apple
Banana
Cherry
orange
Add a New Fruit
