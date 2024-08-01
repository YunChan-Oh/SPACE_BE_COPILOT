# 1️⃣ 과제 안내
> 당신은 유인 및 무인 우주 탐사선 시스템을 개발하는 소프트웨어 개발자로 고용되었습니다. 유인 및 무인 탐사선 시스템을 구현하는 것이 당신의 첫 번째 과제입니다. 다음 요구사항을 충족하는 클래스를 작성하세요.

<br>

## 2️⃣ 기능 요구 사항
- [ ] 탐사선은 다음과 같은 속성을 가집니다.
  - 이름
- [ ] 탐사선의 이름을 변경할 수 있습니다.
- [ ] 무인 탐사선은 탐사 대원을 가질 수 없습니다.
- [ ] 유인 탐사선은 탐사 대원을 가질 수 있습니다.
- [ ] 탐사선의 정보를 확인할 수 있습니다.
  - 탐사선 정보, 탐사 대원 등
- [ ] 탐사 대원은 탐사선에 탑승할 수 있습니다.
- [ ] 탐사 대원은 탐사선에서 내릴 수 있습니다.
- [ ] 탐사 대원은 다음과 같은 속성을 가집니다.
  - 이름
- [ ] 탐사 대원의 이름을 변경할 수 있습니다.

## 제한 사항
- [ ] 모든 변수는 'private'으로 선업합니다.
- [ ] 각각의 변수는 'getter', 'setter'로 접근 합니다.

## 코드 작성 시 유의사항
- [ ] 클래스별로 파일을 구분해야 합니다.
- [ ] 패키지, 변수, 메서드 작성시에는 꼭 그에 알맞는 네이밍 컨벤션을 따라야 합니다.

## 예시 출력 결과
```java
Spaceship: Voyager 1
우주선 속 탐사대원이 존재하지 않습니다.

        Spaceship: BSSM 1
우주선 속 탐사대원이 존재하지 않습니다.

        Spaceship: Apollo 11
Neil Armstrong 우주대원이 탐사 중 입니다.

Spaceship: Apollo 11
OYC 우주대원이 탐사 중 입니다.
```

<br>

# 2️⃣ 과제 제출 방법
  1. 이 레포지토리를 포크합니다.
  2. 본인의 이름으로 브랜치를 생성합니다.
  3. 모두 완료한 후 Pull Request를 보내주세요.

<br>

## 3️⃣ 커밋 메시지 규칙
다음 명령어를 사용하면 커밋 템플릿을 통해 커밋 메시지를 작성할 수 있습니다.

```bash
git commit
```

### 형식
커밋 메시지는 머리글, 본문, 바닥글로 구성합니다.

```html
<머리글>

<본문>

<바닥글>
```

### 머리글(필수)
```
<커밋 유형>: <짧은 요약>
커밋 유형 : feat|fix|perf|refactor
짧은 요약 : 현재, 명령형으로 작성. 마침표 금지. 
```
#### 유형

| 유형     | 설명                                                     |
|----------|----------------------------------------------------------|
| feat     | 새로운 기능 추가                                         |
| fix      | 버그 수정                                                |
| perf     | 성능 개선                                                |
| refactor | 버그를 수정하거나 기능을 추가하지 않은 코드 리팩토링     |

#### 요약

"**무엇**"을 변경했는지를 작성합니다.

- 명령형, 현재 시제 사용 (예시): "변경"으로 작성 ("변경함", "변경했음" X)
- 끝에 마침표(.) 금지
- 한글 사용 권장

### 본문

- 한글 권장
- "**왜**" 변경했는지를 작성합니다.
- 자유 형식

### 바닥글(선택 사항)
참고 사항 또는 추가로 할 말이 있을 때 작성합니다.

### 명령어 예시
```bash
git commit -m "feat :: 우주선 객체
- ~~ 구체적인 설명
"
```
