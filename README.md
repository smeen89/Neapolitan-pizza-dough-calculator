<h1>Neapolitan pizza dough calculator for Home Assistant</h1><br>

![kalkylator](https://user-images.githubusercontent.com/106514124/214378704-5c25df76-21cf-44c7-9757-b0146867b47e.png)<br>

<h2>This calculator aims to:</h2>

<b>1. Simplify scaling of a dough recipe by automaticly calculate dough weight based on:</b> <br>
  <b>a)</b> input of number of pizzas and<br>
  <b>b)</b> weight of each pizza
  
 <b>2. Calculate required amount of fresh yeast* based on:</b><br>
   <b>a)</b> surrounding temperature of the dough throughout the fermentation i.e room temperature (or fridge temperature)<br>
   <b>b)</b> time until baking out the pizzas.<br>
   
 <b>3. Make it easy for the user to change hydration and salt levels to encourage experimentation.</b>
 
 <h2>This repository consists of 4 main files:</h2>
   
<b>The 4 main files are:</b><br>
<b>1.</b> HACS repositories - i.e a list of links to github repositories for Home Assistant that I've used for the setup.<br>
<b>2.</b> Input Helpers - a list of the input helpers (names** and settings) that needs to be created in order for the calculator to work.<br>
<b>3.</b> Yaml code - the code needs to go in your configuration.yaml file. This sets up the calculation and the sensors needed.<br>
<b>4.</b> Lovelace UI card yaml code - this is the code for the user interface and goes in your lovelace view.<br>

 <h2>Some quick notes on how I make a pizza dough:</h2>
 <b>1.</b> Start by disolving the yeast in lukewarm water, add salt and flour and mix the ingredients until they form a rough dough. No need for stretcing or kneeding. This is a "no knead dough"<br>
 <b>2.</b> Cover dough and let rest for 30 minutes.<br>
 <b>3.</b> Fold the dough over itself five times. There is great videos on YouTube on how to fold a "no knead pizza dough".<br>
 <b>4.</b> Cover dough and wait for 15 minutes.<br>
 <b>5.</b> Fold the dough over itself five times.<br>
 <b>6.</b> Cover dough and wait for 15 minutes.<br>
 <b>7.</b> Fold the dough over itself five times.<br>
 <b>8.</b> Now it's time for bulk fermentation. Cover dough and let it ferment.<br>
 <b>9.</b> Form into dough balls, cover and proof for remaining time.<br><br>
 <i>I usually let the dough bulk ferment for the first half of the time, and then proof for the rest of the time as individual dough balls.<br> 
 Please feel free to try out what you prefer.</i><br><br>

For video demonstration and great ideas see this reddit thread: https://www.reddit.com/r/homeassistant/comments/10k28wu/i_made_a_neapolitan_pizza_dough_calculator_with/<br><br>


<i>*note 1: The yeast is calculated based on fresh yeast. I'm from Sweden and use Kronjäst blå. Other brands or yeast types may give varying results.</i><br>

<i>**note 2: The input helpers, sensors and lovelace UI card yaml code have swedish names and terms.</i> <br>
