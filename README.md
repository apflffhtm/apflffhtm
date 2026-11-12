<!-- ───────────────────────────── HEADER ───────────────────────────── -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0c0909,55:5a1414,100:d73232&height=240&section=header&text=shxn&fontSize=86&fontColor=f6eded&fontAlignY=36&desc=%2F%2F%20secure%20by%20design%2C%20built%20for%20users&descSize=18&descAlignY=58&animation=fadeIn" width="100%" alt="shxn" />

<a href="https://shxn.dev">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2800&pause=900&color=D73232&center=true&vCenter=true&width=620&lines=Developer+%2B+Cyber+Security;Security+Researcher+%C2%B7+CVE+Hunter;Web+Developer+%C2%B7+Node.js+%2F+Next.js;ZeroDay+%40+Youngju+High+School" alt="typing" />
</a>

<h3>서비스를 만들고, 취약점을 발견합니다.</h3>

<sub>직접 부딪히며 배우고 경험으로 성장하고 있습니다. 작은 기능 하나도 이해하고 제 것으로 만들려고 합니다.</sub>

<br/><br/>

<a href="https://shxn.dev"><img src="https://img.shields.io/badge/shxn.dev-D73232?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
<a href="https://shxn.dev/blog"><img src="https://img.shields.io/badge/Blog-1A1212?style=for-the-badge&logo=rss&logoColor=D73232" /></a>
<a href="mailto:me@shxn.dev"><img src="https://img.shields.io/badge/me@shxn.dev-1A1212?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxwYXRoIGQ9Ik00IDRoMTZjMS4xIDAgMiAuOSAyIDJ2MTJjMCAxLjEtLjkgMi0yIDJINGMtMS4xIDAtMi0uOS0yLTJWNmMwLTEuMS45LTIgMi0yeiIvPjxwb2x5bGluZSBwb2ludHM9IjIyLDYgMTIsMTMgMiw2Ii8%2BPC9zdmc%2B" /></a>
<a href="https://www.tiktok.com/@dev.code10"><img src="https://img.shields.io/badge/@dev.code10-1A1212?style=for-the-badge&logo=tiktok&logoColor=white" /></a>
<a href="https://www.tiktok.com/@cyber.secu"><img src="https://img.shields.io/badge/@cyber.secu-1A1212?style=for-the-badge&logo=tiktok&logoColor=D73232" /></a>

<br/>

<img src="https://img.shields.io/badge/CVE-5-D73232?style=flat-square&labelColor=0C0909" />
<img src="https://img.shields.io/badge/GHSA-1-D73232?style=flat-square&labelColor=0C0909" />
<img src="https://img.shields.io/badge/Awards-10-D73232?style=flat-square&labelColor=0C0909" />
<img src="https://img.shields.io/badge/Team-ZeroDay-D73232?style=flat-square&labelColor=0C0909" />
<img src="https://komarev.com/ghpvc/?username=apflffhtm&label=Views&color=d73232&style=flat-square&labelColor=0c0909" />

</div>

<br/>

<!-- ───────────────────────────── WHOAMI ───────────────────────────── -->

## `// whoami`

```text
┌──(shxn㉿zeroday)-[~/portfolio]
└─$ whoami --verbose

  handle       shxn
  alias        elba.code  ·  dev.code10
  role         Web Developer  +  Security Researcher
  team         영주고등학교 정보보안팀 ZeroDay
  lead         DevCREW 웹 개발팀 Founder / Team Lead  (≈30명 · 8팀)
  based        Jeju, South Korea
  focus        Web Security · Access Control · Pentest · Full-stack Web
  license      정보기기운용기능사 (국가기술자격)
  motto        "secure by design, built for users"

└─$ _
```

<br/>

<!-- ───────────────────────────── SECURITY ───────────────────────────── -->

## `// 01. Security Research`

> WordPress 플러그인과 오픈소스 라이브러리에서 직접 찾아 제보한 취약점들입니다.

| ID | Target | Type | Impact | Date |
| :-- | :-- | :-- | :-- | :--: |
| [**CVE-2026-124418**](https://patchstack.com/database/wordpress/plugin/wp-job-portal/vulnerability/wordpress-wp-job-portal-plugin-2-7-2-cross-site-scripting-xss-vulnerability) | WP Job Portal `≤ 2.7.2` | Stored XSS | 구독자가 삽입한 스크립트가 관리자 브라우저에서 실행 | 2026.11 |
| [**CVE-2026-124417**](https://patchstack.com/database/wordpress/plugin/wp-job-portal/vulnerability/wordpress-wp-job-portal-plugin-2-7-2-broken-access-control-vulnerability-3) | WP Job Portal `≤ 2.7.2` | Broken Access Control | 다른 사용자의 비공개 정보 열람·수정 | 2026.11 |
| [**CVE-2026-121575**](https://patchstack.com/database/wordpress/plugin/wp-user-manager/vulnerability/wordpress-wp-user-manager-plugin-2-10-4-broken-access-control-vulnerability) | WP User Manager `≤ 2.10.4` | Broken Access Control | 미결제 사용자가 제한 콘텐츠 열람 | 2026.11 |
| [**CVE-2026-52708**](https://patchstack.com/database/wordpress/plugin/wp-user-frontend/vulnerability/wordpress-wp-user-frontend-plugin-4-3-13-broken-access-control-vulnerability-2) | WP User Frontend `≤ 4.3.13` | Broken Access Control | 결제 없이 유료 구독 활성화 | 2026.10 |
| [**CVE-2026-25450**](https://patchstack.com/database/wordpress/plugin/user-registration/vulnerability/wordpress-user-registration-plugin-5-3-0-broken-access-control-vulnerability) | User Registration `≤ 5.3.0` | Broken Access Control | 비로그인 사용자가 결제 금액 조작 | 2026.10 |
| [**GHSA-37g9-w4hg-h9qr**](https://github.com/websockets/ws/security/advisories/GHSA-37g9-w4hg-h9qr) | Node.js `ws` | DoS | Ping 폭주로 메모리 고갈 + 빈 Ping을 이용한 초기 패치 우회 | — |

<br/>

<!-- ───────────────────────────── AWARDS ───────────────────────────── -->

## `// 02. Awards`

| Year | Competition | Result | Host |
| :--: | :-- | :-- | :-- |
| 2026 | **호남지역 정보보호 해커톤 대회** | 🏆 **대학/고등부 3위** · 한국인터넷진흥원 원장상 | 과학기술정보통신부 |
| 2026 | **제61회 전국기능경기대회** · 사이버보안 | 🏆 **전국 6위** · 장려상 | 한국산업인력공단 |
| 2026 | **사이버공격방어대회** | **11위** | 국가정보원 / 국가보안기술연구소 |
| 2026 | **사이버 가디언즈 CMX** | **본선 진출** · 23위 (11,471pt) | 과학기술정보통신부 / KISIA |
| 2026 | **GEEKs Hackathon 2026** | 🏆 **프론트엔드 1인 특별상** | 키키랩 |

<details>
<summary><b>전체 수상 보기 (10)</b></summary>
<br/>

| Year | Competition | Result | Host |
| :--: | :-- | :-- | :-- |
| 2026 | **창의 지식재산(IP) 컨퍼런스** | 🏆 **우수 논문상** | 제주대학교 IP 중심대학 사업단 |
| 2026 | **지방기능경기대회** · 사이버보안 | 🏆 **3위** | 한국산업인력공단 |
| 2026 | **제3회 국제 창의 AI드론 경진대회** | 🏆 **우수상** | 국제e모빌리티엑스포 |
| 2026 | **UNICON CTF** | **중등부 5위** | 선린인터넷고등학교 |
| 2025 | **제주 AI 유스 페스티벌** | 🏆 **장려상** | 제주특별자치도 |

> 📄 우수 논문 — *스마트 팜 보안 고도화를 위한 AI 기반 농지 침입 패턴 분석 및 위험 사전 예측 모델 구현*

</details>

<br/>

<!-- ───────────────────────────── PROJECTS ───────────────────────────── -->

## `// 03. Projects`

<table>
<tr>
<td width="50%" valign="top">

### 🔐 [HackByte](https://hackbyte.kr)
<sub>조코딩 × OpenAI × Primer AI 해커톤</sub>

AI가 사용자 맞춤형 CTF 문제와 강좌를 만들어 주는 정보보안 학습 플랫폼.

<img src="https://img.shields.io/badge/Node.js-1A1212?style=flat-square&logo=nodedotjs&logoColor=5FA04E" />
<img src="https://img.shields.io/badge/EJS-1A1212?style=flat-square&logo=ejs&logoColor=white" />
<img src="https://img.shields.io/badge/OpenAI_API-1A1212?style=flat-square&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-1A1212?style=flat-square&logo=mysql&logoColor=4479A1" />

</td>
<td width="50%" valign="top">

### 🏫 [영주 알리뮈](https://youngju-hs.com)
<sub>제주 영주고등학교 교내 정보 자동화</sub>

급식표·시간표·학사일정을 인스타그램 계정과 웹사이트로 자동 발행하는 완전 자동화 시스템.

<img src="https://img.shields.io/badge/Node.js-1A1212?style=flat-square&logo=nodedotjs&logoColor=5FA04E" />
<img src="https://img.shields.io/badge/Instagram_Graph_API-1A1212?style=flat-square&logo=instagram&logoColor=E4405F" />
<img src="https://img.shields.io/badge/OpenAI_API-1A1212?style=flat-square&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-1A1212?style=flat-square&logo=mysql&logoColor=4479A1" />

</td>
</tr>
</table>

<br/>

<!-- ───────────────────────────── STACK ───────────────────────────── -->

## `// 04. Skill Stack`

<table>
<tr>
<td align="center" width="140"><b>Language</b></td>
<td><img src="https://skillicons.dev/icons?i=js,py,mysql&theme=dark" /></td>
</tr>
<tr>
<td align="center"><b>Frontend</b></td>
<td><img src="https://skillicons.dev/icons?i=nextjs,html,css&theme=dark" /></td>
</tr>
<tr>
<td align="center"><b>Backend</b></td>
<td><img src="https://skillicons.dev/icons?i=nodejs,express,redis&theme=dark" /></td>
</tr>
<tr>
<td align="center"><b>Infra</b></td>
<td><img src="https://skillicons.dev/icons?i=linux,docker&theme=dark" /></td>
</tr>
<tr>
<td align="center"><b>Arsenal</b></td>
<td>
<img src="https://img.shields.io/badge/Kali_Linux-D73232?style=for-the-badge&logo=kalilinux&logoColor=white" />
<img src="https://img.shields.io/badge/Burp_Suite-D73232?style=for-the-badge&logo=burpsuite&logoColor=white" />
<img src="https://img.shields.io/badge/Wireshark-D73232?style=for-the-badge&logo=wireshark&logoColor=white" />
<img src="https://img.shields.io/badge/Packet_Tracer-D73232?style=for-the-badge&logo=cisco&logoColor=white" />
</td>
</tr>
<tr>
<td align="center"><b>Mindset</b></td>
<td><code>입력 검증</code> &nbsp; <code>권한 처리</code> &nbsp; <code>로그 분석</code> &nbsp; <code>취약점 분석</code></td>
</tr>
</table>

<br/>

<!-- ───────────────────────────── TIMELINE ───────────────────────────── -->

## `// 05. Timeline`

```yaml
2026.11:  CVE-2026-124418 · CVE-2026-124417 · CVE-2026-121575 발급
          호남지역 정보보호 해커톤 — 대학/고등부 3위 (KISA 원장상)
          JOIN 2026 제주지역창업페스티벌
2026.10:  CVE-2026-52708 · CVE-2026-25450 발급
2026.09:  Cyber Summit Korea 2026
2026.08:  제61회 전국기능경기대회 사이버보안 — 6위 장려상
          사이버공격방어대회 — 11위
```

<details>
<summary><b>전체 타임라인 보기 (26)</b></summary>

```yaml
2026.08:  사이버 가디언즈 CMX — 예선 통과
          GEEKs Hackathon 2026 — 프론트엔드 1인 특별상
2026.07:  창의 지식재산(IP) 컨퍼런스 — 우수 논문상
          국가기술자격 정보기기운용기능사 — 취득
2026.05:  IT 네트워크 시스템 기초 기술 교육 (SAMSUNG | GIFTS) — 수료
2026.04:  DevCREW 웹 개발팀 운영 — Founder / Team Lead
          지방기능경기대회 사이버보안 — 3위
2026.03:  제3회 국제 창의 AI드론 경진대회 — 우수상
          영주고등학교 정보보안팀 ZeroDay 합류
          보안의 첫 걸음
2026.02:  조코딩 × OpenAI × Primer AI 해커톤 — HackByte 개발
2026.01:  UNICON CTF — 중등부 5위
2025.12:  제주 AI 유스 페스티벌 — 장려상
2024.12:  2024 제주 웹 컨퍼런스
2024.04:  2024 제주 AI 컨퍼런스
2023.06:  웹 개발의 첫 걸음
```

</details>

<br/>

<!-- ───────────────────────────── CONTACT ───────────────────────────── -->

## `// 06. Contact`

<div align="center">

**프로젝트 협업, 대회 참여 및 기타 문의를 언제든지 환영합니다.**

<a href="mailto:me@shxn.dev"><img src="https://img.shields.io/badge/me@shxn.dev-D73232?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxwYXRoIGQ9Ik00IDRoMTZjMS4xIDAgMiAuOSAyIDJ2MTJjMCAxLjEtLjkgMi0yIDJINGMtMS4xIDAtMi0uOS0yLTJWNmMwLTEuMS45LTIgMi0yeiIvPjxwb2x5bGluZSBwb2ludHM9IjIyLDYgMTIsMTMgMiw2Ii8%2BPC9zdmc%2B" /></a>
<a href="mailto:cyber@shxn.dev"><img src="https://img.shields.io/badge/cyber@shxn.dev-1A1212?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSJ3aGl0ZSIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiIHN0cm9rZS1saW5lam9pbj0icm91bmQiPjxwYXRoIGQ9Ik00IDRoMTZjMS4xIDAgMiAuOSAyIDJ2MTJjMCAxLjEtLjkgMi0yIDJINGMtMS4xIDAtMi0uOS0yLTJWNmMwLTEuMS45LTIgMi0yeiIvPjxwb2x5bGluZSBwb2ludHM9IjIyLDYgMTIsMTMgMiw2Ii8%2BPC9zdmc%2B" /></a>
<a href="https://shxn.dev"><img src="https://img.shields.io/badge/Portfolio-1A1212?style=for-the-badge&logo=googlechrome&logoColor=D73232" /></a>

</div>

<!-- ───────────────────────────── FOOTER ───────────────────────────── -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:d73232,45:5a1414,100:0c0909&height=130&section=footer" width="100%" />

<div align="center"><sub><code>// 2026 shxn.dev</code></sub></div>
