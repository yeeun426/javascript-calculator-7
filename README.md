# javascript-calculator-precourse

## 구현할 기능 목록

- [x] 문자열을 입력 받는다
- [x] 문자열 앞 부분에 "//"가 있는지, 없는지 구별한다.
- [x] '//'이 있다면 '\n'사이에 있는 구분자를 커스텀 구분자로 지정한다.
- [x] 구분자를 기준으로 숫자 배열을 만든다.
  - [x] 커스텀 구분자가 없다면 "," 또는 ":" 구분자를 기준으로 숫자 배열을 만든다.
  - [x] 구분자 사이가 빈 문자열이라면 0을 넣는다.
- [x] 숫자 배열의 합을 출력한다.

## 예외 처리

- [ ] 문자열이 "//"로 시작하는데 "\n"이 없는 경우 예외처리한다.
  - [ERROR] 커스텀 구분자가 지정되지 않았습니다.
- [ ] 기본 구분자 외의 문자가 문자열에 들어가 있는 경우 예외처리한다.
  - [ERROR] 기본 구분자가 사용되지 않았습니다.
- [ ] 커스텀 구분자 외의 문자가 문자열에 들어가 있는 경우 예외처리한다.
  - [ERROR] 커스텀 구분자의 범위를 벗어났습니다.
- [ ] 입력값이 양수가 아닌 경우 예외처리한다.
- [ ] 입력값에 공백이 들어간 경우 예외처리한다.
- [ ] 문자열이 "//" 또는 숫자로 시작하지 않는 경우 예외처리한다.
  - [ERROR] 구분자와 양수로 구성된 문자열을 입력해주세요.
