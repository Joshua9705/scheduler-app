# scheduler-app
11音控團隊排班表 - Serverless 排班系統 (Vercel + Turso)
# 複製新建立的 repo
git clone https://github.com/Joshua9705/scheduler-app.git
cd scheduler-app

# 移除預設檔案
rm README.md
{
  "name": "scheduler-app",
  "version": "1.0.0",
  "description": "11音控團隊排班表 - Serverless 排班系統 (Vercel + Turso)",
  "private": true,
  "scripts": {
    "dev": "next dev -p 3001",
    "build": "next build",
    "start": "next start",
    "lint": "next lint"
  },
  "dependencies": {
    "react": "^19.0.0",
    "react-dom": "^19.0.0",
    "next": "^16.0.0",
    "@libsql/client": "^0.14.0",
    "@dnd-kit/core": "^6.1.0",
    "@dnd-kit/sortable": "^8.0.0",
    "@dnd-kit/utilities": "^3.2.0",
    "@react-pdf/renderer": "^3.3.8",
    "date-fns": "^3.0.0",
    "clsx": "^2.0.0"
  },
  "devDependencies": {
    "typescript": "^5.3.3",
    "@types/node": "^20.10.0",
    "@types/react": "^18.2.42",
    "@types/react-dom": "^18.2.17",
    "tailwindcss": "^4.0.0",
    "postcss": "^8.4.31",
    "autoprefixer": "^10.4.16",
    "@typescript-eslint/eslint-plugin": "^6.13.2",
    "@typescript-eslint/parser": "^6.13.2",
    "eslint": "^8.55.0",
    "eslint-config-next": "^16.0.0"
  }
}
