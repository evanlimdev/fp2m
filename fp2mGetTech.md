# AI fp2m Service & Library

## 작성
* 제목 : 구현방법 구상, 기반 기술 조사/배치
* 작성일 : 2019-06-03
* 작성자 : 임휘준

### 구현방법 구상
  - 화면은 리액트와 텐서플로우로 기능구현한다.
  - 화면 UI/UX는 w3schools 의 w3.CSS web template 로 구현한다.
  - 작성중
    * 프론트앤드 텐서플로우 javascript에선 텐서플로우의 화면그리기 기능만을 구현한다.
    * 백앤드 텐서플로우 python에선 그리기를 제외한 기능을 구현한다.
  - 데이베이스는 몽고 db를 사용한다.
  - 백앤드는 파이썬 flask 를 사용한다.
  - flask에서 db연결을 pymongo로 구현한다. 
  - face 얼굴인식 기술은 tensorflow를 사용하며 react에서 구현가능한 기술로 제한한다.
  - nodejs 로 된 tensorflow js 는 react에 포팅하여 구현한다.

## 기술 배치
* 프론트엔드 : react js, tensorflow js, github [face], w3schools
* 백엔드 : flask, tensorflow python, pymongo
* 데이터베이스 : mongodb 

### 프론트엔드
* 구글검색어 : face object detection tensorflow js
* [face] Node.js + face-recognition.js : Simple and Robust Face Recognition using Deep Learning
  - https://medium.com/@muehler.v/node-js-face-recognition-js-simple-and-robust-face-recognition-using-deep-learning-ea5ba8e852
  - https://github.com/justadudewhohacks/opencv4nodejs

* [face] face-api.js for Nodejs - GitHub
  - https://github.com/justadudewhohacks/face-api.js

* [face] tracking.js － detect faces, eyes and mouths in a image
  - https://trackingjs.com/examples/face_hello_world.html
  - https://github.com/eduardolundgren/tracking.js

* [tensorflow js] Machine Learning with Javascript
  - https://www.udemy.com/machine-learning-with-javascript/

* [web template] w3schools - w3.CSS Templates
  - https://www.w3schools.com/w3css/w3css_templates.asp

### 백엔드
* 구글검색어 : python mongodb
* 플라스크(Flask) #3_ 플라스크에서 MongoDB 연결(연동)하기
  - https://doorbw.tistory.com/48 [Tigercow.Door]

