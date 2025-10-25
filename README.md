<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Video Google Drive dengan Thumbnail</title>
  <style>
    .video-container {
      position: relative;
      width: 100%;
      max-width: 800px;
      aspect-ratio: 16 / 9;
      margin: auto;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
  </style>
</head>
<body>
  <div class="video-container">
    <video controls poster="https://i.ytimg.com/vi/_Xm6jy5Id7o/maxresdefault.jpg">
      <source src="https://drive.google.com/uc?export=preview&id=1NKqLT27YvsfIYPGGQxKy6amSFndDfuf3" type="video/mp4">
      Browser kamu tidak mendukung video tag.
    </video>
  </div>
</body>
</html>
