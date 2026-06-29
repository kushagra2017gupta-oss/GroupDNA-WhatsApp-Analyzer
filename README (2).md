
# GROUP DNA - WHATSAPP CHAT ANALYZER

## OVERVIEW :

GroupDNA is a Python-based WhatsApp chat analysis project that extracts insights from group conversations.

It analyzes message patterns, activity trends, heatmap, response behaviour, word usage and personality archetypes.

## FEATURES EXECUTED :

### 1. CHAT PARSER:

 Extracts date, time, sender and message
 Handles system messages
 Handles media messages
 Handles deleted messages

### 2. GROUP OVERALL ANALYSIS:

 Total participants
 Total messages
 Message contribution percentage

### 3. MOST ACTIVE DAY AND HOUR:

 Busiest day
 Busiest hour
 Daily message activity
 Monthly activity
 Hourly activity

 ## MESSAGE CONTENT ANALYSIS (EXTRA FEATURE):

Analyzes the content and writing behaviour of messages.

Includes:

 Total words written in the group
 Average words per message
 Average characters per message
 Media message count
 Deleted message count
 Longest message in the chat
 Participant who typed the most words
 Total words typed by each participant

This feature helps understand the communication style and contribution of each member.

### 4. ACTIVITY HEATMAP (NumPy):

 Total words
 Average words per message
 Average characters per message
 Longest message
 Most words typed by participant

### 5. TOP WORDS :

Extracting every word from every real message counts
 Finds most frequently used words
 Displays top words with frequency

### 6. RESPONSE SPEED AND SILENT STREAKS :

 Fastest responder
 Slowest responder
 Longest silent period

### 7. PERSONALITY ARCHETYPE DETECTION :

 Detects members based on chat behaviour:

 THE GROUP MOM
 THE NIGHT OWL
 THE STORYTELLER
 THE DRAMA QUEEN
 THE GHOST

### Bonus Archetype: THE CAMPUS SURVIVOR

Detection Rule:

Identifies members who frequently discuss Indian college life topics such as assignments, exams, projects, classes, attendance, professors and labs.

## Concepts Used :

 Python loops
 Dictionaries
 Lists
 Functions
 Conditional statements
 String processing
 Datetime parsing

## Tools Used :

 Python
 Google Colab

## Conclusion :

GroupDNA converts WhatsApp chat exports into meaningful insights about communication patterns, activity trends and member behaviour.
