#  필터

## 필터 사용하기

컬럼별로 타입은 각 `text`, `number`, `select`, `date` 의 필터 옵션을 제공합니다.

```javascript
gridColumnData = [
    { fieldName: "Type__c", label: "Type Label", sortable: true, merge: true, filter: true }
    , { fieldName: "Count__c",  filter: true }
    , { fieldName: "Address__c",filter: true, sortable: true}
    , { fieldName: "StartDate__c", sortable: true }
    , { fieldName: "EndDate__c", sortable: true, filter: true }
];
```
- 필터 사용 여부는 filter: true 옵션을 사용합니다. 반대로  filter: false 이거나 filter의 속성 값을 입력하지 않으면 필터가 비활성화 됩니다.


필터 타입에 대한 설명

| option            | type   |
| ----------------- | ------ |
| `=`               | number |
| `>`               | number |
| `<`               | number |
| `>=`              | number |
| `<=`              | number |
| `!=`              | number |
| `Contains`        | text   |
| `Equals`          | text   |
| `Not equals`      | text   |
| `Starts with`     | text   |
| `Ends with`       | text   |
| `Equals`          | date   |
| `Not equals`      | date   |
| `After`           | date   |
| `After or Equal`  | date   |
| `Before`          | date   |
| `Before or Equal` | date   |
