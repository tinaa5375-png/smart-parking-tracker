# Smart Parking License Plate Tracker 🚗🅿️

פרויקט מעשי במסגרת לימודי DevOps, המדמה מערכת לניהול כניסת רכבים לחניון חכם באמצעות מיקרו-סרביסים.

## 🛠 טכנולוגיות בשימוש
* **Docker & Docker Compose** – אריזת הסרביסים והרצתם בסביבה מבודדת.
* **Nginx** – שרת Web להצגת לוח הבקרה (Dashboard) לשומר.
* **Apache / Redis** (בהתאם למסלול) – שרת אחסון/בסיס נתונים.
* **GitHub Actions** – אוטומציית CI/CD לבדיקת תקינות Build בכל Push.

---

## 🚀 הוראות הרצה (Quick Start)

1. ודאו שמותקנים אצליכם Docker ו-Docker Compose.
2. שכפלו את המאגר למחשב שלכם והיכנסו לתיקייה.
3. הריצו את הפקודה הבאה בטרמינל:
   ```bash
   docker compose up --build
