# Gachon CS50 Web Programming Takehome Test

## 본 문서의 위상
본 문서는 2016년 가을학기 가천대학교 웹 프로그래밍 과목의 기말고사 Take Home에 대해서 기술하는 문서이다 본 문서의 작성 목적은 Take Home의 가이드를 위한 것으로 Take Home에서 제출해야 할 최종 산출물의 상세 요구사항을 정리한다

## Service Objective
Takehome Test의 최종 산출물은 시간표 신청 시스템이다. 본 시스템은 사용자가 로그인 한후 시간표 리스트에서 자신이 원하는 과목을 선택하여 시간표에 채워넣을 수 있게하는 것을 목적으로 한다
 
## 요구사항 리스트
- 본 서비스는 사용자의 로그인, 시간표 리스트 보기, 수강과목 선택, 구성된 시간표 보기 등으로 기능이 구성된다
- 본 서비스의 메뉴는 About, 시간표 선택하기, 시간표 보기, 로그인(로그인시 로그아웃) 으로 구성된다.
- About 페이지는 기본적인 서비스에 대한 설명이 담긴 페이지이다
- 시간표 선택 페이지는 교과목 리스트가 Table 형태로 존재하며, 사용자가 선택하면 사용자의 시간표로 이동된다
    - 단 이때 해당 교과목에 해당하는 시간이 이미 존재한다면, 사용자에 시간표에 추가할 수 없다
    - 사용자는 18학점을 추가할 수 없다
- 시간표에는 현재까지 사용자가 선택한 교과목을 Time Table형태로 보여준다.
- 로그인과 로그아웃 그리고 회원가입의 기능이 제공된다.
- 시간표 데이터는 CSV 형태로 제공되며, Admin기능을 통해 입력할 수 있거나 데이터를 한번에 업로드하는 프로그램이 작성되어야 한다
- 모든 디자인은 Bootstrap을 기본으로 한다
- Jquery를 사용한다
- 사용자 데이터는 Email, First Name, Last Name, Password 로 구성한다.
- 교과목 데이터는 교과목명, 교과코드, 학점, 개설시간으로 구성한다.
- 개설 시간은 월요일부터 금요일까지 1교시 부터 7교시 중 하나로 선택가능하며 총 35개의 선택지가 존재한다.
- 데이터의 추가 및 삭제는 개발자가 임의로 할 수 있다.

## 평가 요소 (총 50점)
- About 페이지등 단순 HTML과 CSS를 사용하여 페이지를 꾸민다 (5점)
- Bootstrap을 사용하여 각 메뉴를 구성한다 (5점)
- 각 메뉴별로 기본이 되는 페이지를 구성한다 (10점)
- 로그인과 로그아웃, 회원 가입 기능을 구현한다 (5점)
- 교과목 리스트를 테이블로 표현하여 불러온다 (5점)
- 교과목을 선택하여 개인시간표에 추가한다 (5점)
- 중복 시간표를 방지하고 18학점 이상 교과목을 추가할 수 없도록 한다(5점)
- 시간표 결과를 Time Table로 표현한다 (5점)
- 시간표 데이터를 Admin을 통해 입력할 수 있다 (5점)
- 교과목 리스트에 교과목 선택시 Ajax 기능을 사용하여 시간표에 추가한다 (10점)

## 유의사항
- 결과물은 반드시 GitHub을 통해서만 제출하여야한다
- 각 평가요소별로 완성되었을 경우, 손쉽게 확인할 수 있도록 Commit을 실행하고 Commit 메세지에 해당 평가 요소를 기입한다
    - 이를 하지 않을 경우 10%의 감점을 적용한다 

## 참고사항
- [예제 Subject Data](data/subject_list.csv)
- [예시 화면](https://goo.gl/t8H7f3)


