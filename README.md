# 📊 ChartBoard

## 📢 Introduction 
**ChartBoard** — A data visualization web service that transforms SQL query results into various charts and manages them at a glance through customizable dashboards.

<img width="1639" height="760" alt="image" src="https://github.com/user-attachments/assets/0c86c8af-7048-4979-83a6-59edc9d8af8b" />


## 📝 Service Overview
ChartBoard is a data visualization tool designed to help users manage data intuitively. By inputting SQL queries, users can visualize results in various chart formats and add them to personalized dashboards for efficient data monitoring.



## 👥 Developer

| Name   | Role         |
|--------|--------------|
| Chaeyeon Kwak | Full-stack development |


## 🛠 Tech Stack

- **Frontend**: React, TypeScript  
- **Backend**: Spring Boot  
- **Database**: MariaDB  


## 📁 Key File Structure
```
chartboardproject/
├── public/
│ └── (Logo Images)
│
├── src/
│ ├── api/
│ │ └── chartboardApi.ts
│ │
│ ├── assets/
│ │ └── (Logo Images)
│ │
│ ├── layouts/
│ │ └── ChartBoardLayout.tsx
│ │
│ ├── pages/
│ │ ├── collections/
│ │ │ ├── CollectionMainPage.tsx
│ │ │ ├── CollectionChartListPage.tsx
│ │ │ ├── CollectionDashboardListPage.tsx
│ │ │ ├── RowToChartPage.tsx
│ │ │ └── RowToDashboard.tsx
│ │ │
│ │ ├── customSqlSearch/
│ │ │ └── CustomSqlSearchPage.tsx
│ │ │
│ │ └── user/
│ │ ├── LoginPage.tsx
│ │ ├── SignupPage.tsx
│ │ ├── ConnectDbPage.tsx
│ │ └── MyPage.tsx
│ │
│ ├── router/
│ │ └── router.tsx
│ │
│ ├── App.css
│ ├── App.tsx
│ ├── index.css
│ └── main.tsx
│
└── index.html
```


## 📌 Key Features

### ✅ SQL Query Execution
- Input SELECT statements: Instantly visualize query results via tables and various chart types (Bar, Line, Scatter).
- Save Charts: Store generated charts for future use.

### 📋 Dashboard Management
- Organize: Place saved charts onto a centralized dashboard.
- Customization: Adjust chart positions and sizes using Drag & Resize functionality.

![BI Tool dashboard gif](https://github.com/user-attachments/assets/803b6419-5488-4538-8030-2de71687bbe7)

## 🚀 Getting Started (Local Execution)
⚙️ The backend server must be running simultaneously for data to be displayed correctly.

```bash
# Clone the repository
git clone https://github.com/kwak513/chart-board-front.git

# Navigate to the directory
cd chart-board-front

# Install dependencies
npm install

# Run the development server
npm run dev
```
## 🧩 Related Repositories
**Backend**: [Link to Backend Repo](https://github.com/kwak513/chart-board-back)


