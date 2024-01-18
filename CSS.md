
| 셀렉터 | 예시 | 예시 설명 |
|----------------------|-----------------------|--------------------------------------------------------------------------|
| .class | .intro | class="intro"가 있는 모든 요소를 선택 |
| .class1.class2 | .name1.name2 | class 속성 내에 name1 및 name2 가 모두 설정된 모든 요소를 선택 |
| .class1 .class2 | .name1 .name2 | name1이 있는 요소의 후손인 name2를 가진 모든 요소를 선택 |
| #id | #firstname | id="firstname"인 요소를 선택 |
| _ | _ | 모든 요소를 선택 |
| element | p | 모든 <p> 요소를 선택 |
| element.class | p.intro | class="intro"가 있는 모든 <p> 요소를 선택 |
| element,element | div, p | 모든 <div> 요소와 모든 <p> 요소를 선택 |
| element element | div p | <div> 요소 안의 모든 <p> 요소를 선택 |
| element>element | div > p | 부모가 <div> 요소인 모든 <p> 요소를 선택 |
| element+element | div + p | <div> 요소 바로 다음에 위치한 첫 번째 <p> 요소를 선택 |
| element1~element2 | p ~ ul | <p> 요소에 앞서는 모든 <ul> 요소를 선택 |
| [attribute] | [target] | target 속성을 가진 모든 요소를 선택 |
| [attribute=value] | [target="_blank"] | target="\_blank"인 모든 요소를 선택 |
| [attribute~=value] | [title~="flower"] | title 속성에 "flower"라는 단어가 포함된 모든 요소를 선택 |
| [attribute\|=value] | [lang\|="en"] | lang 속성 값이 "en"과 같거나 "en-"으로 시작하는 모든 요소를 선택 |
| [attribute^=value] | a[href^="https"] | href 속성 값이 "https"로 시작하는 모든 <a> 요소를 선택 |
| [attribute$=value] | a[href$=".pdf"] | href 속성 값이 ".pdf"로 끝나는 모든 <a> 요소를 선택 |
| [attribute*=value] | a[href*="w3schools"] | href 속성 값에 "w3schools"라는 부분 문자열이 포함된 모든 <a> 요소를 선택 |
| :active | a:active | 활성 링크를 선택 |
| ::after | p::after | 각 <p> 요소의 내용 다음에 무언가를 삽입 |
| ::before | p::before | 각 <p> 요소의 내용 앞에 무언가를 삽입 |
| :checked | input:checked | 체크된 모든 <input> 요소를 선택 |
| :default | input:default | 기본 <input> 요소를 선택 |
| :disabled | input:disabled | 비활성화된 모든 <input> 요소를 선택 |
| :empty | p:empty | 자식이 없는 모든 <p> 요소를 선택 (텍스트 노드 포함) |
| :enabled | input:enabled | 활성화된 모든 <input> 요소를 선택 |
| :first-child | p:first-child | 부모의 첫 번째 자식인 모든 <p> 요소를 선택 |
| ::first-letter | p::first-letter | 모든 <p> 요소의 첫 글자를 선택 |
| ::first-line | p::first-line | 모든 <p> 요소의 첫 번째 줄을 선택 |
| :first-of-type | p:first-of-type | 부모의 첫 번째 <p> 요소인 모든 <p> 요소를 선택 |
| :focus | input:focus | 포커스가 있는 input 요소를 선택 |
| :fullscreen | :fullscreen | 전체 화면 모드인 요소를 선택 |
| :hover | a:hover | 마우스 오버 시 링크를 선택 |
| :in-range | input:in-range | 지정된 범위 내 값이 있는 input 요소를 선택 |
| :indeterminate | input:indeterminate | 불확정 상태인 input 요소를 선택 |
| :invalid | input:invalid | 잘못된 값이 있는 모든 input 요소를 선택 |
| :lang(language) | p:lang(it) | lang 속성 값이 "it"(이탈리아어)인 모든 <p> 요소를 선택 |
| :last-child | p:last-child | 부모의 마지막 자식인 모든 <p> 요소를 선택 |
| :last-of-type | p:last-of-type | 부모의 마지막 <p> 요소인 모든 <p> 요소를 선택 |
| :link | a:link | 방문하지 않은 모든 링크를 선택 |
| ::marker | ::marker | 리스트 항목의 마커를 선택 |
| :not(selector) | :not(p) | <p> 요소가 아닌 모든 요소를 선택 |
| :nth-child(n) | p:nth-child(2) | 부모의 두 번째 자식인 모든 <p> 요소를 선택 |
| :nth-last-child(n) | p:nth-last-child(2) | 마지막 자식부터 세었을 때 부모의 두 번째 자식인 모든 <p> 요소를 선택 |
| :nth-last-of-type(n) | p:nth-last-of-type(2) | 마지막 자식부터 세었을 때 부모의 두 번째 <p> 요소인 모든 <p> 요소를 선택 |
| :nth-of-type(n) | p:nth-of-type(2) | 부모의 두 번째 <p> 요소인 모든 <p> 요소를 선택 |
| :only-of-type | p:only-of-type | 부모의 유일한 <p> 요소인 모든 <p> 요소를 선택 |
| :only-child | p:only-child | 부모의 유일한 자식인 모든 <p> 요소를 선택 |
| :optional | input:optional | "required" 속성이 없는 input 요소를 선택 |
| :out-of-range | input:out-of-range | 지정된 범위 밖의 값이 있는 input 요소를 선택 |
| ::placeholder | input::placeholder | "placeholder" 속성이 지정된 input 요소를 선택 |
| :read-only | input:read-only | "readonly" 속성이 지정된 input 요소를 선택 |
| :read-write | input:read-write | "readonly" 속성이 지정되지 않은 input 요소를 선택 |
| :required | input:required | "required" 속성이 지정된 input 요소를 선택 |
| :root | :root | 문서의 루트 요소를 선택 |
| ::selection | ::selection | 사용자에 의해 선택된 요소의 부분을 선택 |
| :target | #news:target | 현재 활성화된 #news 요소를 선택 (해당 앵커 이름을 포함하는 URL 클릭) |
| :valid | input:valid | 유효한 값이 있는 모든 input 요소를 선택 |
| :visited | a:visited | 방문한 모든 링크를 선택 |
