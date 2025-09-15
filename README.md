# 📊 Telegram Channel Dashboard  

A Power BI project where I analyzed **327 posts** from my personal Telegram channel (2021–2025).  
The goal was to practice text cleaning, data modeling, and visualization — and to see how my writing habits have evolved over time.  

---

## 🚀 Project Overview  
- **Dataset**: Exported JSON from my Telegram channel (messages, dates, text).  
- **Tools**: Power BI, DAX, Power Query.  
- **Focus**: Posting frequency, writing style, and trends across time.  

---

## 🔧 Steps Taken  
1. **Data Preparation**  
   - Exported channel history as JSON from Telegram.  
   - Cleaned in Power Query (flattened lists → text, filtered only posts, removed service actions).  
   - Created calculated columns:  
     - `WordCount` (number of words per post)  
     - `CharCount` (number of characters)  
     - `Year`, `Month`, `DayOfWeek` (from post date).  

2. **Data Modeling**  
   - Built measures for total posts, average word count, longest/shortest posts.  
   - Categorized posts by year/month/day.  

3. **Visualization**  
   - **KPIs**: total posts, average word count, longest/shortest post.  
   - **Posting rhythm**: line chart (posts per month), bar chart (posts by weekday).  
   - **Writing style**: average word count per year, histogram of post lengths.  
   - **Details**: table of longest posts with previews.  

---

## 📈 Key Insights  
- 🗓️ **2022** was the peak year — I posted almost daily.  
- 📅 **Thursdays and Sundays** were my main posting days.  
- ✍️ My **average post length grew** over time: short notes in 2021–2022 → much longer reflections in 2025.  
- 📖 My longest post reached **407 words in 2025**, showing how my writing shifted into deeper reflections.  

---

## 📷 Screenshots  
(Add images from your dashboard here, for example:)  
- `images/posting-behaviour.png`  
- `images/trends-in-length.png`    

--- 
