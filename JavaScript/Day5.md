# Arrays Methods
push : 배열 끝에 항목을 삽입함
pop  : 배열 끝 항목을 삭제함
shift : 배열 시작점 항목을 삭제함
unshift : 배열 시작점에 항목을 삽입함
concat : 두 배열을 합쳐 새 배열을 만듬
 
    ex ) const array1 = [1,2]; const array2 = [3,4]
         const array3 = array1.concat(array2); // array3 = [1,2,3,4]

includes : 배열에 특정 값이 있는지 찾고 true, false값을 출력함
indexOf : 배열에 특정 값을 찾고 그 값의 인덱스값을 출력함 
          (존재하지 않으면 -1 출력)
reverse : 배열 항목의 순서를 뒤집음
slice   : 배열의 일부분을 출력함

    ex) let colors = ['red','blue','green','orange','indigo','violet']
        color.slice(1) = ['blue','green','orange','indigo']
        color.slice(2,4) = ['green','orange','indigo']

splice  : 배열의 기존 요소를 삭제, 교체하거나 배열에 새 요소를 추가함

    ex ) const months = ['Jan', 'March', 'April', 'June']
         months.splice(1, 0, 'Feb') 
         // 첫째 인수는 인덱스, 둘째 인수는 대체할 요소수, 
            셋째 인수는 삽입할 요소
         console.log(months) // ['Jan', 'Feb', 'March', 'April', 'June']

sort    : 배열 요소의 크기를 비교해서 정렬함

