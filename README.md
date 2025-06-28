# 📊 Market Research Analysis – CodeX Energy Drink (India Launch)

## 🏢 About the Company
**CodeX** is a Germany-based beverage company known for its innovative and high-performance energy drinks. The brand is now expanding into international markets and recently entered the Indian market by launching its energy drink across 10 major cities.

## 📌 Project Objective
This repository contains data and analysis conducted as part of a market research study by the marketing team at CodeX. The study aims to understand consumer behavior, perception, and preferences around energy drinks in India, based on a survey conducted among **10,000 respondents** in 10 different Indian cities.

The insights will support strategic decisions around:
- Increasing **brand awareness**
- Expanding **market share**
- Guiding **product development**

---

## 📁 Dataset Overview

The data is organized into the following tables:

### 1. `dim_respondents`
Contains demographic and location-based details of survey participants.

| Column Name     | Description |
|----------------|-------------|
| Respondent_ID   | Unique identifier for each respondent |
| Name            | Name of the respondent |
| Age_Group       | Age group category: `15-18`, `19-30`, `31-45`, `46-65`, `65+` |
| Gender          | Gender identity: `Male`, `Female`, `Non-binary` |
| City_ID         | Foreign key referencing `dim_cities` |

---

### 2. `dim_cities`
Provides metadata about the cities where the survey was conducted.

| Column Name | Description |
|-------------|-------------|
| City_ID     | Unique identifier for each city |
| City        | Name of the city (`Delhi`, `Mumbai`, `Bangalore`, etc.) |
| Tier        | Tier classification of the city (e.g., Tier 1, Tier 2) |

---

### 3. `fact_survey_responses`
Captures all responses from participants across a wide range of survey questions.

| Column Name                  | Description |
|-----------------------------|-------------|
| Response_ID                 | Unique ID for each survey response |
| Respondent_ID               | Foreign key referencing `dim_respondents` |
| Consume_frequency           | How often the respondent consumes energy drinks |
| Consume_time                | When the respondent typically consumes energy drinks |
| Consume_reason              | Main reason for energy drink consumption |
| Heard_before                | Has the respondent heard of CodeX before? |
| Brand_perception            | Opinion on CodeX brand/logo/design |
| General_perception          | Overall perception of energy drinks |
| Tried_before                | Has the respondent tried CodeX before? |
| Taste_experience            | Rating of taste and experience (1 to 5) |
| Reasons_preventing_trying   | Reasons for not trying CodeX |
| Current_brands              | Other energy drink brands consumed |
| Reasons_for_choosing_brands| Why those brands are preferred |
| Improvements_desired        | Desired improvements in energy drinks |
| Ingredients_expected        | Expected ingredients in energy drinks |
| Health_concerns             | Any health concerns about energy drinks? |
| Interest_in_natural_or_organic | Interest in natural or organic variants |
| Marketing_channels          | Common platforms where respondents see energy drink ads |
| Packaging_preference        | Preferred packaging style |
| Limited_edition_packaging   | Interest in limited edition packaging |
| Price_range                 | Preferred price range for energy drinks |
| Purchase_location           | Usual purchase locations |
| Typical_consumption_situations | Situational context of consumption |

---

## 👨‍💼 About the Analyst
**Peter Pandey** – Marketing Data Analyst at CodeX. Tasked with translating raw survey data into actionable insights for the marketing and product development teams.

---

## 📈 Analysis Areas
- Brand awareness and trial rates by city, age, and gender
- Consumption patterns (frequency, time, and reasons)
- Brand perception vs. competitors
- Barriers to trial and brand adoption
- Preferences around ingredients, packaging, and pricing
- Health-related concerns and organic preferences
- Marketing channel effectiveness

---

## 📊 Tools Used
- Python / Pandas / NumPy
- Data visualization: Matplotlib / Seaborn / Plotly / MS PowerBI
- SQL (for preprocessing or querying data)

---

## 🚀 Goals
This research is part of a broader effort to:
- Understand Indian consumer behavior around energy drinks
- Refine CodeX’s product positioning in India
- Make informed decisions on future product innovation, pricing, and promotions

---

## 📬 Feedback & Contribution
Feel free to fork the repository, raise issues, or contribute ideas to enhance the insights!

---
