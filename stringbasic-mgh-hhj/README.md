## 문제 
문자열 s의 길이가 4 혹은 6이고, 숫자로만 구성돼있는지 확인해주는 함수, solution을 완성하세요. 예를 들어 s가 a234이면 False를 리턴하고 1234라면 True를 리턴하면 됩니다.

입출력 예   
s	return  
a234  	false  
1234  	true


## 이해
 a. 주어진 것은 무엇인가?  
 
    - 숫자로만 이루어진 문자열을 찾아야 한다.  
 b. 아는 것은 무엇인가?
 
    - 문자열 정규식 
    - 숫자 정규식
 c. 제한사항  
 
    - 문자열 길이는 1이상 8이하이다.
## 계획
    1. 문자열 길이 부터 검사한다.
        1.1 길이가 4 또는 6이 아니면 false를 리턴한다. 
    2. 정규식으로 문자열을 검사한다. 
    