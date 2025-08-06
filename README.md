# 🌦️ Flask Weather App with OpenWeatherMap API on Amazon EC2

This project is a simple **Flask web application** that allows users to enter a city name and retrieve **real-time weather information** using the [OpenWeatherMap API](https://openweathermap.org/). The app is hosted on an **Amazon EC2 instance** running **Amazon Linux 2**.

---

## 📦 Tech Stack

- **Python 3**
- **Flask**
- **OpenWeatherMap API**
- **Amazon EC2 (Amazon Linux 2)**
- **Virtualenv**

---

## ✅ Prerequisites

- An AWS EC2 instance (Amazon Linux 2)
- Port `5000` open in EC2 Security Group
- A valid OpenWeatherMap API key ([Get one here](https://openweathermap.org/api))

---

## 🚀 Setup Instructions

### 🔹 1. Connect to Your EC2 Instance
```bash
ssh -i your-key.pem ec2-user@<your-ec2-public-ip>
sudo yum install python3 -y
pip3 install --upgrade pip
pip3 install virtualenv

mkdir weatherly
cd weatherly
virtualenv myenv
source myenv/bin/activate
pip freeze > requirements.txt
source myenv/bin/activate
python app.py
<img width="1919" height="1017" alt="Screenshot 2025-08-06 094701" src="https://github.com/user-attachments/assets/76e045a9-a7b7-42aa-9c44-57b4e8ab3b3f" />
<img width="1917" height="1022" alt="Screenshot 2025-08-06 094721" src="https://github.com/user-attachments/assets/d4266b4c-b68c-443b-af65-36e2b6044515" />
<img width="1919" height="1015" alt="Screenshot 2025-08-06 095010" src="https://github.com/user-attachments/assets/efa543f1-7c60-4465-99bf-5437d50e0362" />
<img width="1919" height="1012" alt="Screenshot 2025-08-06 095048" src="https://github.com/user-attachments/assets/95af40fe-cad3-4e74-a677-281aa7d38516" />


