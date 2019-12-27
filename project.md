# Car Ramrod - Darts Club Management System

[Navigator](#)
- [Meet the Team](./team.md)
- [Interesting Jobs](./jobs.md)
- [Whiepapers - Our Expertise](./reports.md)
- Project Idea (Darts Club Management System)

Based heavily off of Justin Reid's idea from A1
*Explain the idea*
Create a digitally assisted management system for people who play darts, competitively or just in their backyard.  The DCSM will do away with non-random competition draws, chalkboard scoring, mistaken mathematics, and, provide a live stream of any current darts game dart-by-dart, whilst also linking the clubs around the world statistically, and socially.

*Identify potential market for it*
 For years world darts leagues are ‘chalked’ ie they’re scored on a chalkboard. Once the game is over there’s a piece of paper with the scores and a few stats but nothing permanent – occasional darts websites excepted. There’s also nothing to tie the clubs together, or the leagues, or the greater world darts community. There’s no standardised club management system despite a (mostly) standard set of club rules, there’s no standard way to draw players and have them compete in a league without ‘borrowing’ from others websites. There’s no statistics unless you’re really good, but no one truly knows you’re really good unless you turn up and go ‘through the ranks’ and hope local politics doesn’t have you sidelined before you’ve warmed up.

Until now.

*Risk assessment*
The issues that could come with this project are potential data breaches, the data will need to be stored in an encrypted format to prevent this. If there is no acecss to the internet for any reason, or a bad quality connection the data could be corrupted and shouldn't then be officailly tracked. This could be solved using a Progressive Web App methodology of using Service workers to track data locally then do batch pushing to the server whenever a stable connection can be established. Tracking the actual dart scoring could be difficult and this woulld initially be entered manually, essentially combining the chalked score boards with collaboration between different dart clubs/teams.

*Required skills*
Although the skills required for this would seem broad at first, they are mostly ‘ordinary web building skills.

- Web development
- Custom Networking

*This would be good to discuss in further detail with Justin*
- Potential Hardware could be created to actually track the position of the darts on the board, using lasers or a gyroscope or something...

~~No special hardware would be required.~~ The software skills for creating this are easily found in online marketplaces such as Freelancer. From my experience the most difficult part is deploying to the AWS environment. This is due to expertise required in establishing scalable cloud infrastrure, and, the lack of tutorials an duser guides available – which provide limited help due to not being maintained as fast as the AWS environment changes. A person with AWS experience would be required to be found.

*Technologies*
- Django or Ruby on Rails
- PostGreSQL
- Swift
- Java,
- JavaScript, including react.js
- VCS / Git.
- AWS server management

*Conclusion*
*Need to fix this up*
Play some darts locally. Crush the world championship globally. Manage it all with this.