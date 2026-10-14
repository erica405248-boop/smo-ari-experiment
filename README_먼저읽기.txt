GitHub Pages 정적 실험 흐름 테스트 전용 — 본실험 배포 금지

1. 이 폴더 전체를 정적 호스팅하면 index.html에서 SMO로 이동할 수 있습니다.
2. 아리의 8개 질문 응답은 서버에 저장하지 않습니다. 8개 응답 완료 후 PANAS T2로 이동합니다.
3. PANAS T2 URL에 p, c=SMO조건, ai_condition, ari_completed=1이 전달됩니다. Qualtrics에서 ari_completed 임베디드 데이터를 저장하도록 설정해야 합니다.
4. URL의 ari_completed=1은 조작 가능한 값으로, 독립적으로 검증된 완료 증거가 아닙니다.
5. Qualtrics PANAS T1 종료 링크의 localhost 주소를 배포한 아리의 HTTPS 주소로 변경해야 합니다.
6. ID는 브라우저에서 임의 생성하므로 중복/재접속/중복참여를 방지하지 못합니다. 실제 모집 전 업체 고유 ID 또는 안전한 ID 발급·검증 체계가 필요합니다.
7. 연구 동의, 외로움군 선별, IRB 심의/면제 확인, 보안/데이터 관리, 양 조건 검증, 외부 HTTPS 라이브러리 점검이 필요합니다.
8. PANAS T2 및 의인화 설문의 임베디드 데이터 연결은 Qualtrics에서 별도 검증하세요.
9. 실제 응답 JSON 파일, Python 저장 서버, 파일럿 자료는 포함하지 않았습니다.
