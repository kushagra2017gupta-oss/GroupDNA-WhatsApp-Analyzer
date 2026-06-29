%%writefile README.md

# GroupDNA - WhatsApp Chat Analyzer

## Overview

GroupDNA is a Python-based WhatsApp chat analysis project that extracts insights from group conversations.

It analyzes message patterns, activity trends, response behaviour, word usage and personality archetypes.

## Features Implemented

### 1. Chat Parser
- Extracts date, time, sender and message
- Handles system messages
- Handles media messages
- Handles deleted messages

### 2. Group Overview
- Total participants
- Total messages
- Message contribution percentage

### 3. Date and Time Analysis
- Busiest day
- Busiest hour
- Daily message activity
- Monthly activity

### 4. Message Content Analysis (Extra Feature)
- Total words
- Average words per message
- Average characters per message
- Longest message
- Most words typed by participant

### 5. Favourite Words Analysis
- Finds most frequently used words
- Displays top words with frequency

### 6. Response Speed and Silent Streaks
- Fastest responder
- Slowest responder
- Longest silent period

### 7. Personality Archetype Detection

Detects members based on chat behaviour:

- THE GROUP MOM
- THE NIGHT OWL
- THE STORYTELLER
- THE DRAMA QUEEN
- THE GHOST

### Bonus Archetype: THE CAMPUS SURVIVOR 

Detection Rule:

Identifies members who frequently discuss Indian college life topics such as assignments, exams, projects, classes, attendance, professors and labs.

## Concepts Used

- Python loops
- Dictionaries
- Lists
- Functions
- Conditional statements
- String processing
- Datetime parsing

## Tools Used

- Python
- Google Colab

## Conclusion

GroupDNA converts WhatsApp chat exports into meaningful insights about communication patterns, activity trends and member behaviour.
