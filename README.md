# 손상배 [201840119]
## 2021-04-06
>오늘 배운내용 요약<br>
>요약 : 
## (역) for 반복문

```jsx
역 for 반복문

let array = [1, 2, 3, 4, 5, 6];
//배열 생성

for (let i = array.length -1; i>=0; i--){
	console.log(array[i]);
}
```

 tab키 위에있는 ` = 문자와 변수를 같이 넣고싶을때 ex)     ``console.log(${i}번째 요소:)``

    

## 이중 for문

```jsx
let output = "";

for (let i = 0; i<5;i++){
  for (let j =0;j<i+1; j++){
    output += "*";
  }
 output += "\n"; 
}
console.log(output);
```



### 삼각형 찍기

```jsx
let op="";

for(i=0;i<10;i++){
  for(j=0;j<10-i;j++){
    op+=" ";
}
for(let j=0;j< i+1;j++){
  op += "*";
}
for(let j=1; j<i+1;j++){
  op += "*";
}
op+="\n";
}

console.log(op);
```


---

## While 문

```jsx
let array =[1,31,273,57,8,11];
let op;
let i =0;

while(true){
  if (array[i]%2 ==0){
    op = array[i];
    break;
  }
  i++ // i=i+1;
}
  console.log(`처음 발견한 짝수는 ${op}입니다`);
```

***출력 :  처음 발견한 짝수는 8입니다***

---

**push**는 배열의 끝에 원하는 값을 추가해주는 함수  **foo.push(1,2,3);**

**pop**은 배열의 마지막 주소에 있는 값을 제거해주는 함수. **foo.pop();**

**shift**는 배열의 첫번째 주소에 있는 값을 제거한 후에 반환해주는 함수**.foo.shift():**

**push**와 **pop**을 이용하면 **stack**으로 이용할 수 있다.

**push**와 **shift**를 이용하면 **quene**로 이용할 수 있다.


# 손상배 [201840119]
## 2021-03-30
>오늘 배운내용 요약<br>
>요약 : ## **if 문**

```jsx
let date = new Date();
let hours = date.getHours();

if (hours<11){
	console.log("아침 먹을 시간입니다");
} else if (hours<15) {
		console.log("점심 먹을 시간입니다");
}else {
	console.log("저녁 먹을 시간입니다");
}
```

## Switch 조건문

```jsx
let input = 32;

switch(input%2){
    case 0:
        console.log("짝수");
        break;

    case 1:
        console.log("홀수");
        break;
    default:
        console.log("정수가 아닙니다");
        break;
}
```

```jsx
let date = new Date();
console.log(date.getMonth());
switch (date.getMonth()+1){ 
    case 12:
    case 1 :
    case 2 :
        console.log("겨울");
        break;
    case 3 :
    case 4 :
    case 5 :
        console.log("봄");
        break;
    case 6:
    case 7 :
    case 8 :
        console.log("여름");
        break;    
    case 9 :
    case 10 :
    case 11 :
        console.log("가을");
        break;
    default : console.log("정수x");
							break; 

}
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <script>
        let input = prompt("입력해주세요");
        console.log(input);

    </script>
</head>
<body>
    
</body>
</html>
```

```jsx
let date = new Date();
let hours = date.getHours(); 

if (hours<11){
	console.log("아침 먹을 시간입니다");
} else if (hours<15) {
		console.log("점심 먹을 시간입니다");
}else {
	console.log("저녁 먹을 시간입니다");
}
```

## 배열

## while 반복문

```jsx
let i = 0;
let array =[52,273,32,65,103];
//반복을 수행합니다
while(i < array.length){
//출력
console.log(i + "번째 출력" + array[i]);
//탈출 변수 
i++;
}
```

## for 반복문

```jsx
let output = 0;

for (let i =0;i<= 100; i++){
	output += i;
}
console.log(output);

// 1부터 100까지 더하기
```

## 2021-03-23
>오늘 배운내용 요약<br>
>요약 : 논리 연산자 

## 2021-03-16
>오늘 배운 내용 요약<br>
>요약 : nord.js설치함


