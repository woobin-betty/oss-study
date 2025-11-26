# 📌 Git & GitHub 정리

## ✅ 1. Git이란?
**파일의 변경 이력을 기록하고 관리하는 버전 관리 시스템**

### 🔹 Git이 필요한 이유
- 과거 버전으로 되돌릴 수 있다
- 어떤 부분이 언제 어떻게 바뀌었는지 기록된다
- 여러 사람이 함께 작업할 때 충돌을 줄여준다

### 🔹 Git의 핵심 개념
| 개념 | 설명 |
|------|------|
| Repository(저장소) | 파일과 변경 기록이 저장되는 공간 |
| Working Directory | 실제로 작업하는 내 컴퓨터 공간 |
| Staging Area | 커밋 전 변경 내용을 잠시 올려두는 공간 |
| Commit | 변경 내용을 기록으로 저장하는 행위 |
| Branch | 작업을 나누는 가지(독립 작업 가능) |
| Merge | 나뉜 브랜치를 다시 합치는 것 |

---

## ✅ 2. Git 주요 명령어
```bash
git init              # 로컬 저장소 생성
git clone URL         # GitHub 저장소 복사
git status            # 현재 상태 확인
git add 파일명        # 변경 내용을 Staging Area에 올림
git commit -m "메시지" # 변경 내용 저장(버전 생성)
git push              # GitHub로 업로드
git pull              # GitHub에서 최신 내용 가져오기
git branch            # 브랜치 목록 확인
git checkout -b 이름  # 새 브랜치 생성 후 이동
