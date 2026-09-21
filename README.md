# Git & Markdown 실습

> Git CLI의 기본 명령을 사용하고, GitHub에서 Markdown 문서가 어떻게 표현되는지 확인하기 위한 실습입니다.

## 1. 실습 목표

- Git의 전역 사용자 정보 설정하기
- 로컬 저장소에서 파일을 커밋하기
- 원격 저장소를 `clone`으로 내려받기
- Markdown 문서를 GitHub 저장소에 업로드하기

## 2. Git 실습 내용

| 순서 | 명령어 | 의미 | 완료 여부 |
|:---:|---|---|:---:|
| 1 | `git config --global` | 사용자 이름과 이메일 설정 | ✅ |
| 2 | `git init` | 현재 폴더를 Git 저장소로 생성 | ✅ |
| 3 | `git add` | 커밋할 파일을 스테이징 | ✅ |
| 4 | `git commit` | 변경 사항을 하나의 버전으로 기록 | ✅ |
| 5 | `git clone` | 원격 저장소 복제 | ✅ |
| 6 | `git push` | 로컬 커밋을 GitHub에 업로드 | ✅ |

사용한 기본 명령어는 다음과 같습니다.

```bash
git init -b main
git add README.md
git commit -m "Add initial Markdown practice file"
git clone https://github.com/django/django.git
git push -u origin main
```

## 3. Markdown 문법 정리

### 글자 꾸미기

- **굵은 글씨**: 중요한 내용을 강조할 때 사용
- *기울임 글씨*: 용어나 가벼운 강조에 사용
- ~~취소선~~: 수정하거나 취소한 내용을 표현할 때 사용
- `인라인 코드`: 명령어나 파일명을 문장 안에 표시할 때 사용

### 목록과 체크박스

1. Git 설치 상태를 확인했다.
2. 전역 사용자 정보를 설정했다.
3. 로컬 저장소에서 첫 커밋을 만들었다.
4. Django 공식 저장소를 클론했다.
5. Markdown 파일을 GitHub에 업로드했다.

- [x] Git 설치 및 전역 설정
- [x] 로컬 커밋 생성
- [x] Django 저장소 클론
- [x] GitHub 저장소 생성
- [x] Markdown 업로드

### 링크와 인용문

- [Git 공식 사이트](https://git-scm.com/)
- [GitHub Markdown 문법 안내](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [Django 공식 GitHub 저장소](https://github.com/django/django)

> Markdown은 간단한 기호만으로 문서의 구조와 강조 표현을 만들 수 있어 README나 개발 문서를 작성할 때 유용하다.

---

## 4. 실습 소감

GUI를 사용하지 않고 Git 명령어를 직접 실행하면서 `add`, `commit`, `push`가 서로 다른 단계라는 것을 확인했다. 또한 Markdown 원문이 GitHub에서 제목, 표, 목록, 코드 블록으로 변환되는 과정을 확인할 수 있었다.

앞으로 프로젝트를 진행할 때 README에 **프로젝트 목적**, **사용 방법**, **진행 상황**을 정리하여 다른 사람이 쉽게 이해할 수 있도록 작성하고 싶다.

---

작성 계정: `sylee21c`
