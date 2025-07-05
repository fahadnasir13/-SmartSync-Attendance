# 📸 SmartSync Attendance

> A smart, AI-powered attendance system using real-time face recognition — accessible directly in your browser.

🧠 **Built with**: Python · DeepFace · Gradio · OpenCV  
🚀 **Deploys on**: Hugging Face Spaces

---

## 🌟 Features

- ✅ **Face Recognition-Based Check-In**
- ✅ **Webcam or Image Upload Support**
- ✅ **Accurate Matching via DeepFace**
- ✅ **Simple UI with Gradio**
- ✅ **No installation needed — runs in browser**
- ✅ **CSV-based Attendance Log**

---

## 🛠 Tech Stack

| Tool       | Purpose                         |
|------------|---------------------------------|
| DeepFace   | Face recognition engine         |
| Gradio     | Web-based user interface        |
| OpenCV     | Image capture and preprocessing |
| Pandas     | CSV log and timestamp tracking  |
| Hugging Face Spaces | Free deployment         |

---

## 📁 Folder Structure
smartsync-attendance/
├── app.py # Gradio interface + face logic
├── dataset/ # Known user images
├── attendance.csv # Output attendance file
├── requirements.txt
├── README.md
└── assets/ # Optional logos/screenshots



## 🚀 How to Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/fahadnasir13/smartsync-attendance.git
cd smartsync-attendance

# 2. Install requirements
pip install -r requirements.txt

# 3. Start the app
python app.py
🧪 How to Use (Live)
Visit the Hugging Face Space link

Upload your image OR use webcam

If your face matches an existing record → attendance is logged

CSV gets updated with name, time, and match score

📸 Screenshots
(Add some screenshots or a preview GIF here)
Or drop a [demo video link] if available.

🗂 Future Improvements
 Cloud-based storage (Firebase/Drive)

 Admin dashboard to manage users

 Real-time multi-face support

 Mobile-friendly UI

 Attendance analytics & insights

👤 Creator
Fahad Nasir
AI & Full Stack Developer

GitHub: https://github.com/fahadnasir13

LinkedIn: https://linkedin.com/in/fahadnasir15

Portfolio: https://fahadnasir.macaly-app.com

📄 License
MIT License — Free to use, modify, and deploy with credit.

🙌 Contributions
Pull requests and feedback are welcome.
Let’s build the future of smart, contactless systems!
