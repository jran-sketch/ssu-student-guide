2026 숭실대학교 디지털특성화대학 통합안내 포털 - 11월 메뉴 복구본

기준: 사용자가 제공한 2026-10-29 GitHub ZIP 원본

변경 파일
- index.html: 상단/본문에 만족도조사 및 수료생 혜택 링크 추가, 멘토링 안내 삭제
- benefit.html: 과거 제작된 수료생 특별혜택 신청 페이지 복원(3종 혜택만 유지)

변경하지 않은 파일
- schedule.html: 11월 기초/심화 일정 포함 기존 파일 그대로 유지
- soongsil-logo.jpg: 원본 그대로 유지

만족도조사 링크: https://ssu-survey-status.vercel.app/ (기존 소스에 기재된 주소)
특별혜택 접수: benefit.html 안의 기존 Apps Script POST 엔드포인트 사용

중요: 외부 설문 링크의 현재 접속 가능 여부와 특별혜택 Apps Script의 실제 저장 성공 여부는 검증하지 못했습니다.
교육생 배포 전에 테스트 응답 1건을 제출하고 운영관리 시트에서 저장 여부를 확인하세요.

GitHub 저장소 https://github.com/jran-sketch/ssu-student-guide 의 main 브랜치에
index.html, benefit.html, schedule.html, soongsil-logo.jpg를 같은 루트에 배치하면
기존 Vercel-GitHub 자동 배포 설정에 따라 사이트가 갱신됩니다.
