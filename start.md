#  시작하기

## 패키지 설치

패키지 설치 어쩌구

## 그리드 생성하기

### HTML

컨테이너 엘리먼트를 생성한다.
```javascript
<c-dkbmc-grid object-name="오브젝트명"
        column-data={컬럼데이터}
        key-field="Id"
        use-pagination="true" // 페이지네이션 사용 여부
        page-per-view="5" // 한 페이지에 보여질 개수
        show-key-field="false"
        lwc:ref="오브젝트명">
</c-dkbmc-grid>
```
