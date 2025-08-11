# Visualize-JSON-data-via-HTML-table-using-Angular
Implement a html page in Angular showing a table of employees that are ordered by the total time worked. The table should show the Name, and the Total time worked. Color the table row if the employee worked less than 100 hours. The data for this task must be retrieved from a GET call on following API endpoint:



readme.md


# Full-Stack Angular + Node.js Project

A full-stack application with an **Angular 20.1.5** frontend and a **Node.js + TypeScript** backend.

---

## 📂 Structure
```
Angular/
 ├── backend/   # Node.js + TypeScript backend
 └── frontend/  # Angular frontend
```

---

## 🚀 Frontend (Angular)
**Start Dev Server**
```bash
cd Angular/frontend
npm install
ng serve
```
Visit: [http://localhost:4200](http://localhost:4200)  
Auto-reloads on file changes.

**Build for Production**
```bash
ng build
```

**Generate Component**
```bash
ng generate component component-name
```

**Run Tests**
```bash
ng test
```

---

## ⚙ Backend (Node.js + TypeScript)
**Start Server**
```bash
cd Angular/backend
npm install
npx ts-node server.ts
```
Default: [http://localhost:3000](http://localhost:3000)

**Build**
```bash
npm run build
```

---

## 🔗 Connecting Frontend & Backend
- Update API URLs in Angular services to point to backend host/port.

---

## 📦 Tech Stack
- **Frontend**: Angular 20.1.5, TypeScript, SCSS
- **Backend**: Node.js, Express.js, TypeScript


