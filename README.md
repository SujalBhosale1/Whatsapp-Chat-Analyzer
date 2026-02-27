# WhatsApp Chat Analyzer

A simple web application built with Streamlit and Python to analyze and visualize WhatsApp chats. You can just export any WhatsApp chat as a `.txt` file and upload it to the app to see group stats, activity graphs, and more.

## Features
- **Overall Statistics:** see total messages, total words, media shared, and links sent.
- **Timelines:** view monthly and daily message timelines.
- **Activity Maps:** find out the busiest days and months, plus a weekly heat map to see when the chat is most active.
- **Most Active Users:** see who messages the most in group chats.
- **Word Analysis:** generates a word cloud and a bar chart of the most used words.
- **Emoji Analysis:** tracks the most frequently used emojis.

## How to run locally

1. Clone this repository to your local machine.
2. Install the requirements:
   ```bash
   pip install streamlit pandas matplotlib seaborn wordcloud urlextract emoji
   ```
3. Start the app:
   ```bash
   streamlit run app.py
   ```
4. Export your chat from WhatsApp (without media) and upload the `.txt` file to the app.

## Project Screenshots

Here's how the app looks when analyzing a chat:

**1. Main Dashboard & Top Stats**
![Top Statistics](screenshots/Screenshot%202026-02-28%20003450.png)
![Top Statistics](screenshots/Screenshot%202026-02-28%20003522.png)

**2. Chat Timelines**
![Monthly Timeline](screenshots/Screenshot%202026-02-28%20003531.png)
![Daily Timeline](screenshots/Screenshot%202026-02-28%20003538.png)

**3. Activity Maps & Heatmap**
![Activity Map](screenshots/Screenshot%202026-02-28%20003544.png)
![Heatmap](screenshots/Screenshot%202026-02-28%20003550.png)

**4. Busiest Users (Group Chats)**
![Most Busy Users](screenshots/Screenshot%202026-02-28%20003556.png)

**5. Word Cloud & Common Words**
![Wordcloud](screenshots/Screenshot%202026-02-28%20003601.png)
![Most Common Words](screenshots/Screenshot%202026-02-28%20003607.png)

**6. Emoji Usage**
![Emoji Analysis](screenshots/Screenshot%202026-02-28%20003612.png)
