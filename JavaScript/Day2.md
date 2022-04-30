# Variable
let   : 변수

    ex) let num = 5;  
    
const : 상수

    ex) let BoilingPointC = 100;

# Naming
CamelCase을 사용

    ex) let currentYear = 2022;  

# Strings
변수에 문자열을 할당

    ex) let name = "Kim";  

문자열은 인덱싱되어있음

    ex) let animal = "elepant"; animal[3] = 4 

# Methods
문자열에 적용가능한 특정 동작   

    ex)  str.toUpperCase() : str의 문자열을 전부 대문자로 바꿈  
         str.toLowerCase() : str의 문자열을 전부 소문자로 바꿈  
         str.trim()        : str의 문자열 앞뒤의 공백을 전부 삭제함  

메소드는 중첩하여 적용가능  
  
    ex) str.trim().toUpperCase() : str의 문자열 앞뒤의 공백을 전부 삭제후 문자열을 대문자로 바꿈  

# Boolean Logic
기본적으로 다른 비교연산자들과 같으나 이중 등호와 삼중 등호의 개념을 잘알아야함
    
    ==  : 비교하는 두 값이 타입이 같도록 전환하고 비교함
    ex) 1 == 1;  //true 'b'=='c'; //false 7 == '7' //true
        0 == ''; //true  0 == false; //true null == undefined; //true
    === : 비교하는 두 값의 타입을 구분하고 값과 타입 모두를 비교함
    ex) 1 === '1'; //false 0 === false; //false 0 === ''; //false 

