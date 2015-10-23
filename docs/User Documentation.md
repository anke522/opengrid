<br>
<div align="center"><img src="https://github.com/Chicago/opengrid/blob/master/docs/media/combine32.png"></div>

## Getting Started
<p>OpenGrid is an enterprise geographical information system. Developed to support situational awareness, incident monitoring and responses, historical data retrieval, and real-time advanced analytics.</p>

<p>The OpenGrid architecture consists of three primary parts: the user interface, service layer, and data layer. The user interface is design to remain unchanged. The service layer is meant to be flexible to any data source. The data layer will be implemented based on client specifications.</p>

<p>OpenGrid utilizes MongoDB, a NoSQL database optimized to handle big spatially-enabled data. From the application layer, users may then query data by type, time and distance from a point or within a boundary, while retrieving real-time or historical data. Queries and data flow through a web service to ensure data security.</p>

#### Acknowledgements
OpenGrid was developed with the support of Bloomberg Philanthropies. 

## User Documentation
<p>User documentation is designed to assist end users with the use of OpenGrid product and services. Upon usage of documentation the user will gain appropriate knowledge and capabilities to navigate the system. The user will inherit an understanding of the system and its processes and have the foundation to execute queries for navigation.</p>
 
#### Supported Browsers
We support the latest and previous releases of Firefox, Chrome and Safari. Internet explorer is supported from IE10+ no older versions will be supported. All browsers must have cookies enabled and support JavaScript/ECMAScript version 5.1.

## Quick Search
<p>
The quick search help feature assist users in performing a valid search. Each search is unique based on query type. Some are queried by keyword and others are queried based off keyword followed by key phrase (descriptive text) e.g., tweets and weather query. The search results will appear on the grid as either points or custom icons.
</p>

<p><b>Find an Address</b><br> 50 W. Washington St

<p><b>Display area by Lat and Long</b><br> 41.8270, -87.6423

<p><b>Search by Place Name</b><br> Daley Center

<p><b>Search by Tweets</b><br> Tweet Ballet</p>

<p><b>Search area weather</b><br> Weather 60602</P>

## Advanced Search

<p>Advanced Search allows you to combine search terms by setting specific parameters for your results.It gives the user the ability to narrow their searches by a series of different filters such as adding additional rules, groups,datasets and Geo spatial-filters.</p>

#### Selecting data and date range
<p>To query by data and date range...Click on add datasets, select the saved dataset from the list <b>(for ex: business license)</b>; click submit. Add a rule or group to your dataset <b><small>(Adding a rule or group gives the user an option to query by date, city, name, address, etc. depending on the search criteria.)</b></small>. Date range can be specified with the parameters of:</p>
- equal
- not equal 
- less
- less or equal
- greater 
- greater or equal
- between

<div align="center"><img src="https://github.com/Chicago/opengrid/blob/master/docs/media/combine21.png"></div>

#### Search around a parameter (Point)
<p>To search with given point or boundaries the Geo spatial-filters will have to be applied.<br>
There are two filters to search by <b>“Within”</b> and <b>“Near”</b>. <b>“Within”</b> is used to search boundaries within a query. <b>“Near”</b> is used to search within a given parameter or around the area of your locale.</p>
<b><i>Within</i></b> have search boundaries of:<br>

- Map Extent<br>
- Drawn Extent (create polygon or rectangular perimeter)<br>
- Citywide (within the city limits)<br>
- Zip Code (within a given zip code)<br>
- Ward (within a given ward)<br>

<b><i>Near</i></b> have search points of:<br>

- Near <b>“Me”</b> (search around the user geo location)<br>
- Near <b>“Marker”</b> (search around a given area)

#### Monitoring Queries
<p>The monitor mode in the quick search section allows the user to monitor and update activity using auto-refresh. To use auto-refresh for monitoring queries:</p>
- Enable the auto-refresh check-box
- Ascend or descend on the seconds needed for refreshing the screen <b><i><small>(seconds are user preference)</b></i></small>.

## Table Functions
<p>The table functionality is used to organized information that has been displayed via query. The table displays the data that was pulled from the queried results and in return structures it in a readable format for the user to interpret. Each dropdown are intertwined with one another.The table consist of five drop down sections: </p>

<div align="center"><img src="https://github.com/Chicago/opengrid/blob/master/docs/media/combine33.png"></div>
#### 1. Columns<br>
The columns section displays the list of columns from the query data-sets and places them in order by default. The columns can be interchangeable and removed to fit the user preference.

#### 2. Exportation<br>
The exportation dropdown is used to send or transmit data from the query into csv, pdf or MS- excel format. 

#### 3. Graphing<br>
The graphing functionality is used to display the query results into graph formation based on the information. The user has the decision to create a graph based key search criteria’s that displays in the dropdown list.

#### 4. Heat Map<br>
Heat Map function is displayed where values contained in a matrix are represented as colors. There are many color schemes that can be used to illustrate a heat map.

#### 5. Tile Map
Tile Maps are small images, usually rectangular or isometric that acts like a puzzle piece to cover an intended area.

### Manage Saved Queries
<p>Search criteria that’s been entered and saved within the database are called Saved Queries. The saved queries are store in the Manage Queries section. To save a query, the user enters in the preferred name for a query; then clicks the saved button. The user will also be given an option to overwrite other queries and save it using an existing name.</p>
<p>There are three icons for managing queries submit, share and delete. The submit function allows the user to run the query for the manage queries window. The share function gives the user the ability to share a query either to a group or to another user. The delete function gives the user the option to delete a query.</p>

<div align="center"><img src="https://github.com/Chicago/opengrid/blob/master/docs/media/combine31.png"></div>

## Measure distances and areas
<p>Measuring distances and areas is a function within OpenGrid that allows the user to perform measurements between any given point to another. Once the measurement tool is selected the user will be prompt to start creating measurements by adding points on the map.</p>

## Frequently Asked Questions











