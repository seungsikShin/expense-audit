# 경비집행 점검 프로그램 (Windows)

경비집행 취합파일(xlsx)을 불러와 룰 기반 점검과 크로스체크를 수행하고 결과를 Excel로 출력하는 프로그램임.

## 다운로드
위 파일 목록에서 `expense_audit_v7.zip` 클릭 → 오른쪽 **Download(↓)** 버튼

SHA-256: `124f564f96f2949b8753d575f10c19f7bed37c91ebb4832a802dd5a6958a81ea`

## 설치·실행
1. zip 압축 해제 (쓰기 권한 있는 폴더)
2. `expense_audit\expense_audit.exe` 실행
   - exe만 따로 옮기면 실행 안 됨 (`_internal` 폴더가 같은 위치에 있어야 함)
   - SmartScreen 경고 시 [추가 정보] → [실행]
3. 상세 사용법: 압축 해제 후 `사용안내.txt` 참고

## PC 요건
- Windows 64bit
- Microsoft Excel 설치
- AI 점검(선택)은 사내망 + 개인 키 필요 — `_internal\config\alli.yaml`에 입력
