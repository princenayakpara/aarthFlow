# AarthFlow | Institutional SME Finance Platform

**Turn confirmed orders into instant working capital.**
AarthFlow is a high-fidelity B2B fintech platform designed to help Indian SMEs bridge the 60-90 day payment gap by converting confirmed invoices into immediate liquidity.

---

## 🔗 Project Submission Links

| Field | Link |
| :--- | :--- |
| 👨‍💻 **Developer** | Prince Nayakpara |
| 📧 **Email** | princepatel27507@gmail.com |
| 🎓 **GR Number** | 108692 |
| 🚀 **Live Deployed Project** | [frontend-six-chi-25.vercel.app](https://frontend-six-chi-25.vercel.app/) |
| 📺 **YouTube Demo Video** | *(Add your YouTube demo link here)* |
| 🎨 **Figma Design Prototype** | [View Figma Design](https://www.figma.com/proto/fUfE3lQEQJ6YcYi45y34Qi/Untitled?node-id=3-2&t=KaXFv4XrpfQQqE2m-1&starting-point-node-id=3%3A2) |
| 📬 **Postman API Documentation** | [View API Docs](https://documenter.getpostman.com/view/50464127/2sBXqKofEV) |
| ⚙️ **Backend API** | [api.aarthflow.com](https://api.aarthflow.com) |

---

## 🚩 Problem Statement

Small suppliers selling to large corporate buyers in India face a critical "working capital mismatch." While they must pay their own suppliers and employees within 30 days, their large corporate buyers often demand payment terms of 60 to 120 days. This creates a cash flow gap that forces SMEs to take expensive, high-interest loans (18-24% APR) just to keep operations running.

Large buyers often refuse to negotiate shorter cycles, leaving SMEs cash-starved despite having millions in confirmed, unpaid invoices.

## 💡 Solution

AarthFlow provides an **Institutional Treasury Interface** for SME founders and CFOs. It allows them to:
1.  **Visualize** their cash gaps in real-time.
2.  **Verify** invoices directly against buyer confirmations.
3.  **Access** institutional-grade financing (1.2% flat rate) within 24-48 hours.
4.  **Manage** institutional buyer risk through automated behavioral scoring.

---

## ✨ Key Features

| Feature | Description |
| :--- | :--- |
| **Institutional Dashboard** | A high-fidelity overview of treasury health, funded volume, and exposure at risk. |
| **Invoice Gap Visualizer** | Gantt-style timeline showing receivables vs. obligations side-by-side. |
| **Automated Verification** | Rapid verification of B2B invoices using institutional-grade risk engines. |
| **Direct Payouts** | Initiate and track payouts to vendor accounts directly from the platform. |
| **Buyer CRM** | Detailed tracking of counterparty payment behavior and credit limit utilization. |
| **PDF Reporting** | One-click export of institutional compliance and transaction reports. |
| **Mobile Responsive** | Fully optimized for all screen sizes, from 4K monitors to mobile devices. |
| **Secure Auth** | Multi-factor authentication (OTP) and JWT-based secure institutional access. |

---

## 🛠️ Tech Stack

**Frontend**
*   **React.js** (Vite)
*   **Vanilla CSS** (Custom Design System with CSS Variables)
*   **React Router Dom** (SPA Navigation)
*   **Context API** (State Management)

**Backend**
*   **Node.js & Express.js**
*   **MongoDB & Mongoose** (Database)
*   **JWT & BcryptJS** (Security)
*   **CORS & Dotenv** (Configuration)

---

## 📂 Folder Structure

```text
aarthFlow/
├── frontend/                 # React SPA (Vite)
│   ├── src/
│   │   ├── components/       # Reusable UI components (Sidebar, KPI Cards)
│   │   ├── context/          # State management (AuthContext)
│   │   ├── pages/            # View components (Dashboard, Landing, etc.)
│   │   ├── styles/           # Modular CSS system (responsive.css, tokens.css)
│   │   ├── utils/            # API wrappers and helper functions
│   │   ├── App.jsx           # Main router configuration
│   │   └── main.jsx          # Entry point
│   ├── index.html            # SEO-optimized entry
│   └── vite.config.js
├── backend/                  # Node.js REST API
│   ├── controllers/          # Request handlers
│   ├── middleware/           # Auth and error handling
│   ├── models/               # Mongoose schemas (User, Invoice, Buyer)
│   ├── routes/               # API endpoint definitions
│   ├── server.js             # Entry point
│   └── package.json          # Dependency and script management
└── README.md                 # Project documentation
```

---

## 📸 Project Screenshots

### 1. Institutional Dashboard
![Institutional Dashboard](./screenshot_dashboard.png)

### 2. Invoice Management
![Invoice Management](./screenshot_invoices.png)

### 3. Landing Page
![Landing Page](./screenshot_landing.png)

---

## 🚀 Getting Started

1.  **Clone the Repository**
    ```bash
    git clone https://github.com/your-username/aarthflow.git
    ```
2.  **Setup Backend**
    ```bash
    cd backend
    npm install
    # Create .env with MONGO_URI, PORT, and JWT_SECRET
    npm run dev
    ```
3.  **Setup Frontend**
    ```bash
    cd frontend
    npm install
    npm run dev
    ```

---

*Built for the SMEs that keep India running by Prince Nayakpara.*
