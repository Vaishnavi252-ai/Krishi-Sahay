 **Krishi-Sahay – AI-Powered Credit Assessment Platform 🌾**

📌 Overview

Krishi-Sahay is a web platform designed to modernize agricultural credit assessment using alternative data sources and intelligent scoring algorithms. It enables fair and transparent loan evaluation for small and marginal farmers who lack traditional financial history.

🎯 Key Features

* Alternative credit scoring** based on agricultural practices
* Multi-language support:** English, Hindi, and Marathi
* Demo OCR-ready architecture** for 7/12 land document verification
* Rule-based intelligent credit assessment**
* Loan calculator** for EMI & repayment planning
* Integrated multilingual chatbot**
* *Mobile-first responsive design**

🛠️ Technology Stack

Frontend

* React 18
* TypeScript 5
* Tailwind CSS 3
* Vite 5
* Lucide React Icons

Backend

* Python 3.9+
* Flask 2.3
* Flask-CORS

Database

* SQLite (Dev)

Other
* Dev Tools: npm, ESLint, TypeScript, PostCSS, Autoprefixer

🚀 Quick Start

Prerequisites

* Node.js 18+
* Python 3.9+
* Git


Installation

```bash
git clone https://github.com/Vaishnavi252-ai/agricredit-score.git
cd agricredit-score
```

Frontend

```bash
npm install
npm run dev
```

Backend

```bash
cd backend
python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate

pip install -r requirements.txt
python app.py
```

---

📁 Project Structure

```
Krishi-Sahay/
│
├── client/                         # Frontend (React + Vite + TypeScript)
│   │
│   ├── src/                        # Frontend source code
│   │   ├── components/             # Reusable React UI components
│   │   ├── context/                # Global state (Auth, Language)
│   │   ├── utils/                  # Scoring, loan calc, OCR utils
│   │   ├── types/                  # TypeScript type definitions
│   │   ├── assets/                 # Images and static resources
│   │   ├── pages/                  # Application pages (Dashboard, Login, etc.)
│   │   ├── App.tsx
│   │   └── main.tsx
|
├── server/                      # Flask API server
│   ├── app.py                    # Core backend application
│   └── requirements.txt          # Backend dependencies
│
└── public/                       # Static public files
```

---

📈 Core Features

✔️ Authentication

* Registration with CAPTCHA
* Login via email/phone
* Local session management

✔️ Land Assessment

* Upload 7/12 land document
* Lease land support
* Owner name matching
* Multilingual document processing

✔️ Risk Assessment

* Personal details
* Farming practices
* Financial health
* Community involvement
* Tech adoption

✔️ Credit Scoring

* 50+ scoring parameters
* Risk-based loan suggestions
* Seasonal income consideration
* Weather dependency factor

✔️ Multilingual Support

* English
* Hindi
* Marathi
* Context-aware UI updates


🧪 Demo Testing

* Aadhaar: **Any 12-digit number**
* OTP: **123456**
* Sample 7/12 data included


🎯 Use Cases

* Small & marginal farmers
* Tenant farmers
* Rural entrepreneurs
* Banks & NBFCs
* Government institutions


⚙️ Technical Highlights

* Mobile-first UI
* Modular React architecture
* Clean & typed TypeScript
* High-speed development with Vite
* Scalable REST API


🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request


📄 License

This project is licensed under the **MIT License** — see the `LICENSE` file for details.


❤️ Built for India's Farming Community

⭐Star this repo:
[https://github.com/Vaishnavi252-ai/agricredit-score](https://github.com/Vaishnavi252-ai/Krishi-Sahay)

🐛Report a bug / Request feature:
[https://github.com/Vaishnavi252-ai/agricredit-score/issues](https://github.com/Vaishnavi252-ai/Krishi-Sahay/issues)
