# 🌿 ESP32 Auto Watering System (Soil Capacitive V2)

โครงงานระบบ **รดน้ำต้นไม้อัตโนมัติด้วย ESP32**  
อ่านค่าความชื้นดินด้วย **Soil Moisture Sensor (Capacitive V2)**  
ควบคุม **ปั๊มน้ำผ่าน Relay** และตั้งค่า Threshold ได้อัตโนมัติ

---

## 🧠 Concept
> ใช้ ESP32 อ่านค่าความชื้นในดิน → ถ้าค่าต่ำกว่าเกณฑ์ → เปิดปั๊มน้ำอัตโนมัติ  
> ถ้าค่าสูงกว่ากำหนด → ปิดปั๊มน้ำ พร้อมแสดงผลผ่าน Serial หรือ Web Server

---

## ⚙️ Hardware Required
| อุปกรณ์ | รายละเอียด |
|----------|-------------|
| ESP32 DevKit V1 | บอร์ดหลัก |
| Soil Moisture Sensor (Capacitive V2) | เซนเซอร์วัดความชื้นดิน |
| Relay Module 1 Channel | ควบคุมปั๊มน้ำ |
| ปั๊มน้ำ 5–12VDC | ใช้รดน้ำต้นไม้ |
| Power Supply | จ่ายไฟแยกให้ปั๊ม |

---

## 🧾 Flowchart 
> - Start  
> - อ่านค่าความชื้น  
> - เปรียบเทียบกับ Threshold  
> - ถ้าต่ำกว่า → เปิดปั๊ม  
> - ถ้าสูงกว่า → ปิดปั๊ม  
> - Delay / Loop  

---

## อ่านบทความเต็ม
[ระบบรดน้ำต้นไม้เบื้องต้น ESP32 + Soil Moisture Capacitive v2.0](https://devadiy.com/esp32-auto-watering-soil-capacitive-v2-threshold/)

---

## 🌐 Optional (Web Control)

สามารถต่อยอดโดยเพิ่ม Web Server (ESPAsyncWebServer)
เพื่อควบคุมการเปิด/ปิดปั๊มจากหน้าเว็บ และปรับค่า Threshold ผ่าน Wi-Fi ได้

อ่านเพิ่มเติมที่ → [ESP32 Web Server Guide](https://devadiy.com/esp32-espasyncwebserver-guide/)

---

## 💡 License

MIT License © 2025 [DevaDIY](https://devadiy.com/)

---

