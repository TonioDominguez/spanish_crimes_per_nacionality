<div align="left">
  <h1>CRIME ANALYSIS BY ORIGIN IN SPAIN</h1>

   <img src="https://i.imgur.com/M1vveh0.png" alt="Crime Analysis" style="width: 70%; height: auto;">


---

<div style="text-align: left;">
  <h2>About the Project 🚔	</h2>

 <p>
Europe is experiencing the rise of far-right movements that constantly fuel fear of the foreign population through false data that create non-existent social alarms.
 </p>
 <p>
In Spain, for example, these groups spread baseless figures that accuse people of foreign origin (mainly African) and directly link them to the increase in crime in the country.
</p>
<p>
That is why this data exploration aims to disprove these alarming claims that assert that 40% of crimes committed in Spain are perpetrated by foreigners.
</p>
<p>
  In the face of the impunity of lies spread solely to gain political advantage, data analysis emerges as an indispensable tool to curb this type of injustice.
</p>
  
  <h3>Objective:</h3>
  <p>
   In this project, I compare real data gathered by official institutions to prove my hypotesis: alt-righ fake news are lying to people and creating an awful idea about the inmigration in Spain. My point is to dismiss this false info that overloads our media and some policical speechs.
  </p>
  
  <h3>Methodology:</h3>
  <ol>
    <li><strong>Data Gathering:</strong> Download a specific dataset from <a href="https://www.ine.es/dyngs/INEbase/es/categoria.htm?c=Estadistica_P&cid=1254735573206">INE (Instituto Nacional de Estadística)</a> to analyze the real data about crime in Spain by condemned's origin. </li>
    <li><strong>Data Preprocessing and EDA:</strong> Adjusting and fixing the data gathered for a deep exploration. Studying through EDA the stadistics crime by crime for, after that, make a general analysis of the total crimes and the relation with the origins.</li>
    <li><strong>Conclusions in Slides:</strong> Develop a detailed explanation for the final results in slides and the final confirmation of the hypotesis.</li>
    <li><strong>Power BI Dashboard:</strong> Create a dashboard for the total crimes to see an interactive way to understand the evolution through the years.</li>
  </ol>

---

<div style="text-align: left;">
  <h2>Points to consider ▶️	</h2>

<p>
  Some points to keep in mind to understand the analysis:
</p>

<ul>
    <li>The crimes analyzed consist of a specific selection: homicides, injuries, thefts, robberies, damages, crimes against collective security and crimes against public order. These crimes have been selected due to the relation that the alt-right finds with immigration.</li>
    <li>The data collected's period is between 2013 and 2023, grouped by origin: Spanish, African, American and European. We have discarted the origins from Asia and Oceania as their incidence is 0.6% of the total data.</li>
    <li>The EDA consists on crime count, total percentage, evolution during the period and annual growth percentage (both overall and per crime). In addition to the correlation between crime and origin.</li>
  </ul>

---

<div style="text-align: left;">
<h2>Project Structure :open_file_folder:</h2>

<p>
  This project is developed through one python notebook, one slides document and one power bi dashboard.
</p>

<ol>
  <li>
    <strong><a href="https://github.com/TonioDominguez/spanish_crimes_per_nacionality/blob/main/Crime%20in%20Spain%20v1.ipynb">DATASET PREPROCESSING & EDA (ENGLISH)</a></strong>
  </li>
  
  <li>
    <strong><a href="https://github.com/TonioDominguez/spanish_crimes_per_nacionality/blob/main/slides/Analisis%20de%20delitos%20por%20origen%20en%20Espa%C3%B1a.pdf">SLIDES DOCUMENT (ESPAÑOL)</a></strong>
  </li>
  
  <li>
    <strong><a href="https://github.com/TonioDominguez/spanish_crimes_per_nacionality/tree/main/power%20bi">POWER BI DASHBOARD (ESPAÑOL)</a></strong>
  </li>
</ol>

---

<div style="text-align: left;">
  <h2>Final Conclusions 🧑‍⚖️</h2>
<h3> Hypotesis confirmation</h3>
  <p>
After analyzing the crimes, we have been able to verify that the origin of individuals is not a determining factor in the results during the observed period.
</p>
  <p>
Neither the historical evolution nor the annual growth percentage studied, both in individual crimes and in the total, reveal any trend that indicates origin as an important factor. Nor does it influence the observed patterns.
  </p>
  
  <h3> Observations</h3>
  <ol>
  <li>
    <strong><u>Percentage of Crimes by Origin:</u></strong> 25.61% of the total crimes are committed by foreigners. The average percentage of crimes committed by foreigners per crime category is 24.91%. Foreigners commit up to 1/4 of the crimes in Spain.
    </li>
  
  <li>
    <strong><u>Critical Years:</u></strong> In some crimes, we observed that between 2015 and 2016, the number of incidents grew exponentially (other contextual factors should be analyzed to understand this). The systematic decline in 2020 in all crimes is due to the lockdown.
    </li>
  
  <li>
    <strong><u>Similarity in Patterns:</u></strong> The similarity in the evolution patterns and the high correlation between origins rule out the importance of origin in evaluating data behavior. However, in 4 out of the 7 crimes, we see a substantial increase. We conclude that regardless of origin, more crimes are being committed than 10 years ago.
  </li>
</ol>
</div>
