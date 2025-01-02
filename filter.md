#  필터

## 필터 사용법

### test

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

필터 타입에 대한 설명

| option            | code     | type   |
| ----------------- | -------- | ------ |
| `=`               | eq       | number |
| `>`               | lt       | number |
| `<`               | gt       | number |
| `>=`              | lte      | number |
| `<=`              | gte      | number |
| `!=`              | ne       | number |
| `Equals`          | eq       | text   |
| `Not equals`      | ne       | text   |
| `Contains`        | contain  | text   |
| `Starts with`     | start    | text   |
| `Ends with`       | end      | text   |
| `Equals`          | eq       | date   |
| `Not equals`      | ne       | date   |
| `After`           | after    | date   |
| `After or Equal`  | afterEq  | date   |
| `Before`          | before   | date   |
| `Before or Equal` | beforeEq | date   |
