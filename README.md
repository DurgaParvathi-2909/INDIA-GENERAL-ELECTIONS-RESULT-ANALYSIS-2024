## India General Elections Result Analysis 2024
![image](https://github.com/user-attachments/assets/52eec3f4-8bdb-4ed5-8aa5-244b41fa037d)


## Overview 

The primary goal of this project is to analyze the results of the 2024 Indian General Elections using SQL. By examining key data points such as total seats available, seats won by various alliances (NDA, I.N.D.I.A., and others), and the performance of political parties across different constituencies and states, we aim to use SQL queries to extract insights and provide a comprehensive view of electoral outcomes across the nation.

## Project Overview
This project uses SQL to explore various aspects of the election results:

Calculate the total number of seats available for elections in each state.
Determine the number of seats won by different alliances: National Democratic Alliance (NDA), Indian National Developmental Inclusive Alliance (I.N.D.I.A.), and others.
Examine the performance of political parties within each alliance.
Provide constituency-level results, including winning and runner-up candidates, total votes, and margin of victory.
Compare the distribution of EVM votes vs postal votes for individual candidates.

## Dataset
The dataset consists of five tables that contain detailed election results:

𝗰𝗼𝗻𝘀𝘁𝗶𝘁𝘂𝗲𝗻𝗰𝘆𝘄𝗶𝘀𝗲_𝗿𝗲𝘀𝘂𝗹𝘁𝘀: Contains results for each parliamentary constituency, including the winning candidate, total votes, and margin of victory.

𝗽𝗮𝗿𝘁𝘆𝘄𝗶𝘀𝗲_𝗿𝗲𝘀𝘂𝗹𝘁𝘀: Details political parties, including which alliance (NDA, I.N.D.I.A., or Other) they belong to, and the seats they won.

𝘀𝘁𝗮𝘁𝗲𝘄𝗶𝘀𝗲_𝗿𝗲𝘀𝘂𝗹𝘁𝘀: Provides the results of elections at the state level, mapping parliamentary constituencies to their respective states.

𝗰𝗼𝗻𝘀𝘁𝗶𝘁𝘂𝗲𝗻𝗰𝘆𝘄𝗶𝘀𝗲_𝗱𝗲𝘁𝗮𝗶𝗹𝘀: Contains vote breakdowns for each candidate in a constituency, including EVM and postal votes.

𝘀𝘁𝗮𝘁𝗲𝘀: Includes information about Indian states, used to link election results to their respective regions.

## Key Analyses
𝟭. 𝗧𝗼𝘁𝗮𝗹 𝗦𝗲𝗮𝘁𝘀 𝗮𝗻𝗱 𝗔𝗹𝗹𝗶𝗮𝗻𝗰𝗲𝘀
SQL Query: Calculate the total number of parliamentary constituencies across India and analyze which alliance won the most seats.

𝟮. 𝗦𝗲𝗮𝘁𝘀 𝗪𝗼𝗻 𝗯𝘆 𝗔𝗹𝗹𝗶𝗮𝗻𝗰𝗲𝘀 𝗮𝗻𝗱 𝗣𝗮𝗿𝘁𝗶𝗲𝘀
SQL Query: Identify the total number of seats won by NDA, I.N.D.I.A., and other alliances, as well as the specific parties within each alliance.

𝟯. 𝗖𝗼𝗻𝘀𝘁𝗶𝘁𝘂𝗲𝗻𝗰𝘆-𝗟𝗲𝘃𝗲𝗹 𝗔𝗻𝗮𝗹𝘆𝘀𝗶𝘀
SQL Query: Analyze results at the constituency level, identifying the winning candidate, the runner-up, the total votes received, and the margin of victory.

𝟰. 𝗘𝗩𝗠 𝘃𝘀 𝗣𝗼𝘀𝘁𝗮𝗹 𝗩𝗼𝘁𝗲𝘀
SQL Query: Compare the distribution of EVM and postal votes for each candidate in a specific constituency, highlighting voter behavior across different voting methods.

𝟱. 𝗦𝘁𝗮𝘁𝗲-𝗟𝗲𝘃𝗲𝗹 𝗜𝗻𝘀𝗶𝗴𝗵𝘁𝘀
SQL Query: For specific states like Andhra Pradesh, determine the total seats, total candidates, total parties, and total votes (both EVM and postal).

## Key Takeaways
𝗡𝗗𝗔 𝘃𝘀 𝗜.𝗡.𝗗.𝗜.𝗔. 𝗣𝗲𝗿𝗳𝗼𝗿𝗺𝗮𝗻𝗰𝗲: NDA and I.N.D.I.A. alliances are the two dominant players. Insights into which alliance performed better in different states are derived.

𝗗𝗲𝘁𝗮𝗶𝗹𝗲𝗱 𝗖𝗼𝗻𝘀𝘁𝗶𝘁𝘂𝗲𝗻𝗰𝘆 𝗥𝗲𝘀𝘂𝗹𝘁𝘀: We provide detailed results at the constituency level, giving insights into individual candidate performances.

## Conclusion
This project provides a comprehensive analysis of the 2024 General Election results, offering key insights into electoral trends across India. By leveraging SQL queries on a robust dataset, we can extract valuable information to understand party performance, alliance strategies, and voter behavior.

𝐅𝐞𝐞𝐝𝐛𝐚𝐜𝐤
Feedback and suggestions on this project are highly appreciated. Please feel free to share any thoughts for improvement!
