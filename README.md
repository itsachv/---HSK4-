<!DOCTYPE html>
<html lang="zh">
<head>
<meta charset="UTF-8">
<title>HSK4 阅读练习：糖和大脑</title>
<style>
    body { font-family: Arial, sans-serif; margin: 30px; line-height: 1.6; }
    h1 { color: #333; }
    .question { margin-top: 20px; }
    .btn { 
        padding: 10px 20px; 
        margin-top: 20px; 
        font-size: 18px; 
        background-color: #4CAF50; 
        color: white; 
        border: none; 
        border-radius: 6px; 
        cursor: pointer; 
    }
    .btn:hover { background-color: #45a049; }
    #resultBox {
        margin-top: 20px;
        padding: 15px;
        border-radius: 8px;
        background-color: #f2f2f2;
        display: none;
    }
</style>
</head>

<body>

<h1>HSK4 阅读：糖和大脑</h1>

<p>
糖是一种常见的食物成分。吃糖的时候，舌头会感觉到“甜”，大脑会收到信号，并打开“奖励系统”。  
多巴胺是一种让人感觉开心的化学物质。吃太多糖会让多巴胺一直增加，人可能会想继续吃。  
虽然糖不会像药那样危险，但也应该适量吃。
</p>

<hr>

<h2>选择题（10题）</h2>

<div class="question">
1. “糖”属于哪一类成分？<br>
<input type="radio" name="q1" value="A"> A. 蛋白质  
<input type="radio" name="q1" value="B"> B. 碳水化合物  
<input type="radio" name="q1" value="C"> C. 维生素  
</div>

<div class="question">
2. 吃糖时，大脑会打开什么系统？<br>
<input type="radio" name="q2" value="A"> A. 消化系统  
<input type="radio" name="q2" value="B"> B. 奖励系统  
<input type="radio" name="q2" value="C"> C. 神经系统  
</div>

<div class="question">
3. 多巴胺让人感觉什么？<br>
<input type="radio" name="q3" value="A"> A. 紧张  
<input type="radio" name="q3" value="B"> B. 开心  
<input type="radio" name="q3" value="C"> C. 害怕  
</div>

<div class="question">
4. 为什么有人会一直想吃糖？<br>
<input type="radio" name="q4" value="A"> A. 因为糖让多巴胺一直增加  
<input type="radio" name="q4" value="B"> B. 因为糖有很多维生素  
<input type="radio" name="q4" value="C"> C. 因为糖会让人很紧张  
</div>

<div class="question">
5. 糖会让人感觉？<br>
<input type="radio" name="q5" value="A"> A. 很累  
<input type="radio" name="q5" value="B"> B. 愉快  
<input type="radio" name="q5" value="C"> C. 生气  
</div>

<div class="question">
6. 大脑为什么容易被“甜味”吸引？<br>
<input type="radio" name="q6" value="A"> A. 甜味让人感到舒服  
<input type="radio" name="q6" value="B"> B. 甜味可以让人睡觉  
<input type="radio" name="q6" value="C"> C. 甜味会让人生气  
</div>

<div class="question">
7. 多吃糖会怎样？<br>
<input type="radio" name="q7" value="A"> A. 多巴胺反应持续增加  
<input type="radio" name="q7" value="B"> B. 完全没有感觉  
<input type="radio" name="q7" value="C"> C. 肌肉马上变强  
</div>

<div class="question">
8. 糖和药物比，哪一句正确？<br>
<input type="radio" name="q8" value="A"> A. 糖和药物一样危险  
<input type="radio" name="q8" value="B"> B. 糖不会像药物那么强  
<input type="radio" name="q8" value="C"> C. 糖比药物更强  
</div>

<div class="question">
9. 文章认为糖应该？<br>
<input type="radio" name="q9" value="A"> A. 不应该吃  
<input type="radio" name="q9" value="B"> B. 适量吃  
<input type="radio" name="q9" value="C"> C. 越多越好  
</div>

<div class="question">
10. 多巴胺的作用是什么？<br>
<input type="radio" name="q10" value="A"> A. 让人害怕  
<input type="radio" name="q10" value="B"> B. 让人开心  
<input type="radio" name="q10" value="C"> C. 让人很累  
</div>

<button class="btn" onclick="checkQuiz()">检查答案</button>

<div id="resultBox"></div>

<br>

<!-- 按钮：跳转 Google Form -->
<button class="btn" onclick="window.open('https://forms.gle/88a8CwCdxiMrykMy8', '_blank')">
    👉 去填写 Google Form 评价
</button>

<script>
function checkQuiz() {
    const answers = ["B","B","B","A","B","A","A","B","B","B"];
    let score = 0;

    for (let i = 1; i <= 10; i++) {
        let selected = document.querySelector(`input[name="q${i}"]:checked`);
        if (selected && selected.value === answers[i-1]) {
            score++;
        }
    }

    let box = document.getElementById("resultBox");
    box.style.display = "block";
    box.innerHTML = `<h3>你的分数：${score} / 10</h3>`;
}
</script>

</body>
</html>
