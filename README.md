INTRODUCTION

In response to the need for improved accessibility and analysis of opioid-related data, traditionally managed in cumbersome Excel files, this project implemented a multi-faceted solution. Initially, a Tableau dashboard was developed to provide visual data representation, facilitating easier comprehension of trends and patterns.

Building on this foundation, and drawing from insights gained in courses on Large Language Models (LLMs) and deep learning, the project advanced to develop a chatbot using OpenAI's Langchain framework and a pre-trained LLM. This chatbot allows users to interact with the data through natural language queries, significantly enhancing user engagement and data exploration.

The chatbot is integrated with a PostgreSQL database and boasts advanced capabilities such as dynamic few-shot prompting, dynamic column selection, and chat message history. It is accessible via a user interface built with Streamlit and hosted using ngrok, ensuring ease of access and flexibility.

The solution demonstrates strong proficiency in handling straightforward SQL queries and delivers satisfactory performance with more complex queries, ultimately enhancing the efficiency and effectiveness of data analysis efforts. This tool plays a crucial role in supporting the state's initiatives to combat the opioid crisis by providing a more intuitive and responsive approach to data management and decision-making.

The primary objective of this project was to develop a sophisticated tool to improve the accessibility and analysis of opioid-related data. The existing challenge lay in the reliance on extensive yet inefficiently utilized Excel datasets, which hindered effective decision-making in efforts to combat the opioid epidemic.

To address this, the project aimed to leverage advanced data analytics and machine learning techniques to create a user-friendly chatbot. This chatbot allows users to explore opioid data using intuitive natural language queries, significantly enhancing the efficiency of data-driven decision-making processes. The ultimate goal was to provide a more accessible and efficient means of understanding and utilizing opioid data to support informed decision-making and strategy development in public health initiatives.

DATASET

This dataset was synthetically generated using Pandas and NumPy, inspired by publicly available data sources from official Department of Health and Human Services (DHS) websites. It integrates demographic, social indicators, and recovery scores from the Recovery Ecosystem Index website to provide a comprehensive view of opioid-related statistics across all 67 counties in Florida, segmented by regions.

The dataset includes key metrics such as:

- Opioid fatalities and opioid fatality rates per 100,000 people
- Emergency department cases due to opioid overdoses
- Demographic and social indicators including social vulnerability scores, uninsured adult rates, and youth disconnection rates
- Detailed census data, state population percentages, and rankings for both state population and opioid fatalities
  
This rich dataset is designed for in-depth regional analysis of the opioid crisis, focusing on factors such as social vulnerability and healthcare access. The data aims to support targeted and effective public health interventions by providing actionable insights into the patterns and impacts of opioid use across Florida's diverse communities.


