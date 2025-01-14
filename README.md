# ongdalsaem
프로젝트 전 가볍게 진행할 task입니다.

<br/>

# GitHub 협업 가이드

## 1. Branch 생성 및 사용
### 1.1 Branch 이동
```bash
git checkout [suffix]
```

### 1.2 Branch 확인
작업 전 항상 현재 브랜치를 확인하세요(안그러면 충돌 우려)
<br/>

## 2. 작업 후 Commit 및 Pull Request
### 2.1 Commit 메세지 작성
```bash
git add .
git commit -m "타입: 설명"
```

| 타입       | 설명                                | 예시                           |
|------------|-------------------------------------|--------------------------------|
| FEAT       | 새로운 기능 구현                     | `FEAT: 회원가입 기능 추가`      |
| REFACTOR   | 코드 개선 및 삭제                   | `REFACTOR: 코드 정리 및 변수명 변경` |
| FIX        | 버그 해결                          | `FIX: 결과 조회 API 수정`       |
| CHORE      | 빌드 관련 작업                     | `CHORE: 패키지 의존성 업데이트` |

- 결과
FEAT: 로그인 기능 추가
FIX: 로그인 로직 오류 해결

### 2.2 Push
- 1.자신의 원격 브랜치로 push:
```bash
git push origin [suffix]
```

