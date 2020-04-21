# 그렇다 삽질중이다.







Uncaught TypeError: $(...). is not a function ㅎ ㅏ..


https://dev.eyegood.co.kr/entry/%EB%94%94%EB%B2%84%EA%B9%85-Uncaught-TypeError-is-not-a-function-%ED%95%B4%EA%B2%B0%EB%B2%95

Uncaught TypeError: $(...). is not a function 에러가 발생하는 이유는 크게 3가지 입니다.

1. <head>태그안에 jquery script선언이 다른 script선언보다 위에 있지 않은경우

2. jquery가 중복되어 설치된 경우 (cdn, file 등)

3. jquery가 아예 깔려 있지 않은 경우

기절한다사람.. 
