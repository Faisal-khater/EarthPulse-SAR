<div align="center">

<!-- استبدل الرابط أدناه برابط الصورة من GitHub Issues أو ارفعها في مجلد assets باسم banner.jpg -->
<img src="./assets/banner.jpg" alt="EarthPulse SAR Banner" width="100%" style="border-radius: 12px;" />

<br/>

# 🌍 EarthPulse SAR
### **Powered by Nkta AI**

**Observe Change. Understand Earth. Predict Disasters.**  
*Transforming space-borne radar signals into actionable visual intelligence and proactive disaster forecasting.*

<p>
  <a href="https://earthpulse-sar.netlify.app">
    <img src="https://img.shields.io/badge/Live_Platform-Explore_Demo-0078D4?style=for-the-badge&logo=netlify&logoColor=white" alt="Live Demo" />
  </a>
  <a href="https://spaceappschallenge.org">
    <img src="https://img.shields.io/badge/NASA_Space_Apps-Challenge-E03C31?style=for-the-badge&logo=nasa&logoColor=white" alt="NASA Space Apps" />
  </a>
  <img src="https://img.shields.io/badge/AI_Engine-Nkta_AI-8A2BE2?style=for-the-badge&logo=openai&logoColor=white" alt="Nkta AI" />
  <img src="https://img.shields.io/badge/Python-3.10+-2EA44F?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
</p>

</div>

---

## 🚀 Overview | نبذة عن المشروع

Traditional optical Earth observation is heavily hindered by cloud cover, severe weather, and daylight limitations. **EarthPulse SAR** overcomes these barriers by utilizing **Synthetic Aperture Radar (SAR)** data—enabling continuous, all-weather, day-and-night monitoring of the Earth's surface.

By integrating **Nkta AI**, our next-generation predictive intelligence engine, the platform evolves from passive monitoring into **proactive early-warning forecasting**, identifying environmental anomalies and disaster risks before they escalate.

> **الرؤية:** تجاوز قيود التصوير الفضائي التقليدي عبر دمج بيانات الرادار الفضائي (SAR) مع محرك الذكاء الاصطناعي التنبؤي **Nkta AI** لتحويل الإشارات الخام إلى خرائط إنذار مبكر تدعم اتخاذ القرار في الوقت الحرج.

---

## ⚡ The Core Challenge | التحدي

| التحدي (Challenge) | الأثر (Impact) | حل EarthPulse SAR |
| :--- | :--- | :--- |
| **☁️ Cloud & Weather Obstacles** | تفشل الأقمار البصرية أثناء العواصف والغيوم الكثيفة—وهي اللحظات الأهم للرصد. | اختراق السحب والظروف الجوية عبر موجات الرادار (SAR) على مدار 24 ساعة. |
| **⏱️ Rapid Surface Shifts** | الفيضانات المفاجئة والانهيارات الأرضية تتطور خلال ساعات قليلة. | مقارنة زمنية آلية للمشاهد الرادارية لرصد التغيرات الفيزيائية فور حدوثها. |
| **🧩 Raw Data Complexity** | بيانات الرادار معقدة وتحتاج خبرة تقنية عالية لتحليلها واستخلاص النتائج. | معالجة مؤتمتة ولوحة تحكم بصرية تفاعلية مدعومة بـ **Nkta AI**. |

---

## 🧠 Nkta AI: Predictive Intelligence Pillars | ركائز التنبؤ الذكي

Anchored in scientifically validated remote sensing methodologies aligned with space agency standards, **Nkta AI** focuses on three high-impact predictive tracks:

### 1. ⛰️ Landslide Risk Forecasting *(مخاطر الانهيارات الأرضية)*
* **Methodology:** High-precision slope stability and terrain displacement analysis by fusing SAR interferometry metrics with topographical (DEM) and precipitation datasets. *(Primary Flagship Model)*

### 2. 🌊 Flash Flood Risk & Inundation *(مخاطر الفيضانات والسيول)*
* **Methodology:** Combining space-borne SAR backscatter water-masking with rainfall rates and watershed hydrology models to map water expansion and forecast high-risk flood zones.

### 3. 📉 Earthquake Hazard & Deformation Monitoring *(مراقبة تشوهات القشرة الأرضية)*
* **Methodology:** Long-term tracking of ground surface deformation and structural shifts across tectonically active fault zones to assess infrastructural vulnerability *(focused on structural risk assessment rather than exact earthquake timing prediction)*.

---

## ⚙️ System Architecture & Pipeline | آلية عمل المنصة

```mermaid
graph LR
    A[🛰️ Space SAR Data<br/>NISAR / Sentinel-1] --> B[⚙️ Preprocessing &<br/>Temporal Alignment]
    B --> C[🧠 Nkta AI Engine<br/>Change & Risk Modeling]
    C --> D[🗺️ Interactive Web UI<br/>EarthPulse Dashboard]
    style A fill:#0f172a,stroke:#38bdf8,stroke-width:2px,color:#fff
    style B fill:#0f172a,stroke:#818cf8,stroke-width:2px,color:#fff
    style C fill:#1e1b4b,stroke:#c084fc,stroke-width:2px,color:#fff
    style D fill:#064e3b,stroke:#34d399,stroke-width:2px,color:#fff
