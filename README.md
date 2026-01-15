# Tinder User Engagement Analysis

Data analysis project examining Tinder user engagement patterns to identify the most effective demographic for a targeted marketing campaign.

---

## Table of Contents
- [Overview](#overview)
- [Objective](#objective)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Key Findings](#key-findings)
- [Marketing Recommendations](#marketing-recommendations)
- [Repository Structure](#repository-structure)
- [Technologies Used](#technologies-used)
- [Authors](#authors)

---

## Overview
This project analyzes user engagement data from Tinder to determine which demographic group presents the strongest opportunity for increased engagement and retention. Engagement is measured using app opens, total swipes, and conversation length.

---

## Objective
Identify a high-impact target demographic and propose data-driven marketing strategies to improve conversation depth and reduce dating-app burnout.

---

## Dataset
- Source: Public Tinder dataset from Kaggle
- Size: ~1,200 users
- Features:
  - Age
  - Gender and match preferences
  - App opens
  - Total swipes
  - Conversation length
  - Education level
  - Instagram and Spotify linkage

Sexual orientation was engineered using gender and match-preference data.

---

## Methodology
- Data cleaning and preprocessing:
  - Removed missing values
  - Standardized labels
  - Created age bins
  - Engineered sexual orientation variable
- Exploratory data analysis using Python
- Visual trend analysis across:
  - Age groups
  - Sexual orientation
  - Education level
  - Social media linkage

---

## Key Findings
- Users aged 18–24 generate the highest app opens and swipes but have the shortest conversations
- Users aged 25–34 show the longest conversations with moderate activity
- Gay men demonstrate the highest app engagement but the shortest conversation lengths
- Spotify-linked profiles have significantly longer conversations than non-linked profiles

---

## Marketing Recommendations
- Target gay men aged 18–35
- Promote conversation-building features:
  - Icebreakers and prompts
  - Shared interest tags
- Encourage Spotify profile linkage
- Use casual, inclusive, and non-academic messaging
- Position Tinder as a conversation-focused platform

---

## Technologies Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Google Colab

---

## Authors
- Fong Lieu
- Jessica Thai
- Bhavna Sreekumar

