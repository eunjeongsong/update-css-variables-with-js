# JS 를 이용한 CSS 값 업데이트 하기

- Vanilla Script + CSS

## CSS

### CSS 에 변수 할당

- root 에 spacing 변수를 할당하고, JS 의 이벤트 리스너를 통해 현재 이벤트가 발생한 this 의 name 과 data sizing 을 가져와 같은 변수를 쓰는 CSS 의 속성값을 모두 변경할 수 있도록 함.

```css
:root {
  --spacing: 100px;
}

img {
  padding: var(--spacing);
}
```
