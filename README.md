<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>สมัครงานกับเรา | Genius Traffic System</title>
  <style>
    body { font-family: 'Segoe UI', sans-serif; margin: 0; padding: 0; background: #f6f8fa; color: #333; }
    header { background: #007BFF; color: white; padding: 1rem; text-align: center; }
    section { padding: 2rem; max-width: 800px; margin: auto; background: white; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
    h1, h2 { color: #2d2d2d; }
    form { display: flex; flex-direction: column; gap: 1rem; margin-top: 1rem; }
    input, textarea, select { padding: 0.5rem; font-size: 1rem; border: 1px solid #ccc; border-radius: 4px; }
    button { background: #007BFF; color: white; padding: 0.75rem; font-size: 1rem; border: none; border-radius: 4px; cursor: pointer; }
    button:hover { background: #0056b3; }
    footer { text-align: center; padding: 1rem; font-size: 0.85rem; color: #666; }
  </style>
</head>
<body>
  <header>
    <h1>สมัครงานกับเรา</h1>
    <p>ร่วมเป็นส่วนหนึ่งกับทีม Genius Traffic System</p>
  </header>

  <section>
    <h2>กรอกแบบฟอร์มสมัครงาน</h2>
    <form action="https://formspree.io/f/maylazwp" method="POST" enctype="multipart/form-data">
      <input type="text" name="fullname" placeholder="ชื่อ-นามสกุล" required>
      <input type="email" name="email" placeholder="อีเมล" required>
      <input type="tel" name="phone" placeholder="เบอร์โทรศัพท์" required>
      <input type="text" name="position" placeholder="ตำแหน่งที่สนใจ" required>
      <textarea name="message" rows="4" placeholder="แนะนำตัว หรือข้อความเพิ่มเติม"></textarea>
      <label>แนบเรซูเม่ (PDF หรือ Word): <input type="file" name="resume" accept=".pdf,.doc,.docx"></label>
      <button type="submit">ส่งใบสมัคร</button>
    </form>
  </section>

  <footer>
    &copy; 2025 Genius Traffic System Co., Ltd. | พัฒนาโดยทีม HR
  </footer>
</body>
</html>
