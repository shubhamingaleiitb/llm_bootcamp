"NutriGPT: Getting the Scoop on Nutrition Insights for India 🇮🇳

![image](https://github.com/AnimeshN/nutriGPT-database-python/assets/17973453/b5a183e0-7b0c-4aff-a0b8-863d65ed931c)

## About NutriGPT
NutriGPT is like a smart app powered by AI that links up to a real-time **SQLite database** and cooks up data embeddings. It's into using Pathway’s [LLM App features](https://github.com/pathwaycom/llm-app) to whip up a real-time Large Language Model (LLM)-enabled data pipeline in Python. It's like mixing and matching data from different databases.

## How to Use

Get all the deets on nutrition in India. You can ask questions about different stuff like child health, maternal care, family planning, healthcare access, sanitation, hygiene, childhood diseases, and more. It's a smorgasbord of health and nutrition indicators!

### Health and Nutrition indicator menu

1. **Child Health and Nutrition**
   - Full immunization in 12-23 month olds
   - Received Vitamin A supplementation in 6-59 month olds
   - Overweight in 15-49 year old women

2. **Women's Health and Maternal Care**
   - High Blood Sugar in 15-49 year old women
   - High Blood Sugar in pregnant women
   - Large Hip Circumference in 15-49 year old women

3. **Family Planning and Reproductive Health**
   - Women 15-49 years with an unmet need for spacing method
   - Adolescents 15-19 years with an unmet need for spacing method
   - Adolescents 15-19 years with an unmet need for family planning

4. **Healthcare Access and Utilization**
   - Men who received counseling on the importance of proper nutrition for the mother during pregnancy
   - Women who had any contact with a health worker in the past three months
   - Women 15-49 years of age with hypertension

5. **Sanitation and Hygiene**
   - Open defecation
   - Availability of water/soap for hand washing
   - Safe disposal of child faeces

6. **Childhood Diseases and Healthcare Services**
   - Diarrhoea in children under five years of age
   - Acute Respiratory Infection (ARI)/Pneumonia in past two weeks in under-five year olds
   - Neonatal Mortality Rate

## End User
The main users of NutriGPT are researchers, policymakers, and healthcare pros looking to dive into the nutrition status of India. And hey, students, journalists, and anyone curious about nutrition in India can also check it out.

## Industry Impact
NutriGPT could really shake things up in the healthcare and nutrition biz in India. It's a quick and easy way to access live nutrition data and insights. It helps the big shots make smart decisions and create solid policies. Plus, researchers can dig into trends and patterns for some real health discoveries.

## Business Value
NutriGPT is a gem—it bridges the gap between data sources and useful insights. You can cash in on this by offering cool features or data analysis services to groups interested in a deep dive into nutrition. Make money with subscription models or consulting gigs for data-driven decision-making.

## Using the LLM App
- NutriGPT works its magic with the LLM (Large Language Model) App features from Pathway to make a real-time data pipeline.
- This App is a language whiz, letting users ask questions in plain language and get the scoop on nutrition insights.
- NutriGPT uses the LLM's powers to crunch text data and extract meaning from various sources, including its link to an SQL database.
- Specifically, it uses NFHS5 (National Family Health Survey 5) data, so you're getting the freshest and most reliable info on nutrition in India.
- This direct database link makes NutriGPT super effective—it can grab and analyze data from different apps and databases, giving you a full picture of nutrition trends. This makes things way more efficient and effective.

## Code sample
There's some code that gets things connected to the database and pumps out a JSONL file when there are updates. It's all about keeping things real-time and up to date.

Then there's a snip of code that processes the JSONL file using the Pathway API. It's all about embedding data and getting responses based on queries.

## How to run the project
You can clone the repository, set some environment variables, install dependencies, and run the app. If you're a Windows user, think about using Windows Subsystem for Linux (WSL) or Dockerize the app to get it running.

### Prerequisites
1. Make sure you've got [Python](https://www.python.org/downloads/) 3.10 or higher.
2. Grab [Pip](https://pip.pypa.io/en/stable/installation/) to handle project packages.
3. Get an [OpenAI](https://openai.com/) account and snag an API Key for using their services.

You can find detailed steps in the repository's README on how to set things up and run the app.

### Testing the app
When you upload the file and ask questions on the UI, you'll get responses based on the data. For example:

```
Tell me about high Blood pressure situation in India?
```

And you'll get a cool response with data and insights about high blood sugar in India.

So, yeah, that's the lowdown on NutriGPT. It's a cool app that dishes out nutrition insights for India, keeping you in the loop about all things health-related!"
