# WhatsApp Chat Analyzer

A comprehensive, end-to-end web application built with Python and Streamlit to analyze and visualize exported WhatsApp chat data.

## Features

- **Interactive Dashboard:** Upload your WhatsApp chat export (`.txt`) to instantly generate visual insights.
- **Top Statistics:** View total messages, words, media shared, and links shared.
- **Activity Maps:** Identify the most active days of the week, busiest months, and visualize engagement through a weekly heatmap.
- **User Insights:** Discover the most active members in group chats.
- **Text Analysis:** Extract conversational trends utilizing word clouds and frequently used words.
- **Emoji Analysis:** Analyze sentiment and mood based on the most commonly used emojis in the conversation.

## Tech Stack

- **Frontend:** Streamlit
- **Data Processing:** Pandas, Regex
- **Visualization:** Matplotlib, Seaborn, WordCloud
- **NLP & Utils:** urlextract, emoji

## How to Use

1. Export a WhatsApp chat (Without Media) from your phone.
2. Clone this repository.
3. Install the dependencies using `pip install -r requirements.txt`.
4. Run the application locally with `streamlit run app.py`.
5. Upload the exported `.txt` file into the sidebar of the app to view your analysis!
