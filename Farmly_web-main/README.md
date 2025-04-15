# 🌾 Farmly – Your Smart Agriculture Assistant

Welcome to **Farmly**, a tech-driven solution designed to empower farmers with timely insights, smart recommendations, and practical tools — all in one place. Built with a user-friendly frontend and a Python-powered backend, Farmly helps make informed agricultural decisions using data, AI, and IoT integration.

---

## 🚜 Key Features

- 🌱 **Crop Recommendation**  
  Suggests the most suitable crops based on environmental and soil data.

- 🧪 **Fertilizer Advisory**  
  Recommends optimal fertilizers for healthier crop growth and soil maintenance.

- 🌤️ **Weather Forecasting**  
  Real-time weather updates for better planning of farm activities.

- 🦠 **Plant Disease Detection**  
  Identifies and provides remedies for common plant diseases using ML models.

- 💬 **AI Chatbot Support**  
  Instant help via a chatbot trained to answer basic farming queries.

- 📜 **Government Schemes Portal**  
  Aggregates useful schemes and subsidy information for farmers.

- 💸 **Seed Pricing & Resources**  
  Up-to-date seed price listings and resource availability.

- ☀️ **Solar Panel Info Center**  
  Guidance on renewable energy adoption through affordable solar solutions.

- 📩 **Feedback System**  
  Collects user feedback to improve features and usability.

---

## 🛠️ Tech Stack

### 🔗 Frontend
- **HTML5**
- **CSS3**
- **JavaScript** (for interactivity)

### 🧠 Backend
- **Python 3**
- **Machine Learning** for crop and disease predictions
- **Arduino Integration** for real-world sensor input (soil/environment)

### 🌐 APIs
- **Weather API** (e.g., OpenWeatherMap)
- **Government Resources API** (or static data from portals)

---

## 🗂️ Project Structure

Farmly_web-main/
├── css/                      # Stylesheets for the frontend
├── weatherwebsite/           # Weather integration module (HTML/CSS/JS)
├── Feedback.html             # Feedback form page
├── Fertilizer.html           # Fertilizer recommendation page
├── chatbo.html               # AI Chatbot interface
├── govts.html                # Government schemes information
├── index.html                # Home page
├── seed price.html           # Seed pricing information
├── seed.html                 # Seed details and recommendations
├── solarpanel.html           # Solar panel guidance page
├── tech.html                 # Technologies and resources info
├── ardu.py                   # Arduino sensor integration script
├── crop.py                   # Crop recommendation logic
├── dis.py                    # Data preprocessing or helper functions
├── disea.py                  # Plant disease detection logic
├── disp.py                   # Possibly visualization or display script
├── LICENSE                   # Project license
├── README.md                 # Project documentation (you're reading it!)



---

## ⚙️ Getting Started

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Bhumikax/Farmly_assistant.git
   cd Farmly_assistant/Farmly_web-main
   
2. Install dependencies 
    ```bash
    pip install -r requirements.txt
    
3. Run Python scripts for prediction modules:
   crop.py – Crop Recommendation
   disea.py – Disease Prediction
   ardu.py – Sensor readings (if Arduino connected)
   
4. Open index.html in your browser to explore the UI.

💡 Inspiration
Farmly was born from the desire to leverage technology for India's agricultural backbone. We aim to bridge the information gap for farmers by delivering personalized, timely, and localized insights — directly at their fingertips.
