# comm4190_F25_TikTok_Task

# Overview

In this project we analyzed 1000 comments on a TikTok into a datset around the controversy of the Starbucks Bear Cup. While some costumers loved the design and wanted the cup in their hands, the other half believed it was unreasonably priced and added to wasteful consumerism. Coding the comments into concept 1 and 2, concept 1 expressing negative associations about the cup and concept 2 expressing positive emotions, we were able to train an LLM algorithm using specified prompting to apply our classification method of 100 comments to the rest of the comments. In doing so, we realized the more detail we provided the LLM in prompting, the more accurate or similar it coded comments like we manually did - so the more accurate our algorithm became.

After sorting the data, we were able to analyze findings using graphs and visualizations to explore patterns among the data. In doing so, we answered the question - "Which combinations of sentiments were most common and what type of interactions (likes, replies) were these sentiments associated with?" We found that neutral comments were both the most prevalent and received a significantly more number of likes than negative and positive comments, but the overall number of replies no matter the commenter's attitude didn’t seem to vary by much. Data analysis using LLMs is a powerful tool and this project provides a glimpse into its application.

---

# Project Structure

This repository contains all files for our TikTok comment analysis project. Below is an overview of each file and what it contributes to the assignment.

---

## 📂 `graphs/`

Contains all image files of the graphs generated from analyzing the TikTok comment dataset.

---

## 📄 `final_coded_data.csv`

Our final dataset of all scraped TikTok comments, including:

* Comment text
* Metadata (likes, replies)
* AI-coded concept labels
* Any processed fields used in the analysis

---

## 📘 `llm.ipynb`

**Answers Questions 4 and 5**

Includes:

* All LLM prompts used during coding
* Iterations of prompt refinement
* Inter-rater reliability scores (Cohen’s Kappa)
* Reflection on how prompting strategies were improved to increase reliability

---

## 📙 `overview.ipynb`

**Answers Questions 1, 2, and 3**

Covers:

* The TikTok video URL
* A short description of the video
* Our research question
* Definitions of our two coding concepts

---

## 📗 `results.ipynb`

**Answers Questions 6 and 7**

Contains:

* All charts and graphs used to answer the research question
* Interpretation of the findings
* A written reflection summarizing results and connecting them back to the research question

---

Let me know if you want this in a table format or with a more formal/academic tone!
