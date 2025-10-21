
---

## 🌐 `OTD_MSA_Back_Gateway/README.md`

```markdown
# 🌐 OTD_MSA_Back_Gateway

**OneToday (OTD)** 백엔드 **API Gateway 서비스** 레포지토리입니다.  
Spring Cloud Gateway 기반으로, MSA 환경에서 **라우팅·인증·로깅·트래픽 관리** 역할을 담당합니다.


---

## ⚙️ 기술 스택

| 항목 | 내용 |
|------|------|
| 언어 | Java 17 |
| 프레임워크 | Spring Boot 3.x |
| Gateway | Spring Cloud Gateway |
| 보안 | JWT 인증 필터 |
| Config | Spring Cloud Config (옵션) |
| 빌드도구 | Gradle |
| 배포환경 | Docker, Kubernetes |

---

## 🚀 실행 방법

```bash
# 1) 애플리케이션 실행
./gradlew bootRun

---

💡 주요 기능

🔀 서비스 라우팅 및 로드밸런싱
🛡️ JWT 인증 필터
📜 요청 로깅 및 추적
⚙️ 서비스별 트래픽 관리

---

🧠 시스템 아키텍처

[FrontEnd]
   ↓
[OTD_MSA_Back_Gateway]
   ↓
 ┌──────────────┬──────────────┐
 │ User Service │ Life Service │
 └──────────────┴──────────────┘

