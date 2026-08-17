<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Know N'Go</title>
<style>
  :root {
    --bg: #10151f;
    --panel: #171d29;
    --ink: #f2f3f5;
    --muted: #aeb6c2;
    --personal: #6fa287;
    --pro: #c97d4b;
  }
  * {
    box-sizing: border-box;
  }
  body {
    margin: 0;
    padding: 32px 20px 60px;
    background: var(--bg);
    color: var(--ink);
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
    line-height: 1.5;
  }
  .wrap {
    width: 100%;
    max-width: 760px;
    margin: 0 auto;
  }
  .wordmark {
    margin: 0;
    text-align: center;
    font-family: Georgia, "Times New Roman", serif;
    font-size: 2.2rem;
  }
  .tagline {
    margin: 6px 0 32px;
    text-align: center;
    color: var(--muted);
    font-size: 1.05rem;
  }
  .welcome {
    margin-bottom: 24px;
    padding: 24px;
    background: var(--panel);
    border-radius: 18px;
  }
  .welcome h2 {
    margin: 0 0 8px;
    font-size: 1.5rem;
  }
  .welcome p {
    margin: 0;
    color: var(--muted);
  }
  .actions {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 16px;
    margin-bottom: 28px;
  }
  .action {
    min-height: 120px;
    padding: 20px;
    border: 2px solid transparent;
    border-radius: 18px;
    background: var(--panel);
    color: var(--ink);
    font: inherit;
    font-size: 1.15rem;
    font-weight: 700;
    cursor: pointer;
  }
  .action:focus {
    outline: 4px solid #ffffff;
    outline-offset: 3px;
  }
  .personal {
    border