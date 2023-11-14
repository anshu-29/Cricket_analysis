**Virat Kohli Century Analysis***

### Description:
This SQL script provides a comprehensive analysis of Virat Kohli's cricket centuries, including details such as the number of centuries, centuries in different formats, venues, oppositions, and more. The script utilizes a hypothetical table named `virat_kohli` to fetch and analyze the data.

### SQL Queries:

1. **Ordering by Number:**
   - Retrieves all records from the table and orders them by the "Number" column in ascending order.

2. **Count of Double Centuries in Test:**
   - Counts the number of instances where the "Score" is greater than 200, indicating double centuries in Test matches.

3. **Centuries at Each Batting Position:**
   - Groups the data by batting position and counts the centuries scored at each position.

4. **Centuries in Each Format:**
   - Groups the data by format (ODI, Test, T20i) and counts the centuries scored in each format.

5. **Centuries Against Each Opposition:**
   - Groups the data by the opposition and counts the centuries scored against each team.

6. **Centuries in Each Country:**
   - Groups the data by the host nation and counts the centuries scored in each country.

7. **Centuries at Each Venue in India:**
   - Filters data for matches hosted in India and counts the centuries scored at each venue.

8. **Highest Scores in ODIs, Tests, and T20Is:**
   - Retrieves the highest scores in each format (ODI, Test, T20i).

9. **Centuries for a Winning Cause:**
   - Counts the centuries scored in matches where the outcome was a win.

10. **Centuries for a Winning Cause while Chasing:**
    - Counts centuries scored in ODIs where the team batted in the second inning and won.

11. **Centuries Scored Between 2016 to 2019:**
    - Counts centuries scored in the specified time range.

12. **Centuries Scored Between 2016 to 2019 in ODI and Test:**
    - Groups the data by format and counts centuries scored in each format within the specified time range.

13. **Count of MOTM Awards when Scored a Century in Each Format:**
    - Groups the data by format and counts instances where Virat Kohli received the "Man of the Match" award after scoring a century.

14. **Max Number of Centuries in a Year:**
    - Finds the year with the highest number of centuries and the corresponding count.

15. **Average Balls Taken to Complete a Century in ODI:**
    - Calculates the average number of balls faced when scoring a century in ODIs.

16. **Average Strike Rate When Century Scored in ODI:**
    - Calculates the average strike rate when scoring a century in ODIs.

17. **Out and Not Out Counts in ODI and Test:**
    - Separately counts the number of times Virat Kohli was out and not out in ODIs and Tests.

18. **Highest Score After a Century at Each Venue:**
    - Finds the highest score after a century in each venue for ODIs, Tests, and T20Is.

19. **Centuries in Each Type of Series:**
    - Groups the data by series and counts the centuries scored in each ODI series.

20. **Third Highest Score in World Cup:**
    - Retrieves the third-highest score in matches played in World Cup series.

### Usage:
- The script assumes the existence of a table named `virat_kohli` with appropriate columns (e.g., Number, Score, Format, etc.).
- Modify the queries as needed to match the actual structure of your database.

### Note:
This script is a tool for exploring and analyzing Virat Kohli's century data. Ensure that the database structure aligns with the assumptions made in the queries, and adapt the script accordingly.
