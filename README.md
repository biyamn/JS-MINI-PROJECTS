
#### 💛<span style='color:red'>바닐라자바스크립트 구현 능력을 키우기 위해 특정한 과제를 수행합니다.</span>💛
<br>

### 1. 움직이는 글자
#### 1-1. 움직이는 글자 과제 설명
입력한 글자를 일정한 규칙에 따라 움직이는 것처럼 보이도록 구현하는 과제이다. (by 시니하님)

<br>

#### 1-2. 움직이는 글자  gif 내용
![최종](https://user-images.githubusercontent.com/101965666/197389533-8c2fe699-ea78-4ab2-a3c9-d29698376ab3.gif)

<br>

#### 1-3. 폴더 설명
- '1-1. 정답' 폴더: 정답 코드와 코드를 해석하며 적은 저의 주석이 담긴 폴더입니다.

- '1-2. hard training` 폴더: 정답 코드를 보지 않고 혼자 만들어 본 코드가 담긴 폴더입니다.

<br>

#### 1-4. 내가 구현한 모습
일주일 동안 풀다가 결국 혼자 구현하지못하여 정답 코드에 대한 설명을 듣고 구현해보았다. 

![녹화_2022_10_23_21_27_26_275](https://user-images.githubusercontent.com/101965666/197392199-0d4f923e-ecdb-4838-b314-d055d3730473.gif)

<br>

#### 1-4. 구현 과정을 담은 블로그 포스팅 
<a href='https://velog.io/@hamham/JS-%EC%9B%80%EC%A7%81%EC%9D%B4%EB%8A%94-%EA%B8%80%EC%9E%90-%EA%B5%AC%ED%98%84%ED%95%98%EA%B8%B0'>[JS] 움직이는 글자 구현하기</a>

<br>

---

### 2. 랜덤값
#### 2-1. 랜덤값 과제 설명
- 세 개의 박스 중 하나를 클릭하면 세 박스가 100, 200, 300점 중 하나의 값을 랜덤으로 가진다.
- 박스를 누를 때마다 눌린 박스의 값이 화면에 표시된다. 
- 박스가 클릭될수록 매번 박스의 점수가 누적되어 화면에 보인다. 
- 박스가 클릭될 때마다 랜덤으로 색이 바뀐다.
- 글자 색은 배경 색에 따라 달라진다. (배경이 어두우면 밝게, 배경이 밝으면 어둡게 설정됨)

<br>

#### 2-2. 기능 목록
```
## html로 틀 짜기
- 세 개의 버튼 만들기
- 버튼이 눌릴 때 해당 버튼의 점수를 보여줄 공간 만들기
- 버튼을 누를 때마다 생성되는 점수들의 합을 보여줄 공간 만들기

## 숫자 섞는 기능 만들기
- shuffleScores 함수 만들기
- 100, 200, 300을 섞어서 분배하기

## 색 섞는 기능 만들기
- shuffleColors 함수 만들기
- red, green, blue로 각각 랜덤값을 만들어서 rgb로 색 만들기

## 글자 색 다크모드 기능 만들기
- shuffleColors 함수 안에 만들기
- rgb의 평균값이 128보다 크면 글자는 검정색으로 설정하기
- rgb의 평균값이 128보다 작으면 글자는 흰색으로 설정하기

## 클릭한 버튼의 점수 볼 수 있게 만들기
- textContent로 id가 showScore인 element 변경하기
```

<br>

#### 2-3. 내가 구현한 모습
![chrome_gwrRdtYd25](https://user-images.githubusercontent.com/101965666/203450800-9e0d4227-bf18-41e9-a48f-d8af61035e1e.gif)

<br>

#### 2-4. 구현 과정을 담은 블로그 포스팅 
<a href='https://velog.io/@hamham/%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8-%EB%9E%9C%EB%8D%A4%EC%88%AB%EC%9E%90%EC%99%80-%EB%9E%9C%EB%8D%A4%EC%83%89-%EA%B5%AC%ED%98%84%ED%95%98%EA%B8%B0'>[자바스크립트] 랜덤값 구현하기</a>

<br>

---

### 3. 흔들리는 버튼
#### 3-1. 흔들리는 버튼 과제 설명
흔들리는 버튼을 클론 코딩하는 과제이다. 버튼의 디자인이 모두 주어진 상태에서 
`(1) 스크롤이 버튼이 있는 곳까지 내려가면` `(2) 버튼을 흔든다` 이 두 가지 조건만 만족하게 하면 된다.

![웹사이트 화면](https://user-images.githubusercontent.com/101965666/209787112-94d6124e-fa64-4148-b24a-690f8f1ec2e0.gif)

<br>

#### 3-2. 내가 구현한 모습
![css적용](https://user-images.githubusercontent.com/101965666/210958214-e05f3550-00e4-4e45-ba6a-0ee22959c53a.PNG)

<br>

#### 3-3. 구현 과정을 담은 블로그 포스팅
<a href='https://velog.io/@hamham/CSS-%EC%8A%A4%ED%81%AC%EB%A1%A4%EC%9D%84-%EB%82%B4%EB%A6%AC%EB%A9%B4-%ED%9D%94%EB%93%A4%EB%A6%AC%EB%8A%94-%EB%B2%84%ED%8A%BC-%EB%A7%8C%EB%93%A4%EA%B8%B0'>[CSS, JavaScript] 스크롤을 내리면 흔들리는 버튼 만들기</a>

<br>

---

### 4. 루퍼
#### 4-1. 루퍼 과제 설명
네 가지의 인자(initial, condition, task, fin)를 받아서 의도한대로 결과를 출력하는 함수 loop의 내용을 완성한다.


<br>

#### 4-2. 내가 구현한 모습
![캡처](https://user-images.githubusercontent.com/101965666/210960361-b9f00e6e-a68f-4cd7-8ced-c8d6fd785c8d.PNG)

<br>

#### 4-3. 구현 과정을 담은 블로그 포스팅
<a href='https://velog.io/@hamham/%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8-%ED%95%A8%EC%88%98-%EB%A7%8C%EB%93%A4%EA%B8%B0'>[자바스크립트] 루프 함수 만들기</a>

<br>

---

### 5. 이진 탐색
#### 5-1. 이진 탐색 설명
자바스크립트로 이진 탐색을 구현한다. binarySearch 함수를 구현하는데, binarySearch에 인수로 배열과 찾고자 하는 값을 넣으면 찾고자 하는 값이 위치한 인덱스를 반환한다.


<br>

#### 5-2. 내가 구현한 모습
![캡처](https://user-images.githubusercontent.com/101965666/212708594-28d4a603-38ac-461a-a1c9-5fec7a4f18c5.PNG)

<br>

#### 5-3. 구현 과정을 담은 블로그 포스팅
<a href='https://velog.io/@hamham/%EC%9E%90%EB%B0%94%EC%8A%A4%ED%81%AC%EB%A6%BD%ED%8A%B8-%EC%9D%B4%EC%A7%84-%ED%83%90%EC%83%89Binary-Search-%EA%B5%AC%ED%98%84%ED%95%98%EA%B8%B0'>[자바스크립트] 이진 탐색(Binary Search) 구현하기</a>