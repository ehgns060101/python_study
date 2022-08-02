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
