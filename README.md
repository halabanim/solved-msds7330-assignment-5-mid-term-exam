Download Link: https://assignmentchef.com/product/solved-msds7330-assignment-5-mid-term-exam
<br>
You are asked to develop/manage a database for an association that organizes basketball tournaments.

Each year they host a number of tournaments in different locations, any number of teams can participate in any number of tournaments. Each tournament has a certain number of games.  The following you have been given minimum attributes to store in the database. This is not an inclusive list, as it does not contain any keys needed in a table. Please add any items that you feel will be beneficial.

<ul>

 <li>ToureyID,</li>

 <li>TourneyDate,</li>

 <li>TourneyLocation,</li>

 <li>TeamName,</li>

 <li>HeadCoachFirstName,</li>

 <li>HeadCoachLastName,</li>

 <li>PlayerFirstName,</li>

 <li>PlayerLatName,</li>

 <li>PlayerStreetAddress,</li>

 <li>PlayerCity,</li>

 <li>PlayerZipCode,</li>

 <li>GameNumber (As stated earlier, each tournament has a certain number of games)</li>

 <li>CourtID (This is the court number where the game is being played. Just remember multiple games within a tournament will be played on the same court)</li>

 <li>WinningTeam (Team that won the game)</li>

 <li>HomeTeam &amp; AwayTeam (Designate which team is Home and which is away within a game)</li>

 <li>PlayersScore (Score of each player in a specific game within a tournament)</li>

</ul>

<strong>Tasks to do: </strong>

<ol>

 <li>Develop a normalized schema for the database using MySQL Workbench</li>

 <li>Create the tourney DB using the model you just created (forward engineering)</li>

 <li>Insert values into the Database from the csv files provided.</li>

 <li>Perform the following queries:

  <ol>

   <li>Provide locations where the association is holding tournaments</li>

   <li>Display all players and their address formatted suitably for a mailing list, sorted by zip code.</li>

   <li>Display teams and the name of their head coach.</li>

   <li>Show tournaments that have not been played yet.</li>

   <li>Display name of top 10 scorers (Players who scored highest) along with their score.</li>

   <li>Display players’ names along with their highest score</li>

   <li>List the player (names) whose highest score in a game is more than 10 points higher than their average.</li>

  </ol></li>

</ol>

<ol start="5">

 <li>Create a view of all the tournaments that have been played at Red Rooster.</li>

 <li>Connect to this database using Python</li>

 <li>a) Display name of all the tournaments that were previously held.</li>

</ol>

<strong>Data: </strong>

You will find csv files that should give you most of the attributes that you need to complete the test.

<strong>What to submit: </strong>

<ol>

 <li>Screenshots of the schema</li>

 <li>Screenshots of your queries along with the output</li>

 <li>Screenshot of your code to insert values into the database.</li>

 <li>Screenshot of your python code</li>

 <li>Screenshot of results of your python code.</li>

</ol>

Note: Unless agreed upon ahead of time, there will be no extension to this. NO submission via email. No grade will be provided for a late submission.


