# Project Football Data

**Project Football Data** is a comprehensive data analysis tool designed to streamline data exploration, analysis, and visualisation. The tool supports multiple data formats and provides an intuitive interface for both novice and expert data scientists.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

Live Dashboard link:
https://app.powerbi.com/groups/me/reports/9365cfbe-6f2d-47f5-bc1d-e8c314a07156/7e4ed45010e68ff28721?experience=power-bi


## Dataset Content

* The dataset chosen is from Kaggle;
 https://www.kaggle.com/datasets/maso0dahmed/football-players-data/data

* The football dataset offers information for around 17,000 players. This includes; 
name: Name of the player.
full_name: Full name of the player.
birth_date: Date of birth of the player.
age: Age of the player.
height_cm: Player's height in centimeters.
weight_kgs: Player's weight in kilograms.
positions: Positions the player can play.
nationality: Player's nationality.
overall_rating: Overall rating of the player in FIFA.
potential: Potential rating of the player in FIFA.
value_euro: Market value of the player in euros.
wage_euro: Weekly wage of the player in euros.
preferred_foot: Player's preferred foot.
international_reputation(1-5): International reputation rating from 1 to 5.
weak_foot(1-5): Rating of the player's weaker foot from 1 to 5.
skill_moves(1-5): Skill moves rating from 1 to 5.
body_type: Player's body type.
release_clause_euro: Release clause of the player in euros.
national_team: National team of the player.
national_rating: Rating in the national team.
national_team_position: Position in the national team.
national_jersey_number: Jersey number in the national team.
crossing: Rating for crossing ability.
finishing: Rating for finishing ability.
heading_accuracy: Rating for heading accuracy.
short_passing: Rating for short passing ability.
volleys: Rating for volleys.
dribbling: Rating for dribbling.
curve: Rating for curve shots.
freekick_accuracy: Rating for free kick accuracy.
long_passing: Rating for long passing.
ball_control: Rating for ball control.
acceleration: Rating for acceleration.
sprint_speed: Rating for sprint speed.
agility: Rating for agility.
reactions: Rating for reactions.
balance: Rating for balance.
shot_power: Rating for shot power.
jumping: Rating for jumping.
stamina: Rating for stamina.
strength: Rating for strength.
long_shots: Rating for long shots.
aggression: Rating for aggression.
interceptions: Rating for interceptions.
positioning: Rating for positioning.
vision: Rating for vision.
penalties: Rating for penalties.
composure: Rating for composure.
marking: Rating for marking.
standing_tackle: Rating for standing tackle.
sliding_tackle: Rating for sliding tackle.

* I chose this dataset as it is ideal for data analysis, predictive modeling, and machine learning projects. It can be used for:

* Player performance analysis and comparison.

* Market value assessment and wage prediction.

* Team composition and strategy planning.

* Machine learning models to predict future player potential and career trajectories.

## Stakeholders

* Football scouts - identify talented players across various leagues.
* Football agents (intermediaries) - manage players, negotiate contracts and close deals.
* Club technical staff and coaches - need to know the skill of potential new players to improve new needs.
* Football pundits & journalists - to provide informed content & commentary.
* Fantasy football players and punters - to compete and play.
* Social media and content creators - create videos to analyse games.
* National team managers - choose the players they wish to add to their national sides.
* Advertising companies - decide who to choose their ads and marketing campaigns.
* Video games creators - accurately reperesent player skills in their video games.
* Fans - They can accurately discuss their team with their peers.

## User stories

* US1 - As a football scout, I want to access detailed player skill ratings so that I can identify and shortlist talented players across multiple leagues.
* US2 - As a football agent, I want to access detailed player skill ratings, their wages, value, and their release clauses so that I can manage players better and negotiate their contracts.
* US3 - As a club technical staff member or coach, I want to access detailed player profiles — including skill ratings, age, physical attributes such as weight, height, and body type — so that I can assess players' physical needs, tailor training and dietary plans, and make informed decisions to strengthen the team.
* US4 - As a football pundit or journalist, I want to access detailed player profiles — including full name, age, preferred foot, position(s), national team, and skill ratings — so that I can accurately describe and report on players when commentating or writing.
* US4 - As a Fantasy football player and a punter, I want to access detailed player profiles — including full name, position(s) and skill ratings — so that I can make infored decisions when selecting players and placing any bets.
* US4 - As a social media content creator, I want to access detailed player profiles — including full name, age, preferred foot, position(s), national team, and skill ratings — so that I can produce accurate and engaging content that analyses and showcases players to my audience.
* US4 - As a national team manager, I want to access detailed player profiles — including skill ratings, international reputation, national rating, position(s), age, and nationality — so that I can make informed selection decisions when choosing players for my national squad.
* US4 - As an advertising company, I want to access detailed player profiles — including full name, date of birth, age, height, weight, position(s), nationality, overall rating, and international reputation — so that I can make informed decisions when selecting the most suitable player for my marketing campaigns.
* US4 - As a video game creator, I want to access comprehensive player profiles — including full name, physical attributes, skill ratings, position(s), nationality, and overall rating — so that I can accurately represent each player as a realistic in-game avatar.
* US4 - As a football fan, I want to access detailed player profiles — including full name, age, preferred foot, position(s), national team, and skill ratings — so that I can engage in informed and meaningful discussions about players with my friends and peers.

## Business Requirements

A Data analyst has been approached by a Football data company that has provided a comprehensive dataset that contains information on football players. This includes the following; Players characteristics/attributes such as full name, age, date of birth, height, weight etc. Player technical skills such as passing, finishing, volleys, dribbling etc, it also includes players financial information such as players wages, values and release clauses and information about their national team such as nationality, national team, national rating, national team position etc.

The company consists of a range of Stakeholders: Football scouts, football agents (intermediaries), club technical staff and coaches, football pundits & journalists, fantasy football players and punters, social media and content creators, national team managers, advertising companies, video games creators, football fans they all have their own needs and when analysing and using the data.

BR1: Player Valuation
•Identify the relationships between player attributes such as age, skill ratings, international reputation and their wages, value and release clauses.
•Show relationships with data visualisations such as scatter plots and heat maps.
•Succes criteria:

BR2: Players performances
•Analyse and compare player skill ratings, such as finishing, passing, crossing.
•Enable stakeholders to filter and identify players by position and skillset.
•Provide visualisations that highlight top 10 performing players
•Success criteria:

BR3: Player Biographical Profiling
•Access to biographical and physical data such as age, nationality, height and weight
•Success criteria:

BR4: Predict player model
•Develop a machine learning model to predict a player's wage or release clause based on their attributes
•Achieve a minimum acceptable accuracy on unseen data
•Enable stakeholders such as agents and clubs to estimate a player's market value before negotiations
•Success Criteria: Model R² ≥ 0.85, MAE within an acceptable euro threshold, validated through cross-validation

BR5: Player profiles internationally
•Analyse the relationship between a player's international reputation, overall rating, and their public profile
•Support stakeholders such as advertising companies, journalists, and content creators in identifying high profile players
•Provide rankings and visualisations of players by overall rating and international reputation
•Success Criteria:

BR6: Interactive Dashboard & Data Exploration
•Create a user friendly dashboard for non-technical stakeholders to explore player data
•Enable filtering and segmentation by multiple criteria including position, nationality, age, and skill ratings
•Provide real time visualisations of player distributions and comparisons
•Success Criteria: Dashboard accessible without coding knowledge, responsive to all filter combinations, and usable by stakeholders ranging from football fans to professional scouts

## Hypothesis and how to validate?

* HP1 - The higher a player's overall rating, the higher their wage, value and release clause.

How to validate: Heat map, correlation matrix, violin plots, histogram

Results: Hypothesis supported by findings

* HP2 - the higher the individual skill rating, the higher the overall rating.

How to validate: violin plots, histogram

Results: Hypothesis supported by findings

* HP3 - Taller players will have a higher heading accuracy.

How to validate: Scatter plots and correlation (visual validation)

Results: Grouped HP3-5 to create scatterplots and correlation to check if Hypothese can be proven. 

* Disproved

* HP4 - the higher a player is rated on ball control, the higher rated the finishing.

How to validate: Scatter plots and correlation (visual validation)

Results: Approved

* HP5 - players with higher crossing rating will have a higher freekick accuracy.

How to validate: Scatter plots and correlation (visual validation)

Results: Approved

When doing the core concepts I added another Hypothesis.

* HP6 - Is there a significant difference in overall_rating between players under 25 and players 25 and older?

Null Hypothesis: There is no difference in the overall rating of players under 25 and players who are over 25.

Alternate Hypotheis: There is a significant difference in the overall rating of players under 25 and players who are over 25.

How to validate: T-test

Result: t_statistic: -4.638399535742817

p_value: 4.11081204067634e-06

The p-value is 4.11e-0.6 which converts to 0.00000.41 which far below than 0.05, which means I reject the null hypothesis. There is statistically significant evidence that overall ratings differ between the two age groups.

The t-statistic shows a negative value of -4.638 means players under 25 have a lower mean overall rating than players (5 and older — which intuitively makes sense, as older players tend to be more experienced.

## Project Plan

* Valid the Hypotheses by using statistical tests

* Display atleast 4 different plots to help answer the business requirements and in the dashboard.

* Machine Learning algorithm for predictive analysis

* Ethical considerations - Legal and social

* Created a dashboard with PowerBI that is user friendly and easy to navigate

* Reflections and constant updates to README

## High-level steps taken for the analysis

 ETL Process – Load the dataset taken from Kaggle into VS code.

Transform the data by the cleaning process; missing values, duplicates and outliers.

Used ML feature called Drop feature, there were a lot of columns for individual skills, grouped columns together and then dropped them to keep data clean and easier to analyse.

Created four new features: Defense attributes - marking, standing tackle, sliding tackle, aggression, strength, interceptions, composure

Attack attributes – finishing, heading accuracy, volleys, long shots, shot power, positioning, penalties

Passing attributes – short passing, long passing, curve, freekick accuracy, crossing, ball control, vision, reactions, dribbling

Pace attributes – acceleration, sprint speed, agility, balance, stamina, jumping

Loading the cleaned data in to the appropriate files and folders so it can used for data analysis.

Data Analysis: conducted descriptive statistics such as mean, median, standard deviation.

Visualisation of data: Using scatterplots, boxplots and barplots to identify key correlations between the different variables.

In depth Data Visualisation: Using scatter plots and heatmaps to examine relations and correlations that relate back to my busiess requirements and hypotheses.

Created a Machine Learning algorithm to predict value_euro based on overall_rating, potential using linear regression and Random forest regression.

Reports:
Consistently reported progress and maintained comprehensive documentation throughout the project's duration.

* How was the data managed throughout the collection, processing, analysis and interpretation steps?
* Why did you choose the research methodologies you used?




## The rationale to map the business requirements to the Data Visualisations

A Data analyst has been approached by a Football data company that has provided a comprehensive dataset that contains information on football players. This includes the following; Players characteristics/attributes such as full name, age, date of birth, height, weight etc. Player technical skills such as passing, finishing, volleys, dribbling etc, it also includes players financial information such as players wages, values and release clauses and information about their national team such as nationality, national team, national rating, national team position etc.

The company consists of a range of Stakeholders: Football scouts, football agents (intermediaries), club technical staff and coaches, football pundits & journalists, fantasy football players and punters, social media and content creators, national team managers, advertising companies, video games creators, football fans they all have their own needs and when analysing and using the data.

BR1: Player Valuation
•Identify the relationships between player attributes such as age, skill ratings, international reputation and their wages, value and release clauses.
•Show relationships with data visualisations such as scatter plots and heat maps.
•Succes criteria:

BR2: Players performances
•Analyse and compare player skill ratings, such as finishing, passing, crossing.
•Enable stakeholders to filter and identify players by position and skillset.
•Provide visualisations that highlight top 10 performing players
•Success criteria:

BR3: Player Biographical Profiling
•Access to biographical and physical data such as age, nationality, height and weight
•Success criteria:

BR4: Predict player model
•Develop a machine learning model to predict a player's wage or release clause based on their attributes
•Achieve a minimum acceptable accuracy on unseen data
•Enable stakeholders such as agents and clubs to estimate a player's market value before negotiations
•Success Criteria: Model R² ≥ 0.85, MAE within an acceptable euro threshold, validated through cross-validation

BR5: Player profiles internationally
•Analyse the relationship between a player's international reputation, overall rating, and their public profile
•Support stakeholders such as advertising companies, journalists, and content creators in identifying high profile players
•Provide rankings and visualisations of players by overall rating and international reputation
•Success Criteria:

BR6: Interactive Dashboard & Data Exploration
•Create a user friendly dashboard for non-technical stakeholders to explore player data
•Enable filtering and segmentation by multiple criteria including position, nationality, age, and skill ratings
•Provide real time visualisations of player distributions and comparisons
•Success Criteria: Dashboard accessible without coding knowledge, responsive to all filter combinations, and usable by stakeholders ranging from football fans to professional scouts

## Analysis techniques used

Structured approach: I structured the data analysis technique by following the module handbook and going through each criteria to add to my project, this included reviewing each section. By adhering to the handbook's guidance, I was able to incorporate all necessary elements and maintain consistency throughout the analysis process.

Data limitations: The data did not present any limitations; however, it could have been more of a challenge. There were no missing values or duplicates, which streamlined the data cleaning process. Additionally, there was only one categorical variable which I could not conduct in-depth analysis on categorical data.

Generative AI: I used AI to help with the code and ideas which helped me immensely throughout this project.

## Data Ethics

Ethics refers to the moral principles that govern a person's or organisation's behaviour and decision making. In the context of data and artificial intelligence, ethics concerns how data is collected, used, and interpreted, and whether the systems built from that data are fair, transparent, and beneficial to society. The overarching goal of data ethics can be summarised simply as maximum benefit and minimum harm.

## Asimov's Laws of Robotics
The foundation of thinking about machine ethics was established by science fiction writer Isaac Asimov in 1942, who proposed three laws of robotics that remain highly relevant to AI development today:

* A robot may not injure a human being, or through inaction allow a human being to come to harm.
* A robot must obey orders given by humans, except where such orders would conflict with the first law.
* A robot must protect its own existence, as long as such protection does not conflict with the first or second law

Asimov later added a fourth overarching law — that a robot may not harm humanity, or through inaction allow humanity to come to harm. These laws established the principle that machines and AI systems should always prioritise human safety and wellbeing, a principle that underpins modern AI ethics frameworks.

## European Parliament Civil Law Rules

The EU set out civil law guidelines in 2017, which ultimately resulted in the landmark EU AI Act of 2023. The European Parliament established the following civil law rules regarding AI and robotics:

* Robot manufacturers are liable for any damage caused.
* Robot users are liable for damage caused through improper use
* Robot teachers are liable for damage caused during training
* Robot owners or lessees are liable for damage caused during operation
* Guidelines are available for sovereign parliaments to modify their existing laws accordingly
* Many robots are already legislated for under existing health, safety, and machine operation laws

## Ethical considerations in AI

Ethics must be embedded into every stage of the AI development process, from initial concept through to final deployment. Using design thinking tools that prioritise user needs and ethical considerations, developers can conduct scenario analysis to explore potential ethical dilemmas and design solutions that minimise harm while maximising benefits. User research helps developers understand the diverse needs and concerns of the people who will be affected by AI systems.

An important factor in AI development is algorithmic fairness. Developers must ensure that AI systems do not perpetuate or escalate existing biases. This can be achieved through careful data selection, bias mitigation techniques, and ongoing testing for fairness throughout the development process.

Open communication is essential, through regular ethics reviews and meetings where team members can discuss potential ethical risks and how to mitigate them. These discussions should be inclusive, allowing for diverse perspectives and encouraging collaboration across different departments. Ethical concerns should also be reportable to a dedicated ethics officer or hotline.

Building an ethical AI culture requires more than just policies and procedures — it requires fostering a mindset of ethical responsibility throughout the organisation, creating a workplace where ethical considerations are valued and prioritised in every decision. This includes ethics training and regular updates on new developments in AI ethics and best practices.

## Biases in Generative AI

Generative AI systems can show bias ranging from racial preference to gender based stereotyping. The AI pipeline consists of three stages:

* Input — data is gathered and prepared for AI use
* Model — the AI system is developed and trained using prepared data
* Output — the AI generates results based on its training

Generative AI focuses mostly on the output stage. There are four key ethical principles that must be applied:

1. Transparency — the system's decision making must be explainable

2. Fairness — outputs must not discriminate or show bias

3. Accountability — developers must be able to explain and justify outcomes

4. Privacy — data protection must be maintained throughout

Best practice to reduce bias includes using a 'dislike' feedback mechanism, giving more specific instructions, and regularly reviewing and adjusting outputs.

## Ethical considerations in this project

* Were there any data privacy, bias or fairness issues with the data?

1. Data Privacy - As this dataset contains personal information about football players which include their full names, date of birth, nationality, wages, height, weight etc. The data needs to be handled responsibiliy with care and only used for analytical purposes. I can confirm that this data has only been used for conducting analysis.

2. Bias and fairness - As this dataset contains nationality and physical attributes, no predictions or conclusions should be influenced in a discriminatory way.

* How did you overcome any legal or societal issues?

## Dashboard Design
* List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
* Later, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project you were confident you would use a given plot to display an insight but subsequently you used another plot type).
* How were data insights communicated to technical and non-technical audiences?
* Explain how the dashboard was designed to communicate complex data insights to different audiences. 

## Unfixed Bugs
* Please mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 

## Main Data Analysis Libraries
* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.


## Credits 

* In this section, you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 
* You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site



## Acknowledgements (optional)