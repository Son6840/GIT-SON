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

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/424ebb97-c917-4025-8bdb-7eba4a618e1c/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/424ebb97-c917-4025-8bdb-7eba4a618e1c/Untitled.png)

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/4af2e073-9271-46af-9165-1f3c361e849a/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/4af2e073-9271-46af-9165-1f3c361e849a/Untitled.png)

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


