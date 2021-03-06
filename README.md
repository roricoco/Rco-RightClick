# Rco-RightClick

RightClick.js는 커스텀 된 우클릭 메뉴를 제공합니다.\
여러가지 상호작용 이벤트를 감지하여 상황에 맞는 추가 우클릭 메뉴를 보여줍니다.

### Requirements
 * jQuery (↑ 1.12.4, recommends 3.6.0)
 
## How To Use
### Script 로드
```html
<script src="https://cdn.rococpy.com/js/RightClick.js"></script>
```
> 또는 다운로드한 레포지토리의 `RightClick.js`를 이동 및 로드.

### 사전 설정

> * 이제 없습니다. 기존에 있던 URL바로가기는 선택적 옵션으로 변경되었습니다.

### URL 바로가기 설정

> * URL 바로가기를 사용시 HTML `<script>`를 통해 RightClick.js가 로드 되기 전에 선언을 해주시면 됩니다.
```js
const Rco__urls = [
  ["메인페이지", "/"],
  ["표시할 이름", "이동시킬 URL"]
]
```

### 다크 모드
> * HTML `<style>` 또는 CSS파일을 통해 하단의 CSS코드가 포함되어있을시 적용됩니다.
```css
.Rco__right{
  background: #333!important;
  color: white!important;
}

.Rco__right li:before{
  background: gray!important;
}
```
 
## Preview
* Rococpy의 패밀리 사이트 대부분 해당 라이브러리가 적용되어 있습니다. https://rococpy.com

### 기본 우클릭 (URL 바로가기 미포함)
![rjssample1-1](https://user-images.githubusercontent.com/50366343/128288154-0d25ac97-dd37-43e3-8129-1d63c862270c.png)

### 기본 우클릭 (URL 바로가기 포함)
![rjssample](https://user-images.githubusercontent.com/50366343/127797290-50923186-09f8-4390-b419-a82c23d00fc2.png)

### 이미지 우클릭
![rjssample1](https://user-images.githubusercontent.com/50366343/127797426-396c4f36-0b82-406e-b18b-648491e8a5d8.png)

### A태그 우클릭
![rjssample2](https://user-images.githubusercontent.com/50366343/127797533-cdbafc7f-d079-4dce-a793-ed24113f7b2e.png)

### Dark Mode
![rjssample3](https://user-images.githubusercontent.com/50366343/127798117-e0ed9e85-96f9-4d44-a7b8-b8e3761d1e92.png)

## License
Apache License 2.0이 적용됩니다.
