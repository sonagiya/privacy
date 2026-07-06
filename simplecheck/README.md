# 간단 체크! 개인정보처리방침

**앱 이름**: 간단 체크! (Simple Check)  
**패키지명**: `com.ssona.simplecheck`  
**버전**: 1.0.0  
**시행일**: 2026년 6월 2일  
**최종 수정일**: 2026년 6월 2일

---

## 1. 개요

「간단 체크!」(이하 "앱")은 일·주·월·년 단위 체크리스트를 관리하는 모바일 애플리케이션입니다.  
본 개인정보처리방침은 앱 이용과 관련하여 어떤 정보가 수집·이용·보관·제공되는지 설명합니다.

앱의 **핵심 기능(체크리스트·대시보드·캘린더)은 인터넷 연결 없이 기기 내에서 동작**합니다.  
네트워크 연결은 광고 표시, Google 로그인·백업 등 **사용자가 선택하거나 앱이 해당 기능을 제공할 때**에만 필요합니다.

---

## 2. 수집하는 정보

### 2.1 사용자가 직접 입력하는 정보

| 항목 | 수집 시점 | 이용 목적 | 보관 위치 |
|------|-----------|-----------|-----------|
| 체크리스트 항목명 | 항목 추가·편집 시 | 체크리스트 제공 | 기기 내부 저장소 |
| 완료 기록 | 항목 체크 시 | 진행률·이력 표시 | 기기 내부 저장소 |

체크리스트 항목명에는 사용자가 자유롭게 입력한 내용이 포함될 수 있습니다. **이름, 연락처, 주소 등 개인을 식별할 수 있는 정보를 항목명에 입력하지 않는 것을 권장**합니다.

### 2.2 앱 이용 과정에서 자동 생성·저장되는 정보

| 항목 | 내용 | 보관 위치 |
|------|------|-----------|
| 완료 기록 메타데이터 | 항목 ID, 기간 키(periodKey), 완료 시각 | 기기 내부 저장소 |
| 기간별 항목 스냅샷 | 과거 기간 조회를 위한 항목 목록 복사본 | 기기 내부 저장소 |
| 앱 설정 | 마지막 확인 기간 키 등 | 기기 내부 저장소 |

위 정보는 **별도의 운영 서버로 전송되지 않으며**, 사용자 기기에만 저장됩니다.

### 2.3 Google 로그인·백업 (선택)

사용자가 설정에서 **Google 로그인** 및 **백업/복원**을 이용하는 경우에 한해 다음 정보가 처리됩니다.

| 항목 | 수집·이용 목적 | 처리 주체 |
|------|----------------|-----------|
| Google 계정 이메일, 표시 이름, 프로필 사진 | 로그인 상태 표시, 백업 기능 제공 | Google / 앱 |
| 백업 JSON 파일 | 체크리스트·완료 기록·프리미엄 상태 복원 | Google Drive (App Data) |

- OAuth 권한 범위: `https://www.googleapis.com/auth/drive.appdata` (앱 전용 Drive 폴더)
- 백업 파일명: `simple_check_backup.json`
- 백업은 **사용자가 직접 실행**할 때만 Google Drive에 저장됩니다.
- Google의 개인정보 처리에 관해서는 [Google 개인정보처리방침](https://policies.google.com/privacy)을 참고하세요.

### 2.4 광고 (Google AdMob)

무료 이용자에게 하단 배너 광고가 표시될 수 있습니다.  
광고와 관련된 정보(광고 식별자, 기기 정보, IP 주소 등)는 **Google AdMob**을 통해 수집·처리될 수 있습니다.

- [Google AdMob 및 Google 광고 개인정보처리방침](https://policies.google.com/technologies/ads)

---

## 3. 정보의 이용 목적

수집·처리된 정보는 다음 목적에만 이용됩니다.

1. 체크리스트 생성·수정·삭제·체크 기능 제공
2. 주기별 진행률, 대시보드, 캘린더, 이력 차트 표시
3. Google Drive를 통한 데이터 백업·복원 (사용자 요청 시)
4. 광고 표시 처리
5. 앱 안정성·기능 개선 (기기 내 처리 범위)

**마케팅 목적의 푸시 알림, 위치 정보 수집, 연락처·사진 접근은 하지 않습니다.**

---

## 4. 정보의 보관 및 파기

| 구분 | 보관 기간 | 파기 방법 |
|------|-----------|-----------|
| 기기 내 체크리스트·완료 기록 | 앱 삭제 또는 앱 내 데이터 삭제·복원 시까지 | 앱 삭제 또는 로컬 DB 덮어쓰기 |
| Google Drive 백업 | 사용자가 Drive에서 삭제할 때까지 | Google Drive에서 파일 삭제 |
| Google 계정 연동 정보 | 로그아웃 또는 앱 삭제 시 | Google Sign-In 세션 해제 |

앱을 삭제하면 기기에 저장된 데이터는 일반적으로 함께 삭제됩니다.  
Google Drive에 저장된 백업은 별도로 삭제하지 않으면 유지될 수 있습니다.

---

## 5. 제3자 제공 및 처리 위탁

앱 운영자는 이용자의 개인정보를 **외부에 판매하지 않습니다**.

다만 아래 서비스 이용 시 해당 사업자가 정보를 처리할 수 있습니다.

| 수탁·제공 대상 | 제공 목적 | 제공 정보 |
|----------------|-----------|-----------|
| Google LLC (AdMob) | 광고 게재 | 광고 ID, 기기 정보 등 (Google 정책에 따름) |
| Google LLC (Sign-In, Drive) | 로그인·백업 | 계정 정보, 백업 JSON |

---

## 6. 이용자의 권리

이용자는 다음을 요청할 수 있습니다.

- Google Drive 백업 파일 삭제 (Google Drive 또는 앱 복원 후 덮어쓰기)
- Google 계정 연동 해제 (설정 → 로그아웃)
- 앱 삭제를 통한 기기 내 데이터 삭제
- 광고 맞춤설정 관리 (기기 OS 설정 또는 [Google 광고 설정](https://adssettings.google.com))

앱 자체 서버가 없으므로, **기기에 저장된 데이터에 대한 문의**는 아래 연락처로 해 주시면 안내해 드립니다.

---

## 7. 아동의 개인정보

앱은 만 14세 미만 아동을 대상으로 하지 않으며, 아동으로부터 고의로 개인정보를 수집하지 않습니다.

---

## 8. 개인정보의 안전성 확보

- 체크리스트 데이터는 기기 내부 SQLite 데이터베이스에 저장됩니다.
- Google Drive 백업은 Google 계정 인증 후 **앱 전용 App Data 폴더**에만 저장됩니다.
- 백업 JSON에는 체크리스트 데이터만 포함되며, 별도의 비밀번호·주민등록번호 등은 수집하지 않습니다.

---

## 9. 개인정보처리방침의 변경

법령 또는 서비스 변경에 따라 본 방침이 수정될 수 있습니다.  
변경 시 앱 또는 본 문서 URL을 통해 공지하며, **시행일**을 갱신합니다.

---

## 10. 문의

개인정보 처리와 관련한 문의·불만·열람 요청은 아래로 연락해 주세요.

| 항목 | 내용 |
|------|------|
| **운영자** | *sonagiya* |
| **이메일** | *sonagiya@gmail.com* |
| **앱** | 간단 체크! (`com.ssona.simplecheck`) |

---

## English Summary (Privacy Policy)

**App**: Simple Check (`com.ssona.simplecheck`)  
**Effective**: June 2, 2026

- Core checklist features work **offline** on your device.
- We store checklist titles, completion records, and app settings **locally** on your device. We do not operate a backend server for this data.
- **Optional Google Sign-In / Backup**: If you choose backup, checklist data is stored in your Google Drive App Data folder (`simple_check_backup.json`). Scope: `drive.appdata` only.
- **Ads (Google AdMob)**: Non‑premium users may see banner ads; Google may collect advertising identifiers and related data per [Google's policies](https://policies.google.com/privacy).
- We do **not** sell personal data. Contact: *(sonagiya@gmail.com)*.
