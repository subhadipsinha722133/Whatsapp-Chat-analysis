# 📊 WhatsApp Chat Analysis  

This project provides an **interactive dashboard** to analyze WhatsApp chat data.  
It uses **Streamlit** for the interface and includes insights such as message activity, word usage, media sharing, and emoji analysis.  

---

## 🚀 Features
- 📥 Upload exported WhatsApp chat text file.  
- 📈 Visualize **message frequency** (daily, monthly, user-wise).  
- 🔍 Perform **word frequency analysis** and generate a **WordCloud**.  
- 😂 Analyze **emoji usage**.  
- 📊 Compare **active users** in group chats.  
- 🌐 Extract and count **shared links**.  

---

## 📺Live Demo

- 🔗Demo Link :-
  https://whatsapp-chat-analysis-kdjcfeqkokrojsyju6jad3.streamlit.app/
   - Currently this link is not working , **click about section link**
- 🎬Demo Voideo
<img src="https://github.com/subhadipsinha722133/Whatsapp-Chat-analysis/blob/main/WhatsApp%20Chat%20Analysis%20%20.gif">

---
## 🛠️ Tech Stack
- **Python**  
- **Streamlit** → Interactive dashboard  
- **Matplotlib & Seaborn** → Data visualization  
- **Pandas** → Data handling & preprocessing  
- **WordCloud** → Word frequency visualization  
- **Emoji** → Emoji analysis  
- **urlextract** → URL extraction from chat messages  

---

## 📂 Installation
1. Clone the repository:  
   ```bash
   git clone https://github.com/subhadipsinha722133/Whatsapp-Chat-analysis.git
   cd whatsapp-chat-analysis
Create a virtual environment (optional but recommended):

    ```bash
    Copy code
    python -m venv venv
    source venv/bin/activate  # For Linux/Mac
    venv\Scripts\activate     # For Windows
    Install dependencies:


 
    pip install -r requirements.txt<br>

---
# ▶️ Usage
Export your WhatsApp chat (without media) from your phone.<br>

On WhatsApp: More → Export Chat → Without Media<br>

This will save a .txt file.<br>

Run the Streamlit app:<br>

    ```bash
      Copy code
      streamlit run app.py
Upload the exported .txt file in the app.<br>

Explore the interactive insights and visualizations! 🎉

---

# 📊 Example Insights
Most Active User in a group.

Timeline of messages per day/month.<br>

Top words & WordCloud.<br>

Emoji usage stats.<br>

Number of media files & links shared.<br>

---
## 📦 Requirements
Dependencies are listed in requirements.txt:

- nginx
- Copy code
- streamlit
- matplotlib
- seaborn
- urlextract
- wordcloud
- pandas
- emoji

  ---
  
## 📌 Future Improvements
- 🔔 Sentiment Analysis of messages.

- 🌍 Multilingual chat analysis.

- 📱 Integration with Telegram/Slack exports.

---
# 🤝 Contributing
Pull requests are welcome! If you'd like to improve this project, feel free to fork and submit changes.

---
# 📜 License
This project is licensed under the MIT License.

pgsql <br>
Copy code<br>

Would you like me to also **create the `requirements.txt`** file for you with pinned versions so it runs without compat
