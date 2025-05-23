A Lightweight Authentication Protocol for AAL System

보안 공학 프로젝트 - 정형 검증 기반 경량 인증 프로토콜 분석 및 구현작성자: 공종욱학과: 컴퓨터과학과학번: 2018010838

🔍 프로젝트 개요

본 프로젝트는 논문 「전천후 생활 지원 시스템을 위한 경량 인증 프로토콜」의 내용을 기반으로, AAL(Ambient Assisted Living) 시스템을 위한 경량 인증 프로토콜의 구조 및 보안성 검증을 HLPSL 및 AVISPA 툴을 이용해 수행하였습니다.

📄 대상 논문

A Lightweight Authentication Protocol for Ambient Assisted Living System저자: 이명규, 황보택근

📌 주요 내용

고령자 복지를 위한 AAL 시스템에서의 인증 및 보안 문제 해결

AAL 센서, 게이트웨이, 플랫폼 간의 안전한 통신을 위한 경량 인증 프로토콜 제안

해시값, 임시비표, 공개키 기반 암호화 방식 사용

AVISPA Tool을 활용한 정형 검증을 통해 기밀성 및 무결성 검증

🛠 시스템 구성

AAL 시스템은 다음과 같은 구성 요소로 구성됩니다:

AAL 센서: 생체 정보 및 환경 정보 수집

AAL 게이트웨이: 센서 정보 수집 및 중계

AAL 플랫폼: 사용자에게 서비스 제공

인증서버: 공개키 관리 및 인증 지원

 

🔐 제안된 경량 인증 프로토콜

총 9단계의 메시지 교환 과정을 통해 AAL 센서 → 게이트웨이 → 플랫폼 간 인증 및 세션 키 공유를 수행합니다.

주요 특징

센서와 게이트웨이 간에는 임시비표와 해시값 기반 인증

게이트웨이와 플랫폼 간에는 인증서버를 통한 공개키 확인 및 세션 키 수립

AVISPA로 기밀성과 무결성 보장

🧪 정형 검증 (Formal Verification)

🔧 사용 도구

HLPSL: 프로토콜 기술 언어

AVISPA: 자동 보안 프로토콜 검증 툴

Backend: CL-Atse

Modes: Simplify / Verbose

✅ 검증 목표

메시지 기밀성 (Confidentiality)

메시지 무결성 (Integrity)

🔬 결과

모드

결과

Simplify

✅ SAFE

Verbose

✅ SAFE

📁 코드 및 HLPSL 파일

프로젝트에 사용한 HLPSL 파일 및 전체 실험 코드는 아래 GitHub 링크에서 확인할 수 있습니다:

🔗 https://github.com/GongWook/Avispa-AAL-System-Protocol.git

📌 결론

제안된 경량 인증 프로토콜은 AAL 환경에서의 안전한 인증 및 통신을 보장할 수 있으며, 정형 검증을 통해 실질적인 보안성을 입증할 수 있었습니다.

📃 참고 논문

이명규, 황보택근, “전천 후 생활 지원 시스템을 위한 경량 인증 프로토콜,” 정보보호학회 논문지

