# Django
## 기본횐경 셋팅

### 1. __VS code__ 셋팅 

- `ctrl`+`shife`+`` ` ``로 터미널 활성화
- `python --version`으로 version확인 가능
### 2. __가상환경__ 생성 & 실행

- __가상환경 생성__
```
python -m venv (가상환경이름)
```
> venv = Virtual environment 를 의미
>> 가상환경 이름은 `myvenv` 또는 `venv`를 사용

- __가상환경 실행__
```
source (가상환경명)/Scripts/activate
```
> `source`대신 `.`으로 입력가능

- __가상환경 끄기__

```
deactivate
```

### 3. __Djnago__ 설치

```
pip intall django
```
> `pip`은 파이썬관련 패키지를 설치하기 위해 사용되는 명령어
>> 특정 version django 설치
>> ```
>>pip install django==(장고 버전)
>> ```