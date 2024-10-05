<h1>Travel Tide User Segmentation Analysis</h1>
<h3>1.) Project Overview</h3>
This project is a user segmentation analysis for Travel Tide, a company that offers an app for booking flights and hotels. The goal of the project was to create a user segmentation model that could be used to distribute perks to different user groups based on their engagement with the app.
<br><br>
We processed data from four large tables and focused on filtering out only active users from the last 6 months. The resulting dataset had around 50,000 session-based rows, which were aggregated into a user-based table with various metrics. These metrics were then used for segmenting users into different groups.
<h3>2.) Data Sources</h3>
The project utilized the following four key tables:<br><br>

1. sessions; User behaviour when using the Travel Tide app
2. users; Demographic informations
3. flights; Information about booked flights
4. hotels; Information about booked hotels

<h3>3.) Methodology</h3>
<b>Data Filtering:</b><br> We filtered the data to only include active users from the last 6 months to maintain relevance.<br><br>
<b>Data Aggregation:</b><br> Session-based data was aggregated into user-level data, creating metrics like user activity, booking patterns, and engagement.<br><br>
<b>Segmentation:</b><br> Using the aggregated data, we segmented users into different groups based on metrics.<br><br>
<b>Metric Weighting:</b><br> We assigned weights to certain metrics to create a scoring system for each perk, although this was done without substantial data backing. Therefore, we recommend A/B testing to validate the effectiveness of the perks and the weighting approach.
<h3>4.) Tools Used</h3>
<ul>
<li>Python</li>
<li>Postgresql</li>
<li>Pandas for data manipulation</li>
<li>Matplotlib/Seaborn for visualizations</li>
</ul>
<h3>5.) Key Findings</h3>
<ul>
<li><b>User Segmentation:</b> We successfully segmented users based on the aggregated metrics, though improvements can be made with more detailed testing.</li>
<li><b>Recommendation:</b> Since the perk weighting was subjective, A/B testing should be performed to validate the impact of the weighted metrics on user engagement.</li>
</ul>
<h3>6.) Next Steps</h3>
<ul>
<li>Conduct A/B testing to validate the segmentation model and perk distribution strategies.</li>
<li>Refine the user segments based on additional data and feedback from testing.</li>
</ul>

<h3>7.) Authors</h3>
Stephan Welzel
