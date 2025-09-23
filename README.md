# 🌱 Plant Disease Detection Project  

## 📖 Overview  

This project applies **deep learning** to solve a critical agricultural challenge:  
**early detection of plant diseases.**  
Using the **YOLO object detection algorithm**, the system identifies plant types and distinguishes between **healthy** and **diseased** specimens.  

---

## ❌ The Problem  

- **Crop losses** due to plant diseases cause massive **economic damage** and threaten **food security**.  
- Many farmers lack the resources for **early diagnosis**, meaning diseases spread before they can be treated.  
- Manual field inspection is **time-consuming, inefficient, and error-prone**, especially for large farms.  
- Without timely action, farmers often face **reduced yields**, financial hardship, and wasted resources.  

---

## ✅ The Solution  

The **Plant Disease Detection Project** uses **AI-driven automation** to make disease detection and response:  
- **Faster** – Camera-equipped robots simulate drones to scan fields automatically.  
- **Smarter** – YOLOv8 detects plant types and identifies diseases in real time.  
- **Actionable** – The system maps where diseases occur and sends **WhatsApp treatment notifications** to the right farmer.  
- **Scalable** – Can be applied to larger farms, more plant types, and multiple diseases.  

This means farmers can **act immediately**, apply **targeted treatments**, and **protect their crops and income.**  

---

## ⚙️ How It Works  

1. **Field Scanning** – An Arduino-based robot (drone simulation) moves across the field in small steps.  
2. **Image Capture** – At each step, it captures plant images with a camera.  
3. **AI Analysis** – Images are processed by YOLOv8 to classify plants as healthy or diseased.  
4. **Mapping** –  
   - `X` = diseased plant  
   - `-` = healthy plant  
   - Separate map for plant type detection  
   - (Future: GPS geotagging for spatial accuracy)  
5. **Automated Treatment Notification** – PostgreSQL database stores treatments + farmer contacts.  
   - Assigns tasks to the correct farmer (based on job keywords).  
   - Sends treatment recommendations via WhatsApp.  
   - Tracks reminders and repeat treatments with SQL.  

---

## 🌟 Benefits  

- **⏱️ Timely Awareness** – Farmers get notified instantly when disease is detected.  
- **⚡ Efficiency** – Reduces manual inspection and ensures the right farmer applies the right treatment.  
- **📈 Scalability** – Can expand to cover different crops, diseases, or larger farms.  
- **💰 Economic Security** – Helps reduce crop loss, improving yield and income.  

---

## 🛠️ Technologies Used  

- **C# (ASP.NET)** – User Interface  
- **Python** – YOLOv8 model, image analysis, database operations  
- **PostgreSQL** – Relational database for plants, diseases, treatments, and farmers  

---

## 📌 Next Steps  

- Add **GPS-based geotagging** for precise mapping.  
- Expand database with more crops and diseases.  
- Integrate with **real drones** for large-scale deployment.  

---

💡 By combining **AI, automation, and agriculture**, this project helps farmers fight crop disease efficiently, protecting both **food supply** and **livelihoods.**  

