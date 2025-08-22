# Finland[Uploading 23 Jessye Ngai SRB.html.html…]()
<!DOCTYPE html>
<html lang="zh">
<head>
  <meta charset="UTF-8">
  <title>芬兰国家介绍</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #BACDFF;
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }

    header {
            height: 50vh;
            background: url('https://images.unsplash.com/photo-1583496667264-85d8dfe2b8b0?auto=format&fit=crop&w=1950&q=80') no-repeat center center/cover;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: #2973FF;
            text-align: center;
     }

     header h1 {
            font-size: 4rem;
            text-shadow: 2px 2px 10px rgba(0,0,0,0.5);
        }

     header p {
            font-size: 1.5rem;
            max-width: 600px;
            text-shadow: 1px 1px 8px rgba(0,0,0,0.5);
	}
	
     nav {
            position: fixed;
            top: 0;
            width: 100%;
            background: rgba(0,0,0,0.6);
            padding: 1rem 2rem;
            display: flex;
            justify-content: center;
            gap: 20px;
            z-index: 999;
        }
       nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #2962FF;
        }

    section {
      padding: 20px;
      max-width: 800px;
      margin: auto;
      background-color: white;
      margin-top: 20px;
      border-radius: 10px;
    }
    .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
        }
     .gallery img {
            width: 100%;
            height: 220px;
            object-fit: cover;
            border-radius: 10px;
            transition: transform 0.4s ease;
        }
      .gallery img:hover {
            transform: scale(1.05);
        }

    h2 {
      color: #A7A7FA;
    }

    footer {
      text-align: center;
      padding: 15px;
      background-color: #0B2D87;
      color: white;
      margin-top: 30px;
    }

/* https://www.w3schools.com/howto/howto_js_tabs.asp */
/* https://www.w3schools.com/howto/tryit.asp?filename=tryhow_js_tabs */


body {
      font-family: Arial;
      font-size: 17px;
}

/* Style the tab */
.tab {
  overflow: hidden;
  border:0px solid #A69494;
  background-color: #0023FA;
}

/* Style the buttons inside the tab */
.tab button {
  background-color: inherit;
  float: left;
  border: 2px;
  outline: 2px;
  cursor: pointer;
  padding: 14px 16px;
  transition: 0.3s;
  font-size: 18px;
  font-weight: bold;
  color: #D6E7FF;
}

/* Change background color of buttons on hover */
.tab button:hover {
  background-color: #3D7CFC;
}

/* Create an active/current tablink class */
.tab button.active {
  background-color: #739FF5;
}

/* Style the tab content */
.tabcontent {
  display: none;
  padding: 6px 12px;
  border: 1px solid #01215C;
  border-top: none;
}
  </style>
</head>
<body>

<nav>
    <a href="#location">地理位置</a>
    <a href="#culture">文化</a>
    <a href="#history">历史</a>
    <a href="#places">景点</a>
    <a href="#food">美食</a>
</nav>

  <header>
    <h1>芬兰 Finland</h1>
    <p>极光、森林与千湖之国</p>
  </header>

  <section id="location" class="section">
    <h2>📍 地理位置</h2>
<div class="tab">
  <button class="tablinks" onclick="openCity(event, '位置')">位置</button>
  <button class="tablinks" onclick="openCity(event, '主要岛屿')">主要岛屿</button>
  <button class="tablinks" onclick="openCity(event, '森林覆盖')">森林覆盖</button>
  <button class="tablinks" onclick="openCity(event, '首都')">首都</button>
  <button class="tablinks" onclick="openCity(event, '气候')">气候</button>
  <button class="tablinks" onclick="openCity(event, '邻国')">邻国</button>
</div>

<div id="位置" class="tabcontent">
    <p><ul type="disc">
	<li>位于北欧，北接北极圈</li>
	<li>东界俄罗斯，西临瑞典，南濒波罗的海</li>
    </ul></p>
</div>

<div id="主要岛屿" class="tabcontent">
    <p><ul type="disc">
	<li>拥有超过 55,000 个岛屿</li>
	<li>奥兰群岛是最大岛群，享有高度自治</li>
    </ul></p>
</div>

<div id="森林覆盖" class="tabcontent">
    <p><ul type="disc">
	<li>森林覆盖率约 75%</li>
	<li>树种以松树、云杉、白桦为主</li>
    </ul></p>
</div>

<div id="首都" class="tabcontent">
    <p><ul type="disc">
	<li>赫尔辛基位于南部沿海</li>
	<li>濒临波罗的海，是芬兰最大城市</li>
    </ul></p>
</div>

<div id="气候" class="tabcontent">
    <p><ul type="disc">
	<li>属寒带气候，冬季漫长寒冷</li>
	<li>夏季温和短暂，北部常见极昼和极夜</li>
    </ul></p>
</div>

<div id="邻国" class="tabcontent">
    <p><ul type="disc">
	<li>东界俄罗斯，西临瑞典</li>
	<li>南濒波罗的海</li>
    </ul></p>
</div>
</section>

  <section id="culture" class="section">
  <h2>🎉文化</h2>
    <div class="tab">
  <button class="tablinks" onclick="openCity(event, '自然与文化')">自然与文化</button>
  <button class="tablinks" onclick="openCity(event, '桑拿文化')">桑拿文化</button>
  <button class="tablinks" onclick="openCity(event, '设计与艺术')">设计与艺术</button>
  <button class="tablinks" onclick="openCity(event, '教育')">教育</button>
  <button class="tablinks" onclick="openCity(event, '传统节日')">传统节日</button>
  <button class="tablinks" onclick="openCity(event, '语言')">语言</button>
  <button class="tablinks" onclick="openCity(event, '手工艺品')">手工艺品</button>
</div>

<div id="自然与文化" class="tabcontent">
    <p><ul type="disc">
	<li>崇尚自然生活方式</li>
	<li>重视森林、湖泊、极地景观的保护</li>
    </ul></p>
</div>

<div id="桑拿文化" class="tabcontent">
    <p><ul type="disc">
	<li>几乎每个家庭都有桑拿房</li>
	<li>桑拿不仅用于清洁，也是一种社交活动</li>
    </ul></p>
</div>

<div id="设计与艺术" class="tabcontent">
    <p><ul type="disc">
	<li>赫尔辛基是世界设计之都</li>
	<li>芬兰设计风格简约、实用、注重自然元素</li>
    </ul></p>
</div>

<div id="教育" class="tabcontent">
    <p><ul type="disc">
	<li>教育体系被认为是全球最优秀之一</li>
	<li>注重平等、创造力和学生自主学习</li>
    </ul></p>
</div>

<div id="传统节日" class="tabcontent">
    <p><ul type="disc">
	<li>圣诞节：拉普兰是圣诞老人的家乡</li>
	<li>仲夏节：庆祝夏至，点燃篝火、在湖边聚会</li>
    </ul></p>
</div>

<div id="语言" class="tabcontent">
    <p><ul type="disc">
	<li>官方语言：芬兰语、瑞典语</li>
	<li>少数民族语言：萨米语</li>
    </ul></p>
</div>

<div id="手工艺品" class="tabcontent">
    <p><ul type="disc">
	<li>包括编织、陶艺、木雕</li>
	<li>风格注重自然材料与功能性</li>
    </ul></p>
</div>
</section>

<section id="history" class="section">
    <h2>🕰️ 历史</h2>
    <div class="tab">
  <button class="tablinks" onclick="openCity(event, '古代历史')">古代历史</button>
  <button class="tablinks" onclick="openCity(event, '瑞典统治')">瑞典统治</button>
  <button class="tablinks" onclick="openCity(event, '俄国统治')">俄国统治</button>
  <button class="tablinks" onclick="openCity(event, '独立与内战')">独立与内战</button>
  <button class="tablinks" onclick="openCity(event, '二战历史')">二战历史</button>
  <button class="tablinks" onclick="openCity(event, '冷战时期')">冷战时期</button>
  <button class="tablinks" onclick="openCity(event, '现代发展')">现代发展</button>
</div>

<div id="古代历史" class="tabcontent">
     <p><ul type="disc">
	<li>最早由芬兰-乌戈尔族群定居</li>
	<li>受邻近的斯堪的纳维亚与俄罗斯影响</li>
    </ul></p>
</div>

<div id="瑞典统治" class="tabcontent">
     <p><ul type="disc">
	<li>并入瑞典王国</li>
	<li>基督教传入，修建城堡和教堂</li>
    </ul></p>
</div>

<div id="俄国统治" class="tabcontent">
     <p><ul type="disc">
	<li>成为俄罗斯帝国的自治大公国</li>
	<li>首都从图尔库迁至赫尔辛基</li>
    </ul></p>
</div>

<div id="独立与内战" class="tabcontent">
     <p><ul type="disc">
	<li>1917年12月6日宣布独立</li>
	<li>1918年红白两派爆发内战，白军获胜</li>
    </ul></p>
</div>

<div id="二战历史" class="tabcontent">
     <p><ul type="disc">
	<li>冬季战争（1939–1940）：抵抗苏联入侵</li>
	<li>继续战争（1941–1944）：与德国合作对抗苏联</li>
    </ul></p>
</div>

<div id="冷战时期" class="tabcontent">
     <p><ul type="disc">
	<li>奉行中立政策（“芬兰化”）</li>
	<li>与苏联保持贸易与政治关系</li>
    </ul></p>
</div>

<div id="现代发展" class="tabcontent">
     <p><ul type="disc">
	<li>1995年加入欧盟</li>
	<li>高科技产业（如诺基亚）和福利制度闻名全球</li>
    </ul></p>
</div>
</section>

  <section id="places" class="section">
    <h2>🏰 景点</h2>
    <div class="gallery">
	<p>赫尔辛基（Helsinki）<img src="helsinki.jpg">
	<p>拉普兰（Lapland）<img src="lapland.jpg">
	<p>芬兰湖区（Lake District）<img src="lake district.jpg">
	<p>库萨莫（Kuusamo）<img src="kuusamo.jpg">
	<p>奥卢（Oulu）<img src="oulu.jpg">
	<p>阿尔托市（Alto City）<img src="alto city.jpg">
</div>
</section>

<section id="food" class="section">
   <h2>🫓 美食</h2>
    <div class="gallery">
	<p>卡累利阿饼（Karjalanpiirakka）<img src="Karjalanpiirakka.webp">
	<p>芬兰鲑鱼汤（Lohikeitto）<img src="Lohikeitto.jpg">
	<p>拉普兰炖鹿肉（Poronkäristys）<img src="Poronkäristys.jpg">
	<p>芬兰黑麦面包（Ruisleipä）<img src="Ruisleipä.jpg">
	<p>蓝莓派（Mustikkapiirakka）<img src="Mustikkapiirakka.jpg">
	<p>咸味甘草糖果（Salmiakki）<img src="Salmiakki.jpg">
</div>
</section>

  <footer>
    <p>© 2025 芬兰介绍网页</p>
  </footer>

<script>
function openCity(evt, cityName) {
  // Declare all variables
  var i, tabcontent, tablinks;

  // Get all elements with class="tabcontent" and hide them
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }

  // Get all elements with class="tablinks" and remove the class "active"
  tablinks = document.getElementsByClassName("tablinks");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }

  // Show the current tab, and add an "active" class to the button that opened the tab
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
}
</script>

</body>
</html>
