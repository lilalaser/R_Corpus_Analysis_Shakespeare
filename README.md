# Corpus Analysis: Shakespeare

## Overview
This project analyzes the usage of familiar ("thou/thee") and formal ("you/ye") second-person pronouns across various plays by William Shakespeare.  
Using a dataset containing Shakespeare's plays, the analysis investigates two main questions:

1. Which plays include more instances of the familiar second-person pronoun ("thou/thee") relative to the formal pronoun ("you/ye(e)")?  
2. Which characters are most likely to use the familiar pronoun, and which favor the formal one?

## Dataset

The dataset includes all plays from Shakespeare’s three main categories:
- Comedies  
- Histories  
- Tragedies  

### Source
The data was scraped from https://shakespeare.mit.edu/ and processed into .csv format.

### Structure
Each row in the dataset contains the following information:
- Dataline: Unique identifier for each row  
- Play: Name of the play  
- PlayerLinenumber: Line number as spoken by the character  
- ActSceneLine: Play location, formatted as Act.Scene.Line (for example, 1.2.15)  
- Player: Character who speaks the line  
- PlayerLine: The actual text spoken  

## Analysis

### Tools
- Language: R  
- Packages: dplyr, languageR, slam, tm

### Structure of the Analysis
a. Comparative Analysis – Examining the relative frequency of familiar ("thou/thee") vs. formal ("you/ye(e)") pronouns across plays.  
b. Character-Level Analysis – Investigating which characters favor the familiar vs. the formal pronouns.

### Key Findings
- Plays with high familiar pronoun usage:  
  Henry IV, King John, Richard II, Romeo and Juliet, The Tempest, Timon of Athens, and Titus Andronicus.  
  These plays feature protagonists of high social rank, who often address equals or inferiors, explaining the preference for the familiar form.

- Top characters using familiar pronouns:  
  Predominantly regents or high-ranking figures, except Falstaff, whose informal speech aligns with his close relationship to the king.

- Top characters using formal pronouns:  
  Some regents appear here as well, often in public or hierarchical contexts (for example, addressing a group or a superior).  
  Characters like Hamlet and Helena use the formal pronoun when addressing those of higher status.

## Installation and Usage

1. Clone this repository: https://github.com/lilalaser/R--Corpus-Analysis-Shakespeare

2. Open the R script in RStudio or another R environment.

3. Load the data:

   - Run the script.
   - Use file.choose() to select the dataset .csv file when prompted.
   - The script will load and display basic summaries of the dataset.

## Contact
For questions or contributions, please contact me through github. Thank you.
