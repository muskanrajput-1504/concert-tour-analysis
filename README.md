# Highest Grossing Concert Tours Analysis 🎤💰

Hi! I am a 4th-semester B.Tech student working toward a career in Data Analytics. This is Day 2 of my focused daily study routine to build real-world skills for upcoming internships.

After building my first basic chart yesterday, I wanted to tackle a harder dataset. I analyzed the highest-grossing concert tours of all time, but I quickly ran into a classic real-world problem: **Messy Data**.

## 🚧 The Problem
The Kaggle dataset was great, but the revenue numbers were formatted as text strings with dollar signs and commas (e.g., `"$780,000,000"`). Python couldn't do math on text, so I couldn't graph it!

## 🛠️ The Solution (Data Cleaning)
Instead of giving up, I used Pandas to clean the data. I wrote a Python script using `.str.replace()` to strip out the symbols and `.astype(float)` to convert the text into usable numbers. 

**Tools Used:**
* **Python**
* **Pandas** (For data cleaning and manipulation)
* **Matplotlib** (For data visualization)

## 📊 The Result
Once the data was clean, I generated a custom bar chart visualizing the Top 10 tours. (Check out the `.ipynb` file to see my data cleaning script and the final graph!)
