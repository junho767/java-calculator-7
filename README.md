# java-calculator-precourse

## 기능 요구 사항

- [ ] 빈 문자열 검사 → 문자열이 비었거나 null 일 때 0으로 반환
    
- [ ] 쉼표 ( , )과 콜론 ( ; )과 같은 기본 구분자로 분리한 각 숫자들의 합을 반환.  →  “ “ ⇒ 0 , “1:3:5” ⇒ 9 , “2,3,4” ⇒ 9, “4:1,1” ⇒ 6

- [ ] 커스텀 구분자 구현하기 → 문자열이 “//” 로 시작하는 지 우선적으로 검사 -> str.
   
- [ ] 잘못된 값 입력 시 `IllegalArgumentException`을 발생
