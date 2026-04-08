# PM2.5 Predictive Modeling (CRISP-DM Framework)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Green?style=for-the-badge)

โปรเจกต์วิเคราะห์และพยากรณ์ระดับฝุ่นละออง PM2.5 โดยประยุกต์ใช้กระบวนการมาตรฐานอุตสาหกรรม **CRISP-DM** (Cross-Industry Standard Process for Data Mining) เพื่อสร้างโมเดลที่มีประสิทธิภาพและสามารถอธิบายผลได้

---

## Project Overview
โปรเจกต์นี้มีวัตถุประสงค์เพื่อพยากรณ์ค่าฝุ่น PM2.5 ล่วงหน้า โดยใช้ข้อมูลปัจจัยทางสภาพอากาศ และข้อมูลย้อนหลัง 4 ปี(2021-2024) เพื่อช่วยในการเฝ้าระวังและวางแผนรับมือกับปัญหามลพิษทางอากาศ

## Methodology (CRISP-DM)

1. **Business Understanding**: กำหนดเป้าหมายการพยากรณ์และเกณฑ์การวัดผล (MAE, RMSE)
2. **Data Understanding**: การสำรวจข้อมูล (EDA) เพื่อดูความสัมพันธ์ระหว่างตัวแปร เช่น อุณหภูมิ, ความชื้น และค่าฝุ่น
3. **Data Preparation**: การจัดการ Missing Values, การทำ Feature Engineering และการ Scale ข้อมูล
4. **Modeling**: การเปรียบเทียบประสิทธิภาพของโมเดลต่างๆ (Regression Model)
5. **Evaluation**: การวัดผลโมเดลด้วย Test Set และการวิเคราะห์ Error
6. **Deployment**: การนำโมเดลไปประยุกต์ใช้งาน (ผ่านเครื่องมือ Gradio)


## How to use
คุณสามารถเปิดโปรเจกต์นี้บน Google Colab ได้ทันทีผ่านปุ่มด้านล่างนี้:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1gdCjbVA5k1c3uon0ktN4QGj7WJlK0wZ8)
เเละ upload ไฟล์ pm2.52021 pm2.52022 pm2.52023 pm2.52024 เพื่อลองใช้งาน 

