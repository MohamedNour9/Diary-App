<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>مذكرات يومية</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <h1>مذكرات يومية</h1>
    <textarea id="diary-entry" placeholder="اكتب ملاحظاتك هنا..."></textarea>
    <button id="save-btn">حفظ الملاحظة</button>
    <div id="saved-entry">
      <h2>ملاحظتك المحفوظة:</h2>
      <p id="saved-text">لا توجد ملاحظات بعد.</p>
    </div>
  </div>
  <script src="script.js"></script>
</body>
</html>
