제일 먼저 나오는 페이지는 아래와 같다.    

![image](https://user-images.githubusercontent.com/61738600/127736718-84373d95-b482-4915-b25c-07cd85864f33.png)  
![image](https://user-images.githubusercontent.com/61738600/127736773-8d31ea7a-8d6b-46bb-a943-291ccad9daed.png)  
위와 같이 화면 구성은 **Word Test**, **개수**, **단어**, **뜻**으로 이루어져 있다.  
**개수**는 현재 몇 문제를 풀었는지 카운팅되고  
**단어**는 영어단어를 출력해준다.  
**뜻**은 영어단어에 해당하는 뜻을 타이핑하면 된다.  
  
뜻을 적고나서 확인하기 버튼을 누르면 바로 답이 맞았는지 틀렸는지를 알려준다.  
**틀렸을때:**  
![image](https://user-images.githubusercontent.com/61738600/127736846-5a5b0e89-b943-4ed1-bc44-166cdf02eb30.png)  
**맞았을때:**  
![image](https://user-images.githubusercontent.com/61738600/127736864-880a9da3-a59a-4cad-a2db-d1e787e4ae90.png)  
**공백도 모르는걸로 간주한다:**  
![image](https://user-images.githubusercontent.com/61738600/127736885-715a7673-d3ba-44c8-b20f-5cb103c78ae6.png)  
  
영단어 하나에 뜻이 여러개인 경우가 있는데, korean1과 korean2배열로 나누어 or로 둘 중 하나만 맞으면 맞는 답으로 처리했다.
문제를 틀렸을 경우, 결과화면에서 다시 보여줄 수 있도록 따로 배열에 저장했다.  
  
문제를 모두 풀면 아래와 같이 총 문제수, 틀린 문제 수, 그리고 틀린 영단어들과 뜻을 나열한다.  
![image](https://user-images.githubusercontent.com/61738600/127736957-105cf7a4-b076-4c2e-88f3-099783a92de8.png)   
  
💭논외)나중에는 html에 하드코딩하는게 힘들어서 day24처럼 영단어 데이터와 프로그램을 따로 만들었는데 응용프로그램이라 그런지 메일로 전달이 안되서 다시 html로 돌아왔다. 뼈대는 놔두고 데이터만 계속 바꿔서 지금보니 존재하는 소스가 day23밖에 없었다..  
💭논외2)당시에는 앱을 만들 줄 몰라서 웹으로 만들어서 줬는데 학생의 핸드폰에서는 페이지가 열려서 핸드폰으로 시험을 봤다고 했다. 난 안되던데 기종차이인가..  
💭논외3)그래도 학생이 잘 사용하고 재밌어해서 뿌듯했다.  





