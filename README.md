# python_study

## 2022 - 08 -02

- 문자열파트
  - 문자열이름 "word" 혹은 'word'
  - 순서대로 ex) 'Python'/0,1,2,3,4,5/-6,-5,-4,-3,-2,-1 
- 글자를 새롭게 바꿀때 
  - word = 'Python'
  - word2 = 'J' + word[1:]
  - print(word2)
  - 결과:'Jython'
- 문자열의 길이를 계산할때
  - s = 'smiles'
  - len(s)
  - 결과:6
- 임의의 문자열을 입력받아 거꾸로 출력하는 프로그램
  - inStr = input(" ") : 문자열을 입력받음
  - count = len(inStr) : 문자열 길이 계산
- 문자열 구성 파악 함수
  - '123'.isdigit() : 문자열이 숫자인가?
  - 'abcABC'.isalpha() : 문자열이 문자인가?
  - 'Ab122'.isalnum() : 문자열이 문자+숫자 혼합인가?
  - 'AB'.isupper() : 문자열이 대문자인가?
  - 'ab'.islower() : 문자열이 소문자인가?
  - ' '.isspace() : 문자열이 공백인가?
- 문자열 찾기 함수&문자열 공백 삭제 및 변경함수
  - ex) str = 'Python programming is easy!'
  - str.count('i') : 문자열에서 'i' 개수
  - 결과:2
  - ex) str = ' hello '
  - str.strip() : 양쪽에서 공백 제거
  - 결과:'hello'
  - str : 문자열은 변하지 않음
  - 결과:' hello '
  - str.rstrip() : 오른쪽 공백 제거
  - 결과:' hello'
  - str.lstrip() : 왼쪽 공백 제거
  - 결과:'hello '

## 2022 - 08 -02

- 리스트
- 삭제
  - ex) movie_rank = ['닥터 스트레인지', '슈퍼맨', '스플릿', '배트맨']
  - del movie_rank[2] : '스플릿' 제거
  - del movie_rank[2] : '배트맨' 제거
  - print(movie_rank) : movie_rank 
- 두개의 리스트를 포함하는 하나의 리스트
  - lang1 = ["C", "C++", "JAVA"] : 첫번째 리스트
  - lang2 = ["Python", "Go", "C#"] : 두번째 리스트
  - langs = lang1 + lang2 : 두개의 리스트를 포함하는 하나의 리스트 생성
  - print(langs)
- 리스트 합계산
   ```python
    nums = [1, 2, 3, 4, 5]
    print(sum(nums))
    ```
- 내장함수
   - 평균
   ```python
    nums = [1, 2, 3, 4, 5]
    average = sum(nums) / len(nums)
    print(average)
   ```
- 튜플

- 튜플 언팩킹
  - temp = ('apple', 'banana', 'cake')
  - a, b, c = temp
  - print(a, b, c)
- range 함수
  
- 1~99까지 짝수만 저장된 튜플생성
  - data = tuple(range(2, 100, 2))
  print( data )
- 클래스
  - class 클래스이름 : # class 키워드로 정의
  - 클래스변수
  - 메소드(들)
- 생성자
  - 인스턴스를 생성할때 무조건 호출되는 메소드
  - 형식은 __init__
- 캡슐화
  - 데이터와 알고리즘을 하나로 묶어 공용 인터페이스만 제공하며 구현의 세부 사항을 감추는것을 의미
  - 접근자(getter)와 설정자(setter)를 구현하는것이 좋음
- 상속
  - class subClass이름(superClass이름):
