Download Link: https://assignmentchef.com/product/solved-stat210-410-assignment4-dolphin-pacific
<br>
In each assignment you will be able to earn up to 5 marks based on your engagement on the moodle Discussion forums from the topics associated with the given assignment. See the Assignment assessment criteria document for more details.

<h1>Question 2</h1>

Spinner dolphins are a small delphinid that reside in subtropical and tropical waters. I collected data on spinner dolphins in Fiji to explore characteristics of their whistles. The type of whistle (e.g., concave, constant, convex, downsweep, sine, and upsweep) along with a variety of other acoustic properties of individual whistles was measured and is summarised in the <em>Spinner_dolphin </em>data-set.

<table width="603">

 <tbody>

  <tr>

   <td width="301">Variable</td>

   <td width="301">Description</td>

  </tr>

  <tr>

   <td width="301">Whistle</td>

   <td width="301">Whistle classification (Concave, Constant, Convex,Downsweep, Sine or Upsweep)</td>

  </tr>

  <tr>

   <td width="301">Duration</td>

   <td width="301">The time span of the whistle (seconds)</td>

  </tr>

  <tr>

   <td width="301">Centre_Freq</td>

   <td width="301">The frequency recorded at the midpoint (centre) of the whistle (kHz)</td>

  </tr>

  <tr>

   <td width="301">Low_Freq</td>

   <td width="301">The lowest frequency recorded during a whistle(kHz)</td>

  </tr>

  <tr>

   <td width="301">Delta_Freq</td>

   <td width="301">The range in frequency recorded during a whistle(kHz)</td>

  </tr>

  <tr>

   <td width="301">Max_Freq</td>

   <td width="301">Maximum frequency (kHz) recorded during a whistle (kHz)</td>

  </tr>

  <tr>

   <td width="301">Range_50</td>

   <td width="301">Centre frequency [minus] minimum frequency</td>

  </tr>

  <tr>

   <td width="301">Range_100</td>

   <td width="301">Maximum frequency [minus] centre frequency</td>

  </tr>

  <tr>

   <td width="301">Inflections</td>

   <td width="301">Number of points of change in whistle curvature</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Conduct an exploratory data analysis and present a summary of the <em>Spinner_dolphin </em>data-set.</li>

 <li>Find a low-dimensional representation of the numerical variables in the <em>Spinner_dolphin </em>data-set. Provide carefully labeled and well-formatted tables and/or figures – as well as an informative summary of your model and results. In addition, provide a visualisation and brief summary of whistle type in the context of your low-dimensional representation.</li>

</ul>

<h1>Question 3 [15 marks]</h1>

The Pacific Islands region stretches from the eastern coast of Australia all the way to French Polynesia and is comprised of a wide variety of island countries and territories. Exploring the similarities and characteristics of these nations is useful for environmental management and planning. A summary of the variables contained in the <em>Pacific_Islands </em>data-set is listed below.

<table width="602">

 <tbody>

  <tr>

   <td width="332">Variable</td>

   <td width="270">Description</td>

  </tr>

  <tr>

   <td width="332">PICT</td>

   <td width="270">Pacific Island Country or Territory</td>

  </tr>

  <tr>

   <td width="332">Land_area</td>

   <td width="270">Total land area (<em>km</em><sup>2</sup>)</td>

  </tr>

  <tr>

   <td width="332">Coastline</td>

   <td width="270">Total distance of coastlines (<em>km</em>)</td>

  </tr>

  <tr>

   <td width="332">EEZ</td>

   <td width="270">Economic Exclusive Zone area (<em>km</em><sup>2</sup>)</td>

  </tr>

  <tr>

   <td width="332">Shelf_Area</td>

   <td width="270">Continental shelf area (<em>km</em><sup>2</sup>)</td>

  </tr>

  <tr>

   <td width="332">Inshore_fishing_area</td>

   <td width="270">Continental shelf area accessible for inshore fishing (<em>km</em><sup>2</sup>)</td>

  </tr>

  <tr>

   <td width="332">Coral_reefs</td>

   <td width="270">Percentage of the world’s coral reefs contained in this PICT</td>

  </tr>

  <tr>

   <td width="332">Seamounts</td>

   <td width="270">Percentage of the world’s seamounts contained in this PICT</td>

  </tr>

  <tr>

   <td width="332">Primary_production</td>

   <td width="270">Estimated primary production for the marine environment (mg of carbon/<em>m</em><sup>2</sup>/day)</td>

  </tr>

  <tr>

   <td width="332">MPA</td>

   <td width="270">“Marine protected areas” (<em>km</em><sup>2</sup>)</td>

  </tr>

  <tr>

   <td width="332">PA</td>

   <td width="270">Terrestrial “protected areas” (<em>km</em><sup>2</sup>)</td>

  </tr>

  <tr>

   <td width="332">Pop</td>

   <td width="270">Population size of the PICT</td>

  </tr>

  <tr>

   <td width="332">Total_spp</td>

   <td width="270">Total number of animal species listed for thisPICT</td>

  </tr>

  <tr>

   <td width="332">Region</td>

   <td width="270">Melanesia, Polynesia or Micronesia</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Use k-means clustering to identify the optimal number of clusters for the <em>Pacific_Islands </em>data-set. Visualise your results, provide some broad insights into cluster membership in relation to Region, and provide a brief summary of your results.</li>

 <li>Create at least two different types of dendrograms based on the <em>Pacific_Islands </em>data-set. Use <em>PICT </em>as your label on each leaf for these plots. Using the same number of clusters in each dendrogram compare and contrast your results. Provide a general interpretation of groupings seen in each of the dendrograms you produce.</li>

</ul>