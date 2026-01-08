# Adsul Accident Hospital - Project Overview

This document provides a detailed, section-by-section breakdown of the **Adsul Accident Hospital** website, including the specific text content and features implemented in each part of the landing page.

---

## 🔝 1. Header & Navigation

### Top Info Bar
- **Contact:** +91 99999 99999 | info@adsulhospital.com 
- **Location:** Phaltan, Satara
- **Social Media:** Facebook, Instagram, LinkedIn links.
- **Behavior:** Scrolls away as the user moves down the page.

### Main Navigation Bar
- **Branding:** Adsul Hospital (with Heart Pulse icon)
- **Links:**
  - **Home**
  - **About Us** (Dropdown: Our Hospital, Dr. Abhijit Adsul, Gallery)
  - **Emergency** (Dropdown: 24/7 Trauma Care, Ambulance)
  - **Specialties** (Dropdown: Joint Replacement, Spine Surgery, Fracture & Trauma, Pediatric Ortho)
  - **Facilities** (Dropdown: Modular OT, Digital X-Ray, Physiotherapy)
  - **Patient Corner** (Dropdown: Insurance/TPA, Govt Schemes, Reviews, Health Blog)
  - **Contact**
- **Action Button:** "Book Appointment" (Teal gradient button)
- **Behavior:** Becomes fixed to the top with a subtle shadow and white background (`.scrolled` class) after scrolling 50px.

---

## � 2. Hero Section (Home)
A full-screen, automatic slider featuring three key messages:

1.  **Slide 1: Trauma Center**
    - **Subtitle:** 24/7 Trauma Center
    - **Title:** Adsul Accident Hospital
    - **Description:** Leading Orthopedic & Trauma Care in Phaltan. Expert management of complex fractures and accidents by Dr. Abhijit Adsul.
    - **Buttons:** Book Visit, Emergency Call.

2.  **Slide 2: Advanced Orthopedics**
    - **Subtitle:** Advanced Orthopedics
    - **Title:** Joint Replacement Surgery
    - **Description:** Total Knee and Hip Replacement surgeries. Restoring mobility and quality of life with modern techniques.
    - **Button:** Learn More.

3.  **Slide 3: Spine Solutions**
    - **Subtitle:** Spine Solutions
    - **Title:** Expert Spine Care
    - **Description:** Compassionate care for back pain, slip disc, and spinal disorders. Minimally invasive procedures for faster recovery.
    - **Button:** Consult Now.

---

## 📊 3. Stats Section
- **23+** Years Experience
- **10K+** Surgeries Done
- **24/7** Emergency Care
- **4.3** Star Rating (Justdial)

---

## 🚨 4. Emergency Services
- **Headline:** 24/7 Emergency Services
- **Description:** Specialized accident and trauma care center. Immediate attention for road accidents, fractures, and emergencies.
- **Components:**
  - **Trauma Center:** Expert handling of polytrauma, head injuries, and complex fractures.
  - **Ambulance Support:** Quick response ambulance service for safe patient transport.
  - **First Aid Ready:** Immediate first aid and stabilization upon arrival.

---

## 🏥 5. About Section
- **Headline:** Adsul Accident Hospital
- **Text:** "Located in Phaltan, Adsul Accident Hospital is a renowned medical facility specializing in exceptional orthopedic care and comprehensive accident management."
- **Key Highlights:** Advanced OT, Expert Surgeons, Digital X-Ray, Cashless Facility.

---

## 👨‍⚕️ 6. Chief Surgeon (Dr. Abhijit Adsul)
- **Headline:** Dr. Abhijit D. Adsul
- **Credentials:** MBBS, MS (Orthopedics)
- **Experience:** Over 23 years of experience.
- **Specialties:** Trauma & Accidents, Joint Replacement, Spine Surgery, Pediatric Ortho.

---

## 🦴 7. Orthopedic Specialties
Six major service categories with detailed cards:
1.  **Joint Replacement:** Knee & Hip surgeries using computer-assisted navigation.
2.  **Spine & Back Surgery:** Disc herniation, scoliosis, and minimally invasive procedures.
3.  **Arthroscopy:** Keyhole surgery for ACL, meniscus, and rotator cuff repair.
4.  **Ilizarov Surgery:** Russian method for limb lengthening and deformity correction.
5.  **Fracture & Trauma:** 24/7 management of complex fractures and polytrauma.
6.  **Sports Injury:** Ligament surgeries (ACL/PCL) and athlete performance optimization.

---

## 💳 8. Insurance & Patient Support
- **Cashless (TPA):** Partnered with Star Health, ICICI Lombard, HDFC Ergo, Bajaj Allianz, and 25+ more.
- **Govt Schemes:** Authorized for Ayushman Bharat, MJPJAY, CGHS/ECHS, and Police Health.
- **Patient Note:** Reminds patients to bring Aadhar Card, Insurance docs, and past records.

---

## ✍️ 9. Health Blog (Bone Care Tips)
- **Knee Care:** 5 Tips to Prevent Knee Pain.
- **Spine Health:** Posture Tips for Back Pain Relief.
- **Nutrition:** Foods for Strong Bones (Calcium-rich diets).

---

## 📅 10. Appointment Section
- **Headline:** Start Your Recovery Journey
- **Features:** Glassmorphism form for callback requests.
- **Form Fields:** Name, Phone Number, Treatment Selection, Issue Description.
- **Contact Info:** 24/7 Emergency Line (1800-123-4567) and OPD Timings (Mon-Sat, 10AM - 8PM).

---

## 🔧 11. Infrastructure & Facilities
- **Modular OT:** Ultra-clean sterile environment with Laminar airflow.
- **Digital X-Ray:** High-frequency radiography for precise fracture detection.
- **24/7 Pharmacy:** In-house stock of medicines and orthopedic implants.
- **Wheelchair Access:** Ramps and elevators for easy mobility.

---

## � 12. Hospital Gallery
- **Categories:** All, Surgeries, Facilities, Events, Patients.
- **Feature:** Custom filter system and a high-resolution lightbox pop-up for viewing images.

---

## ⭐ 13. Testimonials
Successful stories from:
- **Rohan Deshmukh:** Trauma surgery recovery after a bike accident.
- **Priya Patil:** Successful knee replacement for her mother.
- **Suresh Jadhav:** Spine treatment and chronic back pain relief.

---

## � 14. Contact & Footer
- **Contact Cards:** Separated card for "Contact Information" (Location, Phone, Email) and a dedicated card for the "Google Map" to prevent overlapping.
- **Footer Categories:** Quick Links, Our Services, Location Map, and Copyright.
- **Floating Buttons:** WhatsApp icon, Call icon, and a "Back to Top" arrow.

---

## 💻 Tech Implementation Note
- **Vanilla CSS:** Custom variables for Deep Blue (`#0f172a`) and Emergency Red (`#dc2626`).
- **JavaScript Logics:** 
  - Dynamic Scroll Progress Bar at the very top.
  - requestAnimationFrame optimized navbar positioning.
  - AOS (Animate on Scroll) set to `duration: 800` for smooth entry effects.
