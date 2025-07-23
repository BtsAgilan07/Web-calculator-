* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Segoe UI', sans-serif;
}

body {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background: #f3f4f6;
}

.calculator {
  background-color: #1f2937;
  padding: 20px;
  border-radius: 20px;
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
  width: 320px;
}

#display {
  width: 100%;
  height: 60px;
  border: none;
  border-radius: 10px;
  padding: 10px;
  font-size: 28px;
  text-align: right;
  margin-bottom: 15px;
  color: #111827;
}

.buttons {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 10px;
}

button {
  padding: 20px;
  font-size: 20px;
  border: none;
  border-radius: 10px;
  background-color: #374151;
  color: white;
  cursor: pointer;
  transition: background-color 0.3s ease;
}

button:hover {
  background-color: #4b5563;
}

.equal {
  grid-row: span 2;
  background-color: #10b981;
}

.equal:hover {
  background-color: #059669;
}

.zero {
  grid-column: span 2;
}
