# Mermaod 실습(2022-11-09)
- 순서도 실습
    - 첫번째 실습(flowchart)
- 공식 사이트(https://mermaid-js.github.io/mermaid/#/)
- 교수님 페이지(https://kafa46.github.io/mermaid/intro.html)
- 주석은 (%%)로 한다.

```mermaid
flowchart LR
    id(((첫번째 노드)))
```

```mermaid
flowchart 
    A[설날 아침] -->|세뱃돈| B(쇼핑 가기)
    B --> C{뭘 사야하나?}
    C -->|선택1| D[노트북]
    C -->|선택2| E[스마트폰]
    C -->|선택3| F[자동차] 
```

- ` 이 기호는 mermaid 시작점과 끝점을 나타내는 기호로 사용하고 처음은 mermaid라고 적어주시기

```python
print("Hello world")
```

```Java
System.out.println("Hello world");
```