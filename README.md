# Educhakar — Next-Gen School Governance & Student Portal

> Designed with **Apple Human Interface** polish and **Google Material 3** aesthetic for the **Saharanpur Educational Board Ecosystem (CBSE Affiliated)**.

---

## 🌟 Highlights & Features (As Specified in Notes)

### 1. 🏫 School Directory & Public Discovery
- **Affiliated Boards**: Filter by **CBSC (Saharanpur)**, CISCE/ICSE, and UP State Board.
- **CBSC Schools**: Featured institutions:
  - **Pinewood School** (Delhi Road, Saharanpur)
  - **Delhi Public School (DPS)** (Ambala Road, Saharanpur)
- **Reviews & Activities Tabs**: Verified parent/student reviews (with star ratings) and campus activities (Annual Sports Meet, Science Fair, etc.).
- **Scroll Down Login Portals**: Direct Apple/Google style entry cards for **Management** and **Student Management System**.

---

### 2. 🛡️ Management Portal (Faculty & Administration)
- **Authentication**: Secured with username & password (`admin` / `admin123`).
- **Class Selector**: Quick navigation for **Class-1 to Class-8**.
- **Section Selector**: Toggle between **Section A** and **Section B**.
- **4 Core Governance Modules**:
  1. **Attendance (Full List)**:
     - Full roster of 10 students with roll numbers and avatars.
     - Toggle **Present - ✅** and **Absent - ❌** per student or in batch.
     - Live attendance metrics (Total, Present, Absent, %).
     - Persistent commit to local/cloud storage.
  2. **Class Test (Individual)**:
     - Individual student selector and subject chooser.
     - Teacher's custom academic remark textarea.
     - **Photo Upload**: Drag-and-drop or click to upload answer paper photo with **instant real-time image preview**.
  3. **Result (Semesters 1, 2, 3, 4)**:
     - Semester selection tabs: **Semester 1, 2, 3, 4**.
     - Semester 1 &rarr; **Student List**.
     - Student List &rarr; **Student Name** (e.g., Aarav Sharma).
     - Student Name &rarr; **All Subjects** (Mathematics, English, Science, Social Studies, Hindi).
     - Subject &rarr; **Manually write marks** (Theory out of 80, Practical out of 20, auto grade calculation) and **Upload Marksheet** document (PDF/Scan).
  4. **Activity**:
     - Section-A co-curricular activities, workshops, and sports updates.
     - "Post New Activity" interactive modal.

---

### 3. 🎓 Student Profile Dashboard (User Portal)
- **Authentication**: Secured with username & password (`student` / `student123`).
- **Student Profile**: Aarav Sharma &bull; Roll #01 &bull; Class 1-A &bull; Pinewood School.
- **6 Core Modules**:
  1. **View Attendance**: Total percentage circular progress ring (92.5%), working days counter, and interactive calendar dot grid.
  2. **Total Amount Due**: Outstanding tuition invoice (₹18,000) + interactive **"Way to Pay" Simulator** (UPI, Cards, Net Banking) with 1-click payment simulation that automatically clears the fee!
  3. **Fees Paid**: Historical transaction records with verified receipts and **Official PDF Receipt Generator**.
  4. **Total Subjects**: All 5 registered subjects with assigned teachers, course codes, and syllabus progress bars.
  5. **View Ans Sheet**: Subject-wise evaluated answer scripts + **CSV File Upload & Parser** with sample CSV template download.
  6. **View Result (Full Marksheet)**: Official CBSE formatted Marksheet report card with subject breakdown, grand total, CGPA, division, principal signatures, and print/export feature.

---

## 🚀 How to Run the Website

### Option 1: Double-Click (Zero Setup Needed)
Simply open `index.html` directly in Google Chrome, Microsoft Edge, Brave, or Safari:
```
D:\Credible Python\Projects\Educhakar\Frontend\index.html
```
or
```
D:\Credible Python\Projects\AI Driven Product Catalog Manager\Educhakar\index.html
```

### Option 2: Run with Python HTTP Server
```powershell
cd "D:\Credible Python\Projects\Educhakar\Frontend"
python -m http.server 8080
```
Then visit: `http://localhost:8080` in your web browser.

---

## ⚡ Demo Quick Switcher Credentials
| Role | Username | Password |
|---|---|---|
| **Management (Admin / Faculty)** | `admin` | `admin123` |
| **Student (Aarav Sharma - Class 1-A)** | `student` | `student123` |

*Note: You can also use the **"⚡ Quick Demo Mode"** switcher in the top navigation bar to switch between roles in 1 click without typing!*
