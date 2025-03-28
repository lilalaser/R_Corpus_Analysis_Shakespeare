Corpus Analysis Shakespeare

1. Overview
This project analyses the usage of familiar ("thou/thee") and formal ("you/ye") second-person pronouns across various plays by William Shakespeare. Using a dataset that includes Shakespeare's plays, the analysis investigates two main questions: 
- a. Which plays included more instances of the familiar 2p pronoun ("thou/thee") relative to the formal 2p pronoun "you/ye(e)"?
- b. Which characters were most likely to use the familiar 2p pronoun, and which were most likely to use the formal 2p pronoun?

2. Dataset
The dataset contains all plays from the three main categories of Shakespeare's works: Comedies, Histories, and Tragedies.

2.1 Source 
The data was scraped from https://shakespeare.mit.edu/ and processed into .csv format. 

2.2 Dataset Structure

The dataset contains the following columns:
- Dataline: Unique identifier  for each row
- Play: The name of the play from which the line is taken
- PlayerLinenumber: The line number as spoken by the character 
- ActSceneLine: The location in the play, usually formatted like "Act.Scene.Line" (e.g., "1.2.15" for Act 1, Scene 2, Line 15)
- Player: The character who says the line
- PlayerLine: The actual text  spoken by the character

3. Analysis

3.1 Tools used in the Analysis
- R
- Packages: dplyr, languageR, slam, tm


3.2 Structure of the Analysis

- a. Comparative Analysis of Familiar ('Thou/Thee') and Formal ('You/Ye(e)') Pronoun Usage Across Plays

- b. Analysis of the Use of Familiar 2p Pronoun and Formal 2p Pronoun Across Characters 


3.3 Key Findings

a. The plays that feature a higher frequency of the familiar 2P pronoun compared to the formal 2P pronoun include Henry IV, King John, Richard II, Romeo and Juliet, The Tempest, Timon of Athens, and Titus Andronicus. As most of the protagonists in these plays are at the top of society, there is little reason for them to address others in the formal manner. The majority of the people they interact with are either socially equal or inferior to them.


b. Among the top 10 characters who predominantly use the informal 2P pronoun, most are regents or members of high society, with the notable exception of Falstaff. However, since Falstaff is a close companion to the king, his frequent use of the informal pronoun aligns with their personal relationship.

Among the top 10 of the characters who more frequently use the formal 2P pronoun, some regents appear. Their use of the formal pronoun may be explained by speaking publicly or addressing a group. Additionally, the formal pronoun is often used to address those of higher social status, which may explain Hamlet's and Helena's use of "you/ye."


4. Installation/Usage

- Clone this repository
- Open the R script in RStudio or another R environment.
- Load the Data:
        ◦ Run the script and use file.choose() to select the dataset .csv file when prompted.
        ◦ The script will load and display basic summaries of the dataset.

5. Contact


For questions or contributions, please contact me through github. Thank you and enjoy ;)
