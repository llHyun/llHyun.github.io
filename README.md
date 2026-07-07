<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>이도현 | 백엔드 개발자 포트폴리오</title>
    <link href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard/dist/web/static/pretendard.css" rel="stylesheet">
    <style>
        body { font-family: 'Pretendard', sans-serif; background-color: #f4f6f9; color: #333; margin: 0; padding: 0; line-height: 1.6; word-break: keep-all; }
        .container { max-width: 900px; margin: 40px auto; background: #fff; padding: 50px; border-radius: 12px; box-shadow: 0 10px 30px rgba(0,0,0,0.05); }
        header { text-align: center; margin-bottom: 50px; padding-bottom: 30px; border-bottom: 2px solid #f0f2f5; }
        h1 { font-size: 2.8rem; margin: 0 0 10px 0; color: #1a1a1a; letter-spacing: -1px; }
        .subtitle { font-size: 1.2rem; color: #0d6efd; font-weight: 700; margin-bottom: 20px; letter-spacing: 1px; }
        .contact-info { font-size: 0.95rem; color: #555; display: flex; justify-content: center; gap: 10px; flex-wrap: wrap; }
        .contact-info span { background: #f8f9fa; padding: 6px 14px; border-radius: 20px; font-weight: 500; border: 1px solid #e9ecef; }
        .contact-info a { color: inherit; text-decoration: none; }
        .contact-info a:hover { text-decoration: underline; color: #0d6efd; }
        .section-title { font-size: 1.5rem; font-weight: 700; color: #2c3e50; border-left: 5px solid #0d6efd; padding-left: 15px; margin: 50px 0 25px 0; }
        .tech-group { margin-bottom: 25px; }
        .tech-group h3 { font-size: 1.1rem; color: #495057; margin-bottom: 12px; font-weight: 600; }
        .badge { display: inline-block; padding: 6px 14px; background-color: #f8f9fa; color: #495057; border-radius: 6px; font-size: 0.9rem; margin: 0 6px 10px 0; font-weight: 500; border: 1px solid #dee2e6; }
        .badge.main { background-color: #e7f1ff; color: #0d6efd; border-color: #b6d4fe; }
        .project-card { border: 1px solid #e9ecef; border-radius: 10px; padding: 35px; margin-bottom: 30px; }
        .project-header { display: flex; justify-content: space-between; align-items: center; margin-bottom: 15px; flex-wrap: wrap; gap: 10px; border-bottom: 1px solid #f0f2f5; padding-bottom: 15px; }
        .project-title { font-size: 1.4rem; font-weight: 700; color: #212529; margin: 0; }
        .project-meta { font-size: 0.95rem; color: #6c757d; font-weight: 500; text-align: right; }
        .project-stack { margin-bottom: 25px; }
        .project-stack .badge { font-size: 0.8rem; padding: 4px 10px; border-radius: 4px; background-color: #f1f3f5; }
        .roles { background: #f8f9fa; padding: 20px 20px 20px 40px; border-radius: 8px; margin-bottom: 30px; }
        .roles li { margin-bottom: 8px; color: #495057; }
        .ts-title { font-size: 1.1rem; font-weight: 700; color: #212529; margin-bottom: 15px; }
        .ts-grid { display: grid; grid-template-columns: 1fr; gap: 12px; margin-bottom: 25px; }
        .ts-item { background: #fff; border: 1px solid #e9ecef; border-left: 4px solid #adb5bd; padding: 16px; border-radius: 6px; }
        .ts-item.problem { border-left-color: #dc3545; background-color: #fff5f5; }
        .ts-item.solution { border-left-color: #198754; background-color: #f6fff9; }
        .ts-item.result { border-left-color: #0d6efd; background-color: #f5f9ff; }
        .ts-item strong { display: block; margin-bottom: 8px; font-size: 0.85rem; color: #495057; font-weight: 700; }
        .review-box { background: #f8f9fa; padding: 20px; border-radius: 8px; color: #495057; border: 1px solid #e9ecef; margin-top: 20px; font-size: 0.95rem; font-style: italic; }
        @media (max-width: 768px) {
            .container { padding: 30px 20px; margin: 20px; }
            .project-header { flex-direction: column; align-items: flex-start; }
            .project-meta { text-align: left; }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>이도현</h1>
            <div class="subtitle">BACKEND DEVELOPER PORTFOLIO</div>
            <div class="contact-info">
                <span>2001.06.25</span>
                <span>010-7527-0485</span>
                <span>dl1844@naver.com</span>
                <span><a href="https://github.com/IlHyun" target="_blank">GitHub: github.com/IlHyun</a></span>
                <span><a href="https://velog.io/@hyun_ll" target="_blank">Velog: velog.io/@hyun_ll</a></span>
            </div>
        </header>

        <section>
            <h2 class="section-title">TECH STACK</h2>
            <div class="tech-group">
                <h3>주력 기술</h3>
                <span class="badge main">Java</span>
                <span class="badge main">Spring Boot</span>
                <span class="badge main">MySQL (RDS 활용)</span>
                <span class="badge main">AWS (EC2, RDS, S3, Lambda)</span>
                <span class="badge main">Docker (컨테이너 배포 경험)</span>
                <span class="badge main">Redis (토큰 캐싱 적용)</span>
                <span class="badge main">Git (팀 협업 버전 관리)</span>
            </div>
            <div class="tech-group">
                <h3>기타 언어 & 프레임워크</h3>
                <span class="badge">C#/C/C++ (코드 해석 및 작성 가능)</span>
                <span class="badge">Python (FastAPI 코드 해석 가능)</span>
                <span class="badge">React (바이브코딩/코드 해석)</span>
                <span class="badge">Flutter (바이브코딩/코드 해석)</span>
            </div>
        </section>

        <section>
            <h2 class="section-title">PROJECTS</h2>
            
            <!-- Project 01 -->
            <div class="project-card">
                <div class="project-header">
                    <h3 class="project-title">비문을 이용한 반려동물 확인 서비스</h3>
                    <div class="project-meta">
                        25.06-25.09<br>3인 팀 프로젝트
                    </div>
                </div>
                <div class="project-stack">
                    <span class="badge">Flutter</span> <span class="badge">Spring Boot</span> <span class="badge">EC2</span> <span class="badge">RDS</span> <span class="badge">S3</span> <span class="badge">Lambda</span> <span class="badge">Redis</span> <span class="badge">YOLOV8</span>
                </div>
                <ul class="roles">
                    <li>Spring Boot 기반 REST API 설계 및 구현 (반려동물 등록·인증)</li>
                    <li>사용자-반려동물 관계 기반 DB 구조 설계 및 도메인 구성</li>
                    <li>EC2-RDS-S3-Lambda 클라우드 인프라 구성</li>
                    <li>OAuth 기반 소셜 로그인 구현 (구글·카카오·네이버)</li>
                    <li>AWS S3 Presigned URL 연동 파일 업로드 구현</li>
                    <li>Git 기반 협업 환경 코드 관리 및 기획 문서화</li>
                </ul>

                <div class="ts-title">💡 TROUBLE SHOOTING 1. 인프라 구조 개선</div>
                <div class="ts-grid">
                    <div class="ts-item problem">
                        <strong>문제 발견</strong>
                        EC2 단일 서버에 Spring + MySQL + Redis 배포 시 프리티어 메모리 한계 초과로 서비스 중단 발생
                    </div>
                    <div class="ts-item solution">
                        <strong>해결 과정</strong>
                        RDS(MySQL)와 ElastiCache(Redis)를 분리 도입하여 EC2 인스턴스 메모리 부하를 외부 서비스로 분산
                    </div>
                    <div class="ts-item result">
                        <strong>결과</strong>
                        프리티어 t2.micro 인스턴스에서도 안정적인 서비스 구동 달성
                    </div>
                </div>

                <div class="ts-title">💡 TROUBLE SHOOTING 2. 이미지 저장 구조 개선</div>
                <div class="ts-grid">
                    <div class="ts-item problem">
                        <strong>문제 발견</strong>
                        MySQL에 이미지 Binary 직접 저장 시 응답 지연 및 DB 용량 급증 문제 발생
                    </div>
                    <div class="ts-item solution">
                        <strong>해결 과정</strong>
                        프론트에서 S3에 직접 업로드 후 Presigned URL만 백엔드 DB에 저장하는 구조로 개선
                    </div>
                    <div class="ts-item result">
                        <strong>결과</strong>
                        이미지 입출력 속도 향상 및 DB 메모리 절약 달성
                    </div>
                </div>
            </div>

            <!-- Project 02 -->
            <div class="project-card">
                <div class="project-header">
                    <h3 class="project-title">TSP 기반 여행 경로 최적화 서비스</h3>
                    <div class="project-meta">
                        25.06-25.09<br>개인 프로젝트
                    </div>
                </div>
                <div class="project-stack">
                    <span class="badge">Python</span> <span class="badge">FastAPI</span> <span class="badge">Kakao Maps API</span> <span class="badge">React</span> <span class="badge">OSMnx</span> <span class="badge">Scikit-learn</span>
                </div>
                <ul class="roles">
                    <li>OSMnx 기반 실제 도로망 데이터를 활용한 TSP 알고리즘 적용</li>
                    <li>직선 거리가 아닌 실거리 기준 최적 방문 순서 계산 로직 구현</li>
                    <li>장소 밀집도 기반 여행 일정 자동 분할 로직 구현</li>
                    <li>Kakao Maps API 활용 경로 시각화 기능 구현</li>
                    <li>과도한 부가 옵션으로 인한 탐색 정확도 저하를 핵심 기능 위주 코드 간소화로 해결하여 정확도 향상</li>
                </ul>

                <div class="ts-title">💡 TROUBLE SHOOTING. 연박 동선 최적화</div>
                <div class="ts-grid">
                    <div class="ts-item problem">
                        <strong>문제 발견</strong>
                        연박 일정 시 숙소 기준으로 일정 분할하면 다음 날 동선이 지그재그로 꼬이는 문제 발생
                    </div>
                    <div class="ts-item solution">
                        <strong>해결 과정</strong>
                        각도(방향) 기준 탐색 알고리즘 도입으로 진행 방향을 고려한 순서로 장소 배치
                    </div>
                    <div class="ts-item result">
                        <strong>결과</strong>
                        지그재그 이동이 해소되어 효율적인 원형 동선으로 재구성
                    </div>
                </div>
            </div>

            <!-- Project 03 -->
            <div class="project-card">
                <div class="project-header">
                    <h3 class="project-title">음성인식 및 OCR 기반 컴퓨터 제어 프로그램</h3>
                    <div class="project-meta">
                        23.12-24.02<br>5인 팀 프로젝트 (PM)
                    </div>
                </div>
                <div class="project-stack">
                    <span class="badge">C#</span> <span class="badge">Python</span> <span class="badge">Node.js</span> <span class="badge">Google OCR API</span> <span class="badge">MySQL</span> <span class="badge">Azure STT API</span>
                </div>
                <ul class="roles">
                    <li>프로그램 전체 동작 구조 및 실행 흐름 설계</li>
                    <li>OCR 실행 및 화면 요소 선택·클릭 로직 구현</li>
                    <li>사용자별 맞춤형 음성-단축키 매핑 기능 구현</li>
                    <li>PM으로 일정 관리, 역할 분배 및 개발 진행 조율</li>
                    <li>STT 잡음 인식으로 인한 API 과호출 현상을 데시벨 기준 적용으로 호출량 감소시켜 해결</li>
                </ul>
                
                <div class="review-box">
                    <strong>배운 점</strong><br>
                    첫 팀 프로젝트인 만큼 트러블슈팅이라기보다 막히는 부분이 더 많았지만, 그 과정에서 함께 고민하고 풀어나가는 협업의 재미를 처음으로 느낀 프로젝트였습니다. 프로그램의 전체 구조를 먼저 설계했지만, 기능을 하나씩 붙여갈수록 초기 설계에서 고려하지 못한 부분들이 드러나며 복잡도가 점점 높아지는 경험을 했습니다. 이를 통해 초기 아키텍처를 얼마나 탄탄하게 잡느냐가 이후 개발 전체에 영향을 미친다는 것을 직접 체감할 수 있었습니다.
                </div>
            </div>
        </section>
    </div>
</body>
</html>
