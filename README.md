# Data-Engineering
# 🌍 Travel Destination Ranking

## ✨ Project Overview
This project ranks the best weekend travel destinations based on a given city. Using Python and Pandas, it processes a dataset of must-see places in India to recommend top destinations based on distance, rating, and significance.

---

## 💻 Technologies Used
- Python
- Pandas
- Geopy (for geolocation)
- OpenStreetMap API (for coordinates retrieval)

---

## 🔧 Installation & Setup
### **1. Clone the Repository**
```bash
git clone https://github.com/YOUR_USERNAME/Travel-Destination-Ranking.git
cd Travel-Destination-Ranking
```

### **2. Install Dependencies**
```bash
pip install pandas geopy requests
```

### **3. Download the Dataset**



- **OR Download from Kaggle**: [Kaggle Dataset](YOUR_KAGGLE_LINK_HERE)

Place the dataset (`Top Indian Places to Visit.csv`) in the project folder.

---

## 📝 Usage
Run the script to find the top travel destinations from a specific city.

```bash
python travel_rank.py
```

Or, use it in a Jupyter Notebook:
```python
from travel_rank import get_top_destinations
get_top_destinations("Delhi")
```

---

## 🌟 Features
- Takes a **city name** as input.
- Uses **geolocation APIs** to find distances.
- Filters the **top weekend destinations** based on:
  - Distance (within 200-300 km)
  - Google Review Rating
  - Significance
- Outputs a ranked list of places.

---

## 📝 Example Output
```
Top Weekend Destinations from Delhi:
1. Taj Mahal in Agra - 230 km away (Rating: 4.8)
2. Amer Fort in Jaipur - 270 km away (Rating: 4.7)
3. Neemrana Fort in Alwar - 150 km away (Rating: 4.5)
```

---

## 📊 Future Improvements
- Use **Machine Learning** to predict personalized recommendations.
- Integrate **weather data** for better trip planning.
- Add a **web interface** for user-friendly interactions.

---


