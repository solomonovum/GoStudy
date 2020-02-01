# pep8 분석 

## - 협업 과제 및 개인 코드에 적용을 위한 - 

### [python 공식 사이트의 pep8](https://www.python.org/dev/peps/pep-0008)의 내용을 정리


### Contents
#### Comments

- 주석은 완전한 문장이어야한다. 식별자(identifier)가 소문자로 시작되지 않는다면, 첫 단어는 대문자여야한다. (식별자의 case를 절대 변경하지 마라!)
- 여러 문장을 사용하는 주석의 문장 마지막에 2개의 스페이스를 사용해야한다. (마지막 문장은 예외)
- 영어로 작성하라.

Block Comments
- 각 라인은 #와 1개의 스페이스로 시작한다. (주석 안에서 들여쓰기가 아니 이상) <- 엥 그런데 ```이 아니고?

Inline Comments
- 인라인주석은 최소로 사용하라.
- 인라인주석은 코드문과 같은 라인에 있는 주석이다.
- 코드와 주석을 최소 2개의 스페이스로 구분해야한다.
- #와 1개의 스페이스로 시작해야한다.

```
x = x + 1                 # Increment x
```
```
x = x + 1                 # Compensate for border
```

Documentation Strings([PEP 257](https://www.python.org/dev/peps/pep-0257/))
- 모든 public modules, functions, classes, methods 에 대해 docstring을 작성한다.
- non-public method 에는 필수는 아니지만, 무엇을 하는 method인지는 def 다음 라인에 기술하여야한다.  
- 종료 """는 혼자 두어야 하지만, 한줄짜리 주석이라면 같은 라인에 둔다.
