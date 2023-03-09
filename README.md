# Cricket-Data-Analysis
Welcome to my Git repository for my cricket data analysis project, where I explored and analyzed the data of the T20 Cricket World Cup 2022. This project involved web scraping data from the website of ESPN Sports using Python, transforming and validating it to ensure accuracy and reliability. The analyzed data was then visualized using Power BI and presented in an interactive dashboard.

Through this project, I aimed to extract meaningful insights and trends from the T20 Cricket World Cup 2022 data, including team performance, individual player statistics, and match outcomes. By leveraging advanced analytical techniques and visualization tools, I was able to uncover hidden patterns and relationships in the data, offering valuable insights to both fans and professionals in the cricket industry.

The code and documentation in this repository provide a detailed account of my data analysis process, from web scraping and data cleaning to visualization and dashboard creation. This repository is a valuable resource for those looking to learn more about data analysis and visualization techniques in the context of cricket sports.

The data is extracted from the following website-
https://stats.espncricinfo.com/ci/engine/records/team/match_results.html?id=14450;type=tournament

Four main category of data is fetched using web scrapping-
  a) match_summary -> This data is directly fetched from the table that is available in the above link.
  b) batting_summary -> This data is fetched with the scorecard column links from the above link table's last column and the data of every batting information of the                           match is scrapped.
  c) bowling_summary -> This data is also fetched using the same method as batting_summary was fetched, only difference is that the bowling information is scrapped     
                        here.
  d) player_info -> This data is fetched form the player name link of each data point in each scorecard link. Duplicates are cleaned during iteration.
  
My cricket data analysis project contains a comprehensive collection of visualizations that fall into three main categories: Tournament Stats, Batting Stats, and Bowling Stats.

The Tournament Stats visualization provides information on the most runs, most wickets, highest runs in a match, highest inning score, most team wins, total 4's, total 6's, Final match info card, and ground locations. These statistics are presented in an easy-to-understand format, allowing users to quickly access important information about the tournament.

The Batting Stats and Bowling Stats visualizations are sub-divided into three categories each. The Batting Stats categories include Top Order, Middle Order, and Lower Order, while the Bowling Stats categories include Fast, Medium, and Spin. Each of these categories contains the top batting or bowling lineups based on specific cricket filters used by experts.

By dividing the visualizations into these categories, users can quickly and easily find the specific information they are looking for. Whether you are interested in analyzing the top-performing batsmen or bowlers, or want to gain a broader understanding of the tournament as a whole, these visualizations offer a wealth of information that is both comprehensive and easy to interpret.

Thank you for visiting my Git repository, and please feel free to explore and provide feedback on my work.
