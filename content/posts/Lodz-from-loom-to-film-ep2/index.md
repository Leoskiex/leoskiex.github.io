---
title: "WOW!羅茲 Łódź - 從紡織機💥到電影鏡頭 下集🎬"
date: '2025-04-28T11:16:07+02:00'
showRelatedContent: false
draft: false
layout: "simple"
tags : ['羅茲','紡織','電影','波蘭','播客']

---
{{< spotify "https://open.spotify.com/embed/episode/44zN3gnbqKW6gUlR3PjCOo?utm_source=generator&theme=0" >}}

{{<raw>}}

<!DOCTYPE html>
<html lang="zh-CN" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>羅茲: 織機到鏡頭的波普變奏曲!</title>
    <link href="https://lf3-cdn-tos.bytecdntp.com/cdn/expire-1-M/tailwindcss/2.2.19/tailwind.min.css" rel="stylesheet">
    <link href="https://lf6-cdn-tos.bytecdntp.com/cdn/expire-100-M/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Serif+SC:wght@400;500;700&family=Noto+Sans+SC:wght@300;400;500;700&family=Noto+Sans+TC:wght@300;400;500;700&family=Noto+Serif+TC:wght@400;500;700&display=swap" rel="stylesheet">
    <style>
        /* --- Base Styles & Fonts --- */
        body {
            font-family: 'Noto Sans TC', 'Noto Sans SC', Tahoma, Arial, Roboto, "Droid Sans", "Helvetica Neue", "Droid Sans Fallback", "Heiti SC", "Hiragino Sans GB", Simsun, sans-serif;
            @apply bg-white text-black transition-colors duration-300;
            /* Basic Halftone Dot Simulation for background - adjust as needed */
            background-image: radial-gradient(rgba(0, 0, 0, 0.1) 1px, transparent 1px);
            background-size: 8px 8px;
        }
        .dark body {
            @apply bg-gray-900 text-white;
            background-image: radial-gradient(rgba(255, 255, 255, 0.1) 1px, transparent 1px);
            background-size: 8px 8px;
        }

        h1, h2, h3, .font-serif {
            font-family: 'Noto Serif TC', 'Noto Serif SC', Georgia, 'Times New Roman', Times, serif;
        }

        /* --- Pop Art Style Elements --- */
        .pop-border {
            @apply border-4 border-black;
        }
        .pop-shadow {
            box-shadow: 8px 8px 0px black;
            @apply transition-shadow duration-200;
        }
        .dark .pop-shadow {
             box-shadow: 8px 8px 0px #FFFF00; /* Yellow shadow in dark mode */
        }
        .pop-card {
            @apply bg-white p-6 pop-border pop-shadow rounded-none mb-8; /* No rounded corners for classic Pop Art */
        }
        .dark .pop-card {
            @apply bg-gray-800;
        }

        .pop-bg-red { @apply bg-red-500; }
        .pop-bg-yellow { @apply bg-yellow-400; }
        .pop-bg-blue { @apply bg-blue-500; }
        .pop-text-red { @apply text-red-500; }
        .pop-text-yellow { @apply text-yellow-400; }
        .pop-text-blue { @apply text-blue-500; }

        .pop-outline-text {
            /* Simple text stroke simulation */
            text-shadow: -1px -1px 0 #000, 1px -1px 0 #000, -1px 1px 0 #000, 1px 1px 0 #000;
        }
        .dark .pop-outline-text-dark {
            text-shadow: -1px -1px 0 #FFF, 1px -1px 0 #FFF, -1px 1px 0 #FFF, 1px 1px 0 #FFF;
        }

        /* --- Comic Elements --- */
        .speech-bubble {
            @apply relative bg-blue-500 text-white p-4 border-4 border-black font-bold my-4;
            border-radius: .4em;
        }
        .speech-bubble:after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            width: 0;
            height: 0;
            border: 20px solid transparent;
            border-top-color: #3B82F6; /* Match bg-blue-500 */
            border-bottom: 0;
            border-left: 0;
            margin-left: -10px;
            margin-bottom: -20px;
            border-left-width: 1px; /* Make tail sharper */
             border-right-width: 1px;
             border-top-width: 21px;
             border-bottom-width: 0;

            /* Black outline for the tail */
             filter: drop-shadow(0 4px 0 black);

        }
         .dark .speech-bubble {
              @apply bg-yellow-400 text-black;
         }
         .dark .speech-bubble:after {
            border-top-color: #F59E0B; /* Match bg-yellow-400 */
             filter: drop-shadow(0 4px 0 black);
         }


        .explosion {
             @apply relative inline-block pop-bg-red text-white font-black p-4 m-4 pop-border;
             clip-path: polygon(0% 20%, 15% 22%, 18% 0%, 25% 18%, 40% 10%, 50% 25%, 60% 10%, 75% 18%, 82% 0%, 85% 22%, 100% 20%, 90% 50%, 100% 80%, 85% 78%, 82% 100%, 75% 82%, 60% 90%, 50% 75%, 40% 90%, 25% 82%, 18% 100%, 15% 78%, 0% 80%, 10% 50%);
             transform: rotate(-5deg);
             min-width: 100px; text-align: center;
         }
        .dark .explosion {
            @apply pop-bg-yellow text-black;
        }


        /* --- Scroll Animation --- */
        .reveal {
            opacity: 0;
            transform: translateY(30px);
            transition: opacity 0.6s ease-out, transform 0.6s ease-out;
        }
        .reveal.visible {
            opacity: 1;
            transform: translateY(0);
        }

        /* --- Mermaid Pop Art Styling --- */
        .mermaid-container { @apply p-4 pop-border bg-white mb-8 pop-shadow; }
        .dark .mermaid-container { @apply bg-gray-800; }

        /* General Node Styling */
        .dark #mermaid-render-output .node rect,
        .dark #mermaid-render-output .node circle,
        .dark #mermaid-render-output .node polygon,
        #mermaid-render-output .node rect,
        #mermaid-render-output .node circle,
        #mermaid-render-output .node polygon {
            stroke: #000 !important;
            stroke-width: 4px !important;
        }
        .dark #mermaid-render-output .node rect,
        .dark #mermaid-render-output .node circle,
        .dark #mermaid-render-output .node polygon {
             stroke: #FFF !important; /* White stroke in dark mode */
        }


        /* Specific Class Styling */
        #mermaid-render-output .popPrimary > rect { fill: #F59E0B !important; /* Yellow */ color: black !important; }
        #mermaid-render-output .popSecondary > rect { fill: #EF4444 !important; /* Red */ color: white !important; }
        #mermaid-render-output .popTertiary > rect { fill: #3B82F6 !important; /* Blue */ color: white !important; }
        #mermaid-render-output .popHighlight > rect { fill: #FFFFFF !important; color: black !important; stroke-dasharray: 5 5 !important; stroke-width: 3px !important;}

        .dark #mermaid-render-output .popPrimary > rect { fill: #F59E0B !important; color: black !important; }
        .dark #mermaid-render-output .popSecondary > rect { fill: #EF4444 !important; color: white !important; }
        .dark #mermaid-render-output .popTertiary > rect { fill: #3B82F6 !important; color: white !important; }
        .dark #mermaid-render-output .popHighlight > rect { fill: #374151 !important; /* Dark Gray */ color: white !important; stroke-dasharray: 5 5 !important; stroke-width: 3px !important;}


        /* Text Styling */
        #mermaid-render-output .node .nodeLabel { font-weight: bold !important; font-family: 'Noto Sans TC', 'Noto Sans SC', sans-serif !important; }
        #mermaid-render-output .popPrimary .nodeLabel { color: black !important; }
        #mermaid-render-output .popSecondary .nodeLabel { color: white !important; }
        #mermaid-render-output .popTertiary .nodeLabel { color: white !important; }
        #mermaid-render-output .popHighlight .nodeLabel { color: black !important; }


        .dark #mermaid-render-output .popPrimary .nodeLabel { color: black !important; }
        .dark #mermaid-render-output .popSecondary .nodeLabel { color: white !important; }
        .dark #mermaid-render-output .popTertiary .nodeLabel { color: white !important; }
        .dark #mermaid-render-output .popHighlight .nodeLabel { color: white !important; }


        /* Edge Styling */
        #mermaid-render-output .edgePath path {
            stroke: #000 !important;
            stroke-width: 3px !important;
        }
         .dark #mermaid-render-output .edgePath path {
             stroke: #FFF !important; /* White edges in dark mode */
         }
        #mermaid-render-output .edgeLabel {
             background-color: white !important;
             color: black !important;
             font-weight: bold !important;
             border: 2px solid black !important;
             padding: 2px 4px !important;
        }
         .dark #mermaid-render-output .edgeLabel {
             background-color: #1F2937 !important; /* Dark background for labels */
             color: white !important;
             border: 2px solid white !important;
         }

         /* Subgraph Title Styling */
        #mermaid-render-output .subgraph-title {
             font-family: 'Noto Serif TC', 'Noto Serif SC', serif !important;
             font-size: 1.1em !important;
             font-weight: bold !important;
             fill: #000 !important;
         }
        .dark #mermaid-render-output .subgraph-title {
             fill: #FFF !important;
         }
         #mermaid-render-output .subgraph rect {
            stroke: #000 !important;
            stroke-width: 2px !important;
            fill: rgba(0,0,0,0.05) !important; /* Light grey fill for subgraph */
            stroke-dasharray: 10 5 !important;
         }
         .dark #mermaid-render-output .subgraph rect {
            stroke: #FFF !important;
             fill: rgba(255,255,255,0.1) !important; /* Lighter grey fill for subgraph */
         }


    </style>
</head>
<body class="pt-16">

    <!-- Theme Switcher -->
    <button id="theme-toggle" class="fixed top-4 right-4 z-50 p-2 rounded-full pop-border pop-bg-yellow text-black dark:pop-bg-blue dark:text-white focus:outline-none transition-transform duration-200 active:scale-90 pop-shadow">
        <i class="fas fa-sun text-xl hidden dark:inline"></i>
        <i class="fas fa-moon text-xl inline dark:hidden"></i>
    </button>

    <!-- Hero Section -->
    <header class="pop-bg-yellow py-16 px-4 text-center pop-border border-b-8 border-black relative overflow-hidden">
         <!-- Decorative Dots -->
        <div class="absolute top-0 left-0 w-full h-full" style="background-image: radial-gradient(rgba(0, 0, 0, 0.3) 2px, transparent 2px); background-size: 15px 15px; opacity: 0.5;"></div>

        <div class="relative z-10">
            <h1 class="text-5xl md:text-7xl font-black text-black pop-outline-text mb-4 uppercase" style="letter-spacing: 2px;">
                <span class="pop-text-red">羅茲</span><span class="pop-text-blue">!</span>
            </h1>
            <h2 class="text-3xl md:text-5xl font-bold text-black pop-outline-text mb-6 uppercase">
                從<i class="fas fa-cog mx-1 text-red-500"></i>織機<i class="fas fa-cog mx-1 text-red-500"></i>到<i class="fas fa-film mx-1 text-blue-500"></i>鏡頭<i class="fas fa-film mx-1 text-blue-500"></i>的城市變奏!
            </h2>
            <p class="text-lg md:text-xl text-black font-semibold max-w-3xl mx-auto bg-white p-4 pop-border inline-block pop-shadow">
                歡迎回來羅茲的故事下集。今天，帶你走進波蘭羅茲的故事。一個關於轉型，從紡織帝國到銀幕傳奇，在崩潰邊緣又在電影魔法中重生的震撼故事! <span class="text-red-600 font-bold text-2xl">WOW!</span>
            </p>
        </div>
    </header>

    <main class="container mx-auto px-4 py-8 md:py-12">

        <!-- Section 1: The Rise (Textile Boom) -->
        <section class="mb-12 reveal">
            <div class="pop-card pop-bg-red text-white">
                 <h3 class="text-4xl font-black mb-4 pop-outline-text uppercase flex items-center">
                     <i class="fas fa-industry text-yellow-400 text-3xl mr-3"></i> 19世紀: 煙囪之城! <span class="text-yellow-400 ml-2">崛起!</span>
                 </h3>
                 <p class="text-lg mb-4">19世紀的羅茲，從泥濘村莊<strong class="pop-text-yellow">爆炸性</strong>成長為「波蘭的曼徹斯特」。俄羅斯關稅、廣闊土地、政府推動，點燃了工業野心。</p>
                 <div class="grid md:grid-cols-2 gap-6 text-black">
                     <div class="bg-yellow-400 p-4 pop-border border-black">
                         <h4 class="text-2xl font-bold mb-2 flex items-center"><i class="fas fa-chess-king mr-2"></i> 工業巨頭</h4>
                         <p>伊茲雷爾·波茲南斯基的<strong class="text-red-600">曼努法克圖拉</strong> (7000台織機!) 和卡羅爾·謝布勒的<strong class="text-red-600">克謝日·穆溫</strong> (工廠、宿舍、醫院...)，如同城中之城，紅磚帝國拔地而起!</p>
                     </div>
                     <div class="bg-blue-500 p-4 pop-border border-black text-white">
                         <h4 class="text-2xl font-bold mb-2 flex items-center"><i class="fas fa-users mr-2"></i> 多元熔爐</h4>
                         <p>波蘭人、德國人、猶太人湧入，在彼得科夫斯卡街形成<strong class="pop-text-yellow">充滿活力卻緊張</strong>的多語言文化。光輝背後是工人的血汗...</p>
                     </div>
                 </div>
                 <p class="mt-4 text-lg">工人每天勞作14-16小時，噪音震耳，「褐肺病」蔓延，童工在危險機器下爬行。公寓裡十人一間，霍亂肆虐。弗拉迪斯瓦夫·雷蒙特的小說<strong class="pop-text-yellow">《應許之地》</strong>捕捉了這驚人的貧富分化、野心與絕望。</p>
            </div>
             <div class="text-center -mt-4">
                 <span class="explosion pop-bg-yellow text-black dark:pop-bg-red dark:text-white">BOOM!</span>
             </div>
        </section>

        <!-- Section 2: The Fall (Decline) -->
        <section class="mb-12 reveal">
             <div class="pop-card bg-blue-700 text-white">
                 <h3 class="text-4xl font-black mb-4 pop-outline-text uppercase flex items-center">
                    <i class="fas fa-star text-red-500 text-3xl mr-3"></i> 20世紀: 巨輪停轉 <span class="text-red-500 ml-2">衰落!</span>
                 </h3>
                 <p class="text-lg mb-4">巨型機器無法永遠運轉。一戰、邊界變動、新經濟現實帶來動盪。共產主義下工廠苟延殘喘，但火焰漸熄。</p>
                 <p class="text-lg font-bold mb-4">1989年共產主義垮台，國營工廠無法競爭，<strong class="pop-text-yellow">紛紛關閉!</strong> 失業率飆升至20%，人們離開。紅磚工廠寂靜，煙囪如墓碑聳立。城市失去身份，陷入空虛。</p>
                 <div class="text-center my-4">
                    <i class="fas fa-ghost text-6xl text-yellow-400 opacity-80"></i>
                    <p class="font-bold mt-2 pop-text-yellow">蒸汽與線的幽靈...</p>
                 </div>
            </div>
        </section>

        <!-- Section 3: The Turn (Film School) -->
        <section class="mb-12 reveal">
             <div class="pop-card pop-bg-yellow text-black">
                 <h3 class="text-4xl font-black mb-4 pop-outline-text uppercase flex items-center">
                     <i class="fas fa-film text-blue-500 text-3xl mr-3"></i> 轉捩點: 電影之光! <span class="text-blue-500 ml-2">重生?</span>
                 </h3>
                 <p class="text-lg mb-4">就在崩潰時刻，非凡轉變發生! 二戰後，華沙電影中心化為廢墟，電影產業看向<strong class="text-blue-600">羅茲</strong>——因為它<strong class="text-red-600">還在</strong>! 建築、工廠、別墅尚存。</p>
                 <p class="text-lg font-bold mb-4">1948年，<strong class="text-red-600">羅茲電影學校</strong>成立! 在舊德國學校建築內，用拼湊的椅子、配給的膠片，創造非凡。街道、庭院、衰敗的工業景觀，成為課堂與片場。</p>
                 <div class="speech-bubble">
                    培養了改變波蘭電影的人才：安傑伊·瓦伊達、羅曼·波蘭斯基、克日什托夫·基耶斯洛夫斯基! <span class="text-yellow-300 text-2xl">WOW!</span>
                 </div>
                 <p class="text-lg">他們捕捉城市的粗獷與情緒，催生了「波蘭電影學派」——道德複雜、直面現實。故事片製片廠也在改建的紡織倉庫中運作。城市不僅是背景，它的<strong class="text-red-600">物質結構</strong>促成了這波電影新浪潮!</p>
             </div>
        </section>

        <!-- Section 4: Łódź on Screen -->
        <section class="mb-12 reveal">
            <h3 class="text-4xl font-black text-center mb-8 pop-text-red dark:pop-text-yellow pop-outline-text dark:pop-outline-text-dark uppercase">
                <i class="fas fa-video mr-2"></i> 羅茲登上銀幕 <i class="fas fa-star ml-2"></i>
            </h3>
            <div class="grid md:grid-cols-2 gap-8">
                <div class="pop-card">
                    <h4 class="text-3xl font-bold mb-3 pop-text-blue flex items-center"><i class="fas fa-landmark mr-2"></i> 《應許之地》</h4>
                    <p class="text-lg mb-3"><strong class="text-red-600">瓦伊達 (1975):</strong> 羅茲的電影紀念碑! 改編自雷蒙特小說，捕捉19世紀工業熱潮。在<strong class="text-blue-600">真實場景</strong> (謝布勒宮、波茲南斯基宮、曼努法克圖拉) 拍攝，將羅茲基因編織進每一幀。</p>
                    <p class="text-lg mb-3">用1870年代機器，噪音震耳。1500名當地臨時演員參與，營造<strong class="text-red-600">「幽靈般的真實主義」</strong>。對比視覺捕捉規模與人力成本。批判資本主義，獲奧斯卡提名。<strong class="text-blue-600">羅茲不是布景，是根基!</strong></p>
                    <div class="text-center mt-4"><i class="fas fa-medal text-4xl pop-text-yellow"></i></div>
                </div>
                <div class="pop-card">
                    <h4 class="text-3xl font-bold mb-3 pop-text-red flex items-center"><i class="fas fa-cross mr-2"></i> 《修女艾達》</h4>
                    <p class="text-lg mb-3"><strong class="text-blue-600">帕夫利科夫斯基 (2014):</strong> 呈現羅茲的另一面。黑白電影，捕捉<strong class="text-red-600">「時光凍結的樸素」</strong>。避開宏偉遺跡，尋找戰後傷痕與寂靜。</p>
                    <p class="text-lg mb-3">剝落公寓、濕潤鵝卵石、褪色別墅成為背景。歐洲最大的<strong class="text-blue-600">猶太公墓</strong>承載揪心場景，捕捉悲傷與克制。4:3畫面如老照片，靜態鏡頭讓城市質感觸手可及。贏得<strong class="text-red-600">奧斯卡最佳外語片!</strong></p>
                     <div class="text-center mt-4"><i class="fas fa-award text-4xl pop-text-yellow"></i></div>
                </div>
            </div>
            <p class="text-center text-lg mt-6 font-semibold pop-outline-text dark:pop-outline-text-dark">大衛·林奇的<strong class="pop-text-blue">《內陸帝國》</strong>、<strong class="pop-text-red">《瑪麗·居里》</strong>、紀錄片... 羅茲持續在銀幕上講述多篇章的故事! <span class="text-2xl pop-text-yellow">🎬</span></p>
        </section>

         <!-- Section 5: Revival -->
        <section class="mb-12 reveal">
             <div class="pop-card pop-bg-green-500 text-white" style="background-color: #10B981;"> <!-- Custom Green for variety -->
                 <h3 class="text-4xl font-black mb-4 pop-outline-text uppercase flex items-center">
                     <i class="fas fa-recycle text-yellow-400 text-3xl mr-3"></i> 從鏽跡到光芒! <span class="text-yellow-400 ml-2">復興!</span>
                 </h3>
                 <p class="text-lg mb-4">電影聲譽如何影響實體城市? 1989年後市場崩潰，工廠空置，失業嚴重。但<strong class="pop-text-yellow">復興種子</strong>在90年代末萌芽。遺產引領復興，優先保存工業遺址。</p>
                 <div class="grid md:grid-cols-2 gap-6 text-black mt-6">
                     <div class="bg-yellow-400 p-4 pop-border border-black">
                         <h4 class="text-2xl font-bold mb-2 flex items-center"><i class="fas fa-building mr-2 text-red-600"></i> 曼努法克圖拉</h4>
                         <p>2006年，波茲南斯基的紅磚帝國以<strong class="text-red-600">2.7億歐元</strong>翻新! 融合舊磚牆與現代玻璃。現有商店、電影院、博物館、餐廳... 每年吸引<strong class="text-blue-600">2000萬</strong>遊客! 從工業勞動到文化休閒的<strong class="text-red-600">驚人轉型!</strong></p>
                     </div>
                     <div class="bg-blue-500 p-4 pop-border border-black text-white">
                         <h4 class="text-2xl font-bold mb-2 flex items-center"><i class="fas fa-paint-brush mr-2 text-yellow-400"></i> OFF 彼得科夫斯卡</h4>
                         <p>2011年，藝術家復興舊毛廠。庭院充滿塗鴉、小酒館、科技音樂。50家<strong class="pop-text-yellow">創意企業</strong>取代舊工人。當地人稱其為<strong class="text-yellow-300">「羅茲的柏林」</strong>!</p>
                     </div>
                 </div>
                  <p class="text-lg mt-6 font-bold">2017年，羅茲成為<strong class="pop-text-yellow">聯合國教科文組織電影之城!</strong> <i class="fas fa-trophy text-yellow-400"></i> 慶祝電影博物館、國家電影文化中心、電影學校、電影節、電影基金五大支柱。電影旅遊興旺!</p>
             </div>
              <div class="text-center -mt-4">
                 <span class="explosion pop-bg-blue text-white dark:pop-bg-yellow dark:text-black">ZAP!</span>
             </div>
        </section>

        <!-- Section 6: Mermaid Visualization -->
        <section class="mb-12 reveal">
            <h3 class="text-4xl font-black text-center mb-6 pop-text-blue dark:pop-text-yellow pop-outline-text dark:pop-outline-text-dark uppercase">
               <i class="fas fa-project-diagram mr-2"></i> 羅茲的轉型之路!
            </h3>
            <div class="mermaid-container">
                 <div id="mermaid-render-output" class="mermaid flex justify-center items-center min-h-[400px]">
                     <!-- Mermaid chart will be rendered here -->
                     <p class="text-center font-bold text-lg">正在加載視覺化圖表... <i class="fas fa-spinner fa-spin ml-2"></i></p>
                </div>
            </div>
            <!-- Mermaid Definition (Hidden) -->
            <pre id="mermaid-graph-definition" style="display: none;">
graph TD
    %% === STRICT Mermaid v8.14.0 Syntax ===

    %% 1. Define ALL Nodes FIRST
    A["<i class='fas fa-industry fa-fw'></i> 19世紀 紡織<br/><strong>繁榮</strong><br/>(波蘭的曼徹斯特)"]
    B["<i class='fas fa-arrow-down fa-fw'></i> 20世紀 工業<br/><strong>衰落</strong><br/>(戰爭與體制變革)"]
    C["<i class='fas fa-university fa-fw'></i> <strong>羅茲電影學院</strong><br/>(1948 誕生)"]
    D["<i class='fas fa-film fa-fw'></i> <strong>波蘭電影學派</strong><br/>(瓦伊達, 波蘭斯KI...)"]
    E["<i class='fas fa-video fa-fw'></i> <strong>羅茲登上銀幕</strong>"]
    F["《應許之地》<br/>(工業時代寫照)"]
    G["《修女艾達》<br/>(戰後沉思)"]
    H["<i class='fas fa-sync-alt fa-fw'></i> 後工業<br/><strong>城市復興</strong>"]
    I["<i class='fas fa-store fa-fw'></i> 曼努法克圖拉<br/>(文化商業中心)"]
    J["<i class='fas fa-lightbulb fa-fw'></i> OFF 彼得科夫斯卡<br/>(創意區)"]
    K["<i class='fas fa-star fa-fw'></i> <strong>UNESCO</strong><br/>電影之城 (2017)"]

    %% 2. Define Subgraphs (List contained Node IDs)
    subgraph "紅色帝國 <i class='fas fa-fire'></i>"
        A
    end
    subgraph "灰色轉折 <i class='fas fa-cloud'></i>"
        B
    end
    subgraph "銀色光影 <i class='fas fa-magic'></i>"
        C
        D
        E
        F
        G
    end
    subgraph "彩色重生 <i class='fas fa-palette'></i>"
        H
        I
        J
        K
    end

    %% 3. Define ALL Links LAST
    A -- "時代變遷" --> B
    B -- "尋找新機" --> C
    C -- "人才輩出" --> D
    D -- "創作實踐" --> E
    E -- "代表作" --> F
    E -- "代表作" --> G
    B -- "城市轉型" --> H
    H -- "旗艦項目" --> I
    H -- "創意空間" --> J
    E -- "聲譽累積" --> K
    H -- "官方認可" --> K

    %% 4. Define Classes (Strictly one assignment per line!)
    classDef popPrimary fill:#F59E0B,stroke:#000,stroke-width:4px,color:#000,font-weight:bold;
    classDef popSecondary fill:#EF4444,stroke:#000,stroke-width:4px,color:#FFF,font-weight:bold;
    classDef popTertiary fill:#3B82F6,stroke:#000,stroke-width:4px,color:#FFF,font-weight:bold;
    classDef popHighlight fill:#FFFFFF,stroke:#000,stroke-width:3px,color:#000,font-weight:bold,stroke-dasharray: 5 5;

    %% 5. Assign Classes (Strictly one assignment per line!)
    class A popPrimary;
    class B popSecondary;
    class C popTertiary;
    class D popTertiary;
    class E popTertiary;
    class F popHighlight;
    class G popHighlight;
    class H popPrimary;
    class I popPrimary;
    class J popPrimary;
    class K popSecondary;

            </pre>
        </section>

        <!-- Section 7: Synthesis -->
        <section class="mb-12 reveal">
            <div class="pop-card bg-blue-700 text-white">
                 <h3 class="text-4xl font-black mb-4 pop-outline-text uppercase flex items-center">
                     <i class="fas fa-link text-yellow-400 text-3xl mr-3"></i> 織機與鏡頭的交織! <span class="text-yellow-400 ml-2">融合!</span>
                 </h3>
                 <p class="text-lg mb-4">織機與鏡頭交織在羅茲的基因中。織機的紀律化為電影製作的堅韌，工業建築節省了製作成本。羅茲的掙扎融入電影主題，映照波蘭靈魂。</p>
                 <p class="text-xl font-bold mt-4"><strong class="pop-text-yellow">羅茲不僅承載故事，它塑造了它們，過去編織進每一幀。</strong></p>
                  <p class="text-lg mt-4">這是一個史詩弧線：從煙囪到攝影機，從線到光，從廢墟到重生。一座註定成為遺跡的城市，將歷史與痛苦轉為<strong class="pop-text-yellow">創意力量!</strong></p>
                  <div class="text-center mt-6">
                     <i class="fas fa-infinity text-5xl text-yellow-400 animate-pulse"></i>
                      <p class="font-bold mt-2">羅茲永遠重生，它的鏡頭對未來完全敞開!</p>
                  </div>
            </div>
             <div class="text-center -mt-4">
                 <span class="explosion pop-bg-yellow text-black dark:pop-bg-red dark:text-white">WOW!</span>
             </div>
        </section>


    <footer class="text-center py-6 mt-8 border-t-4 border-black bg-yellow-400 text-black dark:bg-gray-800 dark:text-gray-400 dark:border-yellow-400">
        <p>&copy; 2023 羅茲故事演繹. 設計靈感源自波普藝術.</p>
    </footer>

    <script src="https://lf3-cdn-tos.bytecdntp.com/cdn/expire-1-M/mermaid/8.14.0/mermaid.min.js"></script>
    <script>
        // --- Theme Switcher ---
        const themeToggle = document.getElementById('theme-toggle');
        const htmlElement = document.documentElement;
        const mermaidOutputDiv = document.getElementById('mermaid-render-output');
        const graphDefinition = document.getElementById('mermaid-graph-definition').textContent;
        const uniqueMermaidId = 'popArtLodzGraph'; // Unique ID for rendering

        // Function to set theme (light/dark)
        function setTheme(isDark) {
            if (isDark) {
                htmlElement.classList.add('dark');
                localStorage.setItem('theme', 'dark');
            } else {
                htmlElement.classList.remove('dark');
                localStorage.setItem('theme', 'light');
            }
            renderMermaid(isDark); // Re-render Mermaid chart on theme change
        }

        // Toggle theme on button click
        themeToggle.addEventListener('click', () => {
            const isDark = htmlElement.classList.contains('dark');
            setTheme(!isDark);
        });

        // Apply initial theme based on localStorage or system preference
        const storedTheme = localStorage.getItem('theme');
        const prefersDark = window.matchMedia('(prefers-color-scheme: dark)').matches;
        const initialThemeIsDark = storedTheme ? storedTheme === 'dark' : prefersDark;
        // Set initial theme without rendering Mermaid yet
         if (initialThemeIsDark) {
                htmlElement.classList.add('dark');
            } else {
                htmlElement.classList.remove('dark');
            }


        // --- Mermaid Rendering (Strict v8.14.0 Manual Render) ---
        function renderMermaid(isDarkTheme) {
            const currentTheme = isDarkTheme ? 'dark' : 'neutral'; // Use 'dark' or 'neutral' theme for Mermaid

             // MUST Initialize Mermaid BEFORE each render call to set the theme
            mermaid.initialize({
                startOnLoad: false,
                theme: currentTheme, // 'dark' or 'neutral'
                logLevel: 3, // Adjust log level for debugging if needed (0-5)
                securityLevel: 'loose', // REQUIRED for Font Awesome icons & <br/> in labels
                htmlLabels: true, // REQUIRED for Font Awesome icons & <br/> in labels
                 flowchart: { // Specific flowchart settings if needed
                    htmlLabels: true
                 },
                 // Define custom theme properties if 'neutral' isn't sufficient
                 // themeVariables: { ... }
            });

            try {
                // Clear previous render
                mermaidOutputDiv.innerHTML = '';

                 // Use mermaidAPI.render for manual rendering
                mermaid.mermaidAPI.render(uniqueMermaidId, graphDefinition, (svgCode, bindFunctions) => {
                    console.log("Mermaid rendered successfully for theme:", currentTheme);
                    mermaidOutputDiv.innerHTML = svgCode;
                    if (bindFunctions) {
                         console.log("Binding functions...");
                         bindFunctions(mermaidOutputDiv); // Bind interactions if any
                     }

                }, mermaidOutputDiv); // Pass the container element
                 console.log("Mermaid rendering process initiated for theme:", currentTheme);


            } catch (error) {
                 console.error("Mermaid rendering failed:", error);
                 mermaidOutputDiv.innerHTML = `<p class="text-red-500 font-bold text-center">Oops! 無法繪製圖表。請檢查 Mermaid 語法。<br>${error.message || error}</p>`;
            }
        }


        // --- Scroll Animations ---
        const reveals = document.querySelectorAll('.reveal');

        const observerOptions = {
            root: null, // relative to document viewport
            rootMargin: '0px',
            threshold: 0.1 // trigger when 10% of the element is visible
        };

        const observer = new IntersectionObserver((entries, observer) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                    // Optional: Stop observing once revealed
                    // observer.unobserve(entry.target);
                }
                 // Optional: Remove class if scrolling back up
                 // else {
                 //     entry.target.classList.remove('visible');
                 // }
            });
        }, observerOptions);

        reveals.forEach(reveal => {
            observer.observe(reveal);
        });

         // --- Initial Mermaid Render on Load ---
         // Use DOMContentLoaded to ensure the DOM is ready, but Mermaid script might still be loading
         // window.onload is safer as it waits for all resources including scripts
        window.onload = () => {
             console.log("Window loaded. Performing initial Mermaid render.");
             // Determine theme *again* right before rendering, in case system preference changed
             const isDark = htmlElement.classList.contains('dark');
             renderMermaid(isDark);
         };

    </script>
</body>
</html>

{{</raw>}}
