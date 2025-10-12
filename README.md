
<!-- README.md: Privacy Vault (Dark Cyber + Glowing Animated Title) -->

<p align="center" style="margin-top:8px;">
  <!-- Animated glowing SVG title (fallbacks to static if animation is not supported) -->
  <svg xmlns="http://www.w3.org/2000/svg" width="100%" viewBox="0 0 1200 120" preserveAspectRatio="xMidYMid meet" role="img" aria-label="Privacy Vault">
    <defs>
      <!-- Glow filter -->
      <filter id="glow">
        <feGaussianBlur stdDeviation="6" result="blur"/>
        <feMerge>
          <feMergeNode in="blur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
      <!-- Slight blur for secondary glow -->
      <filter id="softglow">
        <feGaussianBlur stdDeviation="12" result="soft"/>
        <feMerge>
          <feMergeNode in="soft"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>

    <!-- Blurred glow layer (pulses) -->
    <text x="50%" y="60" text-anchor="middle" font-family="Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial" font-size="40" fill="#00ffcc" filter="url(#softglow)" opacity="0.6">
      🛡️ Privacy Vault
      <animate attributeName="opacity" values="0.25;0.95;0.25" dur="2.8s" repeatCount="indefinite"/>
    </text>

    <!-- Crisp glow layer -->
    <text x="50%" y="60" text-anchor="middle" font-family="Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial" font-size="40" fill="#00ffaa" filter="url(#glow)">
      🛡️ Privacy Vault
    </text>

    <!-- Main readable text on top -->
    <text x="50%" y="60" text-anchor="middle" font-family="Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial" font-size="40" fill="#dffdf2" font-weight="700">
      🛡️ Privacy Vault
    </text>
  </svg>
</p>

**Project Status:** ✅ Completed — October 2025

<p align="center" style="background: radial-gradient(circle at center, #050505 0%, #000000 100%); padding: 20px; border-radius: 20px; box-shadow: 0 0 28px rgba(0,255,170,0.18), inset 0 0 18px rgba(0,255,170,0.06);">
  <img src="banner.png" alt="Privacy Vault Banner" width="80%" style="border-radius: 16px; border: 2px solid rgba(0,255,170,0.16); box-shadow: 0 0 30px rgba(0,255,170,0.25);">
</p>

---

## 🖼️ Visual Overview
<p align="center" style="background: linear-gradient(160deg, #000000, #021b1f, #013a3a); padding: 20px; border-radius: 20px; box-shadow: 0 0 25px rgba(0, 255, 200, 0.14), inset 0 0 20px rgba(0,255,170,0.06);">
  <img src="banner.png" alt="Privacy Vault Overview" width="80%" style="border-radius: 16px; border: 2px solid rgba(0,255,204,0.16); box-shadow: 0 0 20px rgba(0,255,204,0.18);">
</p>

---

## 🎯 Project Objectives

- Develop a reliable system for **secure data storage**  
- Enhance **user trust** through transparent encryption  
- Simplify access without compromising data protection  
- Promote **digital privacy awareness**

---

## ⚙️ Technologies Used

- **Programming Language:** Python  
- **Database:** SQLite / MySQL  
- **Frameworks:** Flask (backend), HTML/CSS (frontend)  
- **Encryption:** AES-256 Secure Encryption  
- **Version Control:** Git & GitHub  
- **Design Tools:** Figma / Canva (UI design)

---

## 💡 Key Features

- 🔐 End-to-end encryption for sensitive data  
- 👥 User authentication and session management  
- 💾 Encrypted local & cloud backup  
- 🧩 Intuitive, futuristic interface design  
- 🔍 Transparent security protocols  
- 🌍 Fully responsive layout for all devices

---

## 🚀 Future Improvements

- Integration with **blockchain** for enhanced transparency  
- Support for **multi-user access and sharing permissions**  
- **AI-based anomaly detection** for unauthorized access  
- Improved **real-time encryption** and performance

---

## 👨‍💻 Author

**Aina Olamilekan**  
Department of Computer Science  
Federal University of Technology Akure (FUTA)  
📧 **Email:** [privacyvault11@gmail.com](mailto:privacyvault11@gmail.com)

---

<p align="center" style="color:#00ffaa; font-weight:bold;">
  © 2025 <b>Privacy Vault</b> — Empowering Digital Privacy.
</p>
