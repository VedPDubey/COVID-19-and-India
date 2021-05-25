# Covid-19-Dashboard

<h2>===================================================================================================</h2>

<h2>Click on the given link to see presentation:</h2>
<h3>https://drive.google.com/file/d/1-oQ0fuWZSxi80-nqGoHrtOlIFMnCeLCh/view?usp=sharing</h3>

<h2>Click on the given link to see demo (video):</h2>
<h3>https://www.youtube.com/watch?v=BTZSivNDwPM&t=152s</h3>

<h2>Click on the given link to see what it looks like:</h2>
<h3>https://rwishavg.github.io/COVID-19-and-India/frontend/index.html</h3>

<h2>-----------------------------------------------------------------------------------------------------</h2>
<h2>ALERT : Kibana Dashboard Will Not Work on Chrome!!!</h2>
<p>Chrome is not compatible with Elastic Kibana</p>

<h2>What?</h2>
<h3>A Data Science Web App to visualise and predict India's fight against Covid-19</h3>

<h2>Why?</h2>
<h3>The recent surge in cases of covid-19 due to the second wave of the pandemic has created a crisis within the country. This calls for an analysis of how we've been handling the initial wave, how we are doing currently and what we can potentially do in the future. It is also important to make this information accessible to the people and that is what we aim to do.</h3>

<h2>How?</h2>
<h3>It been made possible by working with the data fetched from API's, analyzing it thoroughly, and creating vivid and impactful visualizations that are not only appealing to look at but are also important in drawing inferences from the data. This is has been neatly surmised into a web application with an appealing UI that your average user can use to get a grasp of the situation. We have also integrated a chatbot into our web app that updates the users on location specific pandemic data through simple conversation.</h3>

<h2>How we built it</h2>
<h3>
  1.Data preprocessing and sending the data to Elasticsearch using Bulk API.  /
  2. Analyzing the data using Kibana, and creating a dashboard of visualizations using it.  /
  3. Created an embeddable link of the dashboard.  /
  4. At this time the front-end of the website had been completed.  /
  5. Implemented live data update of COVID19 by writing scripts to read API's generated by scraping the web. Parsed the API into .JSON files and extracted data        from them.  
  6. Built a chatbot using RASA and Python, trained it on custom interaction, to make it handle general conversation. It is a chatbot that provides the user with      the up-to-date pandemic stats which is location specific.  
  7. All of the individual modules were integrated, and deployed to the localhost using Flask.  
</h3>

<h2>Challenges We Faced:</h2>
<h3>
  1. Getting the Bulk API to work with mapping in Elastic 7.12.1. This was fixed by using a generator function.  
  2. Configuring Kibana user settings and authentication to make the embedded link open without prompting the login screen.  
  3. Handling null values in the .JSON since the COVID19 API updates in real time.  
  4. Implementing the RASA chatbot in our web app.  
 </h3>
 
 <h2>What we are Proud Of:</h3>
 <h3>
  1. Implementing the Elastic stack in particular Elasticsearch and Kibana in order to perform data analysis and present impactful visualizations through the          Kibana dashboard.  
  2. Displaying Covid statistics that update in real time by reading from API's.  
  3. Building a RASA chatbot by training it on custom interaction and also enabling it to update the user with location specific pandemic statistics.  
 </h3>
 
 <h2>What's next for COVID-19 and India : An Analytical and Interactive Approach</h2>
 
 <h3>
  1. Better and more appealing UI/UX implementation for the web application.  
  2. Improving the RASA chatbot by training it with more interactions. Adding more APIs to it such as a news API which can provide users with related news              headlines to covid. Adding a feature that can provide the user with requirements they need in the area, such as essentials, number of beds available in the        nearby hospitals, vaccination sites, etc.  
  3. Deploy the web application to the Internet.  
  </h3>


<h3>Technologies Used:

<p>Elastic</p>
<p>Flask</p>
<p>Rasa</p>
</h3>



