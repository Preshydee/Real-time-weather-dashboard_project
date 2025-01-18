
```markdown
# 🌤️ Weather Dashboard: Automating Real-Time Weather Data Collection

Welcome to the **Weather Dashboard** project!  
This Python-based application automates the process of fetching real-time weather data using the OpenWeather API and securely storing it on AWS S3. It’s scalable, efficient, and built with error handling to ensure robust performance.

---

## 🚀 Project Overview

I created this project as part of the **#DevOps30DaysChallenge**, aiming to build hands-on solutions while learning critical tools and concepts in the DevOps space.

---

### Key Features
- **Dynamic Weather Updates**: Fetches real-time weather data for any city.  
- **Cloud Integration**: Stores weather data in JSON format on AWS S3 for scalability and easy access.  
- **Error Handling & Logging**: Robust error-handling mechanisms with logs for debugging and monitoring.  
- **Customizable & Scalable**: Dynamically accepts city inputs and adapts to region-specific AWS configurations.  

---

## 📂 Project Structure

```plaintext
weather-dashboard/
├── src/
│   └── weather-dashboard.py    # Main Python script  
├── tests/                      # Contains test scripts  
├── data/                       # Local data storage  
├── .env                        # Environment variables  
├── .gitignore                  # Files ignored by Git  
├── requirements.txt            # Python dependencies  
```

---

## 💻 Getting Started

### Prerequisites
- **AWS Account**: With S3 bucket access and configured IAM credentials.  
- **OpenWeather API Key**: Sign up at [OpenWeather](https://openweathermap.org/) to get your API key.  
- **Python 3.8+**  
- **VS Code**

---

### Installation Steps

1. Clone this repository:
   ```bash
   git clone https://github.com/Preshydee/Real-time-weather-dashboard_project.git
   cd Real-time-weather-dashboard_project
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up environment variables in a `.env` file:
   ```env
   OPENWEATHER_API_KEY=your_api_key_here  
   AWS_BUCKET_NAME=your_s3_bucket_name  
   AWS_ACCESS_KEY_ID=your_aws_access_key  
   AWS_SECRET_ACCESS_KEY=your_aws_secret_key  
   AWS_REGION=your_aws_region  
   ```

4. Run the script:
   ```bash
   python src/weather-dashboard.py
   ```

---

## 🛠️ Technologies Used
- **Python**  
- **OpenWeather API**  
- **AWS S3**  
- `boto3` for AWS integration  
- `python-dotenv` for managing environment variables  
- `requests` for API calls  

---

## 📝 Lessons Learned
- **Automation**: Streamlined workflows for efficiency.  
- **AWS Proficiency**: Gained hands-on experience with AWS S3 and boto3.  
- **Error Handling**: Developed robust code for managing API and runtime errors.  

---

## 🔗 Useful Links
- **GitHub Repository**: [Weather Dashboard](https://github.com/Preshydee/Real-time-weather-dashboard_project)  
- **Article on Medium**: [Building the Weather Dashboard](https://https://shorturl.at/xxMWE/)  

---

## 🙌 Acknowledgments
Special thanks to **Ifeanyi Otuonye, MBA**, **DeShae Lyda**, and **Alicia Ahl** for their guidance and support throughout this journey!

---

## 🏆 Let’s Connect!
Feel free to reach out on [LinkedIn](https://www.linkedin.com/in/adekoya-precious//) or check out more of my work on [Medium](https://medium.com/@adekoyapreciouspa/).  

Let’s keep building and learning together! 🚀


