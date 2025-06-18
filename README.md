import React from "react";
import "./App.css";

function App() {
  return (
    <div className="app-root">
      {/* Header */}
      <header className="app-header">
        <div className="header-left">
          Thế giới di động
        </div>
        <div className="header-center">
          <svg height="18" width="18" fill="white" viewBox="0 0 24 24">
            <circle cx="12" cy="12" r="10" />
          </svg>
        </div>
      </header>
      {/* Main content here */}
    </div>
  );
}

export default App;.app-root {
  min-height: 100vh;
  background: #f5f5fa;
  font-family: 'Segoe UI', Arial, sans-serif;
}

.app-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background: linear-gradient(90deg, #5468ff 0%, #7a39fa 100%);
  height: 70px;
  padding: 0 28px;
  color: #fff;
  font-size: 2rem;
  font-weight: 700;
  box-shadow: 0 2px 8px #0002;
}

.header-left {
  font-size: 2rem;
  font-weight: bold;
}

.header-center {
  display: flex;
  align-items: center;
}{
  "name": "dong-store",
  "version": "1.0.0",
  "private": true,
  "dependencies": {
    "react": "^18.0.0",
    "react-dom": "^18.0.0",
    "react-scripts": "5.0.1"
  },
  "scripts": {
    "start": "react-scripts start"
  }
}
