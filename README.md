# Grid - Operations Analytics Prototype

This is a prototype submission for the **Full-Stack Intern Challenge at Shipzu**.  
It demonstrates KPI computation from shipment data and a minimal static dashboard to visualize performance.

---

## 📊 Features
- **KPI Computation** (from dataset):
  - Delivered %
  - RTO %
  - Orders at Risk
  - DRR (Delivery-to-RTO Ratio)
- **Threshold Editing**  
  - Delivered % → higher is better  
  - RTO % & Risk % → lower is better  
  - Default thresholds: `85 / 8 / 20`
- **Rules Output (Green/Red)** updates dynamically based on thresholds.
- **Badges Colorization** for quick performance check.
- **IST Timestamp** visible and updates every second.
- **No console errors, clean file hygiene**.

---

## 📂 Files in Submission
- `submission.json` → Generated KPIs in required shape.  
- `index.html` → Static dashboard page.  
- `styles.css` → Custom styles.  
- `index.ipynb` → Jupyter script to compute KPIs from dataset (not required in hosted version, used for submission.json).  

---

## ▶️ How to Run
1. Clone or download this repository.  
2. Open `index.html` in any modern browser.  
   - The dashboard loads `submission.json` and shows computed KPIs.  
3. To host online:
   - Push repo to GitHub → enable GitHub Pages.  
   - Or deploy on [Vercel](https://vercel.com).  

---

## ✅ Validation Checklist
- Numbers match `submission.json`.  
- Threshold editing works.  
- Rules output (Green/Red) updates correctly.  
- Badges colorization behaves as expected.  
- IST timestamp visible.  
- Page is responsive, no console errors.  
- File hygiene: no secrets, simple README, clean submission.json.  

---

## 📝 Notes
This is a **prototype**, not production-ready.  
The goal is to demonstrate problem-solving, KPI computation, and a clean UI as per the challenge.


