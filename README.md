<html lang="zh-Hans">
<head>
  <meta charset="UTF-8" />
  <title>糖和大脑 - HSK4 阅读测验</title>
  <style>
    body {
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f7fb;
      color: #222;
      line-height: 1.6;
    }

    .container {
      max-width: 900px;
      margin: 40px auto;
      padding: 24px 20px 60px;
      background: #ffffff;
      border-radius: 16px;
      box-shadow: 0 10px 30px rgba(0,0,0,0.06);
    }

    h1 {
      font-size: 26px;
      text-align: center;
      margin-bottom: 8px;
    }

    .subtitle {
      text-align: center;
      color: #666;
      font-size: 14px;
      margin-bottom: 24px;
    }

    .article-box {
      background: #f0f4ff;
      border-radius: 12px;
      padding: 16px 18px;
      margin-bottom: 28px;
      border: 1px solid #d7e0ff;
    }

    .article-title {
      font-weight: 700;
      margin-bottom: 8px;
    }

    .article-text {
      font-size: 14px;
    }

    .quiz-intro {
      font-size: 15px;
      margin-bottom: 10px;
    }

    .question {
      margin-bottom: 22px;
      padding: 14px 16px;
      border-radius: 10px;
      border: 1px solid #e2e6f0;
      background: #fafbff;
      position: relative;
    }

    .question.correct {
      border-color: #28a745;
      background: #f2fff5;
    }

    .question.incorrect {
      border-color: #dc3545;
      background: #fff5f5;
    }

    .question-header {
      font-weight: 600;
      margin-bottom: 8px;
    }

    .question-th {
      font-size: 13px;
      color: #555;
      margin-bottom: 6px;
    }

    .choices {
      margin-top: 4px;
    }

    .choice {
      display: block;
      margin-bottom: 4px;
      font-size: 14px;
      cursor: pointer;
    }

    .choice input {
      margin-right: 6px;
    }

    .actions {
      text-align: center;
      margin: 30px 0 18px;
    }

    button {
      cursor: pointer;
      border: none;
      border-radius: 999px;
      padding: 10px 26px;
      font-size: 15px;
      font-weight: 600;
      background: #3b82f6;
      color: #fff;
      box-shadow: 0 8px 20px rgba(59,130,246,0.3);
      transition: transform 0.05s ease, box-shadow 0.05s ease, background 0.2s;
    }

    button:hover {
      background: #2563eb;
      transform: translateY(-1px);
      box-shadow: 0 10px 24px rgba(37,99,235,0.35);
    }

    button:active {
      transform: translateY(0);
      box-shadow: 0 6px 14px rgba(37,99,235,0.25);
    }

    .score-box {
      text-align: center;
      font-size: 16px;
      font-weight: 600;
      margin-bottom: 10px;
      display: none;
    }

    .score-box span {
      font-size: 18px;
    }

    .explanation {
      margin-top: 10px;
      padding-top: 8px;
      border-top: 1px dashed #d0d5e5;
      font-size: 13px;
      display: none;
    }

    .exp-title {
      font-weight: 700;
      margin-bottom: 4px;
    }

    .exp-block {
      margin-bottom: 4px;
    }

    .exp-choice-label {
      font-weight: 600;
    }

    .exp-correct {
      color: #1a7f37;
    }

    .exp-wrong {
      color: #b42318;
    }

    .footer-note {
      margin-top: 30px;
      font-size: 12px;
      color: #777;
      text-align: center;
    }

    .feedback-box {
      margin-top: 32px;
      padding: 16px 18px;
      border-radius: 12px;
      border: 1px solid #e2e6f0;
      background: #f9fafb;
    }

    .feedback-title {
      font-weight: 700;
      margin-bottom: 8px;
    }

    .feedback-sub {
      font-size: 13px;
      color: #555;
      margin-bottom: 10px;
    }

    .rating-row {
      margin-bottom: 10px;
      font-size: 14px;
    }

    .rating-row label {
      margin-right: 8px;
      cursor: pointer;
    }

    .feedback-textarea {
      width: 100%;
      min-height: 80px;
      border-radius: 8px;
      border: 1px solid #d0d5e5;
      padding: 8px 10px;
      font-size: 14px;
      resize: vertical;
      box-sizing: border-box;
      font-family: inherit;
    }

    .feedback-actions {
      margin-top: 12px;
      display: flex;
      gap: 10px;
      align-items: center;
      flex-wrap: wrap;
    }

    .feedback-msg {
      font-size: 13px;
      color: #16a34a;
      display: none;
    }

    .feedback-error {
      font-size: 13px;
      color: #b42318;
      display: none;
    }

    @media (max-width: 600px) {
      .container {
        margin: 16px;
        padding: 16px 12px 40px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>《糖和大脑》HSK4 阅读测验</h1>
    <div class="subtitle">
      อ่านบทความภาษาจีน → ตอบคำถาม 10 ข้อ → กดตรวจคำตอบ → ดูเฉลย และส่งคะแนน+รีวิวเข้า Google Form / Google Sheet ได้
    </div>

    <div class="article-box">
      <div class="article-title">文章：糖和大脑（HSK4短文版）</div>
      <div class="article-text">
        “糖”是一种碳水化合物，在蛋糕、饮料、番茄酱、酸奶等很多食物里都能看到。
        当我们吃到甜味时，舌头上的甜味点会把信号传给大脑。这个信号会启动大脑的奖励系统，
        让我们觉得开心，并想“要不要再吃一次”。<br><br>
        在奖励系统里，一个很重要的化学物质叫多巴胺。多巴胺越多，我们就越觉得快乐。
        糖能让多巴胺增加，但像西兰花这样的食物不会有这样的作用。<br><br>
        大脑喜欢新的味道，所以多巴胺的变化会因为新的食物而改变。如果一个人吃太多糖，
        多巴胺不会变得稳定，而是会一直保持在较高水平，让人觉得想继续吃。
        但是偶尔吃一块蛋糕是没有问题的。
      </div>
    </div>

    <div class="quiz-intro">
      👉 เลือกคำตอบที่ถูกต้องที่สุดในแต่ละข้อ (一个正确答案) แล้วกดปุ่มด้านล่างเพื่อดูคะแนนและเฉลย
    </div>

    <div id="scoreBox" class="score-box"></div>

    <!-- 10 ข้อสอบ -->
    <div class="question" data-question="1" data-answer="B">
      <div class="question-header">第 1 题</div>
      <div class="question-zh">“糖”主要属于哪一种营养？</div>
      <div class="question-th">น้ำตาลจัดเป็นสารอาหารประเภทไหนเป็นหลัก?</div>
      <div class="choices">
        <label class="choice"><input type="radio" name="q1" value="A">A. 蛋白质</label>
        <label class="choice"><input type="radio" name="q1" value="B">B. 碳水化合物</label>
        <label class="choice"><input type="radio" name="q1" value="C">C. 维生素</label>
        <label class="choice"><input type="radio" name="q1" value="D">D. 脂肪</label>
      </div>
      <div class="explanation">
        <div class="exp-title">解析（คำอธิบาย）</div>
        <div class="exp-block exp-correct">
          <span class="exp-choice-label">B. 碳水化合物：</span>
          文章一开始就说：“糖是一种碳水化合物。”
        </div>
      </div>
    </div>

    <div class="question" data-question="2" data-answer="B">
      <div class="question-header">第 2 题</div>
      <div class="question-zh">糖常常出现在哪些食物里？</div>
      <div class="question-th">น้ำตาลมักจะถูกเติมลงไปในอาหารชนิดใดบ้างตามบทความ?</div>
      <div class="choices">
        <label class="choice"><input type="radio" name="q2" value="A">A. 面条和米饭</label>
        <label class="choice"><input type="radio" name="q2" value="B">B. 番茄酱和酸奶</label>
        <label class="choice"><input type="radio" name="q2" value="C">C. 水果和茶叶</label>
        <label class="choice"><input type="radio" name="q2" value="D">D. 清水和盐</label>
      </div>
      <div class="explanation">
        <div class="exp-title">解析</div>
        <div class="exp-block exp-correct">
          <span class="exp-choice-label">B：</span>
          文章说糖在“蛋糕、饮料、番茄酱、酸奶等很多食物里都能看到”。
        </div>
      </div>
    </div>

    <div class="question" data-question="3" data-answer="C">
      <div class="question-header">第 3 题</div>
      <div class="question-zh">当我们吃到甜味时，最先接收到信号的是？</div>
      <div class="question-th">เมื่อเรากินของหวาน อวัยวะส่วนไหนรับสัญญาณก่อน?</div>
      <div class="choices">
        <label class="choice"><input type="radio" name="q3" value="A">A. 鼻子</label>
        <label class="choice"><input type="radio" name="q3" value="B">B. 牙齿</label>
        <label class="choice"><input type="radio" name="q3" value="C">C. 舌头上的甜味点</label>
        <label class="choice"><input type="radio" name="q3" value="D">D. 喉咙</label>
      </div>
      <div class="explanation">
        <div class="exp-title">解析</div>
        <div class="exp-block exp-correct">
          <span class="exp-choice-label">C：</span>文章说“舌头上的甜味点会把信号传给大脑”。
        </div>
      </div>
    </div>

    <div class="question" data-question="4" data-answer="B">
      <div class="question-header">第 4 题</div>
      <div class="question-zh">甜味信号会让大脑里的什么开始工作？</div>
      <div class="question-th">สัญญาณรสหวานไปกระตุ้นระบบใดในสมอง?</div>
      <div class="choices">
        <label class="choice"><input type="radio" name="q4" value="A">A. 呼吸系统</label>
        <label class="choice"><input type="radio" name="q4" value="B">B. 奖励系统</label>
        <label class="choice"><input type="radio" name="q4" value="C">C. 消化系统</label>
        <label class="choice"><input type="radio" name="q4" value="D">D. 循环系统</label>
      </div>
      <div class="explanation">
        <div class="exp-title">解析</div>
        <div class="exp-block exp-correct">
          <span class="exp-choice-label">B：</span>文章写道“这个信号会启动大脑的奖励系统”。
        </div>
      </div>
    </div>

    <div class="question" data-question="5" data-answer="B">
      <div class="question-header">第 5 题</div>
      <div class="question-zh">奖励系统会让我们产生什么想法？</div>
      <div class="question-th">ระบบรางวัลทำให้เราเกิดความคิดอะไรขึ้นมา?</div>
      <div class="choices">
        <label class="choice"><input type="radio" name="q5" value="A">A. 这个贵不贵？</label>
        <label class="choice"><input type="radio" name="q5" value="B">B. 要不要再吃一次？</label>
        <label class="choice"><input type="radio" name="q5" value="C">C. 我累不累？</label>
        <label class="choice"><input type="radio" name="q5" value="D">D. 我要不要工作？</label>
      </div>
      <div class="explanation">
        <div class="exp-title">解析</div>
        <div class="exp-block exp-correct">
          <span class="exp-choice-label">B：</span>奖励系统会让我们想“要不要再做一次”，这里就是“再吃一次”。
        </div>
      </div>
    </div>

    <div class="question" data-question="6" data-answer="B">
      <div class="question-header">第 6 题</div>
      <div class="question-zh">在奖励系统中，一个很重要的化学物质是？</div>
      <div class="question-th">ในระบบรางวัล มีสารเคมีที่สำคัญตัวหนึ่งคืออะไร?</div>
      <div class="choices">
        <label class="choice"><input type="radio" name="q6" value="A">A. 盐</label>
        <label class="choice"><input type="radio" name="q6" value="B">B. 多巴胺</label>
        <label class="choice"><input type="radio" name="q6" value="C">C. 水分</label>
        <label class="choice"><input type="radio" name="q6" value="D">D. 氧气</label>
      </div>
      <div class="explanation">
        <div class="exp-title">解析</div>
        <div class="exp-block exp-correct">
          <span class="exp-choice-label">B：</span>文章写道“一个很重要的化学物质叫多巴胺”。
        </div>
      </div>
    </div>

    <div class="question" data-question="7" data-answer="C">
      <div class="question-header">第 7 题</div>
      <div class="question-zh">哪种食物不会让多巴胺增加？</div>
      <div class="question-th">อาหารชนิดใด “ไม่ทำให้” โดปามีนเพิ่มขึ้นตามบทความ?</div>
      <div class="choices">
        <label class="choice"><input type="radio" name="q7" value="A">A. 蛋糕</label>
        <label class="choice"><input type="radio" name="q7" value="B">B. 冰淇淋</label>
        <label class="choice"><input type="radio" name="q7" value="C">C. 西兰花</label>
        <label class="choice"><input type="radio" name="q7" value="D">D. 甜饮料</label>
      </div>
      <div class="explanation">
        <div class="exp-title">解析</div>
        <div class="exp-block exp-correct">
          <span class="exp-choice-label">C：</span>文章明确说“像西兰花这样的食物不会有这样的作用”。
        </div>
      </div>
    </div>

    <div class="question" data-question="8" data-answer="A">
      <div class="question-header">第 8 题</div>
      <div class="question-zh">大脑为什么喜欢新的味道？</div>
      <div class="question-th">ทำไมสมองถึง “ชอบ” รสชาติใหม่ ๆ?</div>
      <div class="choices">
        <label class="choice"><input type="radio" name="q8" value="A">A. 可以发现坏掉的食物</label>
        <label class="choice"><input type="radio" name="q8" value="B">B. 可以吃得更多</label>
        <label class="choice"><input type="radio" name="q8" value="C">C. 可以睡得更好</label>
        <label class="choice"><input type="radio" name="q8" value="D">D. 可以不觉得饿</label>
      </div>
      <div class="explanation">
        <div class="exp-title">解析</div>
        <div class="exp-block exp-correct">
          <span class="exp-choice-label">A：</span>这是文章中解释大脑对“新味道”敏感的原因之一。
        </div>
      </div>
    </div>

    <div class="question" data-question="9" data-answer="C">
      <div class="question-header">第 9 题</div>
      <div class="question-zh">如果一个人吃太多糖，多巴胺会怎么样？</div>
      <div class="question-th">ถ้าคนเรากินน้ำตาลมากเกินไป ระดับโดปามีนจะเป็นอย่างไร?</div>
      <div class="choices">
        <label class="choice"><input type="radio" name="q9" value="A">A. 很快变少</label>
        <label class="choice"><input type="radio" name="q9" value="B">B. 完全不出现</label>
        <label class="choice"><input type="radio" name="q9" value="C">C. 一直保持在较高水平</label>
        <label class="choice"><input type="radio" name="q9" value="D">D. 让人马上生病</label>
      </div>
      <div class="explanation">
        <div class="exp-title">解析</div>
        <div class="exp-block exp-correct">
          <span class="exp-choice-label">C：</span>文章指出“多巴胺不会变得稳定，而是会一直保持在较高水平”。
        </div>
      </div>
    </div>

    <div class="question" data-question="10" data-answer="B">
      <div class="question-header">第 10 题</div>
      <div class="question-zh">文章最后说，偶尔吃一块蛋糕怎么样？</div>
      <div class="question-th">ท้ายบทความบอกว่า ถ้ากินเค้กเป็นครั้งคราว จะเป็นอย่างไร?</div>
      <div class="choices">
        <label class="choice"><input type="radio" name="q10" value="A">A. 一定会生病</label>
        <label class="choice"><input type="radio" name="q10" value="B">B. 没问题</label>
        <label class="choice"><input type="radio" name="q10" value="C">C. 肯定会发胖</label>
        <label class="choice"><input type="radio" name="q10" value="D">D. 会影响睡觉</label>
      </div>
      <div class="explanation">
        <div class="exp-title">解析</div>
        <div class="exp-block exp-correct">
          <span class="exp-choice-label">B：</span>文章最后说“偶尔吃一块蛋糕是没有问题的”。
        </div>
      </div>
    </div>

    <div class="actions">
      <button id="checkBtn">ตรวจคำตอบทั้งหมด</button>
    </div>

    <!-- Feedback + Google Form -->
    <div class="feedback-box">
      <div class="feedback-title">แบบประเมินแบบทดสอบ & ส่งเข้า Google Form / Sheet</div>
      <div class="feedback-sub">
        หลังจากตรวจคำตอบแล้ว ให้ให้คะแนนแบบทดสอบนี้ และเขียนข้อเสนอแนะ ระบบจะส่งข้อมูลไปยัง Google Form ที่คุณตั้งค่าไว้
      </div>
      <div class="rating-row">
        ความพอใจต่อแบบทดสอบ (1 = น้อยมาก, 5 = ดีมาก):<br/>
        <label><input type="radio" name="rating" value="1"> 1</label>
        <label><input type="radio" name="rating" value="2"> 2</label>
        <label><input type="radio" name="rating" value="3"> 3</label>
        <label><input type="radio" name="rating" value="4"> 4</label>
        <label><input type="radio" name="rating" value="5"> 5</label>
      </div>
      <div>
        ข้อเสนอแนะเพิ่มเติม / สิ่งที่อยากให้ปรับปรุง:<br/>
        <textarea id="feedbackText" class="feedback-textarea" placeholder="เช่น อยากให้มีข้อสอบฟังเพิ่ม, อยากให้มีระดับ HSK3 เพิ่ม, อยากให้มี timer ฯลฯ"></textarea>
      </div>
      <div class="feedback-actions">
        <button id="feedbackBtn" type="button">ส่งข้อมูลไปที่ Google Form</button>
        <div id="feedbackMsg" class="feedback-msg">กำลังส่งข้อมูลไปยัง Google Form…</div>
        <div id="feedbackError" class="feedback-error">กรุณาใส่ URL Google Form และชื่อช่อง (entry.xxx) ให้ถูกต้องในโค้ดก่อนใช้งาน</div>
      </div>
    </div>

    <div class="footer-note">
      Tip: เปิดไฟล์นี้ใน Editor แล้วใส่ URL Google Form + entry.xxx ให้ตรงกับฟอร์มของคุณ ข้อมูลจะถูกบันทึกลง Google Sheet อัตโนมัติ
    </div>
  </div>

  <!-- ฟอร์มซ่อนสำหรับส่งไป Google Form -->
  <!-- TODO: แก้ action เป็น URL formResponse ของ Google Form ของคุณ
       และแก้ name="entry.xxxxx" ให้ตรงกับแต่ละข้อในฟอร์ม -->
  <form id="gform" action="https://docs.google.com/forms/d/YOUR_GOOGLE_FORM_ID/formResponse" method="POST" target="hidden_iframe" style="display:none;">
    <!-- ช่องสำหรับเก็บ "คะแนนแบบทดสอบ" -->
    <input type="hidden" name="entry.1111111111" id="entryScore">
    <!-- ช่องสำหรับเก็บ "ความพอใจ (1-5)" -->
    <input type="hidden" name="entry.2222222222" id="entryRating">
    <!-- ช่องสำหรับเก็บ "ข้อเสนอแนะ / รีวิว" -->
    <input type="hidden" name="entry.3333333333" id="entryReview">
  </form>
  <iframe name="hidden_iframe" style="display:none;"></iframe>

  <script>
    const checkBtn = document.getElementById('checkBtn');
    const scoreBox = document.getElementById('scoreBox');

    let lastScoreText = "";

    checkBtn.addEventListener('click', () => {
      const questions = document.querySelectorAll('.question');
      let correctCount = 0;
      let total = questions.length;

      questions.forEach(q => {
        const qNum = q.getAttribute('data-question');
        const answer = q.getAttribute('data-answer');
        const selected = document.querySelector('input[name="q' + qNum + '"]:checked');
        const explanation = q.querySelector('.explanation');

        q.classList.remove('correct', 'incorrect');

        if (selected) {
          if (selected.value === answer) {
            correctCount++;
            q.classList.add('correct');
          } else {
            q.classList.add('incorrect');
          }
        } else {
          q.classList.add('incorrect');
        }

        if (explanation) {
          explanation.style.display = 'block';
        }
      });

      lastScoreText = 'ได้คะแนน ' + correctCount + ' / ' + total;
      scoreBox.style.display = 'block';
      scoreBox.innerHTML = 'คุณได้คะแนน <span>' + correctCount + ' / ' + total + '</span>';
    });

    <<!-- ปุ่มไปทำแบบประเมิน Google Form -->
<div style="margin-top: 20px;">
    <button onclick="window.open('https://forms.gle/88a8CwCdxiMrykMy8', '_blank')" 
            style="padding: 10px 20px; font-size: 18px; background-color: #4CAF50; color: white; border: none; border-radius: 6px; cursor: pointer;">
        ทำแบบประเมิน (Google Form)
    </button>
</div>
