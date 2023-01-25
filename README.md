<h1>Neapolitan pizza dough calculator for Home Assistant</h1><br>

![EN](https://user-images.githubusercontent.com/106514124/214527109-94c0348d-859f-41d2-83ea-7d57da702fe8.png)    ![SE](https://user-images.githubusercontent.com/106514124/214527268-2072c149-29e9-4e71-b3eb-2d4985c2870b.PNG)

<h2>Prerequisits</h2>
I have used the following HACS addons in order to setup the calculator

https://github.com/custom-cards/button-card<br>
https://github.com/custom-cards/stack-in-card<br>
https://github.com/thomasloven/lovelace-card-mod<br>

<h2>This calculator aims to</h2>

<b>1. Simplify scaling of a dough recipe by automaticly calculate dough weight based on:</b> <br>
  <b>a)</b> number of pizzas<br>
  <b>b)</b> weight of each pizza
  
 <b>2. Calculate required amount of fresh yeast* based on:</b><br>
   <b>a)</b> surrounding temperature of the dough throughout the fermentation i.e room temperature or fridge temperature<br>
   <b>b)</b> time until baking out the pizzas.<br>
   
 <b>3. Make it easy for the user to change hydration and salt levels to encourage experimentation.</b>
 
 <h2>Installation</h2>
 
 <h3>This repository consists of an English and a Swedish version each containing 3 files</h3>
 <i> Choose either the EN or SE version. Don't mix them!</i><br>
 
<h3>Swedish versison</h3>
<b>1. SE Input Helpers</b><br>
A list of the input helpers (type, names and settings) that needs to be created in your installation in order for you to be able to input data to the calculator.<br><br>
<b>2. SE Yaml code</b><br>
The code needs to go in your configuration.yaml file. This sets up the calculation parameters and creates the necessary sensors.<br><br>
<b>3. SE Lovelace UI card yaml code</b><br>
This is the code for the user interface and goes in your lovelace view.<br>

<h3>English versison</h3>
<b>1. EN Input Helpers</b><br>
A list of the input helpers (type, names and settings) that needs to be created in your installation in order for you to be able to input data to the calculator.<br><br>
<b>2. EN Yaml code</b><br>
The code needs to go in your configuration.yaml file. This sets up the calculation parameters and creates the necessary sensors.<br><br>
<b>3. EN Lovelace UI card yaml code</b><br>
This is the code for the user interface and goes in your lovelace view.<br>

 <h2>Some quick notes on how I make a pizza dough</h2><br>
 <b>Basic settings to get started that works well with Caputo Pizzeria flour</b><br><br>

<b>Jästemperatur:</b> 21 °C<br>
<b>Jästid:</b> 24 h<br>
<b>Vatten:</b> 66%<br>
<b>Salt:</b> 3%<br>
 
 <b>1.</b> Start by disolving the yeast in lukewarm water, add salt and flour and mix the ingredients until they form a rough dough. No need for stretcing or kneeding. This is a "no knead dough"<br>
 <b>2.</b> Cover dough and let rest for 30 minutes.<br>
 <b>3.</b> Fold the dough over itself five times. There is great videos on YouTube on how to fold a "no knead pizza dough".<br>
 <b>4.</b> Cover dough and wait for 15 minutes.<br>
 <b>5.</b> Fold the dough over itself five times.<br>
 <b>6.</b> Cover dough and wait for 15 minutes.<br>
 <b>7.</b> Fold the dough over itself five times.<br>
 <b>8.</b> Now it's time for bulk fermentation. Cover dough and let it ferment.<br>
 <b>9.</b> Form into dough balls, cover and proof for remaining time.<br><br>
 <i>I usually let the dough bulk ferment for the first half of the time, and then proof for the rest of the time as individual dough balls. Please feel free to try out what you prefer.</i><br><br>

For video demonstration and great ideas see this reddit thread: https://www.reddit.com/r/homeassistant/comments/10k28wu/i_made_a_neapolitan_pizza_dough_calculator_with/<br><br>

<b>Additional notes:</b><br>
<i>*note 1: The yeast is calculated based on fresh yeast. I'm from Sweden and use Kronjäst blå. Other brands or yeast types may give varying results.</i><br>
