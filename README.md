<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>手机壁纸展示</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        h1 {
            text-align: center;
            color: #333;
            margin-bottom: 20px;
        }
        .wallpapers-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .wallpaper {
            background-color: #fff;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            max-width: 300px;
            width: 100%;
        }
        .wallpaper img {
            width: 100%;
            height: auto;
            display: block;
        }
        .description {
            padding: 10px;
            text-align: center;
            font-size: 1em;
            color: #555;
            background-color: #f9f9f9;
            border-top: 1px solid #ddd;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>手机壁纸展示</h1>
        <div class="wallpapers-grid">
            <div class="wallpaper">
                <img src="https://www.pexels.com/photo/sunset-over-snow-covered-mountains-1485213/" alt="雪山日落">
                <div class="description">雪山日落</div>
            </div>
            <div class="wallpaper">
                <img src="https://www.pexels.com/photo/lake-and-mountain-under-white-sky-1594186/" alt="湖泊和山脉">
                <div class="description">湖泊和山脉</div>
            </div>
            <div class="wallpaper">
                <img src="https://www.pexels.com/photo/blue-sea-under-clear-blue-sky-4477969/" alt="海洋和沙滩">
                <div class="description">海洋和沙滩</div>
            </div>
            <div class="wallpaper">
                <img src="https://www.pexels.com/photo/high-rise-buildings-during-nighttime-2519841/" alt="夜晚城市高楼">
                <div class="description">夜晚城市高楼</div>
            </div>
            <div class="wallpaper">
                <img src="https://www.pexels.com/photo/multicolored-abstract-painting-3827074/" alt="抽象艺术画">
                <div class="description">抽象艺术画</div>
            </div>
            <div class="wallpaper">
                <img src="https://www.pexels.com/photo/red-dahlia-flower-1819665/" alt="红色大丽花">
                <div class="description">红色大丽花</div>
            </div>
            <div class="wallpaper">
                <img src="https://www.pexels.com/photo/close-up-photo-of-brown-lion-3026336/" alt="棕色狮子">
                <div class="description">棕色狮子</div>
            </div>
            <div class="wallpaper">
                <img src="https://www.pexels.com/photo/gray-and-white-abstract-painting-2973774/" alt="灰白抽象画">
                <div class="description">灰白抽象画</div>
            </div>
            <div class="wallpaper">
                <img src="https://www.pexels.com/photo/brown-and-black-wolf-close-up-photography-1267304/" alt="狼的特写">
                <div class="description">狼的特写</div>
            </div>
            <div class="wallpaper">
                <img src="https://www.pexels.com/photo/close-up-photography-of-pink-petaled-flower-3471410/" alt="粉色花朵">
                <div class="description">粉色花朵</div>
            </div>
        </div>
    </div>
</body>
</html>
