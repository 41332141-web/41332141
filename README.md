# 41332141
本網站以 Nothing 品牌耳機為主題，介紹 Nothing 品牌的設計理念、品牌特色、耳機產品種類、外觀設計、音質表現與功能特色，並分享不同耳機產品的介紹與比較，讓使用者更加認識 Nothing 耳機的獨特魅力。
nothing-website/
│
├── index.html
├── products.html
├── ear.html
├── ear-a.html
├── headphone.html
├── features.html
└── about.html

<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nothing 耳機網站</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, "Microsoft JhengHei", sans-serif;
            background-color: #f5f5f5;
        }

        /* 導覽列 */
        #centeredmenu {
            width: 100%;
            background-color: black;
            text-align: center;
        }

        #centeredmenu ul {
            list-style: none;
            display: inline-flex;
        }

        #centeredmenu ul li {
            position: relative;
        }

        #centeredmenu ul li a {
            display: block;
            padding: 20px 30px;
            color: white;
            text-decoration: none;
            font-size: 16px;
        }

        #centeredmenu ul li a:hover {
            background-color: #444;
        }

        /* 下拉式選單 */
        #centeredmenu ul li ul {
            display: none;
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 180px;
            background-color: black;
            flex-direction: column;
            z-index: 1000;
        }

        #centeredmenu ul li:hover ul {
            display: flex;
        }

        #centeredmenu ul li ul li a {
            padding: 15px;
            text-align: left;
        }

        /* 網頁內容 */
        .content {
            text-align: center;
            padding: 100px 20px;
        }

        h1 {
            font-size: 50px;
            letter-spacing: 8px;
        }

        p {
            margin-top: 20px;
            font-size: 18px;
        }
    </style>
</head>

<body>

    <nav id="centeredmenu">
        <ul>

            <li>
                <a href="index.html">首頁</a>
            </li>

            <li>
                <a href="products.html">耳機系列 ▾</a>

                <ul>
                    <li>
                        <a href="ear.html">Nothing Ear</a>
                    </li>

                    <li>
                        <a href="ear-a.html">Nothing Ear (a)</a>
                    </li>

                    <li>
                        <a href="headphone.html">Headphone (1)</a>
                    </li>
                </ul>
            </li>

            <li>
                <a href="features.html">產品特色</a>
            </li>

            <li>
                <a href="about.html">關於品牌</a>
            </li>

        </ul>
    </nav>

    <div class="content">
        <h1>NOTHING</h1>
        <p>讓科技回歸簡單，展現設計的純粹。</p>
    </div>

</body>
</html>
