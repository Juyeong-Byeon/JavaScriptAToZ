#ES6의 배열

## 비구조화 할당

```JavaScript
let [a,b]=[1,2]//a=1,b=1
let [c,d];
[c,d]=[1*2,2*2];//c=2,d=4
//우변보다 좌변이 많거나 그 반대일 경우 많은쪽이 무시된다. 

let [x,t,p,...f]=[1,2,3,1,2,3];
//f 에 앞의 1 2 3 이 제외된 배열이 할당된다.
```
만약 함수가 array를 return 할 때 비구조화 할당을 이용하면 깔끔한 처리가 가능하다. 

```javaScript
let foo=(x)=>{
    return[x*1,x*2,x*3,x*4]
}

let [a,b,c,d]=foo(10);
```
## 객체 비구조화 할당 obj Destructuring

객체 또한 비구조화 할당을 사용할 수 있다


## spread 연산 

## ArrayBuffer 와 형식화 배열

## Set

