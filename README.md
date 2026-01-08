<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>英语打字练习 (30天 + 复习不熟练 + ⭐奖励)</title>
  <style>
    :root {
      --primary: #2563eb;
      --primary-hover: #1d4ed8;
      --bg-color: #f3f4f6;
      --card-bg: #ffffff;
      --text-main: #1f2937;
      --text-sub: #6b7280;
      --border: #e5e7eb;
      --success: #10b981;
      --error: #ef4444;
      --warning: #f59e0b;
    }
    body {
      margin: 0; padding: 20px;
      font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
      background: var(--bg-color);
      color: var(--text-main);
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
    }
    h1 { margin-bottom: 10px; font-size: 1.8rem; text-align: center; }
    .subtitle {
      background: #e0e7ff; color: #3730a3;
      padding: 8px 16px; border-radius: 20px;
      font-size: 0.9rem; margin-bottom: 20px;
      font-weight: 600;
    }

    /* 布局容器 */
    .container {
      display: flex;
      gap: 20px;
      width: 100%;
      max-width: 1100px;
      align-items: flex-start;
    }
    /* 左侧：练习区 */
    .main-panel {
      flex: 2;
      background: var(--card-bg);
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 4px 6px -1px rgba(0,0,0,0.1);
      display: flex;
      flex-direction: column;
      gap: 20px;
    }
    /* 右侧：复习面板 */
    .side-panel {
      flex: 1;
      background: var(--card-bg);
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 6px -1px rgba(0,0,0,0.1);
      max-height: 80vh;
      overflow-y: auto;
    }

    /* 顶部控制栏 */
    .controls {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      align-items: center;
      justify-content: space-between;
    }
    select, button {
      padding: 8px 14px;
      border: 1px solid var(--border);
      border-radius: 6px;
      font-size: 0.95rem;
      cursor: pointer;
      background: #fff;
      transition: all 0.2s;
    }
    select:hover, button:hover { border-color: var(--primary); }
    button:active { transform: translateY(1px); }
    
    .btn-primary {
      background: var(--primary); color: #fff; border: none;
    }
    .btn-primary:hover { background: var(--primary-hover); }

    .btn-outline {
      color: var(--primary); border-color: var(--primary);
    }
    .btn-outline:hover { background: #eff6ff; }

    /* 状态栏 */
    .stats-bar {
      display: flex;
      justify-content: space-between;
      background: #f9fafb;
      padding: 10px 15px;
      border-radius: 8px;
      border: 1px solid var(--border);
      font-size: 0.9rem;
    }
    .stat-item { display: flex; align-items: center; gap: 6px; }
    .stat-item strong { font-size: 1.1rem; }

    /* 单词显示区 */
    .word-display {
      text-align: left;
      margin: 10px 0;
    }
    .en-text {
      font-size: 3rem;
      font-weight: 700;
      color: var(--text-main);
      line-height: 1.2;
      margin-bottom: 8px;
    }
    .cn-text {
      font-size: 1.2rem;
      color: var(--text-sub);
    }

    /* 输入框 */
    .input-area { position: relative; }
    input[type="text"] {
      width: 100%;
      padding: 15px;
      font-size: 1.5rem;
      border: 2px solid var(--border);
      border-radius: 10px;
      outline: none;
      transition: border-color 0.2s;
      box-sizing: border-box; 
      font-family: inherit;
    }
    input[type="text"]:focus { border-color: var(--primary); box-shadow: 0 0 0 3px rgba(37,99,235,0.1); }
    input[type="text"].shake { animation: shake 0.4s; border-color: var(--error); }
    input[type="text"].success { border-color: var(--success); }

    @keyframes shake {
      0%, 100% { transform: translateX(0); }
      25% { transform: translateX(-5px); }
      75% { transform: translateX(5px); }
    }

    /* 进度条 */
    .progress-container {
      height: 6px;
      background: #e5e7eb;
      border-radius: 3px;
      overflow: hidden;
      margin-top: 10px;
    }
    .progress-bar {
      height: 100%;
      background: var(--success);
      width: 0%;
      transition: width 0.3s ease;
    }
    .progress-text {
      font-size: 0.85rem; color: var(--text-sub); margin-top: 5px;
    }

    /* 提示信息 */
    .hint-msg {
      font-size: 0.95rem; color: var(--text-sub); min-height: 1.4em;
    }
    .hint-msg span.soft { color: #9ca3af; }

    /* 复习列表样式 */
    .review-header {
      display: flex; justify-content: space-between; align-items: center;
      margin-bottom: 15px; padding-bottom: 10px;
      border-bottom: 1px solid var(--border);
    }
    .review-header h3 { margin: 0; font-size: 1.1rem; }
    
    .review-list {
      display: flex; flex-direction: column; gap: 10px;
    }
    .review-list .item {
      background: #f9fafb;
      padding: 10px;
      border-radius: 6px;
      border: 1px solid #eee;
      font-size: 0.9rem;
      position: relative;
    }
    .review-list .item .a { font-weight: 700; font-size: 1rem; color: #333; }
    .review-list .item .b { color: #666; font-size: 0.85rem; margin-top: 2px; }
    .review-list .item .meta {
      margin-top: 5px; display: flex; gap: 8px; font-size: 0.75rem; color: #888;
    }
    .tag {
      padding: 2px 6px; border-radius: 4px; background: #e5e7eb;
    }
    .tag.bad { background: #fee2e2; color: #991b1b; }
    .tag.ok { background: #d1fae5; color: #065f46; }

    /* 媒体展示（图片/技巧） */
    .media-box {
      margin-top: 10px; 
      background: #fff; border: 1px solid #eee; 
      padding: 10px; border-radius: 8px;
      display: none; /* 默认隐藏 */
    }
    .media-box img {
      max-width: 100%; height: auto; border-radius: 6px; display: block; margin-bottom: 8px;
    }
    .media-box .tip {
      font-size: 0.9rem; color: #555; line-height: 1.4;
      background: #fffbeb; padding: 8px; border-radius: 4px; border-left: 3px solid #f59e0b;
    }

    /* 响应式 */
    @media (max-width: 768px) {
      .container { flex-direction: column; }
      .side-panel { width: 100%; max-height: 300px; }
      .en-text { font-size: 2rem; }
    }
  </style>
</head>
<body>

  <h1>英语打字练习 (30天 + 复习不熟练 + ⭐奖励)</h1>
  <div class="subtitle">朱哥哥，朱妹妹你们要努力学习!</div>

  <div class="container">
    <!-- 主面板 -->
    <div class="main-panel">
      <!-- 顶部选单 -->
      <div class="controls">
        <div style="display:flex; gap:8px; align-items:center;">
          <label>选择：</label>
          <select id="daySelect"></select>
        </div>
        <div style="display:flex; gap:8px;">
          <button id="prevBtn">上一条</button>
          <button id="nextBtn">下一条</button>
          <button id="speakBtn" class="btn-primary" style="background:#1f2937;">🔊 朗读</button>
          <button id="markBtn" class="btn-outline">⭐ 加入复习</button>
          <button id="resetBtn" style="color:#ef4444;border-color:#ef4444;">重置当前进度</button>
        </div>
      </div>

      <!-- 状态栏 -->
      <div class="stats-bar">
        <div class="stat-item" title="星星总数">⭐ 星星: <strong id="starTotal">0</strong></div>
        <div class="stat-item" title="连续答对">🔥 连击: <strong id="streakEl">0</strong></div>
        <div class="stat-item" title="完成目标得奖励">🎯 今日目标: <strong id="goalEl">20</strong> ⭐</div>
        <button id="setGoalBtn" style="padding:2px 8px; font-size:0.8rem;">设置目标</button>
      </div>

      <div class="stats-bar" style="background:#fff; border:none; padding:0;">
        <button id="clearStarsBtn" style="background:#b91c1c; color:#fff; border:none; padding:4px 10px; border-radius:4px; font-size:0.85rem; cursor:pointer;">清空星星</button>
      </div>

      <!-- 显示区 -->
      <div class="word-display">
        <div class="en-text" id="enText">Hello</div>
        <div class="cn-text" id="cnText">你好</div>
        
        <!-- 图片/技巧区域 -->
        <div class="media-box" id="mediaBox">
          <img id="ipaImg" src="" alt="示意图" />
          <div class="tip" id="ipaTip"></div>
        </div>
      </div>

      <!-- 输入区 -->
      <div class="input-area">
        <input type="text" id="inputEl" placeholder="输入英文..." autocomplete="off" />
      </div>

      <!-- 提示与进度 -->
      <div>
        <div class="hint-msg" id="hintEl">提示：按 Enter 提交</div>
        <div class="progress-text">进度: <span id="posEl">0</span>/<span id="totalEl">0</span> &nbsp; 正确: <span id="correctEl">0</span> 错误: <span id="wrongEl">0</span> 正确率: <span id="accEl">0%</span></div>
        <div class="progress-container">
          <div class="progress-bar" id="barEl"></div>
        </div>
      </div>
    </div>

    <!-- 侧边栏：复习面板 -->
    <div class="side-panel">
      <div class="review-header">
        <h3>复习面板</h3>
        <div style="font-size:0.8rem; color:#666;">
          <span id="modeName">Day 1</span>
        </div>
      </div>
      
      <div style="display:flex; gap:10px; margin-bottom:10px; flex-wrap:wrap;">
        <div class="stat-item" style="font-size:0.85rem;">⭐ 标记不熟练: <strong id="markCount">0</strong></div>
        <div class="stat-item" style="font-size:0.85rem;">❌ 错题: <strong id="wrongCount">0</strong></div>
      </div>

      <div style="margin-bottom:15px; display:flex; gap:5px; flex-wrap:wrap;">
        <button id="reviewModeDayBtn" class="btn-outline" style="font-size:0.8rem;">📌 复习 (当天不熟练)</button>
        <button id="reviewModeAllBtn" class="btn-outline" style="font-size:0.8rem;">📚 复习 (全局不熟练)</button>
      </div>

      <div style="font-weight:600; font-size:0.9rem; margin-bottom:8px;">不熟练清单 (当前选择)</div>
      <div class="review-list" id="reviewList">
        <!-- JS 填充 -->
      </div>
    </div>
  </div>

<script>
/* 
  数据结构:
  DAYS = {
    "Day 1": [ {en:"apple", cn:"苹果", ipa:"/.../"}, ... ],
    ...
  }
  
  LocalStorage:
  - "english_typing_progress": {
      "Day 1": { pos: 0, correct: 0, wrong: 0 },
      ...
    }
  - "english_typing_records": {
      "Day 1::apple": { star: true/false, wrong: 2, right: 5 },
      ...
    }
  - "english_typing_global": {
      starsTotal: 100,
      streak: 5,
      goal: 20
    }
*/

const DAYS = {
  "Day 1": [
    {en:"hello", cn:"你好", ipa:"/həˈləʊ/"},
    {en:"hi", cn:"嗨", ipa:"/haɪ/"},
    {en:"good morning", cn:"早上好", ipa:"/ɡʊd ˈmɔːnɪŋ/"},
    {en:"good afternoon", cn:"下午好", ipa:"/ɡʊd ˌɑːftəˈnuːn/"},
    {en:"good evening", cn:"晚上好", ipa:"/ɡʊd ˈiːvnɪŋ/"},
    {en:"goodbye", cn:"再见", ipa:"/ˌɡʊdˈbaɪ/"},
    {en:"see you", cn:"再见（回头见）", ipa:"/siː juː/"},
    {en:"how are you", cn:"你好吗？", ipa:"/haʊ ɑː juː/"},
    {en:"I am fine", cn:"我很好", ipa:"/aɪ æm faɪn/"},
    {en:"thank you", cn:"谢谢", ipa:"/θæŋk juː/"},
  ],
  "Day 2": [
    {en:"what is your name", cn:"你叫什么名字？", ipa:"/wɒt ɪz jɔː neɪm/"},
    {en:"my name is", cn:"我的名字是...", ipa:"/maɪ neɪm ɪz/"},
    {en:"nice to meet you", cn:"很高兴见到你", ipa:"/naɪs tuː miːt juː/"},
    {en:"this is my friend", cn:"这是我的朋友", ipa:"/ðɪs ɪz maɪ frend/"},
    {en:"he is a student", cn:"他是个学生", ipa:"/hiː ɪz ə ˈstjuːdənt/"},
    {en:"she is a teacher", cn:"她是个老师", ipa:"/ʃiː ɪz ə ˈtiːtʃə/"},
    {en:"we are happy", cn:"我们要开心", ipa:"/wiː ɑː ˈhæpi/"},
    {en:"they are busy", cn:"他们很忙", ipa:"/ðeɪ ɑː ˈbɪzi/"},
    {en:"are you ready", cn:"你准备好了吗？", ipa:"/ɑː juː ˈredi/"},
    {en:"yes I am", cn:"是的，我准备好了", ipa:"/jes aɪ æm/"},
  ],
  "Day 3": [
    {en:"apple", cn:"苹果", ipa:"/ˈæpl/"},
    {en:"banana", cn:"香蕉", ipa:"/bəˈnɑːnə/"},
    {en:"cat", cn:"猫", ipa:"/kæt/"},
    {en:"dog", cn:"狗", ipa:"/dɒɡ/"},
    {en:"egg", cn:"鸡蛋", ipa:"/eɡ/"},
    {en:"fish", cn:"鱼", ipa:"/fɪʃ/"},
    {en:"girl", cn:"女孩", ipa:"/ɡɜːl/"},
    {en:"boy", cn:"男孩", ipa:"/bɔɪ/"},
    {en:"home", cn:"家", ipa:"/həʊm/"},
    {en:"ice cream", cn:"冰淇淋", ipa:"/ˌaɪs ˈkriːm/"},
  ],
  "Day 4": [
    {en:"one", cn:"一", ipa:"/wʌn/"},
    {en:"two", cn:"二", ipa:"/tuː/"},
    {en:"three", cn:"三", ipa:"/θriː/"},
    {en:"four", cn:"四", ipa:"/fɔː/"},
    {en:"five", cn:"五", ipa:"/faɪv/"},
    {en:"six", cn:"六", ipa:"/sɪks/"},
    {en:"seven", cn:"七", ipa:"/ˈsevn/"},
    {en:"eight", cn:"八", ipa:"/eɪt/"},
    {en:"nine", cn:"九", ipa:"/naɪn/"},
    {en:"ten", cn:"十", ipa:"/ten/"},
  ],
  "Day 5": [
    {en:"red", cn:"红色", ipa:"/red/"},
    {en:"blue", cn:"蓝色", ipa:"/bluː/"},
    {en:"green", cn:"绿色", ipa:"/ɡriːn/"},
    {en:"yellow", cn:"黄色", ipa:"/ˈjeləʊ/"},
    {en:"black", cn:"黑色", ipa:"/blæk/"},
    {en:"white", cn:"白色", ipa:"/waɪt/"},
    {en:"orange", cn:"橙色", ipa:"/ˈɒrɪndʒ/"},
    {en:"purple", cn:"紫色", ipa:"/ˈpɜːpl/"},
    {en:"pink", cn:"粉色", ipa:"/pɪŋk/"},
    {en:"brown", cn:"棕色", ipa:"/braʊn/"},
  ],
  "Day 6": [
    {en:"head", cn:"头", ipa:"/hed/"},
    {en:"hair", cn:"头发", ipa:"/heə/"},
    {en:"face", cn:"脸", ipa:"/feɪs/"},
    {en:"eye", cn:"眼睛", ipa:"/aɪ/"},
    {en:"ear", cn:"耳朵", ipa:"/ɪə/"},
    {en:"nose", cn:"鼻子", ipa:"/nəʊz/"},
    {en:"mouth", cn:"嘴巴", ipa:"/maʊθ/"},
    {en:"hand", cn:"手", ipa:"/hænd/"},
    {en:"leg", cn:"腿", ipa:"/leɡ/"},
    {en:"foot", cn:"脚", ipa:"/fʊt/"},
  ],
  "Day 7": [
    {en:"father", cn:"父亲", ipa:"/ˈfɑːðə/"},
    {en:"mother", cn:"母亲", ipa:"/ˈmʌðə/"},
    {en:"brother", cn:"兄弟", ipa:"/ˈbrʌðə/"},
    {en:"sister", cn:"姐妹", ipa:"/ˈsɪstə/"},
    {en:"grandfather", cn:"祖父", ipa:"/ˈɡrænfɑːðə/"},
    {en:"grandmother", cn:"祖母", ipa:"/ˈɡrænmʌðə/"},
    {en:"uncle", cn:"叔叔/舅舅", ipa:"/ˈʌŋkl/"},
    {en:"aunt", cn:"阿姨/姑姑", ipa:"/ɑːnt/"},
    {en:"cousin", cn:"堂(表)兄弟姐妹", ipa:"/ˈkʌzn/"},
    {en:"friend", cn:"朋友", ipa:"/frend/"},
  ],
  "Day 8": [
    {en:"pen", cn:"钢笔", ipa:"/pen/"},
    {en:"pencil", cn:"铅笔", ipa:"/ˈpensl/"},
    {en:"book", cn:"书", ipa:"/bʊk/"},
    {en:"bag", cn:"书包", ipa:"/bæɡ/"},
    {en:"desk", cn:"书桌", ipa:"/desk/"},
    {en:"chair", cn:"椅子", ipa:"/tʃeə/"},
    {en:"ruler", cn:"尺子", ipa:"/ˈruːlə/"},
    {en:"eraser", cn:"橡皮", ipa:"/ɪˈreɪzə/"},
    {en:"school", cn:"学校", ipa:"/skuːl/"},
    {en:"classroom", cn:"教室", ipa:"/ˈklɑːsruːm/"},
  ],
  "Day 9": [
    {en:"I like apples", cn:"我喜欢苹果", ipa:"/aɪ laɪk ˈæplz/"},
    {en:"do you like bananas", cn:"你喜欢香蕉吗？", ipa:"/duː juː laɪk bəˈnɑːnəz/"},
    {en:"yes I do", cn:"是的，我喜欢", ipa:"/jes aɪ duː/"},
    {en:"no I do not", cn:"不，我不喜欢", ipa:"/nəʊ aɪ duː nɒt/"},
    {en:"I have a cat", cn:"我有一只猫", ipa:"/aɪ hæv ə kæt/"},
    {en:"she has a dog", cn:"她有一只狗", ipa:"/ʃiː hæz ə dɒɡ/"},
    {en:"this is my book", cn:"这是我的书", ipa:"/ðɪs ɪz maɪ bʊk/"},
    {en:"that is your pen", cn:"那是你的钢笔", ipa:"/ðæt ɪz jɔː pen/"},
    {en:"where is my bag", cn:"我的包在哪里？", ipa:"/weər ɪz maɪ bæɡ/"},
    {en:"it is on the desk", cn:"它在桌子上", ipa:"/ɪt ɪz ɒn ðə desk/"},
  ],
  "Day 10": [
    {en:"sun", cn:"太阳", ipa:"/sʌn/"},
    {en:"moon", cn:"月亮", ipa:"/muːn/"},
    {en:"star", cn:"星星", ipa:"/stɑː/"},
    {en:"sky", cn:"天空", ipa:"/skaɪ/"},
    {en:"cloud", cn:"云", ipa:"/klaʊd/"},
    {en:"rain", cn:"雨", ipa:"/reɪn/"},
    {en:"snow", cn:"雪", ipa:"/snəʊ/"},
    {en:"wind", cn:"风", ipa:"/wɪnd/"},
    {en:"hot", cn:"热", ipa:"/hɒt/"},
    {en:"cold", cn:"冷", ipa:"/kəʊld/"},
  ],
  "Day 11":[
    {en:"Where is the bathroom?",cn:"洗手间在哪里？",ipa:"/weər ɪz ðə ˈbɑːθruːm/"},
    {en:"Go straight.",cn:"直走。",ipa:"/ɡəʊ streɪt/"},
    {en:"Turn left.",cn:"左转。",ipa:"/tɜːn left/"},
    {en:"Turn right.",cn:"右转。",ipa:"/tɜːn raɪt/"},
    {en:"It is near.",cn:"很近。",ipa:"/ɪt ɪz nɪə/"},
    {en:"It is far.",cn:"很远。",ipa:"/ɪt ɪz fɑː/"},
    {en:"I am on my way.",cn:"我在路上。",ipa:"/aɪ æm ɒn maɪ weɪ/"},
    {en:"I am late.",cn:"我迟到了。",ipa:"/aɪ æm leɪt/"},
    {en:"Wait a moment.",cn:"等一下。",ipa:"/weɪt ə ˈməʊmənt/"},
    {en:"Hurry up.",cn:"快点。",ipa:"/hʌri ʌp/"},
  ],
  "Day 12":[
    {en:"What time is it?",cn:"现在几点？",ipa:"/wɒt taɪm ɪz ɪt/"},
    {en:"It is eight o’clock.",cn:"八点了。",ipa:"/ɪt ɪz eɪt əˈklɒk/"},
    {en:"I get up early.",cn:"我起得很早。",ipa:"/aɪ ɡet ʌp ˈɜːli/"},
    {en:"I go to bed late.",cn:"我睡得很晚。",ipa:"/aɪ ɡəʊ tuː bed leɪt/"},
    {en:"I have breakfast.",cn:"我吃早餐。",ipa:"/aɪ hæv ˈbrekfəst/"},
    {en:"I have lunch.",cn:"我吃午饭。",ipa:"/aɪ hæv lʌntʃ/"},
    {en:"I have dinner.",cn:"我吃晚饭。",ipa:"/aɪ hæv ˈdɪnə/"},
    {en:"I like reading.",cn:"我喜欢阅读。",ipa:"/aɪ laɪk ˈriːdɪŋ/"},
    {en:"I like music.",cn:"我喜欢音乐。",ipa:"/aɪ laɪk ˈmjuːzɪk/"},
    {en:"I like sports.",cn:"我喜欢运动。",ipa:"/aɪ laɪk spɔːts/"},
  ],
  "Day 13":[
    {en:"It is sunny today.",cn:"今天是晴天。",ipa:"/ɪt ɪz ˈsʌni təˈdeɪ/"},
    {en:"It is rainy.",cn:"下雨了。",ipa:"/ɪt ɪz ˈreɪni/"},
    {en:"It is cloudy.",cn:"多云。",ipa:"/ɪt ɪz ˈklaʊdi/"},
    {en:"It is windy.",cn:"有风。",ipa:"/ɪt ɪz ˈwɪndi/"},
    {en:"It is hot.",cn:"很热。",ipa:"/ɪt ɪz hɒt/"},
    {en:"It is cold.",cn:"很冷。",ipa:"/ɪt ɪz kəʊld/"},
    {en:"I feel happy.",cn:"我感到开心。",ipa:"/aɪ fiːl ˈhæpi/"},
    {en:"I feel tired.",cn:"我感到累。",ipa:"/aɪ fiːl ˈtaɪəd/"},
    {en:"I feel nervous.",cn:"我有点紧张。",ipa:"/aɪ fiːl ˈnɜːvəs/"},
    {en:"I feel excited.",cn:"我很兴奋。",ipa:"/aɪ fiːl ɪkˈsaɪtɪd/"},
  ],
  "Day 14":[
    {en:"Can I have water?",cn:"我可以要水吗？",ipa:"/kæn aɪ hæv ˈwɔːtə/"},
    {en:"Can I sit here?",cn:"我可以坐这里吗？",ipa:"/kæn aɪ sɪt hɪə/"},
    {en:"Please help me.",cn:"请帮帮我。",ipa:"/pliːz help miː/"},
    {en:"Excuse me.",cn:"打扰一下。",ipa:"/ɪkˈskjuːs miː/"},
    {en:"You are welcome.",cn:"不客气。",ipa:"/juː ɑː ˈwelkəm/"},
    {en:"No, thanks.",cn:"不用了，谢谢。",ipa:"/nəʊ θæŋks/"},
    {en:"Yes, please.",cn:"好的，请。",ipa:"/jes pliːz/"},
    {en:"I am ready.",cn:"我准备好了。",ipa:"/aɪ æm ˈredi/"},
    {en:"Let’s start.",cn:"我们开始吧。",ipa:"/lets stɑːt/"},
    {en:"Good job!",cn:"做得好！",ipa:"/ɡʊd dʒɒb/"},
  ],
  "Day 15":[
    {en:"I like green.",cn:"我喜欢绿色。",ipa:"/aɪ laɪk ɡriːn/"},
    {en:"I like purple.",cn:"我喜欢紫色。",ipa:"/aɪ laɪk ˈpɜːpl/"},
    {en:"It is beautiful.",cn:"它很漂亮。",ipa:"/ɪt ɪz ˈbjuːtɪfl/"},
    {en:"It looks good.",cn:"它看起来很好。",ipa:"/ɪt lʊks ɡʊd/"},
    {en:"It is classic.",cn:"它很经典。",ipa:"/ɪt ɪz ˈklæsɪk/"},
    {en:"It is perfect.",cn:"它很完美。",ipa:"/ɪt ɪz ˈpɜːfɪkt/"},
    {en:"I love it.",cn:"
