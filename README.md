# Mathroom
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>간단한 수학 문제</title>
</head>
<body>
    <h1>1+1은 얼마입니까?</h1>
    <p>정답을 입력해주세요:</p>
    <input type="text" id="answer">
    <button onclick="checkAnswer()">제출</button>
    <p id="result"></p>

    <script>
        function checkAnswer() {
            var answer = document.getElementById("answer").value;
            if (answer === "2") {
                document.getElementById("result").innerText = "정답입니다!";
            } else {
                document.getElementById("result").innerText = "오답입니다. 정답은 2입니다.";
            }
        }
    </script>
</body>
</html>
