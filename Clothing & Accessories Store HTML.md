```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>NOIRÉ — Clothing & Accessories</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      background: #f7f7f5;
      color: #111;
    }

    /* NAVBAR */
    nav {
      height: 75px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 0 6%;
      background: rgba(255,255,255,0.92);
      border-bottom: 1px solid #ddd;
      position: sticky;
      top: 0;
      z-index: 100;
      backdrop-filter: blur(10px);
    }

    .logo {
      font-size: 25px;
      font-weight: 800;
      letter-spacing: 4px;
    }

    nav ul {
      display: flex;
      list-style: none;
      gap: 35px;
    }

    nav a {
      text-decoration: none;
      color: #111;
      font-size: 14px;
      font-weight: 600;
    }

    nav a:hover {
      opacity: 0.5;
    }

    .cart {
      cursor: pointer;
      font-size: 14px;
      font-weight: bold;
    }

    /* HERO */
    .hero {
      min-height: 650px;
      background:
        linear-gradient(90deg, rgba(0,0,0,.65), rgba(0,0,0,.1)),
        url("https://images.unsplash.com/photo-144520517