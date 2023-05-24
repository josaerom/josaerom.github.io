# josaerom.github.io test
폴더구조

-rompage-

common
 - library
 - css
 - js

v1
 - 정리

v2
 - css
 - js
  - component
  - store
  - route
 - jsp


index.jsp



Araay

Array.prototype.at()
at() 메서드는 정수 값을 받아, 배열에서 해당 값에 해당하는 인덱스의 요소를 반환합니다. 양수와 음수 모두 지정할 수 있고, 음수 값의 경우 배열의 뒤에서부터 인덱스를 셉니다.

Array.prototype.concat()
concat() 메서드는 인자로 주어진 배열이나 값들을 기존 배열에 합쳐서 새 배열을 반환합니다.

Array.prototype.copyWithin()
copyWithin() 메서드는 배열의 일부를 얕게 복사한 뒤, 동일한 배열의 다른 위치에 덮어쓰고 그 배열을 반환합니다. 이 때, 크기(배열의 길이)를 수정하지 않고 반환합니다.

Array.prototype.entries()
entries() 메서드는 배열의 각 인덱스에 대한 키/값 쌍을 가지는 새로운 Array Iterator 객체를 반환합니다.

Array.prototype.every()
every() 메서드는 배열 안의 모든 요소가 주어진 판별 함수를 통과하는지 테스트합니다. Boolean 값을 반환합니다.

Array.prototype.fill()
fill() 메서드는 배열의 시작 인덱스부터 끝 인덱스의 이전까지 정적인 값 하나로 채웁니다.

Array.prototype.filter()
filter() 메서드는 주어진 함수의 테스트를 통과하는 모든 요소를 모아 새로운 배열로 반환합니다.

Array.prototype.find()
find() 메서드는 주어진 판별 함수를 만족하는 첫 번째 요소의 값을 반환합니다. 그런 요소가 없다면 undefined를 반환합니다.

Array.prototype.findIndex()
findIndex() 메서드는 주어진 판별 함수를 만족하는 배열의 첫 번째 요소에 대한 인덱스를 반환합니다. 만족하는 요소가 없으면 -1을 반환합니다.

Array.prototype.findLast()
findLast() 메서드는 배열을 역순으로 반복하고 제공된 테스트 함수를 만족하는 첫 번째 요소의 값을 반환합니다. 테스트 함수를 만족하는 요소가 없다면 undefined가 반환될 것입니다.

Array.prototype.findLastIndex()

Array.prototype.flat()
중첩 배열 평탄화 flat() 메서드는 모든 하위 배열 요소를 지정한 깊이까지 재귀적으로 이어붙인 새로운 배열을 생성합니다.

Array.prototype.flatMap()
flatMap() 메서드는 먼저 매핑함수를 사용해 각 엘리먼트에 대해 map 수행 후, 결과를 새로운 배열로 평탄화합니다. 이는 깊이 1의 flat 이 뒤따르는 map 과 동일하지만, flatMap 은 아주 유용하며 둘을 하나의 메소드로 병합할 때 조금 더 효율적입니다.

Array.prototype.forEach()
forEach() 메서드는 주어진 함수를 배열 요소 각각에 대해 실행합니다.

Array.from()
Array.from() 메서드는 유사 배열 객체(array-like object)나 반복 가능한 객체(iterable object)를 얕게 복사해 새로운Array 객체를 만듭니다.

Array.prototype.includes()
includes() 메서드는 배열이 특정 요소를 포함하고 있는지 판별합니다.

Array.prototype.indexOf()
indexOf() 메서드는 배열에서 지정된 요소를 찾을 수 있는 첫 번째 인덱스를 반환하고 존재하지 않으면 -1을 반환합니다.

Array.isArray()
Array.isArray() 메서드는 인자가 Array인지 판별합니다.

Array.prototype.join()
join() 메서드는 배열의 모든 요소를 연결해 하나의 문자열로 만듭니다.

Array.prototype.keys()
keys() 메서드는 배열의 각 인덱스를 키 값으로 가지는 새로운 Array Iterator 객체를 반환합니다.

Array.prototype.lastIndexOf()
lastIndexOf() 메서드는 배열에서 주어진 값을 발견할 수 있는 마지막 인덱스를 반환하고, 요소가 존재하지 않으면 -1을 반환합니다. 배열 탐색은 fromIndex에서 시작하여 뒤로 진행합니다.

Array.prototype.map()
map() 메서드는 배열 내의 모든 요소 각각에 대하여 주어진 함수를 호출한 결과를 모아 새로운 배열을 반환합니다.

Array.of()
Array.of() 메서드는 인자의 수나 유형에 관계없이 가변 인자를 갖는 새 Array 인스턴스를 만듭니다.

Array.prototype.pop()
pop() 메서드는 배열에서 마지막 요소를 제거하고 그 요소를 반환합니다.

Array.prototype.push()
push() 메서드는 배열의 끝에 하나 이상의 요소를 추가하고, 배열의 새로운 길이를 반환합니다.

Array.prototype.reduce()
reduce() 메서드는 배열의 각 요소에 대해 주어진 리듀서 (reducer) 함수를 실행하고, 하나의 결과값을 반환합니다.

Array.prototype.reduceRight()
reduceRight() 메서드는 누적기에 대해 함수를 적용하고 배열의 각 값 (오른쪽에서 왼쪽으로)은 값을 단일 값으로 줄여야합니다.

Array.prototype.reverse()
reverse() 메서드는 배열의 순서를 반전합니다. 첫 번째 요소는 마지막 요소가 되며 마지막 요소는 첫 번째 요소가 됩니다.

Array.prototype.shift()
shift() 메서드는 배열에서 첫 번째 요소를 제거하고, 제거된 요소를 반환합니다. 이 메서드는 배열의 길이를 변하게 합니다.

Array.prototype.slice()
slice() 메서드는 어떤 배열의 begin 부터 end 까지(end 미포함)에 대한 얕은 복사본을 새로운 배열 객체로 반환합니다. 원본 배열은 바뀌지 않습니다.

Array.prototype.some()
some() 메서드는 배열 안의 어떤 요소라도 주어진 판별 함수를 적어도 하나라도 통과하는지 테스트합니다. 만약 배열에서 주어진 함수가 true을 반환하면 true를 반환합니다. 그렇지 않으면 false를 반환합니다. 이 메서드는 배열을 변경하지 않습니다.

Array.prototype.sort()
sort() 메서드는 배열의 요소를 적절한 위치에 정렬한 후 그 배열을 반환합니다. 정렬은 stable sort가 아닐 수 있습니다. 기본 정렬 순서는 문자열의 유니코드 코드 포인트를 따릅니다.

Array.prototype.splice()
splice() 메서드는 배열의 기존 요소를 삭제 또는 교체하거나 새 요소를 추가하여 배열의 내용을 변경합니다.

Array.prototype.toLocaleString()
toLocaleString() 메서드는 배열의 요소를 나타내는 문자열을 반환합니다. 요소는 toLocaleString 메서드를 사용하여 문자열로 변환되고 이 문자열은 locale 고유 문자열(가령 쉼표 “,”)에 의해 분리됩니다.

Array.prototype.toString()
toString() 메서드는 지정된 배열 및 그 요소를 나타내는 문자열을 반환합니다.

Array.prototype.unshift()
unshift() 메서드는 새로운 요소를 배열의 맨 앞쪽에 추가하고, 새로운 길이를 반환합니다.

Array.prototype.values()
values() 메서드는 배열에서 각 인덱스에 대한 값을 순회하는 array iterator 객체를 반환합니다.


----------------------------------

push() / pop()  배열 끝에 요소를 추가하거나 제거
unshift() / shift()  배열 처음에 요소를 추가하거나 제거
concat()  배열과 배열 또는 값을 합친 새로운 배열 반환
