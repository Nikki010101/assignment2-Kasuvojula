# assignment2-Kasuvojula
# Nikhitha Kasuvojula
### Salar Jung Museum

***Salar Jung Museum*** takes you on a **nostalgic tour of the past**, with its collection of *royal trappings* such as sculpture, paintings, textiles, manuscripts, ceramics, carpets, **clocks**, furniture et al from various parts of the world.

---

#### Directions to Airport
The airport that is closest to the museum is Rajiv Gandhi International Airport.

1. From Airport take a bus to Jubliee Bus Station(AL)
2. Ride to LB Nagar
3. Walk to LB Nagar Ring Road
4. Ride to Chaderghat in 299H Bus
5. From there take a ride to Salar Jung Museum
* Bhongir Fort
* Srishailam Temple
* Srirangapur Temple
* Surendrapuri
* Yadagiriguta

Hey, if you want to know more about me click here: [About me](https://github.com/Nikki010101/assignment2-Kasuvojula/blob/ae12283addeea3b709339f26e50b5967570211a9/AboutMe.md)

|Name of the City|Location to visit|Time to spend (days)|
|:---------------|:---------------:|------------:|
|Paris|Eiffel Tower|1|
|Strasbourg|Gothic Cathedral|2|
|Marseille|The Old Port|2|
|Nice|French Riviera|1|

---
### Quotes

> Spread love everywhere you go. Let no one ever come to you without leaving happier. -*Mother Teresa*

> The greatest glory in living lies not in never falling, but in rising every time we fall. -*Nelson Mandela*

---

> How to change the color of an svg element?

Link for stackflow: <https://stackoverflow.com/questions/22252472/how-to-change-the-color-of-an-svg-element>

### Code

```
 <svg width="100%" height="100%">
  
  <!-- Create mask that we'll use to define a slight gradient -->
  <mask maskUnits="userSpaceOnUse" id="fade">
    <!-- Here's that slight gradient -->
     	<linearGradient id="gradient" x1="0" y1="0" x2="0" y2="100%">
      <stop offset="0" style="stop-color: #FFFFFF"></stop>
      <stop offset="1" style="stop-color: #000000"></stop>
    </linearGradient>
    <!-- The canvas for our mask -->
    <rect fill="url(#gradient)" width="100%" height="100%"></rect>
  </mask>
    
  <!-- Let's define the pattern -->
  <!-- The width and height should be double the circle radius we plan to use -->
  <pattern id="pattern-circles" x="0" y="0" width="40" height="40" patternUnits="userSpaceOnUse">
    <!-- Now let's draw the circle -->
    <!-- We're going to define the `fill` in the CSS for flexible use -->
    <circle mask="url(#fade)" cx="20" cy="20" r="20"></circle>
  </pattern>
  <!-- The canvas with our applied pattern -->
  <rect x="0" y="0" width="100%" height="100%" fill="url(#pattern-circles)"></rect>
  
</svg> 
```
Lets go to the code : <https://css-tricks.com/snippets/svg/svg-patterns/#aa-circle-pattern>
