# StableGadgetsPK-
Mobile Accessories All in One Store 
index.html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>StableGadgetsPK - Insane Deals on Tech Gadgets 🔥</title>
<style>
  * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Poppins', 'Segoe UI', sans-serif; }
  body { background: #0a0a0f; color: #fff; overflow-x: hidden; }
  
  /* Animated background */
  body::before {
    content: ''; position: fixed; top: 0; left: 0; width: 100%; height: 100%;
    background: radial-gradient(circle at 20% 30%, rgba(255,71,87,0.15), transparent 40%),
                radial-gradient(circle at 80% 70%, rgba(0,212,255,0.15), transparent 40%);
    z-index: -1; animation: bgShift 10s ease-in-out infinite alternate;
  }
  @keyframes bgShift { 0% { transform: scale(1); } 100% { transform: scale(1.2); } }

  /* Top urgency bar */
  .top-bar {
    background: linear-gradient(90deg, #ff4757, #ff6348, #ff4757);
    background-size: 200% 100%;
    animation: gradientMove 3s linear infinite;
    padding: 10px; text-align: center; font-weight: 600; font-size: 0.9rem;
  }
  @keyframes gradientMove { 0% { background-position: 0% 50%; } 100% { background-position: 200% 50%; } }
  .top-bar span { display: inline-block; margin: 0 15px; }
  .pulse { animation: pulse 1s ease-in-out infinite; }
  @keyframes pulse { 0%,100% { opacity: 1; } 50% { opacity: 0.5; } }

  /* Header */
  header {
    padding: 20px 5%; display: flex; justify-content: space-between; align-items: center;
    background: rgba(10,10,15,0.9); backdrop-filter: blur(10px); position: sticky; top: 0; z-index: 100;
    border-bottom: 1px solid rgba(255,255,255,0.1);
  }
  .logo { font-size: 1.6rem; font-weight: 800; background: linear-gradient(90deg, #ff4757, #00d4ff); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
  .logo span { font-size: 1.8rem; }
  nav a { color: #ccc; margin-
