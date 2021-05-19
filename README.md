# baek5557   
![image](https://user-images.githubusercontent.com/48464681/118746416-33946a80-b893-11eb-9a04-cf346eee8498.png)
   
다이나믹 프로그래밍 연습   
d[i][j] -> i번째 까지 더해서 j를 만들 수 있는 경우의 수 저장
d[i][j] = d[i-1][j + i번째 수] + d[i-1][j + i번째 수] 를 이용해서 풀기
