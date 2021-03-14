### 1. 변수 x가 10보다 크고 20보다 작을 때 변수 x를 출력하는 조건식을 완성하라

```
var x = 15;

if (10<x<20){
   console.log(x);
}
```



### 2. for문을 사용하여 0부터 10미만의 정수 중에서 짝수만을 작은 수부터 출력하시오.

```
for (var i =0; i<10; i=i+2) {

	console.log(i);

}
```



### 3. for문을 사용하여 0부터 10미만의 정수 중에서 짝수만을 작은 수부터 문자열로 출력하시오.

```
for (var i =0; i<10; i=i+2) {
   var x = i + '';
   console.log(typeof x, x);
};
```



```
for (var i =0; i<10; i=i+2) {

​    i = i + '';

​    console.log(typeof i, i);

};  타입은 문자타입이 맞는데 왜 02468이 안되고. 02까지만 나오는지?
```



## 4. for문을 사용하여 0부터 10미만의 정수 중에서 홀수만을 큰수부터 출력하시오.

```
for (var i = 9; i > 0; i=i-2){
   console.log(i);
}
```



## 5. while문을 사용하여 0 부터 10 미만의 정수 중에서 짝수만을 작은 수부터 출력하시오.

```
var x = 0

while (x<10) {
	console.log(x);
	x = x + 2;
}
```



## 6. while문을 사용하여 0 부터 10 미만의 정수 중에서 홀수만을 큰수부터 출력하시오.

```
var x = 9

while (x>0) {
	console.log(x);
	x = x - 2;
	if (x === 0) break;
}
```



## 7. for 문을 사용하여 0부터 10미만의 정수의 합을 출력하시오.

```
var x = 0;

for (i = 0; i<10; i = i + 1){
	x = i + x;
}
console.log(x);
```



## 8. 1부터 20 미만의 정수 중에서 2 또는 3의 배수가 아닌 수의 총합을 구하시오.

```
var x = 0;



for (var i = 1; i<20; i = i + 1){

​    if(i%2===0 || i%3===0){

​        continue;

​    } else {

​        x = x + i;

​    }

}

console.log(x);
```



## 9. 1부터 20 미만의 정수 중에서 2 또는 3의 배수인 수의 총합을 구하시오.

```
var x = 0;



for (var i = 1; i<20; i = i + 1){

​    if(i%2===0 || i%3===0){

​        x = x + i;

​    }

}

console.log(x);
```



## 10. 두 개의 주사위를 던졌을 때, 눈의 합이 6이 되는 모든 경우의 수를 출력하시오.



```
for(var x = 1; x <7; x=x+1){

​    for(var i = 6; i >0; i=i-1 ){

​        if(i+x===6){

​        console.log([x ,i]);

​    }

}

}
```

