# GDGAIEvent • AI Body Measurement & Fashion Studio

An end-to-end AI fashion, anthropometry, colorimetry, and digital tailoring application built for the Google Developer Groups (GDG) AI Event.

Link: https://chelseahai.github.io/hackathon/web/presentation-workflow/?v=vonage2#title

---

## 🌟 Workflow Pipeline

1. **Upload & Reference Calibration:**
   - Detects physical reference objects (Standard A4 Paper or ID/Credit Card ISO/IEC 7810 ID-1) to calculate real-world pixel-to-centimeter scale.
   - Accepts Front & Profile/Side photos.
2. **Body Dimension Extraction:**
   - Estimates anthropometric keypoints: Height, Shoulder Width, Chest/Bust, Waist, Hips, Inseam, Torso Length, Arm Length.
   - Computes 3D circumferences using elliptical integral cross-sections.
3. **Seasonal Color Analysis:**
   - Analyzes skin tone, undertones (Warm/Cool/Neutral), and contrast.
   - Maps user to 12-season color categories (e.g., Warm Autumn, Cool Winter) with 5 core fabric HEX swatches and colors to avoid.
4. **Silhouette & Pattern Recommender:**
   - Matches body shape (Hourglass, Pear, Rectangle, Inverted Triangle, Apple) with optimal structural cuts, necklines, hemlines, and fabric drape.
5. **Manufacturing Tech Pack (Specification Sheet):**
   - Generates production Point of Measure (POM) specs with wearing ease allowances and manufacturing tolerances.
   - 1-Click Export to **CSV** and **JSON** for garment pattern makers and factories.
6. **Virtual Try-On Render:**
   - Renders the custom tailored garment on the human silhouette with real-time editorial style prompts.

---


