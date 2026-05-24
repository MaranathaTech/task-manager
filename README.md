# Task Manager

A modern, full-stack task management application built with React, TypeScript, Node.js, and Express.

## Features

- ✅ Create, read, update, and delete tasks
- 🎯 Set task priorities (High, Medium, Low)
- 📊 Track task status (Pending, In Progress, Completed)
- 🔍 Filter tasks by status and priority
- 📈 Real-time task statistics dashboard
- 💅 Modern, responsive UI with Tailwind CSS
- 🔄 Real-time updates with optimistic UI
- 📱 Mobile-friendly design

## Technology Stack

### Frontend
- **React 18** with TypeScript
- **Tailwind CSS** for styling
- **Axios** for API communication
- **Lucide React** for icons
- **Create React App** for development setup

### Backend
- **Node.js** with Express
- **CORS** enabled for cross-origin requests
- **In-memory storage** (easily replaceable with database)
- **RESTful API** design
- **Environment configuration** with dotenv

## Quick Start

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/MaranathaTech/task-manager.git
   cd task-manager
   ```

2. **Install all dependencies**
   ```bash
   npm run install:all
   ```

3. **Start the application**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   - Frontend: http://localhost:3000
   - Backend API: http://localhost:5000

## API Endpoints

### Tasks
- `GET /api/tasks` - Get all tasks
- `GET /api/tasks/:id` - Get a specific task
- `POST /api/tasks` - Create a new task
- `PUT /api/tasks/:id` - Update a task
- `DELETE /api/tasks/:id` - Delete a task

### Health Check
- `GET /api/health` - API health status

## Available Scripts

### Root Directory
- `npm run dev` - Start both frontend and backend concurrently
- `npm run install:all` - Install dependencies for all projects

### Backend
- `npm start` - Start production server
- `npm run dev` - Start development server with nodemon

### Frontend
- `npm start` - Start development server
- `npm run build` - Build for production
- `npm test` - Run tests

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## License

MIT License - see LICENSE file for details.