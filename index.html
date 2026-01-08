<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>英语打字练习（30天 + 复习 + 星星奖励）</title>

  <style>
    body{
      font-family: Arial,"PingFang SC","Microsoft YaHei",sans-serif;
      background:#f3f4f6;
      margin:0;
      padding:22px 12px;
      color:#111827;
    }
    .wrap{
      max-width:1050px;
      margin:0 auto;
      background:#fff;
      border-radius:18px;
      padding:18px 16px;
      box-shadow:0 10px 24px rgba(0,0,0,.08);
    }
    .top{
      display:flex; gap:12px; align-items:flex-start; justify-content:space-between; flex-wrap:wrap;
      margin-bottom:12px;
    }
    .title{font-weight:900;font-size:20px; line-height:1.2;}
    .sub{
      margin-top:6px; font-size:14px; color:#6b7280; font-weight:600;
      display:inline-block; padding:6px 10px; border-radius:12px;
      background:#f3f4f6; border:1px solid #e5e7eb;
    }
    .controls{
      display:flex; gap:10px; flex-wrap:wrap; align-items:center; justify-content:flex-end;
    }
    select,button{
      padding:10px 12px; border-radius:12px; border:1px solid #d1d5db;
      background:#fff; font-size:14px; cursor:pointer;
    }
    button.primary{background:#111827; color:#fff; border-color:#111827;}
    button.warn{background:#b91c1c; color:#fff; border-color:#b91c1c;}
    button:disabled{opacity:.55; cursor:not-allowed;}
    .grid{
      display:grid; grid-template-columns: 1.25fr .75fr; gap:14px;
    }
    @media(max-width:900px){ .grid{grid-template-columns:1fr;} }
    .card{
      background:#f9fafb; border:1px solid #e5e7eb; border-radius:18px; padding:16px;
    }
    .en{font-size:34px;font-weight:900;margin:0 0 6px 0;}
    .cn{font-size:16px;color:#6b7280;margin:0 0 12px 0;}
    .input{
      width:100%; font-size:22px; padding:14px;
      border-radius:14px; border:2px solid #e5e7eb; outline:none; box-sizing:border-box;
    }
    .input:focus{border-color:#111827;}
    .hint{margin-top:10px;font-size:14px; line-height:1.6;}
    .ok{color:#16a34a; font-weight:900;}
    .bad{color:#dc2626; font-weight:900;}
    .soft{color:#6b7280;}
    .row{display:flex; gap:10px; flex-wrap:wrap; align-items:center; justify-content:space-between; margin-top:10px;}
    .stats{display:flex; gap:12px; flex-wrap:wrap; font-size:13px; color:#374151;}
    .progress{height:10px;background:#e5e7eb;border-radius:999px;overflow:hidden;flex:1;min-width:220px;}
    .bar{height:100%;width:0%;background:#111827;transition:width .2s ease;}
    .mini{font-size:12px;color:#6b7280;margin-top:10px;}
    .pill{
      display:inline-flex; align-items:center; gap:6px;
      padding:8px 10px; border-radius:999px; background:#fff;
      border:1px solid #e5e7eb; margin:6px 6px 0 0; font-size:12px;
    }
    .side h3{margin:0 0 10px 0; font-size:14px;}
    .list{margin-top:10px; max-height:360px; overflow:auto; border:1px solid #e5e7eb; border-radius:14px; background:#fff;}
    .item{padding:10px 12px; border-bottom:1px solid #f3f4f6;}
    .item:last-child{border-bottom:none;}
    .item .a{font-weight:900;}
    .item .b{color:#6b7280;font-size:12px;margin-top:4px;}
    .item .meta{margin-top:6px; display:flex; gap:8px; flex-wrap:wrap; align-items:center;}
    .tag{font-size:11px;padding:3px 8px;border-radius:999px;border:1px solid #e5e7eb;background:#f9fafb;color:#374151;}
    .tag.bad{border-color:#fecaca;background:#fee2e2;color:#991b1b;}
    .tag.ok{border-color:#bbf7d0;background:#dcfce7;color:#166534;}
    .divider{height:1px;background:#e5e7eb;margin:14px 0;}
    textarea{
      width:100%; height:110px; resize:vertical;
      padding:10px 12px; border-radius:14px; border:1px solid #d1d5db;
      font-size:13px; box-sizing:border-box; outline:none;
    }

    /* ⭐ 星星奖励 */
    .rewardBox{
      display:flex; gap:10px; flex-wrap:wrap; align-items:center;
      padding:10px 12px; border-radius:16px;
      background:#fff; border:1px solid #e5e7eb;
    }
    .stars{
      font-size:18px; font-weight:900;
    }
    .badge{
      display:inline-flex; align-items:center; gap:6px;
      padding:6px 10px; border-radius:999px;
      border:1px solid #e5e7eb; background:#f9fafb; font-size:12px;
    }
    .toast{
      position:fixed; left:50%; top:18px; transform:translateX(-50%);
      background:#111827; color:#fff; padding:10px 14px;
      border-radius:14px; box-shadow:0 12px 26px rgba(0,0,0,.18);
      opacity:0; pointer-events:none; transition:opacity .25s ease, transform .25s ease;
      z-index:9999;
    }
    .toast.show{opacity:1; transform:translateX(-50%) translateY(4px);}
  </style>
</head>

<body>
  <div class="wrap">
    <div class="top">
      <div>
        <div class="title">英语打字练习（30天 + 复习不熟练 + ⭐奖励）</div>
        <div class="sub">朱哥哥，朱妹妹你们要努力学习！</div>
      </div>

      <div class="controls">
        <label class="soft">选择：</label>
        <select id="modeSelect"></select>
        <button id="prevBtn">上一条</button>
        <button id="nextBtn">下一条</button>
        <button id="speakBtn" class="primary">🔊 朗读</button>
        <button id="markBtn">⭐ 加入复习</button>
        <button id="resetBtn">重置当前列表</button>
      </div>
    </div>

    <div class="grid">
      <!-- Main -->
      <div class="card">
        <div class="rewardBox">
          <div class="stars">⭐ 星星：<span id="starTotal">0</span></div>
          <div class="badge">🔥 连击：<span id="streakEl">0</span></div>
          <div class="badge">🎯 今日目标：<span id="goalEl">20</span> ⭐</div>
          <button id="setGoalBtn">设置目标</button>
          <button id="clearStarsBtn" class="warn">清空星星</button>
        </div>

        <div class="divider"></div>

        <div class="en" id="enText">loading...</div>
        
        <!-- 新增：音标图片和技巧 -->
        <div id="mediaBox" style="display:none; margin-bottom:12px; text-align:center;">
          <img id="ipaImg" src="" style="max-height:120px; border-radius:8px; border:1px solid #eee; margin-bottom:8px;" />
          <div id="ipaTip" style="font-size:14px; color:#d97706; font-weight:bold; background:#fffbeb; padding:8px; border-radius:8px;"></div>
        </div>

        <div class="cn" id="cnText"></div>

        <input class="input" id="inputEl" placeholder="输入英文（忽略大小写/多空格/首尾空格）" autocomplete="off"/>

        <div class="hint" id="hintEl"></div>

        <div class="row">
          <div class="stats">
            <div>进度：<b id="posEl">0</b>/<b id="totalEl">0</b></div>
            <div>正确：<b id="correctEl">0</b></div>
            <div>错误：<b id="wrongEl">0</b></div>
            <div>正确率：<b id="accEl">0%</b></div>
          </div>
          <div class="progress"><div class="bar" id="barEl"></div></div>
        </div>

        <div class="mini">
          提示：按 <b>Enter</b> 提交；打对会自动下一条；错了会提示并记录。你也可以点 ⭐ 加入“复习不熟练”。  
        </div>

        <div class="divider"></div>

        <div style="font-weight:900;margin-bottom:8px;">➕ 自己添加内容（可选）</div>
        <textarea id="customArea" placeholder="每行一条：英文=中文
例如：
apple=苹果
I like coffee=我喜欢咖啡"></textarea>
        <div class="controls" style="margin-top:10px;">
          <button id="loadCustomBtn">加载到「自定义」</button>
          <button id="clearCustomBtn" class="warn">清空自定义</button>
          <button id="clearAllBtn" class="warn">清空所有记录</button>
        </div>
        <div class="mini">自定义内容加载后，会出现在选择列表里：<b>自定义</b>，也会进入复习池。</div>
      </div>

      <!-- Side -->
      <div class="card side">
        <h3>复习面板</h3>
        <div>
          <span class="pill">⭐ 标记不熟练：<b id="markCount">0</b></span>
          <span class="pill">❌ 有错误记录：<b id="wrongCount">0</b></span>
          <span class="pill">📌 当前模式：<b id="modeName">-</b></span>
        </div>

        <div class="divider"></div>

        <h3>不熟练清单（当前选择）</h3>
        <div class="list" id="reviewList"></div>

        <div class="mini">
          你可以选择：  
          - <b>复习（当天不熟练）</b>：只练今天/当前列表里薄弱项  
          - <b>复习（全局不熟练）</b>：复习所有天/所有列表薄弱项  
        </div>
      </div>
    </div>
  </div>

  <div class="toast" id="toast"></div>

<script>
/* =========================
   A) 学习内容：30天 + 小学六年级（可继续扩展）
   ========================= */
const DAYS = {
  "Day 1":[
    {en:"hello",cn:"你好",ipa:"/həˈləʊ/"},
    {en:"thank you",cn:"谢谢",ipa:"/θæŋk juː/"},
    {en:"sorry",cn:"对不起",ipa:"/ˈsɒri/"},
    {en:"please",cn:"请",ipa:"/pliːz/"},
    {en:"good morning",cn:"早上好",ipa:"/ɡʊd ˈmɔːnɪŋ/"},
    {en:"good night",cn:"晚安",ipa:"/ɡʊd naɪt/"},
    {en:"see you",cn:"再见",ipa:"/siː juː/"},
    {en:"yes",cn:"是",ipa:"/jes/",ipa:"/jes/"},
    {en:"no",cn:"不",ipa:"/nəʊ/",ipa:"/nəʊ/"},
    {en:"today",cn:"今天",ipa:"/təˈdeɪ/",ipa:"/təˈdeɪ/"},
  ],
  "Day 2":[
    {en:"I",cn:"我",ipa:"/aɪ/"},
    {en:"you",cn:"你",ipa:"/juː/"},
    {en:"he",cn:"他",ipa:"/hiː/"},
    {en:"she",cn:"她",ipa:"/ʃiː/"},
    {en:"we",cn:"我们",ipa:"/wiː/"},
    {en:"they",cn:"他们",ipa:"/ðeɪ/"},
    {en:"my",cn:"我的",ipa:"/maɪ/"},
    {en:"your",cn:"你的",ipa:"/jɔː/"},
    {en:"his",cn:"他的",ipa:"/hɪz/"},
    {en:"her",cn:"她的",ipa:"/hɜː/"},
  ],
  "Day 3":[
    {en:"eat",cn:"吃",ipa:"/iːt/",ipa:"/iːt/"},
    {en:"drink",cn:"喝",ipa:"/drɪŋk/"},
    {en:"go",cn:"去",ipa:"/ɡəʊ/"},
    {en:"come",cn:"来",ipa:"/kʌm/"},
    {en:"like",cn:"喜欢",ipa:"/laɪk/",ipa:"/laɪk/"},
    {en:"want",cn:"想要",ipa:"/wɒnt/"},
    {en:"need",cn:"需要",ipa:"/niːd/",ipa:"/niːd/"},
    {en:"help",cn:"帮助",ipa:"/help/",ipa:"/help/"},
    {en:"know",cn:"知道",ipa:"/nəʊ/"},
    {en:"think",cn:"想",ipa:"/θɪŋk/"},
  ],
  "Day 4":[
    {en:"water",cn:"水",ipa:"/ˈwɔːtə/",ipa:"/ˈwɔːtə/"},
    {en:"food",cn:"食物",ipa:"/fuːd/",ipa:"/fuːd/"},
    {en:"coffee",cn:"咖啡",ipa:"/ˈkɒfi/"},
    {en:"tea",cn:"茶",ipa:"/tiː/"},
    {en:"milk",cn:"牛奶",ipa:"/mɪlk/"},
    {en:"rice",cn:"米饭",ipa:"/raɪs/"},
    {en:"bread",cn:"面包",ipa:"/bred/"},
    {en:"fruit",cn:"水果",ipa:"/fruːt/"},
    {en:"meat",cn:"肉",ipa:"/miːt/"},
    {en:"cake",cn:"蛋糕",ipa:"/keɪk/"},
  ],
  "Day 5":[
    {en:"big",cn:"大",ipa:"/bɪɡ/",ipa:"/bɪɡ/"},
    {en:"small",cn:"小",ipa:"/smɔːl/",ipa:"/smɔːl/"},
    {en:"hot",cn:"热",ipa:"/hɒt/",ipa:"/hɒt/"},
    {en:"cold",cn:"冷",ipa:"/kəʊld/",ipa:"/kəʊld/"},
    {en:"new",cn:"新的",ipa:"/njuː/"},
    {en:"old",cn:"旧的",ipa:"/əʊld/"},
    {en:"easy",cn:"容易",ipa:"/ˈiːzi/",ipa:"/ˈiːzi/"},
    {en:"hard",cn:"难",ipa:"/hɑːd/",ipa:"/hɑːd/"},
    {en:"fast",cn:"快",ipa:"/fɑːst/"},
    {en:"slow",cn:"慢",ipa:"/sləʊ/"},
  ],
  "Day 6":[
    {en:"I like coffee.",cn:"我喜欢咖啡。",ipa:"/aɪ laɪk ˈkɒfi/"},
    {en:"I like tea.",cn:"我喜欢茶。",ipa:"/aɪ laɪk tiː/"},
    {en:"I want water.",cn:"我想要水。",ipa:"/aɪ wɒnt ˈwɔːtə/"},
    {en:"I want food.",cn:"我想要食物。",ipa:"/aɪ wɒnt fuːd/"},
    {en:"I am happy.",cn:"我很开心。",ipa:"/aɪ æm ˈhæpi/",ipa:"/aɪ æm ˈhæpi/"},
    {en:"I am tired.",cn:"我累了。",ipa:"/aɪ æm ˈtaɪəd/"},
    {en:"This is my phone.",cn:"这是我的手机。",ipa:"/ðɪs ɪz maɪ fəʊn/"},
    {en:"This is my bag.",cn:"这是我的包。",ipa:"/ðɪs ɪz maɪ bæɡ/"},
    {en:"I can do it.",cn:"我可以做到。",ipa:"/aɪ kæn duː ɪt/",ipa:"/aɪ kæn duː ɪt/"},
    {en:"Please help me.",cn:"请帮帮我。",ipa:"/pliːz help miː/",ipa:"/pliːz help miː/"},
  ],
  "Day 7":[
    {en:"How are you?",cn:"你好吗？",ipa:"/haʊ ɑː juː/"},
    {en:"I am fine.",cn:"我很好。",ipa:"/aɪ æm faɪn/"},
    {en:"Nice to meet you.",cn:"很高兴认识你。",ipa:"/naɪs tuː miːt juː/",ipa:"/naɪs tuː miːt juː/"},
    {en:"What is this?",cn:"这是什么？",ipa:"/wɒt ɪz ðɪs/"},
    {en:"What is your name?",cn:"你叫什么名字？",ipa:"/wɒt ɪz jɔː neɪm/",ipa:"/wɒt ɪz jɔː neɪm/"},
    {en:"Can you help me?",cn:"你能帮我吗？",ipa:"/kæn juː help miː/"},
    {en:"No problem.",cn:"没问题。",ipa:"/nəʊ ˈprɒbləm/"},
    {en:"Thank you very much.",cn:"非常感谢你。",ipa:"/θæŋk juː ˈveri mʌtʃ/"},
    {en:"See you tomorrow.",cn:"明天见。",ipa:"/siː juː təˈmɒrəʊ/",ipa:"/siː juː təˈmɒrəʊ/"},
    {en:"Have a nice day.",cn:"祝你今天愉快。",ipa:"/hæv ə naɪs deɪ/",ipa:"/hæv ə naɪs deɪ/"},
  ],
  "Day 8":[
    {en:"Where are you from?",cn:"你来自哪里？",ipa:"/weər ɑː juː frɒm/"},
    {en:"I am from China.",cn:"我来自中国。",ipa:"/aɪ æm frɒm ˈtʃaɪnə/"},
    {en:"I am busy today.",cn:"我今天很忙。",ipa:"/aɪ æm ˈbɪzi təˈdeɪ/"},
    {en:"I am free now.",cn:"我现在有空。",ipa:"/aɪ æm friː naʊ/"},
    {en:"Let’s go.",cn:"我们走吧。",ipa:"/lets ɡəʊ/"},
    {en:"Take care.",cn:"保重。",ipa:"/teɪk keə/"},
    {en:"Good luck.",cn:"祝你好运。",ipa:"/ɡʊd lʌk/"},
    {en:"Please speak slowly.",cn:"请说慢一点。",ipa:"/pliːz spiːk ˈsləʊli/"},
    {en:"Please repeat.",cn:"请再说一遍。",ipa:"/pliːz rɪˈpiːt/"},
    {en:"I understand.",cn:"我明白。",ipa:"/aɪ ˌʌndəˈstænd/"},
  ],
  "Day 9":[
    {en:"How much is this?",cn:"这个多少钱？",ipa:"/haʊ mʌtʃ ɪz ðɪs/"},
    {en:"It is cheap.",cn:"它很便宜。",ipa:"/ɪt ɪz tʃiːp/"},
    {en:"It is expensive.",cn:"它很贵。",ipa:"/ɪt ɪz ɪkˈspensɪv/"},
    {en:"I like this one.",cn:"我喜欢这个。",ipa:"/aɪ laɪk ðɪs wʌn/",ipa:"/aɪ laɪk ðɪs wʌn/"},
    {en:"I don’t like it.",cn:"我不喜欢它。",ipa:"/aɪ dəʊnt laɪk ɪt/",ipa:"/aɪ dəʊnt laɪk ɪt/"},
    {en:"I will take it.",cn:"我买了。",ipa:"/aɪ wɪl teɪk ɪt/",ipa:"/aɪ wɪl teɪk ɪt/"},
    {en:"Do you have a discount?",cn:"有折扣吗？",ipa:"/duː juː hæv ə ˈdɪskaʊnt/",ipa:"/duː juː hæv ə ˈdɪskaʊnt/"},
    {en:"That’s fine.",cn:"可以。",ipa:"/ðæts faɪn/"},
    {en:"Too much.",cn:"太贵了。",ipa:"/tuː mʌtʃ/"},
    {en:"Thank you.",cn:"谢谢。",ipa:"/θæŋk juː/",ipa:"/θæŋk juː/"},
  ],
  "Day 10":[
    {en:"I am learning English.",cn:"我在学英语。",ipa:"/aɪ æm ˈlɜːnɪŋ ˈɪŋɡlɪʃ/",ipa:"/aɪ æm ˈlɜːnɪŋ ˈɪŋɡlɪʃ/"},
    {en:"English is hard.",cn:"英语很难。",ipa:"/ˈɪŋɡlɪʃ ɪz hɑːd/"},
    {en:"English is easy.",cn:"英语很简单。",ipa:"/ˈɪŋɡlɪʃ ɪz ˈiːzi/"},
    {en:"Don’t worry.",cn:"别担心。",ipa:"/dəʊnt ˈwʌri/"},
    {en:"I can try.",cn:"我可以试试。",ipa:"/aɪ kæn traɪ/"},
    {en:"I will keep going.",cn:"我会继续坚持。",ipa:"/aɪ wɪl kiːp ˈɡəʊɪŋ/",ipa:"/aɪ wɪl kiːp ˈɡəʊɪŋ/"},
    {en:"I need practice.",cn:"我需要练习。",ipa:"/aɪ niːd ˈpræktɪs/",ipa:"/aɪ niːd ˈpræktɪs/"},
    {en:"I practice every day.",cn:"我每天练习。",ipa:"/aɪ ˈpræktɪs ˈevri deɪ/",ipa:"/aɪ ˈpræktɪs ˈevri deɪ/"},
    {en:"I am improving.",cn:"我在进步。",ipa:"/aɪ æm ɪmˈpruːvɪŋ/",ipa:"/aɪ æm ɪmˈpruːvɪŋ/"},
    {en:"Tomorrow will be better.",cn:"明天会更好。",ipa:"/təˈmɒrəʊ wɪl biː ˈbetə/",ipa:"/təˈmɒrəʊ wɪl biː ˈbetə/"},
  ],

  // 为了让文件不爆炸：Day 11-30 用「实用句子/词」继续补齐（每一天10条）
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
    {en:"I love it.",cn:"我爱它。",ipa:"/aɪ lʌv ɪt/"},
    {en:"I don’t like it.",cn:"我不喜欢它。",ipa:"/aɪ dəʊnt laɪk ɪt/"},
    {en:"This one is better.",cn:"这个更好。",ipa:"/ðɪs wʌn ɪz ˈbetə/"},
    {en:"That one is nice.",cn:"那个也不错。",ipa:"/ðæt wʌn ɪz naɪs/"},
  ],
  "Day 16":[
    {en:"I like my school.",cn:"我喜欢我的学校。",ipa:"/aɪ laɪk maɪ skuːl/"},
    {en:"I like my teacher.",cn:"我喜欢我的老师。",ipa:"/aɪ laɪk maɪ ˈtiːtʃə/"},
    {en:"I like my friends.",cn:"我喜欢我的朋友。",ipa:"/aɪ laɪk maɪ frends/"},
    {en:"We study together.",cn:"我们一起学习。",ipa:"/wiː ˈstʌdi təˈɡeðə/"},
    {en:"We play together.",cn:"我们一起玩。",ipa:"/wiː pleɪ təˈɡeðə/"},
    {en:"I can read.",cn:"我会读。",ipa:"/aɪ kæn riːd/"},
    {en:"I can write.",cn:"我会写。",ipa:"/aɪ kæn raɪt/"},
    {en:"I can speak.",cn:"我会说。",ipa:"/aɪ kæn spiːk/"},
    {en:"I can type.",cn:"我会打字。",ipa:"/aɪ kæn taɪp/"},
    {en:"I can learn.",cn:"我会学习。",ipa:"/aɪ kæn lɜːn/"},
  ],
  "Day 17":[
    {en:"I go to school by bus.",cn:"我坐公交去上学。",ipa:"/aɪ ɡəʊ tuː skuːl baɪ bʌs/"},
    {en:"I go by bike.",cn:"我骑车去。",ipa:"/aɪ ɡəʊ baɪ baɪk/"},
    {en:"I go by car.",cn:"我坐车去。",ipa:"/aɪ ɡəʊ baɪ kɑː/"},
    {en:"I walk to school.",cn:"我走路上学。",ipa:"/aɪ wɔːk tuː skuːl/"},
    {en:"How do you go to school?",cn:"你怎么去上学？",ipa:"/haʊ duː juː ɡəʊ tuː skuːl/"},
    {en:"I like English.",cn:"我喜欢英语。",ipa:"/aɪ laɪk ˈɪŋɡlɪʃ/"},
    {en:"I like math.",cn:"我喜欢数学。",ipa:"/aɪ laɪk mæθ/"},
    {en:"I like science.",cn:"我喜欢科学。",ipa:"/aɪ laɪk ˈsaɪəns/"},
    {en:"English is useful.",cn:"英语很有用。",ipa:"/ˈɪŋɡlɪʃ ɪz ˈjuːsfl/"},
    {en:"I will study hard.",cn:"我会努力学习。",ipa:"/aɪ wɪl ˈstʌdi hɑːd/"},
  ],
  "Day 18":[
    {en:"I have a question.",cn:"我有一个问题。",ipa:"/aɪ hæv ə ˈkwestʃən/"},
    {en:"What is the answer?",cn:"答案是什么？",ipa:"/wɒt ɪz ðə ˈɑːnsə/"},
    {en:"Please give me an example.",cn:"请给我一个例子。",ipa:"/pliːz ɡɪv miː ən ɪɡˈzɑːmpl/"},
    {en:"I will try again.",cn:"我会再试一次。",ipa:"/aɪ wɪl traɪ əˈɡen/"},
    {en:"I made a mistake.",cn:"我犯了一个错误。",ipa:"/aɪ meɪd ə mɪˈsteɪk/"},
    {en:"It is okay.",cn:"没关系。",ipa:"/ɪt ɪz ˌəʊˈkeɪ/"},
    {en:"No worries.",cn:"别担心。",ipa:"/nəʊ ˈwʌriz/"},
    {en:"Keep going.",cn:"继续加油。",ipa:"/kiːp ˈɡəʊɪŋ/"},
    {en:"You can do it.",cn:"你可以做到。",ipa:"/juː kæn duː ɪt/"},
    {en:"Great!",cn:"太棒了！",ipa:"/ɡreɪt/"},
  ],
  "Day 19":[
    {en:"What do you like?",cn:"你喜欢什么？",ipa:"/wɒt duː juː laɪk/"},
    {en:"I like reading books.",cn:"我喜欢看书。",ipa:"/aɪ laɪk ˈriːdɪŋ bʊks/"},
    {en:"I like drawing.",cn:"我喜欢画画。",ipa:"/aɪ laɪk ˈdrɔːɪŋ/"},
    {en:"I like playing football.",cn:"我喜欢踢足球。",ipa:"/aɪ laɪk ˈpleɪɪŋ ˈfʊtbɔːl/"},
    {en:"I like swimming.",cn:"我喜欢游泳。",ipa:"/aɪ laɪk ˈswɪmɪŋ/"},
    {en:"I like dancing.",cn:"我喜欢跳舞。",ipa:"/aɪ laɪk ˈdɑːnsɪŋ/"},
    {en:"I like singing.",cn:"我喜欢唱歌。",ipa:"/aɪ laɪk ˈsɪŋɪŋ/"},
    {en:"I like running.",cn:"我喜欢跑步。",ipa:"/aɪ laɪk ˈrʌnɪŋ/"},
    {en:"I like animals.",cn:"我喜欢动物。",ipa:"/aɪ laɪk ˈænɪmlz/"},
    {en:"I like nature.",cn:"我喜欢大自然。",ipa:"/aɪ laɪk ˈneɪtʃə/"},
  ],
  "Day 20":[
    {en:"What day is it today?",cn:"今天星期几？",ipa:"/wɒt deɪ ɪz ɪt təˈdeɪ/"},
    {en:"It is Monday.",cn:"星期一。",ipa:"/ɪt ɪz ˈmʌndeɪ/"},
    {en:"It is Tuesday.",cn:"星期二。",ipa:"/ɪt ɪz ˈtjuːzdeɪ/"},
    {en:"It is Wednesday.",cn:"星期三。",ipa:"/ɪt ɪz ˈwenzdeɪ/"},
    {en:"It is Thursday.",cn:"星期四。",ipa:"/ɪt ɪz ˈθɜːzdeɪ/"},
    {en:"It is Friday.",cn:"星期五。",ipa:"/ɪt ɪz ˈfraɪdeɪ/"},
    {en:"It is Saturday.",cn:"星期六。",ipa:"/ɪt ɪz ˈsætədeɪ/"},
    {en:"It is Sunday.",cn:"星期日。",ipa:"/ɪt ɪz ˈsʌndeɪ/"},
    {en:"See you next time.",cn:"下次见。",ipa:"/siː juː nekst taɪm/"},
    {en:"Good night.",cn:"晚安。",ipa:"/ɡʊd naɪt/"},
  ],
  "Day 21":[
    {en:"I want to improve my English.",cn:"我想提高我的英语。",ipa:"/aɪ wɒnt tuː ɪmˈpruːv maɪ ˈɪŋɡlɪʃ/"},
    {en:"I read every day.",cn:"我每天阅读。",ipa:"/aɪ riːd ˈevri deɪ/"},
    {en:"I listen every day.",cn:"我每天听。",ipa:"/aɪ ˈlɪsn ˈevri deɪ/"},
    {en:"I speak every day.",cn:"我每天说。",ipa:"/aɪ spiːk ˈevri deɪ/"},
    {en:"I practice every day.",cn:"我每天练习。",ipa:"/aɪ ˈpræktɪs ˈevri deɪ/"},
    {en:"Practice makes perfect.",cn:"熟能生巧。",ipa:"/ˈpræktɪs meɪks ˈpɜːfɪkt/"},
    {en:"I will not give up.",cn:"我不会放弃。",ipa:"/aɪ wɪl nɒt ɡɪv ʌp/"},
    {en:"I can do it.",cn:"我可以做到。",ipa:"/aɪ kæn duː ɪt/"},
    {en:"I am getting better.",cn:"我正在变得更好。",ipa:"/aɪ æm ˈɡetɪŋ ˈbetə/"},
    {en:"I feel proud.",cn:"我感到自豪。",ipa:"/aɪ fiːl praʊd/"},
  ],
  "Day 22":[
    {en:"What do you want?",cn:"你想要什么？",ipa:"/wɒt duː juː wɒnt/"},
    {en:"I want some water.",cn:"我想要一些水。",ipa:"/aɪ wɒnt sʌm ˈwɔːtə/"},
    {en:"I want some bread.",cn:"我想要一些面包。",ipa:"/aɪ wɒnt sʌm bred/"},
    {en:"I want some fruit.",cn:"我想要一些水果。",ipa:"/aɪ wɒnt sʌm fruːt/"},
    {en:"I want to rest.",cn:"我想休息。",ipa:"/aɪ wɒnt tuː rest/"},
    {en:"I want to play.",cn:"我想玩。",ipa:"/aɪ wɒnt tuː pleɪ/"},
    {en:"I want to learn.",cn:"我想学习。",ipa:"/aɪ wɒnt tuː lɜːn/"},
    {en:"I want to help.",cn:"我想帮忙。",ipa:"/aɪ wɒnt tuː help/"},
    {en:"I want to try.",cn:"我想试试。",ipa:"/aɪ wɒnt tuː traɪ/"},
    {en:"I want to win.",cn:"我想赢。",ipa:"/aɪ wɒnt tuː wɪn/"},
  ],
  "Day 23":[
    {en:"I am hungry.",cn:"我饿了。",ipa:"/aɪ æm ˈhʌŋɡri/"},
    {en:"I am thirsty.",cn:"我渴了。",ipa:"/aɪ æm ˈθɜːsti/"},
    {en:"I need a break.",cn:"我需要休息。",ipa:"/aɪ niːd ə breɪk/"},
    {en:"Let’s eat.",cn:"我们吃吧。",ipa:"/lets iːt/"},
    {en:"Let’s drink water.",cn:"我们喝水吧。",ipa:"/lets drɪŋk ˈwɔːtə/"},
    {en:"Let’s go home.",cn:"我们回家吧。",ipa:"/lets ɡəʊ həʊm/"},
    {en:"Let’s go to the park.",cn:"我们去公园吧。",ipa:"/lets ɡəʊ tuː ðə pɑːk/"},
    {en:"Let’s study now.",cn:"我们现在学习吧。",ipa:"/lets ˈstʌdi naʊ/"},
    {en:"Let’s do homework.",cn:"我们写作业吧。",ipa:"/lets duː ˈhəʊmwɜːk/"},
    {en:"Let’s sleep.",cn:"我们睡吧。",ipa:"/lets sliːp/"},
  ],
  "Day 24":[
    {en:"I have time.",cn:"我有时间。",ipa:"/aɪ hæv taɪm/"},
    {en:"I have no time.",cn:"我没时间。",ipa:"/aɪ hæv nəʊ taɪm/"},
    {en:"I am early.",cn:"我来早了。",ipa:"/aɪ æm ˈɜːli/"},
    {en:"I am late.",cn:"我迟到了。",ipa:"/aɪ æm leɪt/"},
    {en:"I am ready.",cn:"我准备好了。",ipa:"/aɪ æm ˈredi/"},
    {en:"I am busy.",cn:"我很忙。",ipa:"/aɪ æm ˈbɪzi/"},
    {en:"I am free.",cn:"我有空。",ipa:"/aɪ æm friː/"},
    {en:"I am happy.",cn:"我很开心。",ipa:"/aɪ æm ˈhæpi/"},
    {en:"I am sad.",cn:"我有点难过。",ipa:"/aɪ æm sæd/"},
    {en:"I am okay.",cn:"我没事。",ipa:"/aɪ æm ˌəʊˈkeɪ/"},
  ],
  "Day 25":[
    {en:"I like this one.",cn:"我喜欢这个。",ipa:"/aɪ laɪk ðɪs wʌn/"},
    {en:"I want this one.",cn:"我想要这个。",ipa:"/aɪ wɒnt ðɪs wʌn/"},
    {en:"How much is it?",cn:"它多少钱？",ipa:"/haʊ mʌtʃ ɪz ɪt/"},
    {en:"That is cheap.",cn:"那很便宜。",ipa:"/ðæt ɪz tʃiːp/"},
    {en:"That is expensive.",cn:"那很贵。",ipa:"/ðæt ɪz ɪkˈspensɪv/"},
    {en:"Do you have a discount?",cn:"有折扣吗？",ipa:"/duː juː hæv ə ˈdɪskaʊnt/"},
    {en:"I will take it.",cn:"我买了。",ipa:"/aɪ wɪl teɪk ɪt/"},
    {en:"Thank you for your help.",cn:"谢谢你的帮助。",ipa:"/θæŋk juː fɔː jɔː help/"},
    {en:"Have a nice day.",cn:"祝你今天愉快。",ipa:"/hæv ə naɪs deɪ/"},
    {en:"See you tomorrow.",cn:"明天见。",ipa:"/siː juː təˈmɒrəʊ/"},
  ],
  "Day 26":[
    {en:"I like to learn.",cn:"我喜欢学习。",ipa:"/aɪ laɪk tuː lɜːn/"},
    {en:"I like to practice.",cn:"我喜欢练习。",ipa:"/aɪ laɪk tuː ˈpræktɪs/"},
    {en:"I need practice.",cn:"我需要练习。",ipa:"/aɪ niːd ˈpræktɪs/"},
    {en:"I will keep practicing.",cn:"我会继续练习。",ipa:"/aɪ wɪl kiːp ˈpræktɪsɪŋ/"},
    {en:"I will try my best.",cn:"我会尽力。",ipa:"/aɪ wɪl traɪ maɪ best/"},
    {en:"I will study hard.",cn:"我会努力学习。",ipa:"/aɪ wɪl ˈstʌdi hɑːd/"},
    {en:"I will be better.",cn:"我会更好。",ipa:"/aɪ wɪl biː ˈbetə/"},
    {en:"I will not stop.",cn:"我不会停。",ipa:"/aɪ wɪl nɒt stɒp/ "},
    {en:"I will not give up.",cn:"我不会放弃。",ipa:"/aɪ wɪl nɒt ɡɪv ʌp/"},
    {en:"I will win.",cn:"我会赢。",ipa:"/aɪ wɪl wɪn/"},
  ],
  "Day 27":[
    {en:"I live here.",cn:"我住在这里。",ipa:"/aɪ lɪv hɪə/"},
    {en:"I go home.",cn:"我回家。",ipa:"/aɪ ɡəʊ həʊm/"},
    {en:"I go to work.",cn:"我去上班。",ipa:"/aɪ ɡəʊ tuː wɜːk/"},
    {en:"I go to school.",cn:"我去上学。",ipa:"/aɪ ɡəʊ tuː skuːl/"},
    {en:"I like my home.",cn:"我喜欢我家。",ipa:"/aɪ laɪk maɪ həʊm/"},
    {en:"I like my city.",cn:"我喜欢我的城市。",ipa:"/aɪ laɪk maɪ ˈsɪti/"},
    {en:"I like my life.",cn:"我喜欢我的生活。",ipa:"/aɪ laɪk maɪ laɪf/"},
    {en:"I like my job.",cn:"我喜欢我的工作。",ipa:"/aɪ laɪk maɪ dʒɒb/"},
    {en:"I like my family.",cn:"我爱我的家人。",ipa:"/aɪ laɪk maɪ ˈfæməli/"},
    {en:"I love you.",cn:"我爱你。",ipa:"/aɪ lʌv juː/"},
  ],
  "Day 28":[
    {en:"Today is a good day.",cn:"今天是美好的一天。",ipa:"/təˈdeɪ ɪz ə ɡʊd deɪ/"},
    {en:"Tomorrow will be better.",cn:"明天会更好。",ipa:"/təˈmɒrəʊ wɪl biː ˈbetə/"},
    {en:"I can do it.",cn:"我可以做到。",ipa:"/aɪ kæn duː ɪt/"},
    {en:"I will keep going.",cn:"我会继续坚持。",ipa:"/aɪ wɪl kiːp ˈɡəʊɪŋ/"},
    {en:"I will keep practicing.",cn:"我会继续练习。",ipa:"/aɪ wɪl kiːp ˈpræktɪsɪŋ/"},
    {en:"Good luck!",cn:"祝你好运！",ipa:"/ɡʊd lʌk/"},
    {en:"Great job!",cn:"做得好！",ipa:"/ɡreɪt dʒɒb/"},
    {en:"Well done!",cn:"干得漂亮！",ipa:"/wel dʌn/"},
    {en:"Keep it up!",cn:"继续保持！",ipa:"/kiːp ɪt ʌp/"},
    {en:"You are the best!",cn:"你最棒！",ipa:"/juː ɑː ðə best/"},
  ],
  "Day 29":[
    {en:"What is your name?",cn:"你叫什么名字？",ipa:"/wɒt ɪz jɔː neɪm/"},
    {en:"My name is Lily.",cn:"我叫莉莉。",ipa:"/maɪ neɪm ɪz ˈlɪli/"},
    {en:"How old are you?",cn:"你多大了？",ipa:"/haʊ əʊld ɑː juː/"},
    {en:"I am twelve years old.",cn:"我十二岁。",ipa:"/aɪ æm twelv jɪəz əʊld/"},
    {en:"What do you like?",cn:"你喜欢什么？",ipa:"/wɒt duː juː laɪk/"},
    {en:"I like reading books.",cn:"我喜欢看书。",ipa:"/aɪ laɪk ˈriːdɪŋ bʊks/"},
    {en:"What time is it?",cn:"现在几点？",ipa:"/wɒt taɪm ɪz ɪt/"},
    {en:"It is eight o’clock.",cn:"八点了。",ipa:"/ɪt ɪz eɪt əˈklɒk/"},
    {en:"Nice to meet you.",cn:"很高兴认识你。",ipa:"/naɪs tuː miːt juː/"},
    {en:"See you later.",cn:"回头见。",ipa:"/siː juː ˈleɪtə/"},
  ],
  "Day 30":[
    {en:"I can do it.",cn:"我可以做到。",ipa:"/aɪ kæn duː ɪt/"},
    {en:"I will keep practicing.",cn:"我会继续练习。",ipa:"/aɪ wɪl kiːp ˈpræktɪsɪŋ/"},
    {en:"Tomorrow will be better.",cn:"明天会更好。",ipa:"/təˈmɒrəʊ wɪl biː ˈbetə/"},
    {en:"I will not give up.",cn:"我不会放弃。",ipa:"/aɪ wɪl nɒt ɡɪv ʌp/"},
    {en:"Practice makes perfect.",cn:"熟能生巧。",ipa:"/ˈpræktɪs meɪks ˈpɜːfɪkt/"},
    {en:"I am improving.",cn:"我在进步。",ipa:"/aɪ æm ɪmˈpruːvɪŋ/"},
    {en:"I feel proud.",cn:"我感到自豪。",ipa:"/aɪ fiːl praʊd/"},
    {en:"Thank you for your help.",cn:"谢谢你的帮助。",ipa:"/θæŋk juː fɔː jɔː help/"},
    {en:"Good luck!",cn:"祝你好运！",ipa:"/ɡʊd lʌk/"},
    {en:"Great job!",cn:"做得好！",ipa:"/ɡreɪt dʒɒb/"},
  ],

  "小学六年级":[
    // 词汇（常用）
    {en:"apple",cn:"苹果",ipa:"/ˈæpl/"},
    {en:"banana",cn:"香蕉",ipa:"/bəˈnɑːnə/"},
    {en:"book",cn:"书",ipa:"/bʊk/"},
    {en:"teacher",cn:"老师",ipa:"/ˈtiːtʃə/"},
    {en:"student",cn:"学生",ipa:"/ˈstjuːdənt/"},
    {en:"family",cn:"家庭",ipa:"/ˈfæməli/"},
    {en:"school",cn:"学校",ipa:"/skuːl/"},
    {en:"homework",cn:"作业",ipa:"/ˈhəʊmwɜːk/"},
    {en:"computer",cn:"电脑",ipa:"/kəmˈpjuːtə/"},
    {en:"internet",cn:"互联网",ipa:"/ˈɪntənet/"},
    {en:"holiday",cn:"假期",ipa:"/ˈhɒlədeɪ/"},
    {en:"travel",cn:"旅行",ipa:"/ˈtrævl/"},
    {en:"future",cn:"未来",ipa:"/ˈfjuːtʃə/"},
    {en:"important",cn:"重要的",ipa:"/ɪmˈpɔːtnt/"},
    {en:"different",cn:"不同的",ipa:"/ˈdɪfrənt/"},
    {en:"problem",cn:"问题",ipa:"/ˈprɒbləm/"},
    {en:"answer",cn:"答案",ipa:"/ˈɑːnsə/"},
    {en:"example",cn:"例子",ipa:"/ɪɡˈzɑːmpl/"},
    {en:"remember",cn:"记住",ipa:"/rɪˈmembə/"},
    {en:"improve",cn:"提高",ipa:"/ɪmˈpruːv/"},

    // 句子（六年级常用表达）
    {en:"I want to improve my English.",cn:"我想提高我的英语。",ipa:"/aɪ wɒnt tuː ɪmˈpruːv maɪ ˈɪŋɡlɪʃ/"},
    {en:"It is important to read every day.",cn:"每天阅读很重要。",ipa:"/ɪt ɪz ɪmˈpɔːtnt tuː riːd ˈevri deɪ/"},
    {en:"We are different but we can be friends.",cn:"我们不同但可以做朋友。",ipa:"/wiː ɑː ˈdɪfrənt bʌt wiː kæn biː frends/"},
    {en:"When I have a problem, I ask for help.",cn:"当我有问题时我会求助。",ipa:"/wen aɪ hæv ə ˈprɒbləm aɪ ɑːsk fɔː help/"},
    {en:"Please give me an example.",cn:"请给我一个例子。",ipa:"/pliːz ɡɪv miː ən ɪɡˈzɑːmpl/"},
    {en:"I want to be a doctor in the future.",cn:"我将来想当医生。",ipa:"/aɪ wɒnt tuː biː ə ˈdɒktə ɪn ðə ˈfjuːtʃə/"},
    {en:"I do my homework after school.",cn:"放学后我做作业。",ipa:"/aɪ duː maɪ ˈhəʊmwɜːk ˈɑːftə skuːl/"},
    {en:"I go to school by bus.",cn:"我坐公交去上学。",ipa:"/aɪ ɡəʊ tuː skuːl baɪ bʌs/"},
    {en:"Practice makes perfect.",cn:"熟能生巧。",ipa:"/ˈpræktɪs meɪks ˈpɜːfɪkt/"},
    {en:"I will try my best.",cn:"我会尽力。",ipa:"/aɪ wɪl traɪ maɪ best/"},
  ],

  "音标-元音 (20个)":[
    // 单元音 - 长元音
    {en:"i:",cn:"长元音 [i:] (see, tea)"},
    {en:"ɑ:",cn:"长元音 [ɑ:] (car, father)"},
    {en:"ɔ:",cn:"长元音 [ɔ:] (door, saw)"},
    {en:"u:",cn:"长元音 [u:] (food, blue)"},
    {en:"ɜ:",cn:"长元音 [ɜ:] (bird, her)"},
    
    // 单元音 - 短元音
    {en:"ɪ",cn:"短元音 [ɪ] (sit, pig)"},
    {en:"e",cn:"短元音 [e] (bed, egg)"},
    {en:"æ",cn:"短元音 [æ] (cat, map)"},
    {en:"ʌ",cn:"短元音 [ʌ] (cup, bus)"},
    {en:"ɒ",cn:"短元音 [ɒ] (dog, hot)"},
    {en:"ʊ",cn:"短元音 [ʊ] (book, good)"},
    {en:"ə",cn:"短元音 [ə] (teacher, banana)"},

    // 双元音
    {en:"eɪ",cn:"双元音 [eɪ] (day, face)"},
    {en:"aɪ",cn:"双元音 [aɪ] (my, bike)"},
    {en:"ɔɪ",cn:"双元音 [ɔɪ] (boy, toy)"},
    {en:"əʊ",cn:"双元音 [əʊ] (no, go)"},
    {en:"aʊ",cn:"双元音 [aʊ] (now, cow)"},
    {en:"ɪə",cn:"双元音 [ɪə] (ear, here)"},
    {en:"eə",cn:"双元音 [eə] (air, care)"},
    {en:"ʊə",cn:"双元音 [ʊə] (tour, sure)"},
  ],

  "音标-辅音 (28个)":[
    // 爆破音
    {en:"p",cn:"清辅音 [p] (pen)"},
    {en:"b",cn:"浊辅音 [b] (bed)"},
    {en:"t",cn:"清辅音 [t] (tea)"},
    {en:"d",cn:"浊辅音 [d] (dog)"},
    {en:"k",cn:"清辅音 [k] (key)"},
    {en:"g",cn:"浊辅音 [g] (go)"},

    // 摩擦音
    {en:"f",cn:"清辅音 [f] (fish)"},
    {en:"v",cn:"浊辅音 [v] (very)"},
    {en:"s",cn:"清辅音 [s] (sun)"},
    {en:"z",cn:"浊辅音 [z] (zoo)"},
    {en:"θ",cn:"清辅音 [θ] (three)"},
    {en:"ð",cn:"浊辅音 [ð] (this)"},
    {en:"ʃ",cn:"清辅音 [ʃ] (she)"},
    {en:"ʒ",cn:"浊辅音 [ʒ] (pleasure)"},
    {en:"h",cn:"清辅音 [h] (hat)"},
    {en:"r",cn:"浊辅音 [r] (red)"},

    // 破擦音
    {en:"tʃ",cn:"清辅音 [tʃ] (chair)"},
    {en:"dʒ",cn:"浊辅音 [dʒ] (job)"},
    {en:"tr",cn:"清辅音 [tr] (tree)"},
    {en:"dr",cn:"浊辅音 [dr] (dress)"},
    {en:"ts",cn:"清辅音 [ts] (cats)"},
    {en:"dz",cn:"浊辅音 [dz] (beds)"},

    // 鼻音
    {en:"m",cn:"浊辅音 [m] (man)"},
    {en:"n",cn:"浊辅音 [n] (no)"},
    {en:"ŋ",cn:"浊辅音 [ŋ] (sing)"},

    // 舌侧音
    {en:"l",cn:"浊辅音 [l] (leg)"},

    // 半元音
    {en:"w",cn:"浊辅音 [w] (we)"},
    {en:"j",cn:"浊辅音 [j] (yes)"},
  ],

  "高频词汇 Level 1 (Top 100)":[
    {en:"the",cn:"这/那 (定冠词)",ipa:"/ðə/"}, {en:"be",cn:"是/在",ipa:"/biː/"}, {en:"to",cn:"去/向",ipa:"/tuː/"}, {en:"of",cn:"...的",ipa:"/ɒv/"}, {en:"and",cn:"和",ipa:"/ænd/"},
    {en:"a",cn:"一个",ipa:"/ə/"}, {en:"in",cn:"在...里",ipa:"/ɪn/"}, {en:"that",cn:"那个",ipa:"/ðæt/",ipa:"/ðæt/"}, {en:"have",cn:"有/吃",ipa:"/hæv/"}, {en:"I",cn:"我",ipa:"/aɪ/"},
    {en:"it",cn:"它",ipa:"/ɪt/"}, {en:"for",cn:"为了",ipa:"/fɔː/"}, {en:"not",cn:"不",ipa:"/nɒt/"}, {en:"on",cn:"在...上",ipa:"/ɒn/"}, {en:"with",cn:"和...一起",ipa:"/wɪð/"},
    {en:"he",cn:"他",ipa:"/hiː/"}, {en:"as",cn:"作为/像",ipa:"/æz/"}, {en:"you",cn:"你",ipa:"/juː/"}, {en:"do",cn:"做",ipa:"/duː/"}, {en:"at",cn:"在",ipa:"/æt/"},
    {en:"this",cn:"这个",ipa:"/ðɪs/"}, {en:"but",cn:"但是",ipa:"/bʌt/"}, {en:"his",cn:"他的",ipa:"/hɪz/"}, {en:"by",cn:"被/由",ipa:"/baɪ/"}, {en:"from",cn:"来自",ipa:"/frɒm/"},
    {en:"they",cn:"他们",ipa:"/ðeɪ/"}, {en:"we",cn:"我们",ipa:"/wiː/"}, {en:"say",cn:"说",ipa:"/seɪ/"}, {en:"her",cn:"她的",ipa:"/hɜː/"}, {en:"she",cn:"她",ipa:"/ʃiː/"},
    {en:"or",cn:"或者",ipa:"/ɔː/"}, {en:"an",cn:"一个",ipa:"/æn/"}, {en:"will",cn:"将要",ipa:"/wɪl/"}, {en:"my",cn:"我的",ipa:"/maɪ/"}, {en:"one",cn:"一个",ipa:"/wʌn/",ipa:"/wʌn/"},
    {en:"all",cn:"所有",ipa:"/ɔːl/",ipa:"/ɔːl/"}, {en:"would",cn:"将要(过去式)",ipa:"/wʊd/"}, {en:"there",cn:"那里",ipa:"/ðeə/"}, {en:"their",cn:"他们的",ipa:"/ðeə/"}, {en:"what",cn:"什么",ipa:"/wɒt/"},
    {en:"so",cn:"所以",ipa:"/səʊ/"}, {en:"up",cn:"向上",ipa:"/ʌp/",ipa:"/ʌp/"}, {en:"out",cn:"外面",ipa:"/aʊt/"}, {en:"if",cn:"如果",ipa:"/ɪf/"}, {en:"about",cn:"关于",ipa:"/əˈbaʊt/",ipa:"/əˈbaʊt/"},
    {en:"who",cn:"谁",ipa:"/huː/"}, {en:"get",cn:"得到",ipa:"/ɡet/"}, {en:"which",cn:"哪一个",ipa:"/wɪtʃ/"}, {en:"go",cn:"去",ipa:"/ɡəʊ/"}, {en:"me",cn:"我(宾格)",ipa:"/miː/"},
    {en:"when",cn:"什么时候",ipa:"/wen/"}, {en:"make",cn:"制作",ipa:"/meɪk/"}, {en:"can",cn:"可以",ipa:"/kæn/"}, {en:"like",cn:"喜欢/像",ipa:"/laɪk/",ipa:"/laɪk/"}, {en:"time",cn:"时间",ipa:"/taɪm/"},
    {en:"no",cn:"不",ipa:"/nəʊ/",ipa:"/nəʊ/"}, {en:"just",cn:"仅仅/刚才",ipa:"/dʒʌst/"}, {en:"him",cn:"他(宾格)",ipa:"/hɪm/"}, {en:"know",cn:"知道",ipa:"/nəʊ/"}, {en:"take",cn:"拿",ipa:"/teɪk/"},
    {en:"people",cn:"人们",ipa:"/piːpl/"}, {en:"into",cn:"进入",ipa:"/ɪntuː/"}, {en:"year",cn:"年",ipa:"/jɪə/"}, {en:"your",cn:"你的",ipa:"/jɔː/"}, {en:"good",cn:"好",ipa:"/ɡʊd/"},
    {en:"some",cn:"一些",ipa:"/sʌm/"}, {en:"could",cn:"可以(过去式)",ipa:"/kʊd/"}, {en:"them",cn:"他们(宾格)",ipa:"/ðem/"}, {en:"see",cn:"看见",ipa:"/siː/"}, {en:"other",cn:"其他的",ipa:"/ʌðə/",ipa:"/ˈʌðə/"},
    {en:"than",cn:"比",ipa:"/ðæn/",ipa:"/ðæn/"}, {en:"then",cn:"然后",ipa:"/ðen/"}, {en:"now",cn:"现在",ipa:"/naʊ/"}, {en:"look",cn:"看",ipa:"/lʊk/",ipa:"/lʊk/"}, {en:"only",cn:"只有",ipa:"/əʊnli/",ipa:"/ˈəʊnli/"},
    {en:"come",cn:"来",ipa:"/kʌm/"}, {en:"its",cn:"它的",ipa:"/ɪts/"}, {en:"over",cn:"结束/在...之上",ipa:"/əʊvə/",ipa:"/ˈəʊvə/"}, {en:"think",cn:"想",ipa:"/θɪŋk/"}, {en:"also",cn:"也",ipa:"/ɔːlsəʊ/"},
    {en:"back",cn:"回来/背部",ipa:"/bæk/",ipa:"/bæk/"}, {en:"after",cn:"在...之后",ipa:"/ɑːftə/",ipa:"/ˈɑːftə/"}, {en:"use",cn:"使用",ipa:"/juːz/",ipa:"/juːz/"}, {en:"two",cn:"二",ipa:"/tuː/"}, {en:"how",cn:"如何",ipa:"/haʊ/"},
    {en:"our",cn:"我们的",ipa:"/aʊə/"}, {en:"work",cn:"工作",ipa:"/wɜːk/",ipa:"/wɜːk/"}, {en:"first",cn:"第一",ipa:"/fɜːst/"}, {en:"well",cn:"好/井",ipa:"/wel/",ipa:"/wel/"}, {en:"way",cn:"方式/路",ipa:"/weɪ/"},
    {en:"even",cn:"甚至",ipa:"/iːvn/",ipa:"/ˈiːvn/"}, {en:"new",cn:"新",ipa:"/njuː/"}, {en:"want",cn:"想要",ipa:"/wɒnt/"}, {en:"because",cn:"因为",ipa:"/bɪˈkɒz/",ipa:"/bɪˈkɒz/"}, {en:"any",cn:"任何",ipa:"/eni/"},
    {en:"these",cn:"这些",ipa:"/ðiːz/"}, {en:"give",cn:"给",ipa:"/ɡɪv/"}, {en:"day",cn:"天",ipa:"/deɪ/"}, {en:"most",cn:"大多数",ipa:"/məʊst/",ipa:"/məʊst/"}, {en:"us",cn:"我们(宾格)",ipa:"/ʌs/"}
  ],
  "高频词汇 Level 2 (Top 100-200)":[
    {en:"is",cn:"是",ipa:"/ɪz/"}, {en:"are",cn:"是(复数)",ipa:"/ɑː/"}, {en:"was",cn:"是(过去式)",ipa:"/wɒz/"}, {en:"were",cn:"是(复数过去式)",ipa:"/wɜː/"}, {en:"has",cn:"有(单三)",ipa:"/hæz/"},
    {en:"had",cn:"有(过去式)",ipa:"/hæd/"}, {en:"did",cn:"做(过去式)",ipa:"/dɪd/"}, {en:"been",cn:"是(过去分词)",ipa:"/biːn/"}, {en:"said",cn:"说(过去式)",ipa:"/sed/"}, {en:"made",cn:"制作(过去式)",ipa:"/meɪd/"},
    {en:"went",cn:"去(过去式)",ipa:"/went/"}, {en:"came",cn:"来(过去式)",ipa:"/keɪm/"}, {en:"saw",cn:"看见(过去式)",ipa:"/sɔː/"}, {en:"knew",cn:"知道(过去式)",ipa:"/njuː/"}, {en:"got",cn:"得到(过去式)",ipa:"/ɡɒt/"},
    {en:"took",cn:"拿(过去式)",ipa:"/tʊk/"}, {en:"gave",cn:"给(过去式)",ipa:"/ɡeɪv/"}, {en:"found",cn:"发现(过去式)",ipa:"/faʊnd/"}, {en:"told",cn:"告诉(过去式)",ipa:"/təʊld/"}, {en:"thought",cn:"想(过去式)",ipa:"/θɔːt/",ipa:"/θɔːt/"},
    {en:"find",cn:"发现",ipa:"/faɪnd/"}, {en:"tell",cn:"告诉",ipa:"/tel/"}, {en:"ask",cn:"问",ipa:"/ɑːsk/"}, {en:"seem",cn:"似乎",ipa:"/siːm/",ipa:"/siːm/"}, {en:"feel",cn:"感觉",ipa:"/fiːl/"},
    {en:"try",cn:"尝试",ipa:"/traɪ/"}, {en:"leave",cn:"离开",ipa:"/liːv/"}, {en:"call",cn:"打电话/叫",ipa:"/kɔːl/",ipa:"/kɔːl/"}, {en:"need",cn:"需要",ipa:"/niːd/",ipa:"/niːd/"}, {en:"should",cn:"应该",ipa:"/ʃʊd/"},
    {en:"become",cn:"变成",ipa:"/bɪˈkʌm/"}, {en:"mean",cn:"意味着",ipa:"/miːn/"}, {en:"keep",cn:"保持",ipa:"/kiːp/"}, {en:"let",cn:"让",ipa:"/let/",ipa:"/let/"}, {en:"begin",cn:"开始",ipa:"/bɪˈɡɪn/",ipa:"/bɪˈɡɪn/"},
    {en:"help",cn:"帮助",ipa:"/help/",ipa:"/help/"}, {en:"talk",cn:"谈话",ipa:"/tɔːk/",ipa:"/tɔːk/"}, {en:"turn",cn:"转/变成",ipa:"/tɜːn/",ipa:"/tɜːn/"}, {en:"start",cn:"开始",ipa:"/stɑːt/",ipa:"/stɑːt/"}, {en:"show",cn:"展示",ipa:"/ʃəʊ/",ipa:"/ʃəʊ/"},
    {en:"hear",cn:"听见",ipa:"/hɪə/",ipa:"/hɪə/"}, {en:"play",cn:"玩",ipa:"/pleɪ/",ipa:"/pleɪ/"}, {en:"run",cn:"跑",ipa:"/rʌn/",ipa:"/rʌn/"}, {en:"move",cn:"移动",ipa:"/muːv/",ipa:"/muːv/"}, {en:"live",cn:"居住",ipa:"/lɪv/",ipa:"/lɪv/"},
    {en:"believe",cn:"相信",ipa:"/bɪˈliːv/",ipa:"/bɪˈliːv/"}, {en:"bring",cn:"带来",ipa:"/brɪŋ/",ipa:"/brɪŋ/"}, {en:"happen",cn:"发生",ipa:"/hæpən/",ipa:"/hæpən/"}, {en:"must",cn:"必须",ipa:"/mʌst/",ipa:"/mʌst/"}, {en:"write",cn:"写",ipa:"/raɪt/",ipa:"/raɪt/"},
    {en:"provide",cn:"提供",ipa:"/prəˈvaɪd/",ipa:"/prəˈvaɪd/"}, {en:"sit",cn:"坐",ipa:"/sɪt/",ipa:"/sɪt/"}, {en:"stand",cn:"站",ipa:"/stænd/",ipa:"/stænd/"}, {en:"lose",cn:"丢失",ipa:"/luːz/",ipa:"/luːz/"}, {en:"pay",cn:"支付",ipa:"/peɪ/",ipa:"/peɪ/"},
    {en:"meet",cn:"遇见",ipa:"/miːt/",ipa:"/miːt/"}, {en:"include",cn:"包括",ipa:"/ɪnˈkluːd/",ipa:"/ɪnˈkluːd/"}, {en:"continue",cn:"继续",ipa:"/kənˈtɪnjuː/",ipa:"/kənˈtɪnjuː/"}, {en:"set",cn:"设置",ipa:"/set/",ipa:"/set/"}, {en:"learn",cn:"学习",ipa:"/lɜːn/",ipa:"/lɜːn/"},
    {en:"change",cn:"改变",ipa:"/tʃeɪndʒ/",ipa:"/tʃeɪndʒ/"}, {en:"lead",cn:"领导",ipa:"/liːd/",ipa:"/liːd/"}, {en:"understand",cn:"理解",ipa:"/ˌʌndəˈstænd/",ipa:"/ˌʌndəˈstænd/"}, {en:"watch",cn:"观看",ipa:"/wɒtʃ/",ipa:"/wɒtʃ/"}, {en:"follow",cn:"跟随",ipa:"/fɒləʊ/",ipa:"/ˈfɒləʊ/"},
    {en:"stop",cn:"停止",ipa:"/stɒp/",ipa:"/stɒp/"}, {en:"create",cn:"创造",ipa:"/kriːˈeɪt/",ipa:"/kriːˈeɪt/"}, {en:"speak",cn:"说(语言)",ipa:"/spiːk/",ipa:"/spiːk/"}, {en:"read",cn:"读",ipa:"/riːd/",ipa:"/riːd/"}, {en:"allow",cn:"允许",ipa:"/əˈlaʊ/",ipa:"/əˈlaʊ/"},
    {en:"add",cn:"增加",ipa:"/æd/",ipa:"/æd/"}, {en:"spend",cn:"花费",ipa:"/spend/",ipa:"/spend/"}, {en:"grow",cn:"成长",ipa:"/ɡrəʊ/",ipa:"/ɡrəʊ/"}, {en:"open",cn:"打开",ipa:"/əʊpən/",ipa:"/ˈəʊpən/"}, {en:"walk",cn:"走",ipa:"/wɔːk/",ipa:"/wɔːk/"},
    {en:"win",cn:"赢",ipa:"/wɪn/",ipa:"/wɪn/"}, {en:"offer",cn:"提供",ipa:"/ɒfə/",ipa:"/ˈɒfə/"}, {en:"remember",cn:"记得",ipa:"/rɪˈmembə/",ipa:"/rɪˈmembə/"}, {en:"love",cn:"爱",ipa:"/lʌv/",ipa:"/lʌv/"}, {en:"consider",cn:"考虑",ipa:"/kənˈsɪdə/",ipa:"/kənˈsɪdə/"},
    {en:"appear",cn:"出现",ipa:"/əˈpɪə/",ipa:"/əˈpɪə/"}, {en:"buy",cn:"买",ipa:"/baɪ/",ipa:"/baɪ/"}, {en:"wait",cn:"等待",ipa:"/weɪt/",ipa:"/weɪt/"}, {en:"serve",cn:"服务",ipa:"/sɜːv/",ipa:"/sɜːv/"}, {en:"die",cn:"死",ipa:"/daɪ/",ipa:"/daɪ/"},
    {en:"send",cn:"发送",ipa:"/send/",ipa:"/send/"}, {en:"expect",cn:"期待",ipa:"/ɪkˈspekt/",ipa:"/ɪkˈspekt/"}, {en:"build",cn:"建立",ipa:"/bɪld/",ipa:"/bɪld/"}, {en:"stay",cn:"停留",ipa:"/steɪ/",ipa:"/steɪ/"}, {en:"fall",cn:"落下",ipa:"/fɔːl/",ipa:"/fɔːl/"},
    {en:"cut",cn:"切",ipa:"/kʌt/",ipa:"/kʌt/"}, {en:"reach",cn:"到达",ipa:"/riːtʃ/",ipa:"/riːtʃ/"}, {en:"kill",cn:"杀",ipa:"/kɪl/",ipa:"/kɪl/"}, {en:"remain",cn:"保持",ipa:"/rɪˈmeɪn/",ipa:"/rɪˈmeɪn/"}, {en:"suggest",cn:"建议",ipa:"/səˈdʒest/",ipa:"/səˈdʒest/"}
  ],

  "高频词汇 Level 3 (Top 200-500)":[
    {en:"student",cn:"学生",ipa:"/ˈstjuːdənt/"}, {en:"why",cn:"为什么",ipa:"/waɪ/"}, {en:"let",cn:"让",ipa:"/let/"}, {en:"great",cn:"伟大的",ipa:"/ɡreɪt/"}, {en:"same",cn:"相同的",ipa:"/seɪm/"},
    {en:"big",cn:"大的",ipa:"/bɪɡ/"}, {en:"group",cn:"组/群",ipa:"/ɡruːp/"}, {en:"begin",cn:"开始",ipa:"/bɪˈɡɪn/"}, {en:"seem",cn:"似乎",ipa:"/siːm/"}, {en:"country",cn:"国家",ipa:"/ˈkʌntri/"},
    {en:"help",cn:"帮助",ipa:"/help/"}, {en:"talk",cn:"谈话",ipa:"/tɔːk/"}, {en:"where",cn:"在哪里",ipa:"/weə/"}, {en:"turn",cn:"转/变成",ipa:"/tɜːn/"}, {en:"problem",cn:"问题",ipa:"/ˈprɒbləm/"},
    {en:"every",cn:"每一个",ipa:"/ˈevri/"}, {en:"start",cn:"开始",ipa:"/stɑːt/"}, {en:"hand",cn:"手",ipa:"/hænd/"}, {en:"might",cn:"可能",ipa:"/maɪt/"}, {en:"American",cn:"美国的",ipa:"/əˈmerɪkən/"},
    {en:"show",cn:"展示",ipa:"/ʃəʊ/"}, {en:"part",cn:"部分",ipa:"/pɑːt/"}, {en:"about",cn:"关于",ipa:"/əˈbaʊt/"}, {en:"against",cn:"反对",ipa:"/əˈɡenst/"}, {en:"place",cn:"地方",ipa:"/pleɪs/"},
    {en:"over",cn:"结束/在...之上",ipa:"/ˈəʊvə/"}, {en:"such",cn:"这样的",ipa:"/sʌtʃ/"}, {en:"again",cn:"再一次",ipa:"/əˈɡen/"}, {en:"few",cn:"很少",ipa:"/fjuː/"}, {en:"case",cn:"情况/案例",ipa:"/keɪs/"},
    {en:"most",cn:"大多数",ipa:"/məʊst/"}, {en:"week",cn:"周",ipa:"/wiːk/"}, {en:"company",cn:"公司",ipa:"/ˈkʌmpəni/"}, {en:"where",cn:"哪里",ipa:"/weə/"}, {en:"system",cn:"系统",ipa:"/ˈsɪstəm/"},
    {en:"program",cn:"程序/计划",ipa:"/ˈprəʊɡræm/"}, {en:"hear",cn:"听见",ipa:"/hɪə/"}, {en:"question",cn:"问题",ipa:"/ˈkwestʃən/"}, {en:"during",cn:"在...期间",ipa:"/ˈdjʊərɪŋ/"}, {en:"work",cn:"工作",ipa:"/wɜːk/"},
    {en:"play",cn:"玩",ipa:"/pleɪ/"}, {en:"government",cn:"政府",ipa:"/ˈɡʌvənmənt/"}, {en:"run",cn:"跑",ipa:"/rʌn/"}, {en:"small",cn:"小的",ipa:"/smɔːl/"}, {en:"number",cn:"数字",ipa:"/ˈnʌmbə/"},
    {en:"off",cn:"离开/关闭",ipa:"/ɒf/"}, {en:"always",cn:"总是",ipa:"/ˈɔːlweɪz/"}, {en:"move",cn:"移动",ipa:"/muːv/"}, {en:"like",cn:"喜欢/像",ipa:"/laɪk/"}, {en:"night",cn:"夜晚",ipa:"/naɪt/"},
    {en:"live",cn:"居住",ipa:"/lɪv/"}, {en:"Mr",cn:"先生",ipa:"/ˈmɪstə/"}, {en:"point",cn:"点/观点",ipa:"/pɔɪnt/"}, {en:"believe",cn:"相信",ipa:"/bɪˈliːv/"}, {en:"hold",cn:"握住/举行",ipa:"/həʊld/"},
    {en:"today",cn:"今天",ipa:"/təˈdeɪ/"}, {en:"bring",cn:"带来",ipa:"/brɪŋ/"}, {en:"happen",cn:"发生",ipa:"/hæpən/"}, {en:"next",cn:"下一个",ipa:"/nekst/"}, {en:"without",cn:"没有",ipa:"/wɪˈðaʊt/"},
    {en:"before",cn:"在...之前",ipa:"/bɪˈfɔː/"}, {en:"large",cn:"大的",ipa:"/lɑːdʒ/"}, {en:"all",cn:"所有",ipa:"/ɔːl/"}, {en:"million",cn:"百万",ipa:"/ˈmɪljən/"}, {en:"must",cn:"必须",ipa:"/mʌst/"},
    {en:"home",cn:"家",ipa:"/həʊm/"}, {en:"under",cn:"在...下面",ipa:"/ˈʌndə/"}, {en:"water",cn:"水",ipa:"/ˈwɔːtə/"}, {en:"room",cn:"房间",ipa:"/ruːm/"}, {en:"write",cn:"写",ipa:"/raɪt/"},
    {en:"mother",cn:"母亲",ipa:"/ˈmʌðə/"}, {en:"area",cn:"区域",ipa:"/ˈeəriə/"}, {en:"national",cn:"国家的",ipa:"/ˈnæʃnəl/"}, {en:"money",cn:"钱",ipa:"/ˈmʌni/"}, {en:"story",cn:"故事",ipa:"/ˈstɔːri/"},
    {en:"young",cn:"年轻的",ipa:"/jʌŋ/"}, {en:"fact",cn:"事实",ipa:"/fækt/"}, {en:"month",cn:"月",ipa:"/mʌnθ/"}, {en:"different",cn:"不同的",ipa:"/ˈdɪfrənt/"}, {en:"lot",cn:"很多",ipa:"/lɒt/"},
    {en:"right",cn:"右边/正确",ipa:"/raɪt/"}, {en:"study",cn:"学习",ipa:"/ˈstʌdi/"}, {en:"book",cn:"书",ipa:"/bʊk/"}, {en:"eye",cn:"眼睛",ipa:"/aɪ/"}, {en:"job",cn:"工作",ipa:"/dʒɒb/"},
    {en:"word",cn:"单词",ipa:"/wɜːd/"}, {en:"though",cn:"虽然",ipa:"/ðəʊ/"}, {en:"business",cn:"生意",ipa:"/ˈbɪznɪs/"}, {en:"issue",cn:"问题/发行",ipa:"/ˈɪʃuː/"}, {en:"side",cn:"边/侧",ipa:"/saɪd/"},
    {en:"kind",cn:"种类/仁慈的",ipa:"/kaɪnd/"}, {en:"four",cn:"四",ipa:"/fɔː/"}, {en:"head",cn:"头",ipa:"/hed/"}, {en:"far",cn:"远",ipa:"/fɑː/"}, {en:"black",cn:"黑色的",ipa:"/blæk/"},
    {en:"long",cn:"长的",ipa:"/lɒŋ/"}, {en:"both",cn:"两个都",ipa:"/bəʊθ/"}, {en:"little",cn:"小的/少许",ipa:"/ˈlɪtl/"}, {en:"house",cn:"房子",ipa:"/haʊs/"}, {en:"yes",cn:"是",ipa:"/jes/"},
    {en:"after",cn:"在...之后",ipa:"/ˈɑːftə/"}, {en:"since",cn:"自从",ipa:"/sɪns/"}, {en:"long",cn:"长的",ipa:"/lɒŋ/"}, {en:"provide",cn:"提供",ipa:"/prəˈvaɪd/"}, {en:"service",cn:"服务",ipa:"/ˈsɜːvɪs/"},
    {en:"around",cn:"在...周围",ipa:"/əˈraʊnd/"}, {en:"friend",cn:"朋友",ipa:"/frend/"}, {en:"important",cn:"重要的",ipa:"/ɪmˈpɔːtnt/"}, {en:"father",cn:"父亲",ipa:"/ˈfɑːðə/"}, {en:"sit",cn:"坐",ipa:"/sɪt/"},
    {en:"away",cn:"离开",ipa:"/əˈweɪ/"}, {en:"until",cn:"直到",ipa:"/ənˈtɪl/"}, {en:"power",cn:"力量/权力",ipa:"/ˈpaʊə/"}, {en:"hour",cn:"小时",ipa:"/ˈaʊə/"}, {en:"game",cn:"游戏",ipa:"/ɡeɪm/"},
    {en:"often",cn:"经常",ipa:"/ˈɒfn/"}, {en:"yet",cn:"还/但是",ipa:"/jet/"}, {en:"line",cn:"线/排",ipa:"/laɪn/"}, {en:"political",cn:"政治的",ipa:"/pəˈlɪtɪkl/"}, {en:"end",cn:"结束",ipa:"/end/"},
    {en:"among",cn:"在...之中",ipa:"/əˈmʌŋ/"}, {en:"ever",cn:"曾经",ipa:"/ˈevə/"}, {en:"stand",cn:"站",ipa:"/stænd/"}, {en:"bad",cn:"坏的",ipa:"/bæd/"}, {en:"lose",cn:"丢失",ipa:"/luːz/"},
    {en:"however",cn:"然而",ipa:"/haʊˈevə/"}, {en:"member",cn:"成员",ipa:"/ˈmembə/"}, {en:"pay",cn:"支付",ipa:"/peɪ/"}, {en:"law",cn:"法律",ipa:"/lɔː/"}, {en:"meet",cn:"遇见",ipa:"/miːt/"},
    {en:"car",cn:"车",ipa:"/kɑː/"}, {en:"city",cn:"城市",ipa:"/ˈsɪti/"}, {en:"almost",cn:"几乎",ipa:"/ˈɔːlməʊst/"}, {en:"include",cn:"包括",ipa:"/ɪnˈkluːd/"}, {en:"continue",cn:"继续",ipa:"/kənˈtɪnjuː/"},
    {en:"set",cn:"设置",ipa:"/set/"}, {en:"later",cn:"后来",ipa:"/ˈleɪtə/"}, {en:"community",cn:"社区",ipa:"/kəˈmjuːnəti/"}, {en:"much",cn:"很多",ipa:"/mʌtʃ/"}, {en:"name",cn:"名字",ipa:"/neɪm/"},
    {en:"five",cn:"五",ipa:"/faɪv/"}, {en:"once",cn:"一次/一旦",ipa:"/wʌns/"}, {en:"white",cn:"白色的",ipa:"/waɪt/"}, {en:"least",cn:"最少",ipa:"/liːst/"}, {en:"president",cn:"总统",ipa:"/ˈprezɪdənt/"},
    {en:"learn",cn:"学习",ipa:"/lɜːn/"}, {en:"real",cn:"真的",ipa:"/rɪəl/"}, {en:"change",cn:"改变",ipa:"/tʃeɪndʒ/"}, {en:"team",cn:"团队",ipa:"/tiːm/"}, {en:"minute",cn:"分钟",ipa:"/ˈmɪnɪt/"},
    {en:"best",cn:"最好的",ipa:"/best/"}, {en:"several",cn:"几个",ipa:"/ˈsevrəl/"}, {en:"idea",cn:"主意",ipa:"/aɪˈdɪə/"}, {en:"kid",cn:"小孩",ipa:"/kɪd/"}, {en:"body",cn:"身体",ipa:"/ˈbɒdi/"},
    {en:"information",cn:"信息",ipa:"/ˌɪnfəˈmeɪʃən/"}, {en:"nothing",cn:"没什么",ipa:"/ˈnʌθɪŋ/"}, {en:"ago",cn:"以前",ipa:"/əˈɡəʊ/"}, {en:"right",cn:"权利/右/对",ipa:"/raɪt/"}, {en:"lead",cn:"领导",ipa:"/liːd/"},
    {en:"social",cn:"社会的",ipa:"/ˈsəʊʃl/"}, {en:"understand",cn:"理解",ipa:"/ˌʌndəˈstænd/"}, {en:"whether",cn:"是否",ipa:"/ˈweðə/"}, {en:"back",cn:"后面/背",ipa:"/bæk/"}, {en:"watch",cn:"观看",ipa:"/wɒtʃ/"},
    {en:"together",cn:"一起",ipa:"/təˈɡeðə/"}, {en:"follow",cn:"跟随",ipa:"/ˈfɒləʊ/"}, {en:"around",cn:"周围",ipa:"/əˈraʊnd/"}, {en:"parent",cn:"父母",ipa:"/ˈpeərənt/"}, {en:"only",cn:"只有",ipa:"/ˈəʊnli/"},
    {en:"stop",cn:"停止",ipa:"/stɒp/"}, {en:"face",cn:"脸",ipa:"/feɪs/"}, {en:"anything",cn:"任何事",ipa:"/ˈeniθɪŋ/"}, {en:"create",cn:"创造",ipa:"/kriːˈeɪt/"}, {en:"public",cn:"公众的",ipa:"/ˈpʌblɪk/"},
    {en:"already",cn:"已经",ipa:"/ɔːlˈredi/"}, {en:"speak",cn:"说",ipa:"/spiːk/"}, {en:"others",cn:"其他人",ipa:"/ˈʌðəz/"}, {en:"read",cn:"读",ipa:"/riːd/"}, {en:"level",cn:"水平",ipa:"/ˈlevl/"},
    {en:"allow",cn:"允许",ipa:"/əˈlaʊ/"}, {en:"add",cn:"增加",ipa:"/æd/"}, {en:"office",cn:"办公室",ipa:"/ˈɒfɪs/"}, {en:"spend",cn:"花费",ipa:"/spend/"}, {en:"door",cn:"门",ipa:"/dɔː/"},
    {en:"health",cn:"健康",ipa:"/helθ/"}, {en:"person",cn:"人",ipa:"/ˈpɜːsn/"}, {en:"art",cn:"艺术",ipa:"/ɑːt/"}, {en:"sure",cn:"确信的",ipa:"/ʃʊə/"}, {en:"such",cn:"如此",ipa:"/sʌtʃ/"},
    {en:"war",cn:"战争",ipa:"/wɔː/"}, {en:"history",cn:"历史",ipa:"/ˈhɪstri/"}, {en:"party",cn:"聚会/党派",ipa:"/ˈpɑːti/"}, {en:"within",cn:"在...之内",ipa:"/wɪˈðɪn/"}, {en:"grow",cn:"成长",ipa:"/ɡrəʊ/"},
    {en:"result",cn:"结果",ipa:"/rɪˈzʌlt/"}, {en:"open",cn:"打开",ipa:"/ˈəʊpən/"}, {en:"change",cn:"变化",ipa:"/tʃeɪndʒ/"}, {en:"morning",cn:"早晨",ipa:"/ˈmɔːnɪŋ/"}, {en:"walk",cn:"走",ipa:"/wɔːk/"},
    {en:"reason",cn:"理由",ipa:"/ˈriːzn/"}, {en:"low",cn:"低的",ipa:"/ləʊ/"}, {en:"win",cn:"赢",ipa:"/wɪn/"}, {en:"research",cn:"研究",ipa:"/rɪˈsɜːtʃ/"}, {en:"girl",cn:"女孩",ipa:"/ɡɜːl/"},
    {en:"guy",cn:"家伙",ipa:"/ɡaɪ/"}, {en:"early",cn:"早的",ipa:"/ˈɜːli/"}, {en:"food",cn:"食物",ipa:"/fuːd/"}, {en:"before",cn:"之前",ipa:"/bɪˈfɔː/"}, {en:"moment",cn:"时刻",ipa:"/ˈməʊmənt/"},
    {en:"himself",cn:"他自己",ipa:"/hɪmˈself/"}, {en:"air",cn:"空气",ipa:"/eə/"}, {en:"teacher",cn:"老师",ipa:"/ˈtiːtʃə/"}, {en:"force",cn:"力量/强迫",ipa:"/fɔːs/"}, {en:"offer",cn:"提供",ipa:"/ˈɒfə/"},
    {en:"enough",cn:"足够的",ipa:"/ɪˈnʌf/"}, {en:"both",cn:"两者",ipa:"/bəʊθ/"}, {en:"education",cn:"教育",ipa:"/ˌedʒuˈkeɪʃn/"}, {en:"across",cn:"穿过",ipa:"/əˈkrɒs/"}, {en:"although",cn:"尽管",ipa:"/ɔːlˈðəʊ/"},
    {en:"remember",cn:"记得",ipa:"/rɪˈmembə/"}, {en:"foot",cn:"脚",ipa:"/fʊt/"}, {en:"second",cn:"第二",ipa:"/ˈsekənd/"}, {en:"boy",cn:"男孩",ipa:"/bɔɪ/"}, {en:"maybe",cn:"也许",ipa:"/ˈmeɪbi/"},
    {en:"toward",cn:"朝向",ipa:"/təˈwɔːd/"}, {en:"able",cn:"能够",ipa:"/ˈeɪbl/"}, {en:"age",cn:"年龄",ipa:"/eɪdʒ/"}, {en:"off",cn:"离开",ipa:"/ɒf/"}, {en:"policy",cn:"政策",ipa:"/ˈpɒləsi/"},
    {en:"everything",cn:"一切",ipa:"/ˈevriθɪŋ/"}, {en:"love",cn:"爱",ipa:"/lʌv/"}, {en:"process",cn:"过程",ipa:"/ˈprəʊses/"}, {en:"music",cn:"音乐",ipa:"/ˈmjuːzɪk/"}, {en:"including",cn:"包括",ipa:"/ɪnˈkluːdɪŋ/"},
    {en:"consider",cn:"考虑",ipa:"/kənˈsɪdə/"}, {en:"appear",cn:"出现",ipa:"/əˈpɪə/"}, {en:"actually",cn:"实际上",ipa:"/ˈæktʃuəli/"}, {en:"buy",cn:"买",ipa:"/baɪ/"}, {en:"probably",cn:"大概",ipa:"/ˈprɒbəbli/"},
    {en:"human",cn:"人类",ipa:"/ˈhjuːmən/"}, {en:"wait",cn:"等待",ipa:"/weɪt/"}, {en:"serve",cn:"服务",ipa:"/sɜːv/"}, {en:"market",cn:"市场",ipa:"/ˈmɑːkɪt/"}, {en:"die",cn:"死",ipa:"/daɪ/"},
    {en:"send",cn:"发送",ipa:"/send/"}, {en:"expect",cn:"期待",ipa:"/ɪkˈspekt/"}, {en:"home",cn:"家",ipa:"/həʊm/"}, {en:"sense",cn:"感觉",ipa:"/sens/"}, {en:"build",cn:"建立",ipa:"/bɪld/"},
    {en:"stay",cn:"停留",ipa:"/steɪ/"}, {en:"fall",cn:"落下",ipa:"/fɔːl/"}, {en:"oh",cn:"噢",ipa:"/əʊ/"}, {en:"nation",cn:"国家",ipa:"/ˈneɪʃn/"}, {en:"plan",cn:"计划",ipa:"/plæn/"},
    {en:"cut",cn:"切",ipa:"/kʌt/"}, {en:"college",cn:"大学",ipa:"/ˈkɒlɪdʒ/"}, {en:"interest",cn:"兴趣",ipa:"/ˈɪntrəst/"}, {en:"death",cn:"死亡",ipa:"/deθ/"}, {en:"course",cn:"课程/过程",ipa:"/kɔːs/"},
    {en:"someone",cn:"某人",ipa:"/ˈsʌmwʌn/"}, {en:"experience",cn:"经验",ipa:"/ɪkˈspɪəriəns/"}, {en:"behind",cn:"在...后面",ipa:"/bɪˈhaɪnd/"}, {en:"reach",cn:"到达",ipa:"/riːtʃ/"}, {en:"local",cn:"当地的",ipa:"/ˈləʊkl/"},
    {en:"kill",cn:"杀",ipa:"/kɪl/"}, {en:"six",cn:"六",ipa:"/sɪks/"}, {en:"remain",cn:"保持",ipa:"/rɪˈmeɪn/"}, {en:"effect",cn:"效果",ipa:"/ɪˈfekt/"}, {en:"use",cn:"使用",ipa:"/juːz/"},
    {en:"suggest",cn:"建议",ipa:"/səˈdʒest/"}, {en:"class",cn:"班级/课",ipa:"/klɑːs/"}, {en:"control",cn:"控制",ipa:"/kənˈtrəʊl/"}, {en:"raise",cn:"举起/抚养",ipa:"/reɪz/"}, {en:"care",cn:"关心",ipa:"/keə/"},
    {en:"perhaps",cn:"也许",ipa:"/pəˈhæps/"}, {en:"little",cn:"一点",ipa:"/ˈlɪtl/"}, {en:"late",cn:"晚的",ipa:"/leɪt/"}, {en:"hard",cn:"努力/硬",ipa:"/hɑːd/"}, {en:"field",cn:"领域/田野",ipa:"/fiːld/"},
    {en:"else",cn:"别的",ipa:"/els/"}, {en:"pass",cn:"通过",ipa:"/pɑːs/"}, {en:"former",cn:"以前的",ipa:"/ˈfɔːmə/"}, {en:"sell",cn:"卖",ipa:"/sel/"}, {en:"major",cn:"主要的",ipa:"/ˈmeɪdʒə/"},
    {en:"sometimes",cn:"有时",ipa:"/ˈsʌmtaɪmz/"}, {en:"require",cn:"需要",ipa:"/rɪˈkwaɪə/"}, {en:"along",cn:"沿着",ipa:"/əˈlɒŋ/"}, {en:"development",cn:"发展",ipa:"/dɪˈveləpmənt/"}, {en:"themselves",cn:"他们自己",ipa:"/ðəmˈselvz/"},
    {en:"report",cn:"报告",ipa:"/rɪˈpɔːt/"}, {en:"role",cn:"角色",ipa:"/rəʊl/"}, {en:"better",cn:"更好的",ipa:"/ˈbetə/"}, {en:"economic",cn:"经济的",ipa:"/ˌiːkəˈnɒmɪk/"}, {en:"effort",cn:"努力",ipa:"/ˈefət/"},
    {en:"up",cn:"向上",ipa:"/ʌp/"}, {en:"decide",cn:"决定",ipa:"/dɪˈsaɪd/"}, {en:"rate",cn:"比率",ipa:"/reɪt/"}, {en:"strong",cn:"强壮的",ipa:"/strɒŋ/"}, {en:"possible",cn:"可能的",ipa:"/ˈpɒsəbl/"},
    {en:"heart",cn:"心",ipa:"/hɑːt/"}, {en:"drug",cn:"药/毒品",ipa:"/drʌɡ/"}, {en:"show",cn:"展示",ipa:"/ʃəʊ/"}, {en:"leader",cn:"领导者",ipa:"/ˈliːdə/"}, {en:"light",cn:"光/轻的",ipa:"/laɪt/"},
    {en:"voice",cn:"声音",ipa:"/vɔɪs/"}, {en:"wife",cn:"妻子",ipa:"/waɪf/"}, {en:"whole",cn:"整个",ipa:"/həʊl/"}, {en:"police",cn:"警察",ipa:"/pəˈliːs/"}, {en:"mind",cn:"头脑/介意",ipa:"/maɪnd/"},
    {en:"finally",cn:"最后",ipa:"/ˈfaɪnəli/"}, {en:"pull",cn:"拉",ipa:"/pʊl/"}, {en:"return",cn:"返回",ipa:"/rɪˈtɜːn/"}, {en:"free",cn:"免费/自由",ipa:"/friː/"}, {en:"military",cn:"军事的",ipa:"/ˈmɪlətri/"},
    {en:"price",cn:"价格",ipa:"/praɪs/"}, {en:"report",cn:"报告",ipa:"/rɪˈpɔːt/"}, {en:"less",cn:"更少",ipa:"/les/"}, {en:"according",cn:"根据",ipa:"/əˈkɔːdɪŋ/"}, {en:"decision",cn:"决定",ipa:"/dɪˈsɪʒn/"},
    {en:"explain",cn:"解释",ipa:"/ɪkˈspleɪn/"}, {en:"son",cn:"儿子",ipa:"/sʌn/"}, {en:"hope",cn:"希望",ipa:"/həʊp/"}, {en:"even",cn:"甚至",ipa:"/ˈiːvn/"}, {en:"develop",cn:"发展",ipa:"/dɪˈveləp/"},
    {en:"view",cn:"观点/看",ipa:"/vjuː/"}, {en:"relationship",cn:"关系",ipa:"/rɪˈleɪʃnʃɪp/"}, {en:"carry",cn:"携带",ipa:"/ˈkæri/"}, {en:"town",cn:"城镇",ipa:"/taʊn/"}, {en:"road",cn:"路",ipa:"/rəʊd/"},
    {en:"drive",cn:"开车",ipa:"/draɪv/"}, {en:"arm",cn:"手臂",ipa:"/ɑːm/"}, {en:"true",cn:"真实的",ipa:"/truː/"}, {en:"federal",cn:"联邦的",ipa:"/ˈfedərəl/"}, {en:"break",cn:"打破/休息",ipa:"/breɪk/"},
    {en:"better",cn:"更好",ipa:"/ˈbetə/"}, {en:"difference",cn:"不同",ipa:"/ˈdɪfrəns/"}, {en:"thank",cn:"谢谢",ipa:"/θæŋk/"}, {en:"receive",cn:"收到",ipa:"/rɪˈsiːv/"}, {en:"value",cn:"价值",ipa:"/ˈvæljuː/"},
    {en:"international",cn:"国际的",ipa:"/ˌɪntəˈnæʃnəl/"}, {en:"building",cn:"建筑物",ipa:"/ˈbɪldɪŋ/"}, {en:"action",cn:"行动",ipa:"/ˈækʃn/"}, {en:"full",cn:"满的",ipa:"/fʊl/"}, {en:"model",cn:"模型",ipa:"/ˈmɒdl/"},
    {en:"join",cn:"加入",ipa:"/dʒɔɪn/"}, {en:"season",cn:"季节",ipa:"/ˈsiːzn/"}, {en:"society",cn:"社会",ipa:"/səˈsaɪəti/"}, {en:"because",cn:"因为",ipa:"/bɪˈkɒz/"}, {en:"tax",cn:"税",ipa:"/tæks/"},
    {en:"director",cn:"导演/主任",ipa:"/dəˈrektə/"}, {en:"early",cn:"早",ipa:"/ˈɜːli/"}, {en:"position",cn:"位置",ipa:"/pəˈzɪʃn/"}, {en:"player",cn:"玩家/选手",ipa:"/ˈpleɪə/"}, {en:"agree",cn:"同意",ipa:"/əˈɡriː/"},
    {en:"especially",cn:"尤其",ipa:"/ɪˈspeʃəli/"}, {en:"record",cn:"记录",ipa:"/ˈrekɔːd/"}, {en:"pick",cn:"挑选",ipa:"/pɪk/"}, {en:"wear",cn:"穿",ipa:"/weə/"}, {en:"paper",cn:"纸",ipa:"/ˈpeɪpə/"},
    {en:"special",cn:"特别的",ipa:"/ˈspeʃl/"}, {en:"space",cn:"空间",ipa:"/speɪs/"}, {en:"ground",cn:"地面",ipa:"/ɡraʊnd/"}, {en:"form",cn:"形式/表格",ipa:"/fɔːm/"}, {en:"support",cn:"支持",ipa:"/səˈpɔːt/"},
    {en:"event",cn:"事件",ipa:"/ɪˈvent/"}, {en:"official",cn:"官方的",ipa:"/əˈfɪʃl/"}, {en:"whose",cn:"谁的",ipa:"/huːz/"}, {en:"matter",cn:"事情/要紧",ipa:"/ˈmætə/"}, {en:"everyone",cn:"每个人",ipa:"/ˈevriwʌn/"},
    {en:"center",cn:"中心",ipa:"/ˈsentə/"}, {en:"couple",cn:"一对",ipa:"/ˈkʌpl/"}, {en:"site",cn:"地点/网站",ipa:"/saɪt/"}, {en:"end",cn:"结束",ipa:"/end/"}, {en:"project",cn:"项目",ipa:"/ˈprɒdʒekt/"},
    {en:"hit",cn:"打击",ipa:"/hɪt/"}, {en:"base",cn:"基础",ipa:"/beɪs/"}, {en:"activity",cn:"活动",ipa:"/ækˈtɪvəti/"}, {en:"star",cn:"星星/明星",ipa:"/stɑː/"}, {en:"table",cn:"桌子",ipa:"/ˈteɪbl/"},
    {en:"need",cn:"需要",ipa:"/niːd/"}, {en:"court",cn:"法庭/球场",ipa:"/kɔːt/"}, {en:"produce",cn:"生产",ipa:"/prəˈdjuːs/"}, {en:"eat",cn:"吃",ipa:"/iːt/"}, {en:"American",cn:"美国人",ipa:"/əˈmerɪkən/"},
    {en:"teach",cn:"教",ipa:"/tiːtʃ/"}, {en:"oil",cn:"油",ipa:"/ɔɪl/"}, {en:"half",cn:"一半",ipa:"/hɑːf/"}, {en:"situation",cn:"情况",ipa:"/ˌsɪtʃuˈeɪʃn/"}, {en:"easy",cn:"容易的",ipa:"/ˈiːzi/"},
    {en:"cost",cn:"成本/花费",ipa:"/kɒst/"}, {en:"industry",cn:"工业",ipa:"/ˈɪndəstri/"}, {en:"figure",cn:"数字/人物",ipa:"/ˈfɪɡə/"}, {en:"face",cn:"面对",ipa:"/feɪs/"}, {en:"street",cn:"街道",ipa:"/striːt/"},
    {en:"image",cn:"图像/形象",ipa:"/ˈɪmɪdʒ/"}, {en:"itself",cn:"它自己",ipa:"/ɪtˈself/"}, {en:"phone",cn:"电话",ipa:"/fəʊn/"}, {en:"either",cn:"两者之一/也",ipa:"/ˈaɪðə/"}, {en:"data",cn:"数据",ipa:"/ˈdeɪtə/"},
    {en:"cover",cn:"覆盖",ipa:"/ˈkʌvə/"}, {en:"quite",cn:"相当",ipa:"/kwaɪt/"}, {en:"picture",cn:"图片",ipa:"/ˈpɪktʃə/"}, {en:"clear",cn:"清楚的",ipa:"/klɪə/"}, {en:"practice",cn:"练习",ipa:"/ˈpræktɪs/"},
    {en:"piece",cn:"片/块",ipa:"/piːs/"}, {en:"land",cn:"土地",ipa:"/lænd/"}, {en:"recent",cn:"最近的",ipa:"/ˈriːsnt/"}, {en:"describe",cn:"描述",ipa:"/dɪˈskraɪb/"}, {en:"product",cn:"产品",ipa:"/ˈprɒdʌkt/"},
    {en:"doctor",cn:"医生",ipa:"/ˈdɒktə/"}, {en:"wall",cn:"墙",ipa:"/wɔː/"}, {en:"patient",cn:"耐心的/病人",ipa:"/ˈpeɪʃnt/"}, {en:"worker",cn:"工人",ipa:"/ˈwɜːkə/"}, {en:"news",cn:"新闻",ipa:"/njuːz/"},
    {en:"test",cn:"测试",ipa:"/test/"}, {en:"movie",cn:"电影",ipa:"/ˈmuːvi/"}, {en:"certain",cn:"确定的",ipa:"/ˈsɜːtn/"}, {en:"north",cn:"北",ipa:"/nɔːθ/"}, {en:"love",cn:"爱",ipa:"/lʌv/"},
    {en:"personal",cn:"个人的",ipa:"/ˈpɜːsənl/"}, {en:"open",cn:"开着的",ipa:"/ˈəʊpən/"}, {en:"support",cn:"支持",ipa:"/səˈpɔːt/"}, {en:"simply",cn:"简单地",ipa:"/ˈsɪmpli/"}, {en:"third",cn:"第三",ipa:"/θɜːd/"},
    {en:"technology",cn:"技术",ipa:"/tekˈnɒlədʒi/"}, {en:"catch",cn:"抓住",ipa:"/kætʃ/"}, {en:"step",cn:"步/步骤",ipa:"/step/"}, {en:"baby",cn:"婴儿",ipa:"/ˈbeɪbi/"}, {en:"computer",cn:"电脑",ipa:"/kəmˈpjuːtə/"},
    {en:"type",cn:"类型",ipa:"/taɪp/"}, {en:"attention",cn:"注意",ipa:"/əˈtenʃn/"}, {en:"draw",cn:"画/拉",ipa:"/drɔː/"}, {en:"film",cn:"电影/胶卷",ipa:"/fɪlm/"}, {en:"Republican",cn:"共和党人",ipa:"/rɪˈpʌblɪkən/"},
    {en:"tree",cn:"树",ipa:"/triː/"}, {en:"source",cn:"来源",ipa:"/sɔːs/"}, {en:"red",cn:"红色的",ipa:"/red/"}, {en:"nearly",cn:"几乎",ipa:"/ˈnɪəli/"}, {en:"organization",cn:"组织",ipa:"/ˌɔːɡənaɪˈzeɪʃn/"},
    {en:"choose",cn:"选择",ipa:"/tʃuːz/"}, {en:"cause",cn:"导致/原因",ipa:"/kɔːz/"}, {en:"hair",cn:"头发",ipa:"/heə/"}, {en:"look",cn:"看",ipa:"/lʊk/"}, {en:"point",cn:"指出",ipa:"/pɔɪnt/"},
    {en:"century",cn:"世纪",ipa:"/ˈsentʃəri/"}, {en:"evidence",cn:"证据",ipa:"/ˈevɪdəns/"}, {en:"window",cn:"窗户",ipa:"/ˈwɪndəʊ/"}, {en:"difficult",cn:"困难的",ipa:"/ˈdɪfɪkəlt/"}, {en:"listen",cn:"听",ipa:"/ˈlɪsn/"},
    {en:"soon",cn:"不久",ipa:"/suːn/"}, {en:"culture",cn:"文化",ipa:"/ˈkʌltʃə/"}, {en:"billion",cn:"十亿",ipa:"/ˈbɪljən/"}, {en:"chance",cn:"机会",ipa:"/tʃɑːns/"}, {en:"brother",cn:"兄弟",ipa:"/ˈbrʌðə/"},
    {en:"energy",cn:"能量",ipa:"/ˈenədʒi/"}, {en:"period",cn:"时期",ipa:"/ˈpɪəriəd/"}, {en:"course",cn:"课程",ipa:"/kɔːs/"}, {en:"summer",cn:"夏天",ipa:"/ˈsʌmə/"}, {en:"less",cn:"较少",ipa:"/les/"},
    {en:"realize",cn:"意识到",ipa:"/ˈriːəlaɪz/"}, {en:"hundred",cn:"百",ipa:"/ˈhʌndrəd/"}, {en:"available",cn:"可用的",ipa:"/əˈveɪləbl/"}, {en:"plant",cn:"植物/工厂",ipa:"/plɑːnt/"}, {en:"likely",cn:"可能的",ipa:"/ˈlaɪkli/"},
    {en:"opportunity",cn:"机会",ipa:"/ˌɒpəˈtjuːnəti/"}, {en:"term",cn:"术语/学期",ipa:"/tɜːm/"}, {en:"short",cn:"短的",ipa:"/ʃɔːt/"}, {en:"letter",cn:"信/字母",ipa:"/ˈletə/"}, {en:"condition",cn:"条件",ipa:"/kənˈdɪʃn/"},
    {en:"choice",cn:"选择",ipa:"/tʃɔɪs/"}, {en:"place",cn:"放置",ipa:"/pleɪs/"}, {en:"single",cn:"单一的",ipa:"/ˈsɪŋɡl/"}, {en:"rule",cn:"规则",ipa:"/ruːl/"}, {en:"daughter",cn:"女儿",ipa:"/ˈdɔːtə/"},
    {en:"administration",cn:"行政",ipa:"/ədˌmɪnɪˈstreɪʃn/"}, {en:"south",cn:"南",ipa:"/saʊθ/"}, {en:"husband",cn:"丈夫",ipa:"/ˈhʌzbənd/"}, {en:"Congress",cn:"国会",ipa:"/ˈkɒŋɡres/"}, {en:"floor",cn:"地板/楼层",ipa:"/flɔː/"},
    {en:"campaign",cn:"运动/战役",ipa:"/kæmˈpeɪn/"}, {en:"material",cn:"材料",ipa:"/məˈtɪəriəl/"}, {en:"population",cn:"人口",ipa:"/ˌpɒpjuˈleɪʃn/"}, {en:"well",cn:"好",ipa:"/wel/"}, {en:"call",cn:"打电话",ipa:"/kɔːl/"},
    {en:"economy",cn:"经济",ipa:"/ɪˈkɒnəmi/"}, {en:"medical",cn:"医疗的",ipa:"/ˈmedɪkl/"}, {en:"hospital",cn:"医院",ipa:"/ˈhɒspɪtl/"}, {en:"church",cn:"教堂",ipa:"/tʃɜːtʃ/"}, {en:"close",cn:"关闭/近的",ipa:"/kləʊs/"},
    {en:"thousand",cn:"千",ipa:"/ˈθaʊznd/"}, {en:"risk",cn:"风险",ipa:"/rɪsk/"}, {en:"current",cn:"当前的",ipa:"/ˈkʌrənt/"}, {en:"fire",cn:"火",ipa:"/ˈfaɪə/"}, {en:"future",cn:"未来",ipa:"/ˈfjuːtʃə/"},
    {en:"wrong",cn:"错误的",ipa:"/rɒŋ/"}, {en:"involve",cn:"涉及",ipa:"/ɪnˈvɒlv/"}, {en:"defense",cn:"防御",ipa:"/dɪˈfens/"}, {en:"anyone",cn:"任何人",ipa:"/ˈeniwʌn/"}, {en:"increase",cn:"增加",ipa:"/ɪnˈkriːs/"},
    {en:"security",cn:"安全",ipa:"/sɪˈkjʊərəti/"}, {en:"bank",cn:"银行",ipa:"/bæŋk/"}, {en:"myself",cn:"我自己",ipa:"/maɪˈself/"}, {en:"certainly",cn:"当然",ipa:"/ˈsɜːtnli/"}, {en:"west",cn:"西",ipa:"/west/"},
    {en:"sport",cn:"运动",ipa:"/spɔːt/"}, {en:"board",cn:"木板/委员会",ipa:"/bɔːd/"}, {en:"seek",cn:"寻求",ipa:"/siːk/"}, {en:"per",cn:"每",ipa:"/pɜː/"}, {en:"subject",cn:"主题/科目",ipa:"/ˈsʌbdʒekt/"},
    {en:"officer",cn:"官员",ipa:"/ˈɒfɪsə/"}, {en:"private",cn:"私人的",ipa:"/ˈpraɪvət/"}, {en:"rest",cn:"休息/其余",ipa:"/rest/"}, {en:"behavior",cn:"行为",ipa:"/bɪˈheɪvjə/"}, {en:"deal",cn:"交易/处理",ipa:"/diːl/"},
    {en:"performance",cn:"表现",ipa:"/pəˈfɔːməns/"}, {en:"fight",cn:"打架",ipa:"/faɪt/"}, {en:"throw",cn:"扔",ipa:"/θrəʊ/"}, {en:"top",cn:"顶部",ipa:"/tɒp/"}, {en:"quickly",cn:"快地",ipa:"/ˈkwɪkli/"},
    {en:"past",cn:"过去",ipa:"/pɑːst/"}, {en:"goal",cn:"目标",ipa:"/ɡəʊl/"}, {en:"second",cn:"秒",ipa:"/ˈsekənd/"}, {en:"bed",cn:"床",ipa:"/bed/"}, {en:"order",cn:"命令/顺序",ipa:"/ˈɔːdə/"},
    {en:"author",cn:"作者",ipa:"/ˈɔːθə/"}, {en:"fill",cn:"填充",ipa:"/fɪl/"}, {en:"represent",cn:"代表",ipa:"/ˌreprɪˈzent/"}, {en:"focus",cn:"聚焦",ipa:"/ˈfəʊkəs/"}, {en:"foreign",cn:"外国的",ipa:"/ˈfɒrən/"},
    {en:"drop",cn:"掉下",ipa:"/drɒp/"}, {en:"plan",cn:"计划",ipa:"/plæn/"}, {en:"blood",cn:"血",ipa:"/blʌd/"}, {en:"upon",cn:"在...之上",ipa:"/əˈpɒn/"}, {en:"agency",cn:"代理处",ipa:"/ˈeɪdʒənsi/"},
    {en:"push",cn:"推",ipa:"/pʊʃ/"}, {en:"nature",cn:"自然",ipa:"/ˈneɪtʃə/"}, {en:"color",cn:"颜色",ipa:"/ˈkʌlə/"}, {en:"no",cn:"没有",ipa:"/nəʊ/"}, {en:"recently",cn:"最近",ipa:"/ˈriːsntli/"},
    {en:"store",cn:"商店",ipa:"/stɔː/"}, {en:"reduce",cn:"减少",ipa:"/rɪˈdjuːs/"}, {en:"sound",cn:"声音",ipa:"/saʊnd/"}, {en:"note",cn:"笔记/注意",ipa:"/nəʊt/"}, {en:"fine",cn:"好的/罚款",ipa:"/faɪn/"},
    {en:"near",cn:"在附近",ipa:"/nɪə/"}, {en:"movement",cn:"运动",ipa:"/ˈmuːvmənt/"}, {en:"page",cn:"页",ipa:"/peɪdʒ/"}, {en:"enter",cn:"进入",ipa:"/ˈentə/"}, {en:"share",cn:"分享",ipa:"/ʃeə/"},
    {en:"than",cn:"比",ipa:"/ðæn/"}, {en:"common",cn:"共同的",ipa:"/ˈkɒmən/"}, {en:"poor",cn:"贫穷的",ipa:"/pɔː/"}, {en:"other",cn:"其他的",ipa:"/ˈʌðə/"}, {en:"natural",cn:"自然的",ipa:"/ˈnætʃrəl/"},
    {en:"race",cn:"种族/比赛",ipa:"/reɪs/"}, {en:"concern",cn:"关心",ipa:"/kənˈsɜːn/"}, {en:"series",cn:"系列",ipa:"/ˈsɪəriːz/"}, {en:"significant",cn:"重要的",ipa:"/sɪɡˈnɪfɪkənt/"}, {en:"similar",cn:"相似的",ipa:"/ˈsɪmələ/"},
    {en:"hot",cn:"热的",ipa:"/hɒt/"}, {en:"language",cn:"语言",ipa:"/ˈlæŋɡwɪdʒ/"}, {en:"each",cn:"每一个",ipa:"/iːtʃ/"}, {en:"usually",cn:"通常",ipa:"/ˈjuːʒuəli/"}, {en:"response",cn:"反应",ipa:"/rɪˈspɒns/"},
    {en:"dead",cn:"死的",ipa:"/ded/"}, {en:"rise",cn:"上升",ipa:"/raɪz/"}, {en:"animal",cn:"动物",ipa:"/ˈænɪml/"}, {en:"factor",cn:"因素",ipa:"/ˈfæktə/"}, {en:"decade",cn:"十年",ipa:"/ˈdekeɪd/"},
    {en:"article",cn:"文章",ipa:"/ˈɑːtɪkl/"}, {en:"shoot",cn:"射击",ipa:"/ʃuːt/"}, {en:"east",cn:"东",ipa:"/iːst/"}, {en:"save",cn:"保存/救",ipa:"/seɪv/"}, {en:"seven",cn:"七",ipa:"/ˈsevən/"},
    {en:"artist",cn:"艺术家",ipa:"/ˈɑːtɪst/"}, {en:"away",cn:"离开",ipa:"/əˈweɪ/"}, {en:"scene",cn:"场景",ipa:"/siːn/"}, {en:"stock",cn:"股票/库存",ipa:"/stɒk/"}, {en:"career",cn:"职业",ipa:"/kəˈrɪə/"},
    {en:"despite",cn:"尽管",ipa:"/dɪˈspaɪt/"}, {en:"central",cn:"中心的",ipa:"/ˈsentrəl/"}, {en:"eight",cn:"八",ipa:"/eɪt/"}, {en:"thus",cn:"因此",ipa:"/ðʌs/"}, {en:"treatment",cn:"对待/治疗",ipa:"/ˈtriːtmənt/"},
    {en:"beyond",cn:"超过",ipa:"/bɪˈjɒnd/"}, {en:"happy",cn:"快乐的",ipa:"/ˈhæpi/"}, {en:"exactly",cn:"确切地",ipa:"/ɪɡˈzæktli/"}, {en:"protect",cn:"保护",ipa:"/prəˈtekt/"}, {en:"approach",cn:"接近/方法",ipa:"/əˈprəʊtʃ/"},
    {en:"lie",cn:"躺/撒谎",ipa:"/laɪ/"}, {en:"size",cn:"尺寸",ipa:"/saɪz/"}, {en:"dog",cn:"狗",ipa:"/dɒɡ/"}, {en:"fund",cn:"基金",ipa:"/fʌnd/"}, {en:"serious",cn:"严肃的",ipa:"/ˈsɪəriəs/"},
    {en:"occur",cn:"发生",ipa:"/əˈkɜː/"}, {en:"media",cn:"媒体",ipa:"/ˈmiːdiə/"}, {en:"ready",cn:"准备好的",ipa:"/ˈredi/"}, {en:"sign",cn:"符号/签字",ipa:"/saɪn/"}, {en:"thought",cn:"思想",ipa:"/θɔːt/"},
    {en:"list",cn:"清单",ipa:"/lɪst/"}, {en:"individual",cn:"个人的",ipa:"/ˌɪndɪˈvɪdʒuəl/"}, {en:"simple",cn:"简单的",ipa:"/ˈsɪmpl/"}, {en:"quality",cn:"质量",ipa:"/ˈkwɒləti/"}, {en:"pressure",cn:"压力",ipa:"/ˈpreʃə/"},
    {en:"accept",cn:"接受",ipa:"/əkˈsept/"}, {en:"answer",cn:"回答",ipa:"/ˈɑːnsə/"}, {en:"hard",cn:"困难的",ipa:"/hɑːd/"}, {en:"resource",cn:"资源",ipa:"/rɪˈzɔːs/"}, {en:"identify",cn:"鉴定",ipa:"/aɪˈdentɪfaɪ/"},
    {en:"left",cn:"左边/留下",ipa:"/left/"}, {en:"meeting",cn:"会议",ipa:"/ˈmiːtɪŋ/"}, {en:"determine",cn:"决定",ipa:"/dɪˈtɜːmɪn/"}, {en:"prepare",cn:"准备",ipa:"/prɪˈpeə/"}, {en:"disease",cn:"疾病",ipa:"/dɪˈziːz/"},
    {en:"whatever",cn:"无论什么",ipa:"/wɒtˈevə/"}, {en:"success",cn:"成功",ipa:"/səkˈses/"}, {en:"argue",cn:"争论",ipa:"/ˈɑːɡjuː/"}, {en:"cup",cn:"杯子",ipa:"/kʌp/"}, {en:"particularly",cn:"特别地",ipa:"/pəˈtɪkjələli/"},
    {en:"amount",cn:"数量",ipa:"/əˈmaʊnt/"}, {en:"ability",cn:"能力",ipa:"/əˈbɪləti/"}, {en:"staff",cn:"全体员工",ipa:"/stɑːf/"}, {en:"recognize",cn:"认出",ipa:"/ˈrekəɡnaɪz/"}, {en:"indicate",cn:"表明",ipa:"/ˈɪndɪkeɪt/"},
    {en:"character",cn:"性格/角色",ipa:"/ˈkærəktə/"}, {en:"growth",cn:"增长",ipa:"/ɡrəʊθ/"}, {en:"loss",cn:"损失",ipa:"/lɒs/"}, {en:"degree",cn:"程度/学位",ipa:"/dɪˈɡriː/"}, {en:"wonder",cn:"想知道/奇迹",ipa:"/ˈwʌndə/"},
    {en:"attack",cn:"攻击",ipa:"/əˈtæk/"}, {en:"herself",cn:"她自己",ipa:"/həˈself/"}, {en:"region",cn:"地区",ipa:"/ˈriːdʒən/"}, {en:"television",cn:"电视",ipa:"/ˈtelɪvɪʒn/"}, {en:"box",cn:"盒子",ipa:"/bɒks/"},
    {en:"TV",cn:"电视",ipa:"/ˌtiː ˈviː/"}, {en:"training",cn:"训练",ipa:"/ˈtreɪnɪŋ/"}, {en:"pretty",cn:"漂亮的/相当",ipa:"/ˈprɪti/"}, {en:"trade",cn:"贸易",ipa:"/treɪd/"}, {en:"deal",cn:"处理",ipa:"/diːl/"},
    {en:"election",cn:"选举",ipa:"/ɪˈlekʃn/"}, {en:"everybody",cn:"每个人",ipa:"/ˈevribɒdi/"}, {en:"physical",cn:"身体的",ipa:"/ˈfɪzɪkl/"}, {en:"lay",cn:"放置",ipa:"/leɪ/"}, {en:"general",cn:"一般的/将军",ipa:"/ˈdʒenrəl/"},
    {en:"feeling",cn:"感觉",ipa:"/ˈfiːlɪŋ/"}, {en:"standard",cn:"标准",ipa:"/ˈstændəd/"}, {en:"bill",cn:"账单/法案",ipa:"/bɪl/"}, {en:"message",cn:"消息",ipa:"/ˈmesɪdʒ/"}, {en:"fail",cn:"失败",ipa:"/feɪl/"},
    {en:"outside",cn:"在外面",ipa:"/ˌaʊtˈsaɪd/"}, {en:"arrive",cn:"到达",ipa:"/əˈraɪv/"}, {en:"analysis",cn:"分析",ipa:"/əˈnæləsɪs/"}, {en:"benefit",cn:"利益",ipa:"/ˈbenɪfɪt/"}, {en:"name",cn:"名字",ipa:"/neɪm/"},
    {en:"sex",cn:"性别/性",ipa:"/seks/"}, {en:"forward",cn:"向前",ipa:"/ˈfɔːwəd/"}, {en:"lawyer",cn:"律师",ipa:"/ˈlɔːjə/"}, {en:"present",cn:"呈现/礼物/现在的",ipa:"/ˈpreznt/"}, {en:"section",cn:"部分",ipa:"/ˈsekʃn/"},
    {en:"environmental",cn:"环境的",ipa:"/ɪnˌvaɪrənˈmentl/"}, {en:"glass",cn:"玻璃/杯",ipa:"/ɡlɑːs/"}, {en:"answer",cn:"答案",ipa:"/ˈɑːnsə/"}, {en:"skill",cn:"技能",ipa:"/skɪl/"}, {en:"sister",cn:"姐妹",ipa:"/ˈsɪstə/"},
    {en:"PM",cn:"下午",ipa:"/ˌpiː ˈem/"}, {en:"professor",cn:"教授",ipa:"/prəˈfesə/"}, {en:"operation",cn:"操作",ipa:"/ˌɒpəˈreɪʃn/"}, {en:"financial",cn:"金融的",ipa:"/faɪˈnænʃl/"}, {en:"crime",cn:"犯罪",ipa:"/kraɪm/"},
    {en:"stage",cn:"舞台/阶段",ipa:"/steɪdʒ/"}, {en:"ok",cn:"好的",ipa:"/ˌəʊ ˈkeɪ/"}, {en:"compare",cn:"比较",ipa:"/kəmˈpeə/"}, {en:"authority",cn:"权威",ipa:"/ɔːˈθɒrəti/"}, {en:"miss",cn:"错过/想念",ipa:"/mɪs/"},
    {en:"design",cn:"设计",ipa:"/dɪˈzaɪn/"}, {en:"sort",cn:"种类",ipa:"/sɔːt/"}, {en:"one",cn:"一个",ipa:"/wʌn/"}, {en:"act",cn:"行动",ipa:"/ækt/"}, {en:"ten",cn:"十",ipa:"/ten/"},
    {en:"knowledge",cn:"知识",ipa:"/ˈnɒlɪdʒ/"}, {en:"gun",cn:"枪",ipa:"/ɡʌn/"}, {en:"station",cn:"车站",ipa:"/ˈsteɪʃn/"}, {en:"blue",cn:"蓝色的",ipa:"/bluː/"}, {en:"state",cn:"状态/州",ipa:"/steɪt/"},
    {en:"strategy",cn:"策略",ipa:"/ˈstrætədʒi/"}, {en:"little",cn:"少许",ipa:"/ˈlɪtl/"}, {en:"clearly",cn:"清楚地",ipa:"/ˈklɪəli/"}, {en:"discuss",cn:"讨论",ipa:"/dɪˈskʌs/"}, {en:"indeed",cn:"的确",ipa:"/ɪnˈdiːd/"},
    {en:"force",cn:"力量",ipa:"/fɔːs/"}, {en:"truth",cn:"真理",ipa:"/truːθ/"}, {en:"song",cn:"歌曲",ipa:"/sɒŋ/"}, {en:"example",cn:"例子",ipa:"/ɪɡˈzɑːmpl/"}, {en:"democratic",cn:"民主的",ipa:"/ˌdeməˈkrætɪk/"},
    {en:"check",cn:"检查",ipa:"/tʃek/"}, {en:"environment",cn:"环境",ipa:"/ɪnˈvaɪrənmənt/"}, {en:"leg",cn:"腿",ipa:"/leɡ/"}, {en:"dark",cn:"黑暗的",ipa:"/dɑːk/"}, {en:"public",cn:"公众",ipa:"/ˈpʌblɪk/"},
    {en:"various",cn:"各种各样的",ipa:"/ˈveəriəs/"}, {en:"rather",cn:"宁愿"}, {en:"laugh",cn:"笑",ipa:"/lɑːf/"}, {en:"guess",cn:"猜",ipa:"/ɡes/"}, {en:"executive",cn:"行政的",ipa:"/ɪɡˈzekjətɪv/"},
    {en:"set",cn:"集合",ipa:"/set/"}, {en:"study",cn:"研究",ipa:"/ˈstʌdi/"}, {en:"prove",cn:"证明",ipa:"/pruːv/"}, {en:"hang",cn:"悬挂",ipa:"/hæŋ/"}, {en:"entire",cn:"整个的",ipa:"/ɪnˈtaɪə/"},
    {en:"rock",cn:"岩石/摇滚",ipa:"/rɒk/"}, {en:"design",cn:"设计",ipa:"/dɪˈzaɪn/"}, {en:"enough",cn:"足够",ipa:"/ɪˈnʌf/"}, {en:"forget",cn:"忘记",ipa:"/fəˈɡet/"}, {en:"since",cn:"因为",ipa:"/sɪns/"},
    {en:"claim",cn:"声称",ipa:"/kleɪm/"}, {en:"note",cn:"便条",ipa:"/nəʊt/"}, {en:"remove",cn:"移除",ipa:"/rɪˈmuːv/"}, {en:"manager",cn:"经理",ipa:"/ˈmænɪdʒə/"}, {en:"help",cn:"帮忙",ipa:"/help/"},
    {en:"close",cn:"近的",ipa:"/kləʊs/"}, {en:"sound",cn:"听起来",ipa:"/saʊnd/"}, {en:"enjoy",cn:"享受",ipa:"/ɪnˈdʒɔɪ/"}, {en:"network",cn:"网络",ipa:"/ˈnetwɜːk/"}, {en:"legal",cn:"合法的",ipa:"/ˈliːɡl/"},
    {en:"religious",cn:"宗教的",ipa:"/rɪˈlɪdʒəs/"}, {en:"cold",cn:"冷的",ipa:"/kəʊld/"}, {en:"form",cn:"形成",ipa:"/fɔːm/"}, {en:"final",cn:"最后的",ipa:"/ˈfaɪnl/"}, {en:"main",cn:"主要的",ipa:"/meɪn/"},
    {en:"science",cn:"科学",ipa:"/ˈsaɪəns/"}, {en:"green",cn:"绿色的",ipa:"/ɡriːn/"}, {en:"memory",cn:"记忆",ipa:"/ˈmeməri/"}, {en:"card",cn:"卡片",ipa:"/kɑːd/"}, {en:"above",cn:"在...之上",ipa:"/əˈbʌv/"},
    {en:"seat",cn:"座位",ipa:"/siːt/"}, {en:"cell",cn:"细胞/电池",ipa:"/sel/"}, {en:"establish",cn:"建立",ipa:"/ɪˈstæblɪʃ/"}, {en:"nice",cn:"美好的",ipa:"/naɪs/"}, {en:"trial",cn:"审判/试验",ipa:"/ˈtraɪəl/"},
    {en:"expert",cn:"专家",ipa:"/ˈekspɜːt/"}, {en:"that",cn:"那个",ipa:"/ðæt/"}, {en:"spring",cn:"春天/弹簧",ipa:"/sprɪŋ/"}, {en:"firm",cn:"公司/坚固的",ipa:"/fɜːm/"}, {en:"Democrat",cn:"民主党人",ipa:"/ˈdeməkræt/"},
    {en:"radio",cn:"收音机",ipa:"/ˈreɪdiəʊ/"}, {en:"visit",cn:"访问",ipa:"/ˈvɪzɪt/"}, {en:"management",cn:"管理",ipa:"/ˈmænɪdʒmənt/"}, {en:"care",cn:"照顾",ipa:"/keə/"}, {en:"avoid",cn:"避免",ipa:"/əˈvɔɪd/"},
    {en:"imagine",cn:"想象",ipa:"/ɪˈmædʒɪn/"}, {en:"tonight",cn:"今晚",ipa:"/təˈnaɪt/"}, {en:"huge",cn:"巨大的",ipa:"/hjuːdʒ/"}, {en:"ball",cn:"球",ipa:"/bɔːl/"}, {en:"no",cn:"不",ipa:"/nəʊ/"},
    {en:"close",cn:"关",ipa:"/kləʊs/"}, {en:"finish",cn:"完成",ipa:"/ˈfɪnɪʃ/"}, {en:"yourself",cn:"你自己",ipa:"/jɔːˈself/"}, {en:"talk",cn:"谈话",ipa:"/tɔːk/"}, {en:"theory",cn:"理论",ipa:"/ˈθɪəri/"},
    {en:"impact",cn:"影响",ipa:"/ˈɪmpækt/"}, {en:"respond",cn:"回答",ipa:"/rɪˈspɒnd/"}, {en:"statement",cn:"声明",ipa:"/ˈsteɪtmənt/"}, {en:"maintain",cn:"维持",ipa:"/meɪnˈteɪn/"}, {en:"charge",cn:"收费/指控",ipa:"/tʃɑːdʒ/"},
    {en:"popular",cn:"流行的",ipa:"/ˈpɒpjələ/"}, {en:"traditional",cn:"传统的",ipa:"/trəˈdɪʃənl/"}, {en:"onto",cn:"在...之上",ipa:"/ˈɒntuː/"}, {en:"reveal",cn:"揭示",ipa:"/rɪˈviːl/"}, {en:"direction",cn:"方向",ipa:"/dəˈrekʃn/"},
    {en:"weapon",cn:"武器",ipa:"/ˈwepən/"}, {en:"employee",cn:"雇员",ipa:"/ɪmˈplɔɪiː/"}, {en:"cultural",cn:"文化的",ipa:"/ˈkʌltʃərəl/"}, {en:"contain",cn:"包含",ipa:"/kənˈteɪn/"}, {en:"peace",cn:"和平",ipa:"/piːs/"},
    {en:"head",cn:"头",ipa:"/hed/"}, {en:"control",cn:"控制",ipa:"/kənˈtrəʊl/"}, {en:"base",cn:"基础",ipa:"/beɪs/"}, {en:"pain",cn:"痛苦",ipa:"/peɪn/"}, {en:"apply",cn:"应用",ipa:"/əˈplaɪ/"},
    {en:"play",cn:"戏剧",ipa:"/pleɪ/"}, {en:"measure",cn:"措施/测量",ipa:"/ˈmeʒə/"}, {en:"wide",cn:"宽的",ipa:"/waɪd/"}, {en:"shake",cn:"摇",ipa:"/ʃeɪk/"}, {en:"fly",cn:"飞",ipa:"/flaɪ/"},
    {en:"interview",cn:"面试",ipa:"/ˈɪntəvjuː/"}, {en:"manage",cn:"管理",ipa:"/ˈmænɪdʒ/"}, {en:"chair",cn:"椅子",ipa:"/tʃeə/"}, {en:"fish",cn:"鱼",ipa:"/fɪʃ/"}, {en:"particular",cn:"特别的",ipa:"/pəˈtɪkjələ/"},
    {en:"camera",cn:"照相机",ipa:"/ˈkæmrə/"}, {en:"structure",cn:"结构",ipa:"/ˈstrʌktʃə/"}, {en:"politics",cn:"政治",ipa:"/ˈpɒlətɪks/"}, {en:"perform",cn:"执行",ipa:"/pəˈfɔːm/"}, {en:"bit",cn:"一点",ipa:"/bɪt/"},
    {en:"weight",cn:"重量",ipa:"/weɪt/"}, {en:"suddenly",cn:"突然地",ipa:"/ˈsʌdnli/"}, {en:"discover",cn:"发现",ipa:"/dɪˈskʌvə/"}, {en:"candidate",cn:"候选人",ipa:"/ˈkændɪdət/"}, {en:"top",cn:"顶端",ipa:"/tɒp/"},
    {en:"production",cn:"生产",ipa:"/prəˈdʌkʃn/"}, {en:"treat",cn:"对待",ipa:"/triːt/"}, {en:"trip",cn:"旅行",ipa:"/trɪp/"}, {en:"evening",cn:"晚上",ipa:"/ˈiːvnɪŋ/"}, {en:"affect",cn:"影响",ipa:"/əˈfekt/"},
    {en:"inside",cn:"在里面",ipa:"/ˌɪnˈsaɪd/"}, {en:"conference",cn:"会议",ipa:"/ˈkɒnfərəns/"}, {en:"unit",cn:"单元",ipa:"/ˈjuːnɪt/"}, {en:"best",cn:"最好的",ipa:"/best/"}, {en:"style",cn:"风格",ipa:"/staɪl/"},
    {en:"adult",cn:"成年人",ipa:"/ˈædʌlt/"}, {en:"worry",cn:"担心",ipa:"/ˈwʌri/"}, {en:"range",cn:"范围",ipa:"/reɪndʒ/"}, {en:"mention",cn:"提及",ipa:"/ˈmenʃn/"}, {en:"rather",cn:"宁愿"},
    {en:"far",cn:"远",ipa:"/fɑː/"}, {en:"deep",cn:"深的",ipa:"/diːp/"}, {en:"front",cn:"前面",ipa:"/frʌnt/"}, {en:"edge",cn:"边缘",ipa:"/edʒ/"}, {en:"individual",cn:"个人",ipa:"/ˌɪndɪˈvɪdʒuəl/"},
    {en:"specific",cn:"具体的",ipa:"/spəˈsɪfɪk/"}, {en:"writer",cn:"作家",ipa:"/ˈraɪtə/"}, {en:"trouble",cn:"麻烦",ipa:"/ˈtrʌbl/"}, {en:"necessary",cn:"必要的",ipa:"/ˈnesəsəri/"}, {en:"throughout",cn:"遍及",ipa:"/θruːˈaʊt/"},
    {en:"challenge",cn:"挑战",ipa:"/ˈtʃælɪndʒ/"}, {en:"fear",cn:"恐惧",ipa:"/fɪə/"}, {en:"shoulder",cn:"肩膀",ipa:"/ˈʃəʊldə/"}, {en:"institution",cn:"机构",ipa:"/ˌɪnstɪˈtjuːʃn/"}, {en:"middle",cn:"中间",ipa:"/ˈmɪdl/"},
    {en:"sea",cn:"海",ipa:"/siː/"}, {en:"dream",cn:"梦想",ipa:"/driːm/"}, {en:"bar",cn:"酒吧/条",ipa:"/bɑː/"}, {en:"beautiful",cn:"美丽的",ipa:"/ˈbjuːtɪfl/"}, {en:"property",cn:"财产",ipa:"/ˈprɒpəti/"},
    {en:"instead",cn:"代替",ipa:"/ɪnˈsted/"}, {en:"improve",cn:"改善",ipa:"/ɪmˈpruːv/"}, {en:"stuff",cn:"东西",ipa:"/stʌf/"}, {en:"detail",cn:"细节",ipa:"/ˈdiːteɪl/"}
  ],

  "自定义":[]
};

/* =========================
   B) 存储：复习记录 + 星星
   ========================= */
const LS_KEY = "ETP_APP_V2";
function loadState(){
  try{
    return JSON.parse(localStorage.getItem(LS_KEY) || "{}");
  }catch(e){ return {}; }
}
function saveState(s){
  localStorage.setItem(LS_KEY, JSON.stringify(s));
}

// state schema
// {
//   items: { "Day 1::hello": {star:true, wrong:1, right:2, lastAt:...}, ... },
//   starsTotal: number,
//   streak: number,
//   goal: number,
//   todayKey: "YYYY-MM-DD",
//   todayStars: number
// }
function ensureState(){
  const s = loadState();
  if(!s.items) s.items = {};
  if(typeof s.starsTotal !== "number") s.starsTotal = 0;
  if(typeof s.streak !== "number") s.streak = 0;
  if(typeof s.goal !== "number") s.goal = 20;
  if(typeof s.todayStars !== "number") s.todayStars = 0;
  if(!Array.isArray(s.customData)) s.customData = [];

  const today = new Date();
  const k = `${today.getFullYear()}-${String(today.getMonth()+1).padStart(2,"0")}-${String(today.getDate()).padStart(2,"0")}`;
  if(s.todayKey !== k){
    s.todayKey = k;
    s.todayStars = 0;
    s.streak = 0; // 新的一天连击清零（也可以不清，你想怎样都行）
  }

  saveState(s);
  return s;
}

let APP = ensureState();

function normalize(s){
  return (s || "").trim().replace(/\s+/g, " ").toLowerCase();
}
function itemKey(day, en){
  return `${day}::${en}`;
}
function getRec(day, en){
  const k = itemKey(day, en);
  if(!APP.items[k]){
    APP.items[k] = { star:false, wrong:0, right:0, lastAt:0 };
  }
  return APP.items[k];
}
function toast(msg){
  const t = document.getElementById("toast");
  t.textContent = msg;
  t.classList.add("show");
  setTimeout(()=>t.classList.remove("show"), 1400);
}

/* =========================
   UI Helpers (IPA Data)
   ========================= */
const IPA_DATA = {
  // 元音
  "i:": { tip: "😊 嘴角向两边用力拉开，像微笑一样。", img: "https://placehold.co/300x200/fff7ed/ea580c?text=Smile+%5Bi:%5D" },
  "ɑ:": { tip: "😮 张大嘴巴，像看牙医说 '啊——'，舌头放平。", img: "https://placehold.co/300x200/fff7ed/ea580c?text=Open+Mouth+%5Ba:%5D" },
  "ɔ:": { tip: "😯 嘴巴张大并成圆形，像说 '噢'。", img: "https://placehold.co/300x200/fff7ed/ea580c?text=Round+Mouth+%5Bc:%5D" },
  "u:": { tip: "😚 嘴唇收圆向前突出，像吹口哨。", img: "https://placehold.co/300x200/fff7ed/ea580c?text=Whistle+%5Bu:%5D" },
  "ɜ:": { tip: "😐 嘴形扁平，舌身平放，像发呆时的声音。", img: "https://placehold.co/300x200/fff7ed/ea580c?text=Flat+Mouth+%5Bz:%5D" },
  "ɪ":  { tip: "🙂 嘴角微微张开，比 i: 放松，短促有力。", img: "https://placehold.co/300x200/fff7ed/ea580c?text=Short+%5Bi%5D" },
  "e":  { tip: "😁 嘴巴张开一指宽，舌尖抵下齿。", img: "https://placehold.co/300x200/fff7ed/ea580c?text=One+Finger+%5Be%5D" },
  "æ":  { tip: "😲 '梅花音'：嘴巴张大（放进三指），舌尖抵下齿。", img: "https://placehold.co/300x200/fff7ed/ea580c?text=Big+Mouth+%5Bae%5D" },
  "ʌ":  { tip: "🤔 嘴巴半开，短促有力，像被针扎了一下 '啊'。", img: "https://placehold.co/300x200/fff7ed/ea580c?text=Short+Ah+%5Bv%5D" },
  "ɒ":  { tip: "🧐 嘴巴张大成圆形，短促。", img: "https://placehold.co/300x200/fff7ed/ea580c?text=Round+Short+%5Bo%5D" },
  "ʊ":  { tip: "😗 嘴唇微圆，比 u: 放松。", img: "https://placehold.co/300x200/fff7ed/ea580c?text=Relax+Round+%5Bu%5D" },
  "ə":  { tip: "😴 嘴巴自然微张，最放松的音，轻读。", img: "https://placehold.co/300x200/fff7ed/ea580c?text=Relax+%5Be%5D" },
  // 双元音
  "eɪ": { tip: "👉 从 e 滑向 ɪ，像字母 A 的发音。", img: "https://placehold.co/300x200/eff6ff/2563eb?text=e+-%3E+i" },
  "aɪ": { tip: "👉 从 a 滑向 ɪ，像 '爱'。", img: "https://placehold.co/300x200/eff6ff/2563eb?text=a+-%3E+i" },
  "ɔɪ": { tip: "👉 从 ɔ 滑向 ɪ，像 'boy'。", img: "https://placehold.co/300x200/eff6ff/2563eb?text=o+-%3E+i" },
  "əʊ": { tip: "👉 从 ə 滑向 ʊ，像 '哦'。", img: "https://placehold.co/300x200/eff6ff/2563eb?text=e+-%3E+u" },
  "aʊ": { tip: "👉 从 a 滑向 ʊ，像被踩了一脚 '嗷'！", img: "https://placehold.co/300x200/eff6ff/2563eb?text=a+-%3E+u" },
  "ɪə": { tip: "👂 从 ɪ 滑向 ə，像 '耳'。", img: "https://placehold.co/300x200/eff6ff/2563eb?text=i+-%3E+e" },
  "eə": { tip: "💨 从 e 滑向 ə，像 '空气'。", img: "https://placehold.co/300x200/eff6ff/2563eb?text=e+-%3E+e" },
  "ʊə": { tip: "👉 从 ʊ 滑向 ə。", img: "https://placehold.co/300x200/eff6ff/2563eb?text=u+-%3E+e" },
  // 辅音
  "p":  { tip: "💥 双唇紧闭，气流突然冲开（爆破）。声带不振动。", img: "https://placehold.co/300x200/f0fdf4/16a34a?text=Pop!+%5Bp%5D" },
  "b":  { tip: "🔊 动作同 p，但声带要振动。", img: "https://placehold.co/300x200/f0fdf4/16a34a?text=Voice+%5Bb%5D" },
  "t":  { tip: "💥 舌尖抵上齿龈，气流冲开。声带不振动。", img: "https://placehold.co/300x200/f0fdf4/16a34a?text=Tip+%5Bt%5D" },
  "d":  { tip: "🔊 动作同 t，但声带要振动。", img: "https://placehold.co/300x200/f0fdf4/16a34a?text=Voice+%5Bd%5D" },
  "k":  { tip: "💥 舌后部抵软腭，气流冲开。声带不振动。", img: "https://placehold.co/300x200/f0fdf4/16a34a?text=Back+%5Bk%5D" },
  "g":  { tip: "🔊 动作同 k，但声带要振动。", img: "https://placehold.co/300x200/f0fdf4/16a34a?text=Voice+%5Bg%5D" },
  "f":  { tip: "🦷 上齿轻咬下唇，吹气。声带不振动。", img: "https://placehold.co/300x200/f0fdf4/16a34a?text=Bite+Lip+%5Bf%5D" },
  "v":  { tip: "🔊 动作同 f，但声带要振动。", img: "https://placehold.co/300x200/f0fdf4/16a34a?text=Voice+%5Bv%5D" },
  "s":  { tip: "🐍 舌尖靠近上齿龈，吹气像蛇叫。声带不振动。", img: "https://placehold.co/300x200/f0fdf4/16a34a?text=Snake+%5Bs%5D" },
  "z":  { tip: "🐝 动作同 s，但声带振动像蜜蜂。", img: "https://placehold.co/300x200/f0fdf4/16a34a?text=Bee+%5Bz%5D" },
  "θ":  { tip: "👅 '咬舌音'：舌尖放在上下齿之间，吹气。声带不振动。", img: "https://placehold.co/300x200/f0fdf4/16a34a?text=Bite+Tongue+%5Bth%5D" },
  "ð":  { tip: "🔊 动作同 θ，但声带要振动。", img: "https://placehold.co/300x200/f0fdf4/16a34a?text=Voice+%5Bth%5D" },
  "ʃ":  { tip: "🤫 卷舌，像叫人 '安静' (shhh)。", img: "https://placehold.co/300x200/f0fdf4/16a34a?text=Hush+%5Bsh%5D" },
  "ʒ":  { tip: "🔊 动作同 ʃ，但声带要振动。", img: "https://placehold.co/300x200/f0fdf4/16a34a?text=Voice+%5Bzh%5D" },
  "r":  { tip: "🌀 舌尖卷起（不接触上颚）。", img: "https://placehold.co/300x200/f0fdf4/16a34a?text=Roll+%5Br%5D" },
  "h":  { tip: "💨 嘴巴自然张开，呵气。", img: "https://placehold.co/300x200/f0fdf4/16a34a?text=Air+%5Bh%5D" },
  "m":  { tip: "🤐 双唇紧闭，声音从鼻子里出来。", img: "https://placehold.co/300x200/f0fdf4/16a34a?text=Nose+%5Bm%5D" },
  "n":  { tip: "👃 舌尖抵上齿龈，声音从鼻子里出来。", img: "https://placehold.co/300x200/f0fdf4/16a34a?text=Nose+%5Bn%5D" },
  "ŋ":  { tip: "👃 舌后部抵软腭，声音从鼻子里出来。", img: "https://placehold.co/300x200/f0fdf4/16a34a?text=Back+Nose+%5Bng%5D" },
  "l":  { tip: "👅 舌尖抵上齿龈，气流从舌头两侧通过。", img: "https://placehold.co/300x200/f0fdf4/16a34a?text=Side+%5Bl%5D" },
  "w":  { tip: "3️⃣ 嘴唇收圆像 w，迅速滑向后面的元音。", img: "https://placehold.co/300x200/f0fdf4/16a34a?text=Round+%5Bw%5D" },
  "j":  { tip: "👉 像发 'y' (yes)，舌面前部抬起。", img: "https://placehold.co/300x200/f0fdf4/16a34a?text=Yeah+%5Bj%5D" }
};

const modeSelect = document.getElementById("modeSelect");
const enText = document.getElementById("enText");
const cnText = document.getElementById("cnText");
const inputEl = document.getElementById("inputEl");
const hintEl = document.getElementById("hintEl");

const posEl = document.getElementById("posEl");
const totalEl = document.getElementById("totalEl");
const correctEl = document.getElementById("correctEl");
const wrongEl = document.getElementById("wrongEl");
const accEl = document.getElementById("accEl");
const barEl = document.getElementById("barEl");

const prevBtn = document.getElementById("prevBtn");
const nextBtn = document.getElementById("nextBtn");
const speakBtn = document.getElementById("speakBtn");
const markBtn = document.getElementById("markBtn");
const resetBtn = document.getElementById("resetBtn");

const customArea = document.getElementById("customArea");
const loadCustomBtn = document.getElementById("loadCustomBtn");
const clearCustomBtn = document.getElementById("clearCustomBtn");
const clearAllBtn = document.getElementById("clearAllBtn");

const markCount = document.getElementById("markCount");
const wrongCount = document.getElementById("wrongCount");
const modeName = document.getElementById("modeName");
const reviewList = document.getElementById("reviewList");

const starTotal = document.getElementById("starTotal");
const streakEl = document.getElementById("streakEl");
const goalEl = document.getElementById("goalEl");
const setGoalBtn = document.getElementById("setGoalBtn");
const clearStarsBtn = document.getElementById("clearStarsBtn");

// app run state
let currentMode = "Day 1";
let currentDayForReview = "Day 1";
let activeList = []; // {day,en,cn}
let pos = 0;

let correct = 0;
let wrong = 0;

function rebuildModeSelect(){
  modeSelect.innerHTML = "";

  Object.keys(DAYS).forEach(k=>{
    const opt = document.createElement("option");
    opt.value = k;
    opt.textContent = k;
    modeSelect.appendChild(opt);
  });

  const opt1 = document.createElement("option");
  opt1.value = "__review_day__";
  opt1.textContent = "复习（当天不熟练）";
  modeSelect.appendChild(opt1);

  const opt2 = document.createElement("option");
  opt2.value = "__review_all__";
  opt2.textContent = "复习（全局不熟练）";
  modeSelect.appendChild(opt2);
}

function buildReview(scope, day){
  const out = [];
  const keys = (scope==="day") ? [day] : Object.keys(DAYS);

  keys.forEach(d=>{
    (DAYS[d]||[]).forEach(it=>{
      const r = getRec(d, it.en);
      if(r.star || r.wrong>0){
        out.push({day:d, en:it.en, cn:it.cn, ipa:it.ipa});
      }
    });
  });

  // sort: wrong desc, star first
  out.sort((a,b)=>{
    const ra = getRec(a.day, a.en);
    const rb = getRec(b.day, b.en);
    if(rb.wrong !== ra.wrong) return rb.wrong - ra.wrong;
    if((rb.star?1:0) !== (ra.star?1:0)) return (rb.star?1:0) - (ra.star?1:0);
    return a.en.localeCompare(b.en);
  });

  return out;
}

function buildActiveList(){
  if(currentMode === "__review_day__"){
    activeList = buildReview("day", currentDayForReview);
  }else if(currentMode === "__review_all__"){
    activeList = buildReview("all");
  }else{
    currentDayForReview = currentMode;
    activeList = (DAYS[currentMode]||[]).map(x=>({day:currentMode, en:x.en, cn:x.cn, ipa:x.ipa}));
  }
}

function updateStatsUI(){
  correctEl.textContent = String(correct);
  wrongEl.textContent = String(wrong);
  const total = correct + wrong;
  const acc = total===0 ? 0 : Math.round(correct/total*100);
  accEl.textContent = acc + "%";
}

function updateProgressUI(){
  const total = activeList.length;
  totalEl.textContent = String(total);
  posEl.textContent = total===0 ? "0" : String(Math.min(pos+1,total));
  const pct = total===0 ? 0 : Math.round((pos/Math.max(1,total))*100);
  barEl.style.width = pct + "%";
}

function updateRewardUI(){
  starTotal.textContent = String(APP.starsTotal);
  streakEl.textContent = String(APP.streak);
  goalEl.textContent = String(APP.goal);
}

function updateSidePanel(){
  let mc = 0, wc = 0;
  Object.values(APP.items).forEach(v=>{
    if(v.star) mc++;
    if(v.wrong>0) wc++;
  });
  markCount.textContent = String(mc);
  wrongCount.textContent = String(wc);

  let name = currentMode;
  if(currentMode==="__review_day__") name = `复习（当天不熟练：${currentDayForReview}）`;
  if(currentMode==="__review_all__") name = "复习（全局不熟练）";
  modeName.textContent = name;

  // list shown: day review unless all-review
  const listToShow = (currentMode==="__review_all__")
    ? buildReview("all")
    : buildReview("day", currentDayForReview);

  reviewList.innerHTML = "";
  if(listToShow.length===0){
    const div = document.createElement("div");
    div.className = "item";
    div.innerHTML = `<div class="a">暂无不熟练内容</div><div class="b">做错或点 ⭐ 后，会自动出现在这里</div>`;
    reviewList.appendChild(div);
    return;
  }

  listToShow.slice(0,80).forEach(it=>{
    const r = getRec(it.day, it.en);
    const div = document.createElement("div");
    div.className = "item";
    div.innerHTML = `
      <div class="a">${it.en}</div>
      <div class="b">${it.cn} <span class="soft">（${it.day}）</span></div>
      <div class="meta">
        <span class="tag ${r.star ? "ok" : ""}">${r.star ? "⭐已标记" : "未标记"}</span>
        <span class="tag ${r.wrong>0 ? "bad" : ""}">❌错误 ${r.wrong}</span>
        <span class="tag">✅正确 ${r.right||0}</span>
      </div>
    `;
    reviewList.appendChild(div);
  });
}

function currentItem(){
  if(activeList.length===0) return null;
  return activeList[pos];
}

function render(){
  buildActiveList();
  pos = 0;
  correct = 0;
  wrong = 0;

  updateRewardUI();
  updateStatsUI();
  updateSidePanel();

  if(activeList.length===0){
    enText.textContent = "（没有内容）";
    cnText.textContent = "这个列表为空：先练习并做错/标记一些，再进入复习。";
    inputEl.value = "";
    inputEl.disabled = true;
    hintEl.innerHTML = `<span class="soft">切换到 Day 或 小学六年级 开始练习。</span>`;
    updateProgressUI();
    markBtn.disabled = true;
    prevBtn.disabled = true;
    nextBtn.disabled = true;
    return;
  }

  inputEl.disabled = false;
  markBtn.disabled = false;
  prevBtn.disabled = false;
  nextBtn.disabled = false;

  const it = currentItem();
  enText.innerHTML = it.en + (it.ipa ? ` <span style="font-size:20px;color:#6b7280;font-weight:400;">${it.ipa}</span>` : "");
  cnText.textContent = it.cn;

  // 检查是否有 IPA 数据（图片/技巧）
  const mediaBox = document.getElementById("mediaBox");
  const ipaImg = document.getElementById("ipaImg");
  const ipaTip = document.getElementById("ipaTip");
  const ipaInfo = IPA_DATA[it.en];

  if(ipaInfo){
    mediaBox.style.display = "block";
    ipaImg.src = ipaInfo.img;
    ipaTip.textContent = ipaInfo.tip;
  }else{
    mediaBox.style.display = "none";
  }

  inputEl.value = "";
  hintEl.innerHTML = `<span class="soft">开始输入英文…（忽略大小写/多空格）</span>`;
  updateProgressUI();
  inputEl.focus();

  const r = getRec(it.day, it.en);
  markBtn.textContent = r.star ? "⭐ 已加入复习（点取消）" : "⭐ 加入复习";
}

function goNext(){
  if(activeList.length===0) return;
  if(pos < activeList.length-1){
    pos++;
    const it = currentItem();
    enText.textContent = it.en;
    cnText.textContent = it.cn;
    inputEl.value = "";
    hintEl.innerHTML = `<span class="soft">开始输入英文…</span>`;
    updateProgressUI();
    inputEl.focus();

    const r = getRec(it.day, it.en);
    markBtn.textContent = r.star ? "⭐ 已加入复习（点取消）" : "⭐ 加入复习";
  }else{
    enText.textContent = "🎉 完成！";
    cnText.textContent = "本列表已练完。可以切换天数或进入复习。";
    hintEl.innerHTML = `<span class="ok">完成！</span> <span class="soft">去复习巩固薄弱项吧。</span>`;
    inputEl.value = "";
    inputEl.disabled = true;
    barEl.style.width = "100%";
  }
}

function goPrev(){
  if(activeList.length===0) return;
  if(pos > 0){
    pos--;
    const it = currentItem();
    enText.textContent = it.en;
    cnText.textContent = it.cn;
    inputEl.value = "";
    hintEl.innerHTML = `<span class="soft">开始输入英文…</span>`;
    updateProgressUI();
    inputEl.focus();

    const r = getRec(it.day, it.en);
    markBtn.textContent = r.star ? "⭐ 已加入复习（点取消）" : "⭐ 加入复习";
  }
}

function speak(){
  const it = currentItem();
  if(!it) return;
  if(!("speechSynthesis" in window)){
    alert("你的浏览器不支持朗读，请用 Chrome/Edge。");
    return;
  }
  const u = new SpeechSynthesisUtterance(it.en);
  u.lang = "en-US";
  u.rate = 0.95;
  window.speechSynthesis.cancel();
  window.speechSynthesis.speak(u);
}

function toggleStar(){
  const it = currentItem();
  if(!it) return;
  const r = getRec(it.day, it.en);
  r.star = !r.star;
  r.lastAt = Date.now();
  saveState(APP);

  markBtn.textContent = r.star ? "⭐ 已加入复习（点取消）" : "⭐ 加入复习";
  updateSidePanel();
  toast(r.star ? "已加入复习 ⭐" : "已取消标记");
}

function resetCurrent(){
  correct = 0; wrong = 0; pos = 0;
  inputEl.disabled = false;
  render();
}

function clearAllRecords(){
  if(!confirm("确定清空所有记录（星标/错误次数/正确次数）吗？")) return;
  APP.items = {};
  saveState(APP);
  render();
}

function addStars(amount){
  APP.starsTotal += amount;
  APP.todayStars += amount;
  saveState(APP);
  updateRewardUI();

  // 达成目标
  if(APP.todayStars >= APP.goal){
    toast(`🎉 达成目标！今天已获得 ${APP.todayStars} ⭐`);
  }
}

function onCorrect(){
  // 星星奖励：基础1，连击加成（最多+3）
  APP.streak = Math.min(10, (APP.streak||0) + 1);
  const bonus = Math.min(3, Math.floor(APP.streak/3)); // 0~3
  const gain = 1 + bonus;
  addStars(gain);

  if(gain >= 3) toast(`🔥 连击 ${APP.streak}！+${gain}⭐`);
}

function onWrong(){
  APP.streak = 0; // 错了连击清零
  saveState(APP);
  updateRewardUI();
}

setGoalBtn.addEventListener("click", ()=>{
  const v = prompt("设置今日目标（星星数）", String(APP.goal));
  if(v===null) return;
  const n = parseInt(v, 10);
  if(!Number.isFinite(n) || n<=0){
    alert("请输入大于0的数字");
    return;
  }
  APP.goal = n;
  saveState(APP);
  updateRewardUI();
  toast(`今日目标已设为 ${n} ⭐`);
});

clearStarsBtn.addEventListener("click", ()=>{
  if(!confirm("确定清空星星吗？（总星星会归零）")) return;
  APP.starsTotal = 0;
  APP.todayStars = 0;
  APP.streak = 0;
  saveState(APP);
  updateRewardUI();
  toast("已清空星星");
});

/* =========================
   输入判断（实时）+ Enter 提交（记录错误）
   ========================= */
inputEl.addEventListener("input", ()=>{
  const it = currentItem();
  if(!it) return;

  const target = normalize(it.en);
  const typed = normalize(inputEl.value);

  if(typed.length === 0){
    hintEl.innerHTML = `<span class="soft">开始输入英文…</span>`;
    return;
  }

  if(typed === target){
    hintEl.innerHTML = `<span class="ok">✔ 正确！</span> <span class="soft">0.5秒后下一条</span>`;
    correct++;
    updateStatsUI();

    const r = getRec(it.day, it.en);
    r.right = (r.right||0) + 1;
    r.lastAt = Date.now();
    saveState(APP);

    onCorrect();
    updateSidePanel();

    setTimeout(()=>{
      if(inputEl.disabled) return;
      goNext();
      updateProgressUI();
    }, 500);
  }else{
    hintEl.innerHTML = `<span class="bad">✖ 继续输入…</span> <span class="soft">（拼写/少字/多字）</span>`;
  }
});

inputEl.addEventListener("keydown",(e)=>{
  if(e.key === "Enter"){
    e.preventDefault();
    const it = currentItem();
    if(!it) return;

    const target = normalize(it.en);
    const typed = normalize(inputEl.value);

    if(typed !== target){
      wrong++;
      updateStatsUI();

      const r = getRec(it.day, it.en);
      r.wrong = (r.wrong||0) + 1;
      r.lastAt = Date.now();
      saveState(APP);

      onWrong();
      updateSidePanel();

      hintEl.innerHTML = `<span class="bad">✖ 不对哦</span> <span class="soft">（已记录错误次数，建议点 ⭐ 加入复习）</span>`;
      toast("已记录错误 ❌");
    }
  }
});

/* =========================
   自定义内容
   ========================= */
loadCustomBtn.addEventListener("click", ()=>{
  const lines = customArea.value.split("\n").map(l=>l.trim()).filter(Boolean);
  const arr = [];
  for(const line of lines){
    const parts = line.split("=");
    if(parts.length < 2) continue;
    const en = parts[0].trim();
    const cn = parts.slice(1).join("=").trim();
    if(en && cn) arr.push({en, cn});
  }
  DAYS["自定义"] = arr;
  APP.customData = arr; // 保存到状态
  saveState(APP);

  rebuildModeSelect();
  currentMode = "自定义";
  modeSelect.value = "自定义";
  currentDayForReview = "自定义";
  render();
  toast("已加载自定义内容并保存 ✅");
});

clearCustomBtn.addEventListener("click", ()=>{
  if(!confirm("确定清空自定义内容吗？")) return;
  customArea.value = "";
  DAYS["自定义"] = [];
  APP.customData = []; // 清空状态
  saveState(APP);
  
  rebuildModeSelect();
  if(currentMode === "自定义") render();
  toast("已清空自定义");
});

/* =========================
   mode change + buttons
   ========================= */
modeSelect.addEventListener("change", ()=>{
  currentMode = modeSelect.value;
  render();
});

prevBtn.addEventListener("click", goPrev);
nextBtn.addEventListener("click", goNext);
speakBtn.addEventListener("click", speak);
markBtn.addEventListener("click", toggleStar);
resetBtn.addEventListener("click", resetCurrent);
clearAllBtn.addEventListener("click", clearAllRecords);

/* =========================
   init
   ========================= */
function init(){
  // 恢复自定义内容
  if(APP.customData && APP.customData.length > 0){
    DAYS["自定义"] = APP.customData;
    // 同时也回填到输入框，方便用户查看
    const lines = APP.customData.map(it => `${it.en}=${it.cn}`);
    customArea.value = lines.join("\n");
  }

  rebuildModeSelect();
  if(!DAYS[currentMode]) currentMode = "Day 1";
  modeSelect.value = currentMode;
  render();
}
init();
</script>
</body>
</html>
