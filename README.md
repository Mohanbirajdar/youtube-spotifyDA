# 🎵 Spotify & YouTube Data Analysis

![Spotify YouTube Data Analysis](Spotify%20YouTube%20Data%20Analysis.png)

## 📋 Overview

This project analyzes a combined dataset of Spotify and YouTube music data to uncover insights about artists, tracks, albums, and user engagement metrics. The analysis explores relationships between streaming platforms and identifies top-performing content.

## 📊 Dataset

The dataset contains information about tracks available on both Spotify and YouTube, including:

- **Track Information**: Track name, Artist, Album, Album type
- **Spotify Metrics**: Streams, Danceability, Energy, and other audio features
- **YouTube Metrics**: Views, Likes, Comments, Channel information

## 🔧 Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization

## 📈 Analysis Questions Covered

| # | Question |
|---|----------|
| 1 | Top 10 Artists with the Highest Views on YouTube |
| 2 | Top 10 Tracks with the Highest Streams on Spotify |
| 3 | Most Common Album Types on Spotify |
| 4 | Average Views, Likes, and Comments by Album Type |
| 5 | Top 5 YouTube Channels based on Views |
| 6 | Top Most Track based on Views |
| 7 | Tracks with Highest Like-to-View Ratio on YouTube |
| 8 | Top Albums with Maximum Danceability |
| 9 | Correlation between Views, Likes, Comments, and Streams |

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy seaborn matplotlib
```

### Running the Analysis

1. Clone or download this repository
2. Update the dataset path in the notebook:
   ```python
   data = pd.read_csv("path/to/Spotify_Youtube Dataset.csv")
   ```
3. Run the Jupyter Notebook cells sequentially

## 📁 Project Structure

```
├── Spotify+&+YouTube+Data+Analysis+-+DSL.ipynb   # Main analysis notebook
├── Spotify_Youtube Dataset.csv                    # Dataset file
├── Spotify YouTube Data Analysis.png              # Project banner
└── README.md                                      # This file
```

## 🔍 Data Preprocessing

1. **Removed unnecessary columns**: `Unnamed: 0`, `Url_spotify`, `Uri`, `Url_youtube`
2. **Handled missing values**:
   - Filled `Likes` and `Comments` with 0
   - Dropped rows with remaining null values

## 📊 Key Visualizations

- **Pie Chart**: Album type distribution
- **Bar Plot**: Comparison of Views, Likes, Comments by Album Type
- **Horizontal Bar Chart**: Top YouTube Channels by Views
- **Heatmap**: Correlation matrix between engagement metrics

## 💡 Key Insights

- Discover which artists dominate YouTube views
- Understand the relationship between Spotify streams and YouTube engagement
- Identify high-performing tracks across both platforms
- Analyze engagement patterns by album type

## 🎯 Practice Questions

The notebook includes practice questions for learners:
- Q.2A) Find 5 Tracks with the Lowest Streams on Spotify
- Q.7.A) Find Top 3 Tracks with the Lowest Like-to-View Ratio

## 👤 Credits

- **Analysis by**: Rohit Grewal
- **Dataset**: Spotify & YouTube combined dataset

## 📄 License

This project is for educational purposes.

---

⭐ If you found this analysis helpful, please give it a star!
