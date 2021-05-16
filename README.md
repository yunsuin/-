# (윤수인)파이썬 기초 공부하기 (21.05.13)
## 05.13 : 파이썬 입력, 출력 (python01.ipynb)
+ 입력 : input() => 정수(int), 실수(float)를 입력할 경우 형변환
+ 출력 : print() => f-string
+ if문장 
  + if ... : 명령문 elif ... : 명령문 else : 
+ for문 : 반복문 => range()
+ while문


## 05.14 : 컬렉션 자료형 1 (python02.ipynb)
+ 컬렉션 자료형 : 순서가 있는지, 없는지
+ 문자열 (str) : 분자들의 모임
+ 리스트 (list) : 요소에는 숫자열
  + 요소에는 숫자, 실수, 문자열, 리스트 ... : 여러가지 자료형을 가질 수 있다
+ 각 요소에 접근하는 방법 : 인덱싱 => 요소의 위치 0부터 시작 x[0]
+ 일부 요소를 추출하는 방법 : 슬라이싱 => x[0:3] 0,1,2
+전체 요소 접근 방법 : for .. in 컬렉션 명:
 
 
## 05.15 : 컬렉션 자료형 2 (python02.ipynb)
+ 리스트
  + 문자열(str) => 숫자열
+ 리스트 변경
  + 추가 : 리스트명.append(추가요소) : 마지막에 추가 / 리스트명.insert(인덱스, 추가요소) : 해당 인덱스에 요소 추가
  + 삭제 : 리스트명.pop() : 마지막 요소 삭제
  + 수정 : 리스트명[인덱스]=변경값
 + 리스트 메소드
   +  리스트명.index(요소값) : 해당 요솟값의 위치 반환 / 리스트명.count(요소값) : 리스트 요소 개수 구하기 / 리스트명.sort() : 오름차순 리스트 정렬 / 
리스트명.reverse() : 요소를 역순으로 뒤집어 줌 
+ 리스트 내장함수 : sum() , min() max() len()
+ 튜플(tuple) - 인덱싱과 슬라이싱은 리스트와 동일 but 수정이 불가능
+ 딕셔너리(비시퀀스) - 키로 값을 구분하며 중괄호로 작성, 순서 x, 키는 변경할 수 없으며 값은 변경 가능
