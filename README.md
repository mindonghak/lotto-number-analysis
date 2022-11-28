# Lotto number analysis
> **Final Project1** of Computational Math

현재 조회일까지의 역대 1등 `lotto` 번호를 `DataFrame`으로 저장하고, 이 배열로
부터 각 숫자별 평균과 분산을 출력하는 프로그램을 `class`를 이용하여 구현하시오.

#### Condition
* [`lotto` 사이트](https://dhlottery.co.kr/)에서 Web Crawling을 이용한다 (예시된 사이트가 적절하지 않을 경우, 다른 사이트를 활용할 수 있음).
* 입력인수는 `yy-MM-dd`, 입력인수 생략시 현재일로 처리한다.
* 입력일까지 1등 `lotto` 번호를 `DataFrame`으로 저장한다. 이 때 `Index`는 `yy-MM-dd`,
`Key`는 번호`(1 ∼ 45)`를 사용한다.
* 출력은 평균과 분산을 `DataFrame`으로 출력한다. `Index`는 `Mean, Variance`를 사용
하고, `Key`는 숫자`(1 ∼ 45)`별 평균과 분산을 `DataFrame`으로 출력한다.
