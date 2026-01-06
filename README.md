# Test Classroom / Test Assignment C File

## 문제

입력으로 정수 $a$, $b$가 차례로 들어온다. 이 둘의 합 $a + b$를 계산하여 출력하는 프로그램을 작성하시오.

반드시 `main.c`를 사용할 것.

## 파일

테스트 케이스 $t$ ($1 \leq t \leq 10$)에 대해, 입력 파일 `{t}.in`이 준비되어있다 (예: `1.in`, `2.in`, ..., `10.in`).

입력 파일을 입력으로 생각하고, 출력 파일 `{t}.out`을 출력으로 생각한다.

파일명은 아래와 같이 지정 할 수 있다:

```C
int t;
sscanf(argv[1], "%d", &t);
char fname_in[100];
char fname_out[100];
sprintf(fname_in, "%d.in", t);
sprintf(fname_out, "%d.out", t);
```

## 입력

$a$, $b$는 각각 1 이상, 1000 미만이라 가정한다.

## 예시

### 입력 예시

```text
2 3
```

### 출력 예시

```text
5
```

## 제한

* 시간 제한: 1초
* 메모리 제한: 128MB
