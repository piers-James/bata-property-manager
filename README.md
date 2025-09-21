# BATA Property Manager

🏠 **BATA Property Manager** is a SaaS-style web application designed to track properties, tenants, rental payments, and maintenance requests — all from a clean, central dashboard.  

This project demonstrates a **full CRUD dashboard** with multiple modules, making it a strong foundation for SaaS products in property, asset, or client management.

---

## 📊 Features
- **Dashboard Overview**  
  - Displays total properties, available units, monthly revenue, and outstanding payments.  
- **Properties Management**  
  - Add, edit, delete, and track property details.  
- **Payments Tracking**  
  - Record rental payments, track due dates, and mark as Paid / Pending / Overdue.  
- **Maintenance Requests**  
  - Log repair issues, set priority levels, and track status (Pending, In Progress, Completed).  
- **Recent Activity Panels**  
  - Quick view of payments and maintenance requests directly from the dashboard.  

---

## 📸 Screenshots

| Dashboard | Properties | Payments | Maintenance | Dashboard + Maintenance |
| :-: | :-: | :-: | :-: | :-: |
| ![Dashboard](./docs/screenshots/dashboard.png) | ![Properties](./docs/screenshots/properties.png) | ![Payments](./docs/screenshots/payments.png) | ![Maintenance](./docs/screenshots/maintenance.png) | ![Dashboard + Maintenance](./docs/screenshots/dashboardmaintenance.png) |


---

## 📂 Repo Structure

bata-property-manager/
│
├── app/                     # Core application logic
│   ├── models/              # Database models (Properties, Payments, Requests)
│   ├── routes/              # API endpoints
│   ├── templates/           # HTML templates (Jinja/React components)
│   └── static/              # CSS, JS, images
│
├── docs/screenshots/        # Project screenshots for README
├── tests/                   # Unit and integration tests
│
├── .gitignore
├── LICENSE
├── README.md
└── requirements.txt         # Dependencies

## 🚀 Getting Started

Follow these steps to run the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/piers-James/bata-property-manager.git
   cd bata-property-manager

   ```

2. **Set up a virtual environment (recommended)**
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate

    ```
   
3. **Install dependencies**
   ```bash
   pip install -r requirements.txt

   ```

4. **Run the application**
   ```bash
   python app/main.py

 ---

## 🤝 Contributing  
Contributions are welcome!  
- Fork the repo  
- Create a new branch (`git checkout -b feature-name`)  
- Commit your changes  
- Open a pull request  

---

## 📄 License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.



