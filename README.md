# Video Game Sales Dashboard

An interactive 4-page Power BI dashboard analysing global video game sales from 1980 to 2016, covering **16,000+ games across 31 platforms and 12 genres**. It shows which consoles, genres and publishers have driven the industry, and how sales differ across North America, Europe, Japan and other regions.

> All sales figures are in **millions of units sold**.

## 📌 Objective
Understand how video game sales vary by platform, genre, publisher, region and release year, and how critic and user scores relate to sales.

## 📂 Dataset
- **Source:** [Video_Games_Sales_as_at_22_Dec_2016]
- **Coverage:** 1980–2016
- **Size:** 16,000+ games, 31 platforms, 12 genres
- **Key fields:** Name, Platform, Year of Release, Genre, Publisher, Developer, ESRB Rating, Global Sales, regional sales (North America, Europe, Japan, Other), Critic Score, User Score

## 🛠️ Tools Used
- **Power BI Desktop**: data modelling, calculated measures and dashboard design
- **Python**: loading the dataset

## 📊 Dashboard Pages

| Page | What it shows |
|---|---|
| **Home** | Overview of the project with headline cards (games count, total sales, top platform, average critic score), Genre and Year slicers, and navigation to the other pages |
| **Sales Performance** | Sales by platform, genre, region and year: top platforms, top-selling games, genre treemap, regional split (donut chart) and sales trend over time |
| **Publishers & Reviews** | Leading publishers and developers, sales by ESRB rating, genre-by-region sales table, and average critic vs user scores by genre |
| **Insights** | Written summary of the key findings from the data |

**Interactive features:** Genre and Year of Release slicers, page navigation buttons, and cross-filtering between visuals.

## 🔍 Key Insights

**Sales overview**
- About **8.8 billion units** were sold between 1980 and 2016.
- Sales grew quickly from the mid-1990s and **peaked at about 672 million units in 2008**, then declined every year afterwards. (2016 data is incomplete, so the final drop is exaggerated.)
- **North America** is the largest market with about **49%** of sales, followed by Europe (27%), Japan (15%) and other regions (9%).

**Platforms, genres and games**
- **PlayStation 2** is the top platform with about **1.23 billion units**, ahead of Xbox 360 (961M), PlayStation 3 (931M) and Wii (892M).
- **Action** is the best-selling genre (about 1.72 billion units), followed by Sports (1.31 billion) and Shooter (1.04 billion). Puzzle and Simulation sell the least.
- **Wii Sports** is the best-selling game at about 83 million copies, followed by Grand Theft Auto V (57M) and Super Mario Bros. (45M).

**Publishers and reviews**
- **Nintendo** leads all publishers with about 1.8 billion units, followed by Electronic Arts (1.1 billion) and Activision (0.7 billion).
- **E-rated (Everyone)** games sell the most (about 2.8 billion units), followed by T (Teen) and M (Mature).
- Average critic and user scores are similar across genres, mostly between **65 and 73 out of 100**, with Role-Playing rated highest.

## ⚠️ Limitations
- 2016 figures are incomplete, so the year-on-year decline at the end of the timeline is overstated.
- Critic scores are available for only about half of the games, so review comparisons are based on a sample.

## 📸 Screenshots

### Home
![Home](<img width="1376" height="777" alt="image" src="https://github.com/user-attachments/assets/6db9df2a-c5d3-46bc-84da-caa5b6b75953" />
)

### Sales Performance
![Sales Performance](<img width="1374" height="773" alt="image" src="https://github.com/user-attachments/assets/ef59f3f8-070a-4e9e-9c37-51f4a172781b" />
)

### Publishers & Reviews
![Publishers & Reviews](<img width="1375" height="773" alt="image" src="https://github.com/user-attachments/assets/32bcfc9f-bcf3-4bdf-9a9a-03656d0d312b" />
)

### Key Insights & Summary
![Key Insights](<img width="1372" height="776" alt="image" src="https://github.com/user-attachments/assets/a3cc927d-9a84-4c68-b83c-4b90a4d27bf3" />
)

## ▶️ How to View
- **Quick view:** open `Dashboard_Report.pdf` (no software needed).
- **Interactive:** download `presentation_dashboard.pbix` and open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows only).

## 👤 Author
**Habeeb mohamed** | [LinkedIn](www.linkedin.com/in/habeeb-mohamed-77004b416) | habeebmohamed2016@gmail.com
