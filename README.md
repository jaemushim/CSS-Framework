# My-CSS-Framework

## Description
utility first CSS Framework 이며 sass의 Mixin을 활용하여 클래스 생성기(engine)를 만든 커스터마이징이 손쉬운 CSS 반응형 프레임워크 입니다.  
classname convention 은 tailwindcss 와 유사합니다.

## Usage
```
npm run sass
```


## Advantage
1. tailwindcss의 컴파일된 css가 17만줄정도 되는데 이것 대비 1만줄로 내가 꼭 필요한부분만을 설정하여 사용할수있다. 가볍고 알차다.
2. 원하는 클래스명칭으로 변경할수있고 더 구체적으로 수치값을 줄수있고 값의 단위도 변경이 가능하다.(em->px)
3. 모든 커스터마이징 손쉽게 가능하다.

## Responsive Design
모든 utility class 는 반응형 브레이크포인트에 적용이 가능하며 복잡한 반응형 인터페이스를 HTML 문서에서 안에서 손쉽게 작성할수있도록 합니다.
모바일 레이아웃을 우선적으로 고려하여 반응형 인터페이스를 구축할수있게 합니다.  

![화면 캡처 2021-07-25 122109](https://user-images.githubusercontent.com/65330249/126886604-e1e8929c-a4e2-41b0-ac03-e970311383e2.png)

## Example
```html
<!-- 모바일에서는 text center and 스크린사이즈 640px 이상은 text left(default) -->
<div class="text-center sm:text-left"></div>
```  
#### Why?   
우선적으로 모바일 레이아웃을 고려하고 sm 스크린, md 스크린, lg 스크린 class를 이따라 추가할수 한다. 
