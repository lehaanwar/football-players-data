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

* I chose this dataset as it is ideal for data analysis, predictive modeling, and machine learning projects.

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

* US5 - As a Fantasy football player and a punter, I want to access detailed player profiles — including full name, position(s) and skill ratings — so that I can make infored decisions when selecting players and placing any bets.

* US6 - As a social media content creator, I want to access detailed player profiles — including full name, age, preferred foot, position(s), national team, and skill ratings — so that I can produce accurate and engaging content that analyses and showcases players to my audience.

* US7 - As a national team manager, I want to access detailed player profiles — including skill ratings, international reputation, national rating, position(s), age, and nationality — so that I can make informed selection decisions when choosing players for my national squad.

* US8 - As an advertising company, I want to access detailed player profiles — including full name, date of birth, age, height, weight, position(s), nationality, overall rating, and international reputation — so that I can make informed decisions when selecting the most suitable player for my marketing campaigns.

* US9 - As a video game creator, I want to access comprehensive player profiles — including full name, physical attributes, skill ratings, position(s), nationality, and overall rating — so that I can accurately represent each player as a realistic in-game avatar.

* US10 - As a football fan, I want to access detailed player profiles — including full name, age, preferred foot, position(s), national team, and skill ratings — so that I can engage in informed and meaningful discussions about players with my friends and peers.

## Business Requirements

A Data analyst has been approached by a Football data company that has provided a comprehensive dataset that contains information on football players. This includes the following; Players characteristics/attributes such as full name, age, date of birth, height, weight etc. Player technical skills such as passing, finishing, volleys, dribbling etc, it also includes players financial information such as players wages, values and release clauses and information about their national team such as nationality, national team, national rating, national team position etc.

The company consists of a range of Stakeholders: Football scouts, football agents (intermediaries), club technical staff and coaches, football pundits & journalists, fantasy football players and punters, social media and content creators, national team managers, advertising companies, video games creators, football fans they all have their own needs and when analysing and using the data.

BR1: Player Valuation
•Identify the relationships between player attributes such as age, skill ratings, international reputation and their wages, value and release clauses.
•Show relationships with data visualisations such as scatter plots and heat maps.

BR2: Players performances
•Analyse and compare player skill ratings, such as finishing, passing, crossing.
•Enable stakeholders to filter and identify players by position and skillset.
•Provide visualisations that highlight top 10 performing players

BR3: Player Biographical Profiling
•Access to biographical and physical data such as age, nationality, height and weight

BR4: Predict player model
•Develop a machine learning model to predict a player's wage or release clause based on their attributes
•Achieve a minimum acceptable accuracy on unseen data
•Enable stakeholders such as agents and clubs to estimate a player's market value before negotiations

 BR5: Player profiles internationally
•Analyse the relationship between a player's international reputation, overall rating, and their public profile
•Support stakeholders such as advertising companies, journalists, and content creators in identifying high profile players
•Provide rankings and visualisations of players by overall rating and international reputation

BR6: Interactive Dashboard & Data Exploration
•Create a user friendly dashboard for non-technical stakeholders to explore player data
•Enable filtering and segmentation by multiple criteria including position, nationality, age, and skill ratings
•Provide real time visualisations of player distributions and comparisons

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

## The rationale to map the business requirements to the Data Visualisations

A Data analyst has been approached by a Football data company that has provided a comprehensive dataset that contains information on football players. This includes the following; Players characteristics/attributes such as full name, age, date of birth, height, weight etc. Player technical skills such as passing, finishing, volleys, dribbling etc, it also includes players financial information such as players wages, values and release clauses and information about their national team such as nationality, national team, national rating, national team position etc.

The company consists of a range of Stakeholders: Football scouts, football agents (intermediaries), club technical staff and coaches, football pundits & journalists, fantasy football players and punters, social media and content creators, national team managers, advertising companies, video games creators, football fans they all have their own needs and when analysing and using the data.

BR1: Player Valuation
•Identify the relationships between player attributes such as age, skill ratings, international reputation and their wages, value and release clauses.
•Show relationships with data visualisations such as scatter plots and heat maps.

•Succes criteria: Using some of the variables above overall rating, wage euro, value euro and release clause euro, relationships were identified using heatmaps and scatter plots. The correlation matrix was utilised to calculate the Pearson correlation coefficient between the variables in the dataset.

* overall_rating vs wage_euro 0.74 Strong — better players earn more

* overall_rating vs value_euro0.83 Very strong — better players are worth more

* overall_rating vs release_clause_euro 0.82 Very strong — better players have higher release clauses 

* value_euro vs release_clause_euro 0.99 Near perfect — clubs set release clauses based on value 

* wage_euro vs value_euro 0.86 Very strong — higher earners are valued more

BR2: Players performances
•Analyse and compare player skill ratings, such as finishing, passing, crossing.
•Enable stakeholders to filter and identify players by position and skillset.
•Provide visualisations that highlight top 10 performing players

•Success criteria: Grouping player attributes, player skills ratings were compared. The top performing players were shown on the dashboard in PowerBI.

BR3: Player Biographical Profiling
•Access to biographical and physical data such as age, nationality, height and weight
•Success criteria: Height vs Weight by position group using a scatterplot with a trend line, top 10 players by overall rating with name and nationality using a bar chart, age distribution by number of players using a histogram.

BR4: Predict player model
•Develop a machine learning model to predict a player's wage or release clause based on their attributes
•Achieve a minimum acceptable accuracy on unseen data
•Enable stakeholders such as agents and clubs to estimate a player's market value before negotiations

•Success Criteria: created simple linear transgression, random tree transgression.
Grouped Random Forest Model Mean Squared Error: 7373506971534.81
Grouped Random Forest Model R-squared: 0.9702

BR5: Player profiles internationally
•Analyse the relationship between a player's international reputation, overall rating, and their public profile
•Support stakeholders such as advertising companies, journalists, and content creators in identifying high profile players
•Provide rankings and visualisations of players by overall rating and international reputation

•Success Criteria: comparing the overall rating distribution by international reputation using a histogram and a violin plot.

BR6: Interactive Dashboard & Data Exploration
•Create a user friendly dashboard for non-technical stakeholders to explore player data
•Enable filtering and segmentation by multiple criteria including position, nationality, age, and skill ratings
•Provide real time visualisations of player distributions and comparisons

•Success Criteria: Dashboard created which is responsive to all filter combinations, and usable by stakeholders ranging from football fans to professional scouts.

## Analysis techniques used

Structured approach: I structured the data analysis technique by following the module handbook and going through each criteria to add to my project, this included reviewing each section. By adhering to the handbook's guidance, I was able to incorporate all necessary elements and maintain consistency throughout the analysis process.

Data limitations: The data did not have any limitations, it was great for data analysis.

Generative AI: I used gen AI throughtout the project; for the planning and ideation at the start of the project, throught to the data cleaning and visualisation. I used co-pilot to helpw with sentence structure and fixing any bugs. I also used chatgpt to fix codes that were difficult to fix via co-pilot.

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

Images were not incorporated into my dashboard design due to the ethical concerns and legal restrictions associated with using images without proper authorisation. Should images be included, it would be essential to address the relevant ethical and legal considerations outlined below.

* Ethical and Legal Considerations for Image Use

* Ethical Considerations

When utilising images, it is essential to demonstrate respect for creators by acknowledging their contributions and valuing their work. Creators possess moral rights, which include receiving proper credit for their creations and having the opportunity to object if their work is used in a manner that could harm their reputation. Furthermore, maintaining professional integrity means avoiding the use of random or uncredited images, as this can undermine credibility and reflect poorly on one's standards.

* Legal Risks

There are significant legal risks associated with the use of images. Most images are protected by automatic copyright from the moment they are created, regardless of whether a copyright symbol is present. Using such images without explicit permission or a valid licence constitutes copyright infringement and may result in legal consequences.

* *Exceptions

Some exceptions to copyright restrictions exist, such as fair use and Creative Commons licences. These provisions allow limited usage of certain images, provided the conditions of the licence or fair use criteria are strictly adhered to.

## Legal frameworks that applies to personal sports data 

In professional football, the General Data Protection Regulation (GDPR) and the UK Data Protection Act 2018 (DPA 2018) provide the primary legal framework for managing player data. This framework treats performance statistics and physiological metrics as personal data, placing significant responsibilities on clubs and third-party data firms to protect player privacy. 

1.Classification of Player Data

Under GDPR, data is categorised based on its sensitivity, which dictates the level of protection required:
Personal Data: General statistics such as height, weight, goals scored, and appearances are considered personal data because they identify a specific natural person.

Special Category Data: Highly sensitive information—including biometric data (e.g., heart rate, fatigue levels, running mechanics) and health data (e.g., injury records, medical diagnoses)—falls under "special category" data. Processing this requires much stricter legal conditions.

2.Lawful Bases for Processing

Clubs and data companies must have a "lawful basis" to collect and use player data. The most relevant grounds include: 

Consent: For sensitive biometric and health data, clubs typically must obtain explicit consent. However, regulators caution that consent in an employer-employee relationship (club vs. player) may not always be "freely given" due to the power imbalance.
Legitimate Interests: Organisations often rely on this for non-sensitive performance data, arguing they have a valid business reason (e.g., scouting or match analysis). This requires a Legitimate Interest Assessment (LIA) to ensure it doesn't override the player’s rights.

Contractual Necessity: Data collection may be deemed necessary to fulfill a player’s employment contract, such as monitoring fitness for match selection.

3.Key Player Rights

Footballers have specific rights regarding their personal and performance data:

Right of Access (SAR): Players can request a copy of all data held on them by a club or third party.

Right to Rectification: Players can demand corrections to inaccurate data, which is critical as errors in stats could impact their transfer value or career prospects.

Right to Erasure ("Right to be Forgotten"): Players can request the deletion of their data when it is no longer necessary, such as after retirement or a transfer.

Right to Withdraw Consent: Players can withdraw their consent for data processing at any time without it jeopardising their contract.

4.Legal Challenges: Project Red Card

A significant movement known as Project Red Card involves hundreds of professional players challenging data firms over the unlicensed use of their performance statistics.

Core Argument: Players argue that firms are profiting from their personal data (stats like goals and passing accuracy) without consent or compensation, which they believe contravenes GDPR.

Goal: The group seeks compensation for past use and the establishment of a licensing model where players are treated as stakeholders in the data ecosystem. 

5.Accountability and Transparency

Clubs act as data controllers and must maintain transparency: 

Privacy Notices: Organisations must clearly inform players about what data is collected, why it is used, and who it is shared with (e.g., betting companies or video game developers).

Data Protection Impact Assessments (DPIAs): These are mandatory before implementing high-risk processing, such as new biometric tracking systems.

Data Security: Organisations must use encryption and anonymisation to protect sensitive player information from breaches.

## Ethical considerations of using individual player performance data or any biases in the dataset

* Performance tracking can easily become intrusive.

Power imbalance: Players may feel pressured to share data (e.g., GPS, sleep) to keep their place, raising doubts about true consent.

Mental health: Constant monitoring can create a “never off-duty” feeling, increasing stress and risk of burnout.

* Interpretation of data can be based

Style bias: Metrics may favour certain playing styles while undervaluing less measurable skills.

Age bias: Algorithms may misjudge players as declining based on physical data alone, ignoring experience.

Confirmation bias: Data can be selectively used to support pre-existing opinions.

* Who benefits from player data is a major ethical issue.

Monetisation: Third parties may profit from player data without compensating players.

Career impact: Inaccurate or misleading stats can harm a player’s reputation, value, and earnings.

## Dashboard Design

* The dashboard was thoughtfully designed with accessibility in mind, particularly for non-technical users. To achieve this, a navigation bar was added to each page, with buttons that included hover and select effects. The background colour was carefully chosen, and emojis were incorporated to make navigation more engaging and intuitive. These design choices help users easily access different pages and interact with the dashboard, ensuring it is user-friendly and approachable for those unfamiliar with technical interfaces.

🏠 Homepage - The homepage serves as the initial landing page and features a bar chart displaying the top players by overall rating. Additionally, a pie chart illustrates players based on their international reputation, both of which offer visually appealing insights suitable for non-technical users. An age slicer allows users to filter the data by specific age ranges, providing a straightforward way to narrow down information. Cards summarising statistics, such as the average attack, were created by utilising DAX measures like Avg Attack = ROUND(AVERAGE('cleaned_data'[attack_attributes]), 1), offering concise and meaningful metrics.

📊 Player Performance - The Player Performance section includes a slicer for overall ratings, employing a range slider that enables users to filter between two rating values. Clustered column charts highlight the top five players, with the Top N filter set to Top 5. A table is also provided to display the top players by overall rating. This section is specifically tailored for non-technical users, presenting performance data in an accessible and clear format.

💡 Data Insights - In the Data Insights section, a hypotheses results table is provided, along with text boxes summarising findings and a card highlighting correlation findings. This area is aimed at technical users, as it delves into hypothesis testing and provides more detailed analytical information.

🤖 ML Prediction Models - The ML Prediction Models section features model performance cards created using DAX measures, a bar chart showing feature importance, and text boxes detailing key findings. This section caters to technical users, offering a comprehensive overview of machine learning prediction results.

* Reflections

A mind map was used to plan the dashboard design, although some aspects were omitted or revised as the data findings emerged. Ethical considerations influenced the decision not to use images of footballers. To enhance familiarity with PowerBI, resources such as YouTube videos and articles on DAX measures were consulted. Although there was an intention to use a theme from the Microsoft Fabric community, the extensive range of options and limited time meant this could not be pursued.

## Unfixed Bugs

* All bugs in this project have been resolved; there are no outstanding issues remaining.

* I recognized gaps in my knowledge with machine learning algorithms and feature engineering. These are complicated and I had to go back to the LMS and refresh my knowledge. I watched youtube videos and visited websites such as GeeksforGeeks and datacamp to help me gain a better understanding of these topics.

* I used auto completion in VS code, chatgpt, co-pilot and gemini to help with the code.

* I also used co-pilot to help me structure sentences in a formal way when writing Markdown and README documentation.

## Development Roadmap

1. Project Planning & Getting Started

 The initial planning phase of this project was extensive, utilising multiple tools simultaneously including a Kanban board, Trello, mind maps, and handwritten notes. While thorough planning is beneficial, the volume of planning tools used slowed the start of the practical work. In future projects, a more streamlined approach using one or two planning tools would allow for a faster transition into implementation. 

2. Time Management 

Due to the slow start caused by the extensive planning phase, time constraints became a recurring challenge throughout the project. This impacted the final dashboard design, which could have been more dynamic and visually polished given more time. Future projects would benefit from setting stricter time boundaries

3. Feature Engineering & Pipeline Issues

During the feature engineering phase, several technical challenges were encountered: - The pipeline was initially run in separate Jupyter notebook cells, causing the grouped feature columns to be lost when the pipeline transformed the data. This was resolved by consolidating all dependent steps into a single cell to ensure correct execution order. - A duplicate "vision" attribute was discovered in the passing_attributes group after the model had been trained, resulting in vision being double weighted. While the impact on the final R² score was minimal, this highlighted the importance of thoroughly reviewing feature engineering steps before model training.

4. File Path & Data Management

Managing multiple versions of the dataset across different folders caused confusion during the cleaning and saving process. The cleaned dataset was initially saved to the wrong directory, resulting in the original raw data being loaded instead of the cleaned version. This was resolved by ensuring consistent file paths were used throughout the notebook and that the correct dataset was always verified after loading using print(df.columns.tolist()).

5. Machine Learning Model Performance

The initial Linear Regression models produced R² scores below the target of 0.85, with the simple baseline model achieving only 0.6797. Multiple iterations were required, progressing through extended linear regression and grouped feature models before switching to a Random Forest Regressor, which achieved the target with an R² score of 0.9702. This highlighted the importance of selecting the appropriate algorithm for non-linear data.

## Reflections

* Consolidate dependent code into single notebook cells to avoid execution order issues.

* Verify file paths and loaded data after every save and load operation.

* Always test multiple ML algorithms rather than relying on a single approach 

* Streamline planning tools to avoid slow project starts 

* Review feature engineering steps thoroughly before model training to catch errors such as duplicate attributes early

## Main Data Analysis Libraries

* Numpy and Pandas – used for data processing

* Matplotlib and Seaborn – used for data visualisation.

* sklearn.model_selection import train_test_split, sklearn.linear_model import LinearRegression, sklearn.metrics import mean_squared_error, r2_score

* Statistical tests – used for statistical analysis

* PowerBI – used for Dashboard.


## Credits

### Content

* Repository and README templates from the following links - https://github.com/Code-Institute-Org/data-analytics-template
https://github.com/Code-Institute-Solutions/da-README-template

* Setting up project in Github by following these slides - https://docs.google.com/presentation/d/1GvPq9uAxaO9lT5a-60Wgk0u0ol4tygyE/edit?slide=id.g2edbf99dd81_0_61#slide=id.g2edbf99dd81_0_61

* Navigation bar help in PowerBI https://youtu.be/VjtdazTz3ho?si=b0knnXCxnMuNI7tB

* Machine learning algorithm help https://www.geeksforgeeks.org/machine-learning/ml-linear-regression/
https://www.geeksforgeeks.org/machine-learning/random-forest-algorithm-in-machine-learning/

* Refreshing powerBI tricks and tips - https://www.datacamp.com/tutorial/tutorial-power-bi-for-beginners

* I went over DAX measures in PowerBI - https://media.datacamp.com/legacy/image/upload/v1653826988/Marketing/Blog/Formulas_in_DAX_Cheat_Sheet.pdf

* I took inspirations for designing the dashboard - https://community.fabric.microsoft.com/t5/Themes-Gallery/EUROCUP-historical-analysis/m-p/3974299

* Refreshed my knowledge by going over previous modules in the LMS - https://lms.codeinstitute.net/learner_module/show/118491?from=%2Flearner_module%2Fshow%2F118491%3Flesson_id%3D506362%26section_id%3D1920576&lesson_id=506363

### Media

* No external media used.

## Acknowledgements

* I would like to thank my course coordinators, Vasi and Mark for providing help in preparing the project and support throughout.