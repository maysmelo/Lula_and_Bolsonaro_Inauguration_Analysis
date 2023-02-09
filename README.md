# Lula and Bolsonaro Inauguration Analysis
This is my first Python project, which has the objective of using Whisper AI to transcribe the inauguration speech of Lula and Bolsonaro so I can run some analysis based on the speech.

## Context:
Lula's third term started in January 1st 2023, his speech was very emotional, talking about all the challenges Brazil has faced in the last 4 years and his objectives for this new term. I wanted to run a quick analysis on the last president's inauguration speech and the current and check what kind of insights will come out of it. 

## Idea:
- Get the top 15 most used words of each speech and explore the data.
- Run an analysis on the entire speech.

## Personal Objectives:
I don't have one big objective with this, but several:
- Build a good first project;
- Expand my knowledge in graphs in Python;

###  ✅ Process Top 15 Words (9/9 - 100%):
- [x] Find the inauguration speech videos in youtube without comments;
- [x] Download the audios of the videos (using pytube);
- [x] Transcribe audios using Whisper AI;
- [x] Add outputs in .txt files;
- [x] Split each speech into words;
- [x] Clean the data (remove unnecessary characters, stop_words and make it all in lowercase);
- [x] Find the most frequent words and build a dataframe;
- [x] Classify the most common words from each president;
- [x] Create graphs displaying insights about the speeches.


### Process Entire Speech (0/3 - 0%):
- [ ] Create DataFrame of entire speech (Name, Count, Lenght and Classification);
- [ ] Find a way to classify words in bulk;
- [ ] Create graphs about the overall speech of each president.
