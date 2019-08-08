# free-for.dev

개발자와 오픈 소스 작성자는 이제 무료 계층을 제공하는 방대한 서비스를 보유하고 있지만 정보에 입각한 결정을 내리기 위해 모든 계층을 찾기가 어려울 수 있습니다.

소프트웨어(SaaS, PaaS, IaaS 등) 및 개발자를위한 무료 계층이있는 기타 제품 목록입니다.

이 특정 목록의 범위는 인프라 개발자(System Administrator, DevOps Practitioners 등)가 유용할 수 있는 것으로 제한됩니다. 우리는 모든 무료 서비스를 좋아하지만 주제를 유지하는 것이 좋습니다. 때때로 약간의 회색 선이므로 약간의 의견이 있습니다. 당신의 기여를 받아들이지 않으면 기분이 상하지 않습니다.

이 목록은 500명 이상이 수행한 풀 요청(pull request), 검토, 아이디어 및 작업의 결과입니다. 풀 요청을 전송하여 더 많은 서비스를 추가하거나 오퍼링이 변경되거나 폐기 된 서비스를 제거하면 도움이 될 수 있습니다.

GitHub 또는 전용 웹 사이트 [free-for.dev](free-for.dev)에서 목록을 찾을 수 있습니다.

참고 : 이 목록은 자체 호스팅 소프트웨어가 아닌 서비스 제공 서비스에만 해당됩니다. 서비스를 받으려면 무료 평가판이 아닌 무료 등급을 제공해야합니다. 프리 티어에 시간이 걸리는 경우 최소 1년 이상이어야합니다.

## 목차

- [주요 클라우드 제공 업체의 무상 한도](##주요-클라우드-제공-업체)
- 분석, 이벤트 및 통계
- API, 데이터 및 ML
- 유물 보관소
- 자동화 된 브라우저 테스트
- BaaS
- CDN 및 보호
- CI / CD
- 코드 품질
- 코드 검색 및 브라우징
- 충돌 및 예외 처리
- 지도상의 데이터 시각화
- DBaaS
- 디자인과 UI
- DNS
- 도커 관련
- 이메일
- IaaS
- IDE 및 코드 편집
- 국제 휴대폰 번호 확인 API 및 SDK
- 이슈 트래킹 및 프로젝트 관리
- 로그 관리
- 관리 시스템
- 여러 가지 잡다한
- 모니터링
- 기타 무료 자료
- PaaS
- 패키지 빌드 시스템
- 결제 / 청구 통합
- 수색
- 보안 및 PKI
- 소스 코드 저장소
- 저장 및 미디어 처리
- STUN, WebRTC, 웹 소켓 서버 및 기타 라우터
- 팀과 협업을위한 도구
- 번역 관리
- 유랑 관련
- 방문자 세션 기록
- 웹 호스팅 

## 주요 클라우드 제공 업체

### 구글 클라우드 플랫폼
        App Engine-하루 28 개의 프런트 엔드 인스턴스 시간, 하루에 9 개의 백엔드 인스턴스 시간
        Cloud Firestore-1GB 스토리지, 50,000 회 읽기, 20,000 회 쓰기, 20,000 회 삭제
        Compute Engine-1 개의 비선 점형 f1-micro, 30GB HDD, 5GB 스냅 샷 스토리지 (특정 지역으로 제한됨)
        클라우드 스토리지-5GB, 1GB 네트워크 송신
        Cloud Pub / Sub-한 달에 10GB의 메시지
        클라우드 함수-한 달에 2 백만 건의 호출 (백그라운드 및 HTTP 호출 모두 포함)
        Google Kubernetes Engine-모든 규모의 클러스터에 대한 클러스터 관리 수수료가 없습니다. 각 사용자 노드는 표준 Compute Engine 요금으로 청구됩니다
        BigQuery-매월 1TB의 쿼리, 매월 10GB의 스토리지
        클라우드 빌드-하루 120 분
        클라우드 소스 리포지토리-최대 5 명의 사용자, 50GB 스토리지, 50GB 송신
        자세한 전체 목록-https: //cloud.google.com/free/docs/gcp-free-tier#always-free-usage-limits 

### 아마존 웹 서비스
        Amazon DynamoDB-25GB NoSQL DB
        Amazon Lambda-매월 1 백만 건의 요청
        Amazon SNS-한 달에 1 백만 건의 게시
        Amazon Cloudwatch-10 개의 사용자 지정 지표 및 10 개의 경보
        Amazon Glacier-10GB 장기 객체 스토리지
        Amazon SQS-100 만 개의 메시징 대기열 요청
        Amazon CodeBuild-매월 100 분의 빌드 시간
        Amazon Code Commit-한 달에 5 명의 활성 사용자
        Amazon Code Pipeline-한 달에 1 개의 활성 파이프 라인
        자세한 전체 목록-https: //aws.amazon.com/free/ ? awsf.Free%20Tier%20Types=categories%23alwaysfree 

### Microsoft Azure
        앱 서비스-10 개의 웹, 모바일 또는 API 앱
        기능-한달에 백만 건의 요청
        DevTest Labs-빠르고 쉬운 린 개발 테스트 환경 지원
        Active Directory-500,000 개의 개체
        Active Directory B2C-월별 50,000 명의 저장된 사용자
        Azure DevOps-5 명의 활성 사용자
        Microsoft IoT Hub-매일 8,000 개의 메시지
        로드 밸런서-1 개의 무료 퍼블릭로드 밸런싱 IP (VIP)
        알림 허브-백만 개의 푸시 알림
        대역폭-월 5GB 송신
        비주얼 스튜디오 코드
        자세한 전체 목록-https: //azure.microsoft.com/en-us/free/ 

소스 코드 저장소

    github.com — 무제한 공개 리포지토리 및 무제한 개인 리포지토리 (최대 3 명)
    bitbucket.org — CI / CD 용 파이프 라인을 사용하여 최대 5 명의 사용자를위한 무제한 공개 및 비공개 리포지토리 (Git 및 Mercurial)
    gitlab.com — 무제한 공동 작업자와 무제한 공용 및 개인 Git 리포지토리
    chiselapp.com — 무제한 공공 및 민간 화석 저장소
    Azure DevOps — 최대 5 명의 사용자 / 팀을위한 무제한 개인 저장소 (Git 및 TFS)
    plasticscm.com — 개인, OSS 및 비영리 단체에 무료
    codebasehq.com — 100MB의 공간과 2 명의 사용자를 가진 하나의 무료 프로젝트
    NotABug — NotABug.org는 Git 기반의 무료 라이센스 프로젝트를위한 자유 소프트웨어 코드 협업 플랫폼입니다
    perforce.com — 무료 1GB 클라우드 및 Git, Mercurial 또는 SVN 리포지토리.
    projectlocker.com — 50MB의 공간이있는 하나의 무료 개인 프로젝트 (Git 및 Subversion)
    ionicframework.com -Ionic으로 응용 프로그램을 개발하기위한 Repo 및 도구
    gitea.com- 무제한 공개 및 비공개 Git 저장소
    codeberg.org- 무제한 공개 및 비공개 Git 저장소 

API, 데이터 및 ML

    ProxyCrawl — 프록시, 인프라 또는 브라우저없이 웹 사이트를 크롤링하고 긁습니다. 보안 문자를 해결하고 차단되지 않도록합니다. 처음 1000 개의 통화는 무료입니다.
    ScrapingNinja — 한곳에서 JS 렌더링, Chrome 헤드리스, 프록시 로테이션 및 보안 문자 해결을 모두 처리합니다. 처음 1000 개는 무료이며 신용 카드가 필요하지 않습니다.
    ApiFlash — Aws Lambda 및 Chrome을 기반으로하는 스크린 샷 API입니다. 전체 페이지, 캡처 타이밍, 뷰포트 크기 등을 처리합니다.
    스크레이퍼 API — 클라우드 기반 웹 스크랩 핑 API는 프록시, 브라우저 및 보안 문자를 처리합니다. 간단한 API 호출로 웹 페이지를 긁어보십시오. 한 달에 1000 번의 무료 API 호출을 시작하십시오.
    dreamfactory.com — 모바일, 웹 및 IoT 애플리케이션을위한 오픈 소스 REST API 백엔드. 모든 SQL / NoSQL 데이터베이스, 파일 스토리지 시스템 또는 외부 서비스를 연결하면 실시간 문서, 사용자 관리 등을 통해 포괄적 인 REST API 플랫폼을 즉시 생성 할 수 있습니다.
    monkeylearn.com — 기계 학습을 통한 텍스트 분석, 월 300 회 무료 쿼리
    wit.ai — 개발자를위한 NLP
    wolfram.com — 클라우드에 내장 된 지식 기반 알고리즘
    parsehub.com — 동적 사이트에서 데이터를 추출하고 동적 웹 사이트를 API로 변환
    wrapapi.com — 웹 사이트를 매개 변수화 된 API로 바꾸 십시오. 한 달에 30k API 호출
    algorithmia.com — 무료 호스트 알고리즘. 알고리즘 실행에 대한 월별 무료 수당이 포함됩니다. 이제 CLI 지원
    bigml.com — 호스팅 된 머신 러닝 알고리즘. 개발을위한 무제한 무료 작업, 16MB 데이터 / 작업 제한
    konghq.com/ — API 마켓 플레이스 및 프라이빗 및 퍼블릭 API를위한 강력한 도구. 프리 티어를 사용하면 모니터링, 경고 및 지원과 같은 일부 기능이 제한됩니다
    dominodatalab.com — Python, R, Spark, Hadoop, Matlab 및 기타를 지원하는 데이터 과학
    restlet.com — APISpark를 통해 모든 API, 애플리케이션 또는 데이터 소유자가 직관적 인 브라우저 인터페이스를 통해 몇 분 안에 API 제공자가 될 수 있습니다
    scrapinghub.com — 비주얼 인터페이스 및 플러그인으로 데이터 스크래핑. 무료 요금제는 공유 서버에서 무제한 스크래핑을 포함합니다
    Apify — 웹 사이트 데이터를 추출하는 API를 생성 할 수있는 웹 스크래핑 및 자동화 플랫폼입니다. 월간 크롤링 횟수가 10 일이고 데이터 보존 기간이 7 일인 프리 티어입니다.
    Diggernaut — 웹 사이트를 데이터 세트로 전환하거나 API와 같이 작업하기위한 클라우드 기반 웹 스크래핑 및 데이터 추출 플랫폼. 무료 요금제에는 월 5K 페이지 요청이 포함됩니다.
    협업 — Nvidia Tesla K80 GPU가 포함 된 무료 웹 기반 Python 노트북 환경.
    tamber — 앱에 심층 학습 기반 권장 사항을 넣습니다. 5K 월간 활성 사용자 무료.
    Ipgeolocation — IP Geolocation API-한 달에 5 만 건의 요청이있는 개발자를위한 무료 플랜입니다.
    RequestBin.com — HTTP 요청을 보낼 수있는 무료 엔드 포인트를 만듭니다. 해당 엔드 포인트로 전송 된 모든 HTTP 요청은 관련 페이로드 및 헤더와 함께 기록되므로 웹 후크 및 기타 서비스의 요청을 관찰 할 수 있습니다.
    MailboxValidator — 실제 메일 서버 연결을 사용하여 유효한 이메일을 확인하는 이메일 확인 서비스입니다. 무료 API 계획은 한 달에 300 번의 검증을받습니다.
    IP2Location — Freemium IP 지리적 위치 서비스입니다. LITE 데이터베이스는 무료로 다운로드 할 수 있습니다. 서버에서 데이터베이스를 가져오고 로컬 쿼리를 수행하여 도시, 좌표 및 ISP 정보를 결정하십시오.
    FraudLabs Pro — 신용 카드 결제 사기에 대한 주문 거래를 선별 합니다. 이 REST API는 주문의 입력 매개 변수를 기반으로 가능한 모든 사기 특성을 감지합니다. 무료 마이크로 요금제에는 한 달에 500 건의 거래가 있습니다.
    IPList — Geo IP 정보, 주소, 호스트 이름 및 ASN 세부 정보와 같은 모든 IP 주소에 대한 조회 세부 정보입니다. 개인 및 비즈니스 사용자에게는 무료입니다.
    IPTrace — 비즈니스에 안정적이고 유용한 IP 위치 정보를 제공하는 매우 간단한 API입니다. 

유물 보관소

    bintray.com — JFrog Bintray는 무료로 오픈 소스 프로젝트를 호스팅하고 Docker, Maven, NuGet, npm, Debian, RPM, Conan, Vagrant, Opkg, yum을 지원 하며 JCenter 의 가장 포괄적 인 Maven 아티팩트 모음을 지원합니다.
    central.sonatype.org — Apache Maven, SBT 및 기타 빌드 시스템의 기본 아티팩트 저장소.
    packagecloud.io — Maven, RPM, DEB, PyPi 및 RubyGem 패키지에 사용하기 쉬운 리포지토리 호스팅 (프리 티어 있음).
    cloudsmith.io — Java / Maven, RedHat, Debian, Python, Ruby, Vagrant + more를위한 단순하고 안전한 중앙 집중식 저장소 서비스입니다. 프리 티어 + 오픈 소스 무료.
    jitpack.io — GitHub의 JVM 및 Android 프로젝트를위한 Maven 저장소이며, 공개 프로젝트는 무료입니다. 

팀과 협업을위한 도구

    scinote.net — 과학적 데이터 관리 및 팀 협업. 무제한의 사용자, 백업 및 1GB의 저장 공간을 갖춘 하나의 팀
    appear.in — 한 번의 클릭으로 비디오 대화를 무료로
    meet.jit.si — 한 번의 클릭으로 비디오 대화, 화면 공유, 무료
    flowdock.com — 채팅 및받은 편지함, 최대 5 명까지 팀 무료
    slack.com — 일부 기능 제한이있는 무제한 사용자에게는 무료
    gitter.im — GitHub를위한 채팅. 무제한 공용 및 개인 실, 최대 25 명까지 팀 무료
    불일치 — 공개 / 개인 실 및 VoIP 서비스와 채팅합니다. 무제한 사용자에게는 무료입니다.
    hangouts.google.com — 무료로 모든 대화를위한 한 곳에서 Google 계정이 필요합니다.
    seafile.com — 개인 또는 클라우드 스토리지, 파일 공유, 동기화, 토론. 개인용 버전이 가득 찼습니다. 클라우드 버전은 1GB입니다.
    yammer.com — 개인 소셜 네트워크 독립형 또는 MS Office 365 용. 관리 도구 및 사용자 관리 기능이 약간 적은 무료
    helpmonks.com — 팀을위한 공유받은 편지함, 오픈 소스 및 비영리 단체를위한 무료
    typetalk.com — 웹 또는 모바일에서 인스턴트 메시징을 통해 팀과 아이디어를 공유하고 토론
    talky.io — 무료 그룹 영상 채팅. 익명. 피어 투 피어. 플러그인, 가입 또는 결제 불필요
    helplightning.com — 증강 현실로 비디오를 통해 도움을줍니다. 분석, 암호화, 지원없이 무료
    evernote.com — 정보 구성 도구. 메모를 공유하고 다른 사람들과 협력
    doodle.com — 실제로 사용할 예약 도구입니다. 회의 날짜가 두 배 더 빠릅니다.
    zoom.us — 보안 비디오 및 웹 회의, 추가 기능 제공. 40 분 무료
    ideascale.com — 고객이 한 커뮤니티에서 25 명의 회원에게 아이디어를 제출하고 투표 할 수 있도록 허용
    wistia.com — 방문자 분석, 25 개의 비디오 및 Wistia 브랜드 플레이어를 이해하는 데 도움이되는 뷰어 분석, HD 비디오 전송 및 마케팅 도구를 갖춘 비디오 호스팅
    flock.com — 팀 이보다 빠르게 커뮤니케이션 할 수 있습니다. 무료 무제한 메시지, 채널, 사용자, 앱 및 통합
    이글루 — 문서, 블로그 및 캘린더 등을 공유하기위한 내부 포털. 최대 10 명의 사용자에게 무료로 제공됩니다.
    riot.im — Matrix에 구축 된 분산 커뮤니케이션 도구입니다. 그룹 채팅, 다이렉트 메시징, 암호화 된 파일 전송, 음성 및 화상 채팅 및 다른 서비스와의 쉬운 통합.
    Microsoft Teams — Microsoft Teams는 대화 기반의 디지털 허브로서 대화, 콘텐츠 및 앱을 한 곳에서 한 곳에서 하나로 통합 할 수 있습니다. 최대 300 명의 사용자에게 무료로 제공됩니다. 

코드 품질

    tachikoma.io — Ruby, Node.js, Perl 프로젝트에 대한 종속성 업데이트, 무료 오픈 소스
    landscape.io — Python 프로젝트를위한 코드 품질, 무료 오픈 소스
    codeclimate.com — 자동화 된 코드 검토로, 오픈 소스 및 무제한 조직 소유 개인 저장소 (최대 4 명)가 무료입니다. 학생 및 기관에도 무료입니다.
    houndci.com — GitHub에 대한 의견은 코드 품질에 대해 커밋하며 오픈 소스 무료
    coveralls.io — 오픈 소스에 대해 무료로 테스트 범위 보고서를 표시합니다
    scrutinizer-ci.com — 지속적인 검사 플랫폼, 무료 오픈 소스
    codecov.io — 코드 커버리지 도구 (SaaS), 무료 오픈 소스 및 무료 개인 저장소 1 개
    insight.sensiolabs.com — PHP / Symfony 프로젝트의 코드 품질, 오픈 소스 무료
    codacy.com — PHP, Python, Ruby, Java, JavaScript, Scala, CSS 및 CoffeeScript에 대한 자동화 된 코드 검토, 무제한 공개 및 비공개 저장소 무료
    gocover.io — 모든 Go 패키지의 코드 범위
    goreportcard.com — Go 프로젝트의 코드 품질, 오픈 소스 무료
    scan.coverity.com — Java, C / C ++, C # 및 JavaScript에 대한 정적 코드 분석, 무료 오픈 소스
    webceo.com — SEO 도구이지만 코드 확인 및 다양한 유형의 조언
    zoompf.com — 웹 사이트의 성능, 상세 분석을 수정
    gtmetrix.com — 웹 사이트 최적화를위한 보고서 및 철저한 권장 사항
    browserling.com — 1024 x 768 해상도의 Vista에서 MS IE 9를 사용하여 3 분 동안 만 무료 대화 형 브라우저 간 테스트
    shields.io — 오픈 소스 프로젝트를위한 품질 메타 데이터 배지
    beanstalkapp.com — 코드 작성, 검토 및 배포를위한 완벽한 워크 플로), 100MB의 스토리지가있는 1 명의 사용자 및 1 개의 저장소 무료 계정
    testanywhere.co — 웹 사이트 또는 웹앱을 지속적으로 자동 테스트하고 초기 단계에서 버그를 발견하며 매월 1,000 회 무료 테스트
    gerrithub.io — 무료 GitHub 리포지토리에 대한 Gerrit 코드 검토
    reviewable.io — GitHub 리포지토리의 코드 검토, 공개 또는 개인 리포지토리 무료
    sonarcloud.io — Java, JavaScript, C / C ++, C #, VB.NET, PHP, Objective-C, Swift, Python, Groovy 및 더 많은 언어에 대한 자동화 된 소스 코드 분석, 무료 오픈 소스
    golangci.com — GitHub 풀 요청에 대한 자동화 된 Go (golang) 코드 검토 서비스입니다.
    lgtm.com — Java, Python, JavaScript, TypeScript, C #, C 및 C ++에 대한 지속적인 보안 분석, 무료 오픈 소스 

코드 검색 및 브라우징

    codota.com — Codota는 전 세계의 모든 코드에서 얻은 통찰력을 제공하여 개발자가 더 나은 소프트웨어를 더 빠르게 만들도록 도와줍니다. 사용 가능한 플러그인.
    library.io — 32 개의 서로 다른 패키지 관리자에 대한 검색 및 종속성 업데이트 알림, 무료 오픈 소스
    sourcegraph.com — Java, Go, Python, Node.js 등, 코드 검색 / 상호 참조, 무료 오픈 소스
    searchcode.com — 포괄적 인 텍스트 기반 코드 검색, 무료 오픈 소스 

CI / CD

    ligurio / awesome-ci — 지속적인 통합 서비스 비교
    Azure Pipelines — Linux, macOS 및 Windows 용 오픈 소스를위한 무제한 분으로 10 개의 무료 병렬 작업
    codefresh.io — 평생 무료 플랜 : 빌드 1 개, 환경 1 개, 공유 서버, 무제한 공용 저장소
    codeship.com — 월 100 건의 개인 빌드, 5 건의 프라이빗 프로젝트, 오픈 소스 무제한
    circleci.com — 하나의 동시 빌드에 대해 무료
    stackahoy.io — 100 % 무료입니다. 무제한 배포, 분기 및 빌드
    travis-ci.org — 공개 GitHub 리포지토리 무료
    semaphoreci.com — 오픈 소스 무료, 매월 100 건의 개인 빌드
    shippable.com — 한 달에 150 번의 개인 빌드, 1 번의 빌드 컨테이너, 개인 및 공용 저장소에 대해 무료
    appveyor.com — Windows 용 CD 서비스, 오픈 소스 용 무료
    deployhq.com — 매일 10 번 배포하는 프로젝트 1 개 (월 30 회 빌드 분)
    styleci.io — 공개 GitHub 리포지토리 만
    buddybuild.com — 하나의 원활한 반복 시스템에서 iOS 및 Android 앱에 대한 피드백을 구축, 배포 및 수집
    gitlab.com — GitLab의 CI 서비스를 사용하여 Git 리포지토리에서 직접 파이프 라인을 생성합니다. 2,000 분 / 월
    buddy.works — 5 개의 무료 프로젝트와 1 개의 동시 실행이있는 CI / CD (매월 120 회 실행)
    bitrise.io — 기본 또는 하이브리드 모바일 앱용 CI / CD입니다. 200 회의 무료 빌드 / 월 10 분의 빌드 시간과 두 명의 팀원. OSS 프로젝트는 45 분의 빌드 시간, +1의 동시성 및 무제한 팀 규모를 갖습니다. 

자동화 된 브라우저 테스트

    gridlastic.com — 최대 4 개의 동시 셀레늄 노드를 무료로 계획하여 Selenium Grid 테스트 / 10 그리드 시작 / 4,000 테스트 분 / 월
    saucelabs.com — 크로스 브라우저 테스트, 셀레늄 테스트 및 모바일 테스트, 오픈 소스 무료
    browserstack.com — 수동 및 자동 브라우저 테스트, 무료 오픈 소스
    everystep-automation.com — 웹 브라우저에서 수행 된 모든 단계를 기록 및 재생하고 적은 옵션으로 무료로 스크립트를 만듭니다.
    Applitools.com — 웹, 기본 모바일 및 데스크탑 앱을위한 스마트 한 시각적 검증. 거의 모든 자동화 솔루션 (예 : Selenium 및 Karma) 및 원격 러너 (Sauce Labs, Browser Stack)와 통합됩니다. 오픈 소스 무료. 주당 검사 점이 제한된 단일 사용자를위한 프리 티어입니다.
    checkbot.io — 웹 사이트가 50 개 이상의 SEO, 속도 및 보안 모범 사례를 따르는 지 테스트하는 브라우저 확장입니다. 소규모 웹 사이트를위한 프리 티어 

보안 및 PKI

    pyup.io — 보안 취약점에 대한 Python 의존성을 모니터링하고 자동으로 업데이트합니다. 하나의 개인 프로젝트에는 무료이며 오픈 소스에는 무제한 프로젝트가 있습니다.
    threatconnect.com — 위협 인텔리전스 : 사이버 위협 인텔리전스에 대해 배우기 시작한 개별 연구원, 분석가 및 조직을 위해 설계되었습니다. 최대 3 명의 사용자 무료
    crypteron.com — 클라우드 우선 개발자 친화적 인 보안 플랫폼으로 .NET 및 Java 애플리케이션에서 데이터 유출 방지
    snyk.io — Snyk가 패키지에서 몇 가지 취약점을 발견하여보고했습니다. 1 개의 개인 프로젝트로 제한 (오픈 소스 프로젝트에는 제한이 없음)
    letsencrypt.org — 모든 주요 브라우저에서 신뢰할 수있는 인증서가있는 무료 SSL 인증 기관
    globalsign.com — 오픈 소스를위한 무료 SSL 인증서
    Okta — 사용자 관리, 인증 및 권한 부여. 최대 1000 명의 월간 활성 사용자에게 무료입니다.
    auth0.com — 개발 SSO를 위해 무료로 호스팅됩니다. 비공개 소스 프로젝트를위한 최대 2 개의 소셜 아이덴티티 공급자.
    ringcaptcha.com — 전화 번호를 ID로 사용하여 무료로 제공되는 도구
    ssllabs.com — SSL 웹 서버 구성에 대한 매우 심층 분석
    qualys.com — 웹 앱 취약점 찾기, OWASP 위험 감사
    alienvault.com — 네트워크에서 손상된 시스템을 발견
    duo.com — 웹 사이트 또는 앱용 2 단계 인증 (2FA). 무료 10 명의 사용자, 모든 인증 방법, 무제한, 통합, 하드웨어 토큰
    tinfoilsecurity.com — 자동화 된 취약점 검색. 무료 계획은 매주 XSS 스캔을 허용합니다
    ponycheckup.com — Django 웹 사이트를위한 자동화 된 보안 점검 도구
    foxpass.com — 호스팅 된 LDAP 및 RADIUS. 서버, VPN 및 무선 네트워크에 사용자별로 쉽게 로그인 할 수 있습니다. 10 명 무료
    opswat.com — 컴퓨터, 장치, 응용 프로그램, 구성 등의 보안 모니터링 ... 무료 25 명의 사용자와 30 일의 기록
    bitninja.io — 블랙리스트를 통한 봇넷 보호, 무료 계획은 각 공격에 대한 제한된 정보 만보고 합니다
    onelogin.com — IDaaS ( Identity as a Service), 싱글 사인온 아이덴티티 공급자, Cloud SSO IdP, 3 개의 회사 앱 및 5 개의 개인 앱, 무제한 사용자
    logintc.com — 푸시 알림을 통한 2 단계 인증 (2FA), 10 명의 사용자에게 무료, VPN, 웹 사이트 및 SSH
    report-uri.io — CSP 및 HPKP 위반보고
    cloudsploit.com — AWS (Amazon Web Services) 보안 및 규정 준수 감사 및 모니터링
    내가 전당 했습니까? — 위반에 대한 정보를 가져 오기위한 REST API.
    Internet.nl — IPv6, DNSSEC, HTTPS, DMARC, STARTTLS 및 DANE와 같은 최신 인터넷 표준 테스트
    Mozilla Observatory — 사이트의 보안 취약점을 찾아 수정하십시오.
    Shieldfy — 웹 애플리케이션 방화벽 및 개발자를위한 취약성 탐지, 한 달에 최대 100k 요청을 무료로 계획합니다. 

관리 시스템

    bitnami.com — IaaS에 준비된 앱을 배포합니다. 1 개의 AWS 마이크로 인스턴스 무료 관리
    jamf.com — iPad, iPhone 및 Mac의 장치 관리, 3 개의 장치 무료 

로그 관리

    bugfender.com — 24 시간 보존으로 최대 하루에 최대 100k 로그 라인 확보
    humio.com — 7 일 보존으로 최대 2GB / 일 무료
    logentries.com — 7 일 보존으로 최대 5GB / 월 무료
    loggly.com — 단일 사용자에게는 무료입니다. lite 옵션 참조
    logz.io — 최대 1GB / 일, 3 일 보존
    papertrailapp.com — 48 시간 검색, 7 일 보관, 100MB / 월
    rollbar.com — 최대 5000 개의 이벤트 / 월, 30 일 보존
    sematext.com — 최대 500MB / 일, 7 일 보존
    sumologic.com — 최대 500MB / 일, 7 일 보존 

번역 관리

    lingohub.com — 최대 3 명의 사용자 무료, 오픈 소스의 경우 항상 무료
    webtranslateit.com — 최대 500 개의 문자열 무료
    transifex.com — 오픈 소스 무료
    oneskyapp.com — 최대 5 명의 사용자를위한 한정판 무료 버전, 오픈 소스 용 무료
    crowdin.com — 오픈 소스를위한 무제한 프로젝트, 무제한 문자열 및 공동 작업자
    Loco — 최대 2000 개의 번역, 무제한 번역가, 10 개의 언어 / 프로젝트, 1000 개의 번역 가능한 자산 / 프로젝트 무료 

모니터링

    cloudsploit.com — AWS 보안 및 구성 모니터링. 무료 : 주문형 검색 무제한, 무제한 사용자, 무제한 저장 계정. 구독 : 자동 스캔, API 액세스 등
    elastic.co — JS 개발자를위한 즉각적인 성능 통찰력. 24 시간 데이터 보존 무료
    appneta.com — 1 시간의 데이터 보존 무료
    thousandeyes.com — 네트워크 및 사용자 경험 모니터링. 주요 웹 서비스의 3 개 위치 및 20 개의 데이터 피드 무료
    datadoghq.com — 최대 5 개의 노드에 대해 무료
    freshworks.com — 무료로 전 세계 위치 10 개 및 공개 상태 페이지 5 개로 1 분 간격으로 50 개의 URL을 모니터링합니다.
    nodequery.com — 최대 10 대의 서버까지 무료 기본 서버 모니터
    circonus.com — 20 개 메트릭에 대해 무료
    uptimerobot.com — 웹 사이트 모니터링, 50 개의 모니터 무료
    statuscake.com — 웹 사이트 모니터링, 제한이없는 무제한 테스트 무료
    bmc.com — 최대 10 대의 서버에 대해 1 초 무료 제공
    ghostinspector.com — 무료 웹 사이트 및 웹 응용 프로그램 모니터링. 단일 사용자, 매월 100 회 테스트 실행
    sematext.com — 24 시간 통계, 무제한 서버 수, 10 개의 사용자 정의 지표, 500,000 개의 사용자 정의 지표 데이터 포인트, 무제한 대시 보드, 사용자 등 무료
    stathat.com — 무료 통계 10 개 시작, 만료 없음
    skylight.io — 처음 100,000 개의 요청에 대해 무료입니다 (레일 전용)
    appdynamics.com — 24 시간 동안 무료로 제공되며 애플리케이션 성능 관리 에이전트는 Java, .NET, PHP 및 Node.js로 제한됩니다.
    deadmanssnitch.com — 크론 작업 모니터링. 1 개의 무료 스 니치 (모니터)
    librato.com — 60 초 해상도에서 최대 100 개의 메트릭을 해제
    freeboard.io — 공개 프로젝트에 무료입니다. 사물 인터넷 (IoT) 프로젝트를위한 대시 보드
    loader.io — 제한이있는 무료로드 테스트 도구
    speedchecker.xyz — 성능 모니터링 API, Ping, DNS 등 확인
    blackfire.io — Blackfire는 SaaS 제공 애플리케이션 성능 솔루션입니다. 무료 해커 플랜 (PHP 만 해당)
    apimetrics.io — 자동화 된 API 성능 모니터링, 테스트 및 분석. 무료 계획, 수동으로 API 호출 및 West Coast 서버에서 실행
    opsdash.com — 자체 호스팅 서버, 클러스터 및 서비스 모니터링, 5 대의 서버 및 5 개의 서비스에 대해 무료
    healthchecks.io — cron 작업 및 백그라운드 작업을 모니터링합니다. 최대 20 개의 수표를 무료로 제공합니다.
    appbeat.io — 웹 사이트 모니터링, 3 개의 모니터 무료. 매우 안정적이고 저렴한 모니터 서비스를 제공합니다.
    assertible.com — 자동화 된 API 테스트 및 모니터링. 팀과 개인을위한 무료 요금제.
    opsgenie.com — 상시 작동 서비스를위한 강력한 경고 및 통화 관리. 최대 5 명의 사용자를 확보하십시오.
    paessler.com — 경고, 강력한 시각화 기능 및 기본보고를 포함한 강력한 인프라 및 네트워크 모니터링 솔루션. 최대 100 개의 센서를 확보하십시오.
    pagertree.com- 경고 및 통화 관리를위한 간단한 인터페이스. 최대 5 명의 사용자를 확보하십시오. 

충돌 및 예외 처리

    rollbar.com — 예외 및 오류 모니터링, 5,000 오류 / 월 무료 플랜, 무제한 사용자, 30 일 보존
    bugsnag.com — 최초 평가판 이후 월 최대 2,000 오류에 대해 무료
    sentry.io — Sentry는 앱 예외를 실시간으로 추적하고 작은 무료 요금제를 가지고 있습니다. 자체 호스팅하는 경우 무료로 무제한 사용 

수색

    algolia.com — 호스팅 검색 유형 (인스턴트). 무료 해커는 최대 10,000 개의 문서와 100,000 개의 작업을 계획합니다. 커뮤니티 / 오픈 소스 프로젝트에 사용할 수있는 더 큰 무료 플랜
    swiftype.com — 호스팅 검색 솔루션 (API 및 크롤러). 최대 1,000 개의 문서가있는 단일 검색 엔진에 대해 무료입니다. 오픈 소스를위한 프리미엄 레벨 무료 업그레이드
    bonsai.io — 무료 1GB 메모리 및 1GB 스토리지
    searchly.com — 무료 2 지수 및 5 MB 저장 용량
    cloudsh.com — 몇 줄의 JavaScript로 웹 사이트를 강력하게 검색합니다. 300 개의 문서가 포함 된 무료 개인 요금제. 최대 10,000 개의 문서를 오픈 소스에 무료로 제공 

이메일

    mailinator.com — 원하는받은 편지함을 사용할 수있는 무료 공개 이메일 시스템
    cloudmersive.com — 개발자를위한 이메일 검증 및 검증 API, 월 10,000 회의 무료 API 요청
    sparkpost.com — 최초 15,000 개 이메일 / 월 무료
    mailgun.com — 최초 10,000 개 이메일 / 월 무료
    tinyletter.com — 가입자 5,000 명 / 월 무료
    mailchimp.com — 가입자 2,000 명과 월 12,000 개의 이메일
    sendgrid.com — 하루에 100 개 이메일 및 2,000 개 연락처 무료
    phplist.com — 호스팅 된 버전은 300 이메일 / 월 무료 허용
    MailerLite.com — 월 1,000 구독자, 무제한 이메일 무료
    mailjet.com — 6,000 개 이메일 / 월 무료
    sendinblue.com — 9,000 개 이메일 / 월 무료
    mailtrap.io — 개발 용 가짜 SMTP 서버,받은 편지함 1 개, 메시지 50 개, 팀원 없음, 초당 2 개의 이메일, 전달 규칙 없음
    zoho.com — 최대 25 명의 사용자를위한 무료 이메일 관리 및 협업
    Yandex.Connect — 최대 1,000 명의 사용자를위한 무료 이메일 및 DNS 호스팅
    moosend.com — 메일 링리스트 관리 서비스. 스타트 업을위한 6 개월 무료 계정
    debugmail.io — 개발자를위한 사용하기 쉬운 테스트 메일 서버
    mailboxlayer.com — 개발자를위한 이메일 검증 및 검증 JSON API. 월 1,000 회 무료 API 요청
    mailcatcher.me — 메일을 잡아 웹 인터페이스를 통해 제공합니다
    yopmail.fr — 일회용 이메일 주소
    kickbox.io — 100 개의 이메일을 무료로 실시간 API 확인 가능
    inumbo.com — SMTP 기반 스팸 필터, 10 명의 사용자에게 무료
    biz.mail.ru — DNS 호스팅을 통해 사용자 지정 도메인 당 25GB 씩 5,000 개의 사서함
    sendpulse.com — 시간당 50 개 이메일, 처음 12,000 개 이메일 / 월 무료
    pepipost.com — 첫 달에 30k 개의 이메일을 무료로 제공 한 다음 첫 100 개의 이메일을 무료로 제공합니다
    elasticemail.com — 하루에 100 개의 무료 이메일. API를 통해 $ 0.09의 이메일 1,000 개 (가상 결제)
    mail-tester.com — 이메일의 dns / spf / dkim / dmarc 설정이 올바른지 테스트합니다 (20 회 무료 / 월)
    migadu.com — 이메일 호스팅 (웹 메일, SMTP, IMAP, ...) — 무료 플랜은 하루에 10 개의 발신 메일로 제한됩니다
    socketlabs.com- 첫 달에 40k 이메일, 그 다음 첫 2000 이메일 / 월 무료
    postmarkapp.com -100 개 이메일 / 월 무료, 무제한 DMARC 주간 요약 

CDN 및 보호

    cloudflare.com — 기본 서비스는 무료이며 블로그에 적합하며 무료 SSL 인증서 서비스와 5 개의 방화벽 규칙도 제공합니다.
    bootstrapcdn.com — 부트 스트랩, 부트 워치 및 fontawesome.io 용 CDN
    cdnjs.com — JavaScript 라이브러리, CSS 라이브러리, SWF, 이미지 등을위한 CDN
    jsdelivr.com — 개발자 및 웹 마스터를위한 OSS의 CDN (JS, CSS, 글꼴), PRs를 통해 추가
    raw.githack.com — Clouflare 를 사용하여 단순히 파일을 호스팅하는 rawgit.com 의 현대적인 대체품
    developers.google.com — Google 호스팅 라이브러리는 가장 인기있는 오픈 소스 JavaScript 라이브러리를위한 콘텐츠 배포 네트워크입니다.
    Microsoft Ajax — Microsoft Ajax CDN은 jQuery와 같은 널리 사용되는 타사 JavaScript 라이브러리를 호스팅하며 웹 응용 프로그램에 쉽게 추가 할 수 있습니다.
    toranproxy.com — Packagist 및 GitHub 용 프록시. CD를 절대로 실패하지 마십시오. 개인용 무료, 개발자 1 명, 지원 없음
    웹 지원 혁명 -무료 CDN, 백업, 방화벽, 바이러스 백신 및 모니터링.
    section.io — 완전한 Varnish Cache 솔루션을 시작하고 관리하는 간단한 방법입니다. 한 사이트에서 영원히 무료로 제공
    netdepot.com — 최초 100GB 무료 / 월
    speeder.io — KeyCDN을 사용합니다. 자동 이미지 최적화 및 무료 CDN 부스트. 무료이며 서버 변경이 필요하지 않습니다
    jare.io — 이미지의 CDN입니다. AWS CloudFront 사용
    unpkg.com — npm의 모든 것을위한 CDN
    staticaly.com — Git 저장소 (GitHub, GitLab, Bitbucket), WordPress 관련 자산 및 이미지 용 CDN
    bitmitigate.com — 무료 CDN 및 DDoS 보호 

PaaS

    engineyard.com — Engine Yard는 500 시간의 무료 시간을 제공합니다
    appharbor.com — 1 명의 무료 작업자를 제공하는 .Net PaaS
    heroku.com — 클라우드에서 앱을 호스팅하고 단일 프로세스 앱에 대해 무료
    firebase.google.com — 실시간 앱 구축, 무료 요금제는 최대 100 개의 연결, 10GB 데이터 전송, 1GB 데이터 저장소, 1GB 호스팅 저장소 및 10GB 호스팅 전송
    IBM Cloud — 월별 무료 수당이있는 IBM PaaS
    outsystems.com — 온 프레미스 또는 클라우드를위한 엔터프라이즈 웹 개발 PaaS, 무료 "개인 환경"제공으로 무제한 코드 및 최대 1GB 데이터베이스 가능
    scn.sap.com — SAP의 인 메모리 Platform-as-a-Service 오퍼링. 무료 개발자 계정에는 1GB 구조화, 1GB 비 구조화, 1GB의 Git 데이터가 제공되며 HTML5, Java 및 HANA XS 앱을 실행할 수 있습니다
    mendix.com — 엔터프라이즈를위한 신속한 애플리케이션 개발, 각각 10 명의 사용자, 100MB의 파일 및 100MB의 데이터베이스 스토리지를 지원하는 무제한 무료 샌드 박스 환경
    pythonanywhere.com — Cloud Python 앱 호스팅. 초보자 계정은 무료이며 your-username.pythonanywhere.com 도메인의 Python 웹 애플리케이션 1 개, 512MB 개인 파일 스토리지, 하나의 MySQL 데이터베이스
    configure.it — 2 개의 프로젝트에 대해 무료이며 기능이 제한적이지만 리소스 제한이없는 모바일 앱 개발 플랫폼
    zeit.co/now — Node.js, 정적 사이트 및 Docker 배포를위한 관리 플랫폼. OSS 프로젝트를위한 동시 인스턴스 3 개, 스토리지 1GB 및 대역폭 1GB로 제한 (소스 파일은 공개 URL에 노출됨)
    sandstorm.io — Sandstorm은 개인 및 개인 클라우드를위한 오픈 소스 운영 체제입니다. 200MB의 스토리지와 5 개의 곡물을 무료로 제공하는 무료 요금제
    gearhost.com — .NET 및 PHP 앱용 플랫폼. 제한된 리소스를 가진 공유 서버에서 256MB의 RAM 무료 제공
    glitch.com — 코드 공유 및 실시간 협업과 같은 기능을 갖춘 무료 무제한 공개 / 비공개 호스팅
    gigalixir.com -Gigalixir는 Elixir / Phoenix 앱에 대해 휴면 상태가없는 1 개의 무료 인스턴스를 제공하고 프리 티어 PostgreSQL 데이터베이스는 2 개의 연결, 10, 000 개의 행 및 백업으로 제한됩니다. 

BaaS

    blockspring.com — 클라우드 기능. 500 만 회 / 월 무료
    progress.com — 모바일 백엔드, 초기 계획에는 초당 1GB의 데이터 저장 용량으로 무제한 요청이 있습니다. 엔터프라이즈 애플리케이션 지원
    backendless.com — 1GB의 파일 저장 공간이없는 모바일 및 웹 Baas, 50000 / 월의 푸시 알림 및 1000 개의 데이터 객체가 테이블에 있습니다.
    hasura.io — 단일 노드 클러스터에 대해 무료로 앱 백엔드를 빠르게 구축 및 배포하는 플랫폼입니다.
    pusher.com — 월간 활성 사용자 2000 명에 대한 무료 무제한 푸시 알림. iOS 및 Android 장치 용 단일 API
    layer.com — 커뮤니케이션을위한 풀 스택 빌딩 블록
    quickblox.com — 인스턴트 메시징, 비디오 및 음성 통화 및 푸시 알림을위한 통신 백엔드
    pushbots.com — 푸시 알림 서비스. 최대 150 만 회 / 월 무료
    onesignal.com — 무제한 무료 푸시 알림
    getstream.io — 몇 주가 아닌 몇 시간 내에 확장 가능한 뉴스 피드 및 활동 스트림을 작성하여 매월 3 백만 개의 피드 업데이트를 무료로 제공합니다.
    tyk.io — 인증, 할당량, 모니터링 및 분석을 통한 API 관리. 무료 클라우드 오퍼링
    iron.io — 프리 티어 및 1 개월 무료 평가판을 사용한 비동기 작업 처리 (AWS Lambda와 같은)
    nstack.com — AWS Lambda와 같은 비동기 작업 처리 10 개의 무료 개인 서비스 및 무제한의 무료 공공 서비스
    pubnub.com — 최대 1 백만 메시지 / 월 및 100 개의 활성 일일 장치에 대한 무료 푸시 알림
    pushtechnology.com — 브라우저, 스마트 폰 및 모든 사람을위한 실시간 메시징. 100 개의 동시 연결 무료 10GB 데이터 / 월
    zapier.com — 사용하는 앱을 연결하여 작업을 자동화합니다. 15 분마다 5 회, 한 달에 100 회
    stackstorm.com — 흐름, 액세스 제어, LDAP 등이없는 앱, 서비스 및 워크 플로우를위한 이벤트 중심 자동화 ...
    simperium.com — 구조화 된 데이터를 멀티 플랫폼으로 무제한 전송 및 저장하여 데이터를 즉각적이고 자동으로 어디서나 이동할 수 있습니다. 월 2,500 명의 사용자
    pushcrew.com — 푸시 알림 서비스. 최대 2000 명의 가입자에게 무제한 알림
    streamdata.io — 모든 REST API를 이벤트 중심 스트리밍 API로 바꿉니다 . 최대 1 백만 개의 메시지와 10 개의 동시 연결 무료 계획
    posthook.io — 작업 예약 서비스. 특정 시간에 대한 요청을 예약 할 수 있습니다. 500 건의 예약 요청 / 월 무료.
    paraio.com — 유연한 인증, 전체 텍스트 검색 및 캐싱을 갖춘 백엔드 서비스 API. 1 개의 앱, 1GB의 앱 데이터에 대해 무료입니다.
    remotemysql.com — 원격 MySQL 데이터베이스 호스팅, 설치가 즉시 완료되며 관리를 위해 phpMyAdmin을 사용하고, 100Mb 데이터, 무료 백업, 쿼리 제한 없음 및 99 % 가동 시간을 무료로 제공 

웹 호스팅

    pages.github.com — GitHub 리포지토리에서 직접 정적 사이트 호스팅
    sourceforge.net — 무료로 오픈 소스 소프트웨어를 찾아서 생성 및 게시
    devport.co — GitHub 프로젝트, 앱 및 웹 사이트를 개인 개발자 포트폴리오로 전환
    netlify.com — 100GB 데이터 및 100GB / 월 대역폭에 대해 무료로 정적 사이트 또는 앱을 빌드, 배포 및 호스팅
    sanity.io – React로 빌드 된 사용자 정의 가능한 MIT 라이센스 편집기로 구조화 된 컨텐츠를위한 호스팅 된 백엔드. 무제한 프로젝트. 프로젝트 당 3 명의 사용자, 2 개의 데이터 세트, 500k API CDN 요청, 5GB 자산 무료
    pantheon.io — Drupal 및 WordPress 호스팅, 자동화 된 DevOps 및 확장 가능한 인프라. 개발자 및 대행사 무료
    acquia.com — Drupal 사이트 호스팅. 개발자를위한 프리 티어. 무료 개발 도구 (예 : Acquia Dev Desktop)도 사용 가능
    readthedocs.org — 버전 관리, PDF 생성 등을 포함한 무료 문서 호스팅
    bubble.is — 코드없이 웹 및 모바일 앱을 구축하기위한 비주얼 프로그래밍, 월 100 방문자 무료, 2 개의 앱
    contentful.com — 서비스로서의 콘텐츠. 클라우드의 컨텐츠 관리 및 제공 API. 3 명의 사용자, 3 개의 저장소 및 100,000 개의 API 요청 / 월 무료
    tilda.cc — 하나의 사이트, 50 페이지, 50 MB 저장 공간, 170 개 이상의 사용 가능한 기본 미리 정의 된 블록 만, 글꼴 없음, 파비콘 없음 및 사용자 정의 도메인 없음
    surge.sh — 프론트 엔드 개발자를위한 정적 웹 출판. 맞춤 도메인 지원을 제공하는 무제한 사이트
    neocities.org — 200GB 대역폭의 정적 1GB 무료 스토리지.
    txti.es — 마크 다운을 사용하여 웹 페이지를 빠르게 만듭니다.
    opeNode.io — 오픈 소스 프로젝트를위한 무료 클라우드 호스팅.
    kuber.host — 무료 플랜으로 호스팅하는 Kubernetes
    cloudno.de — Node.js 앱을위한 무료 클라우드 호스팅.
    heliohost.org — 모두를위한 커뮤니티 기반 무료 호스팅. 

DNS

    freedns.afraid.org — 무료 DNS 호스팅
    dns.he.net — 동적 DNS를 지원하는 무료 DNS 호스팅 서비스
    luadns.com — 무료 DNS 호스팅, 3 개의 도메인, 합리적인 제한이있는 모든 기능
    Yandex.Connect — 최대 1,000 명의 사용자를위한 무료 이메일 및 DNS 호스팅
    selectel.com — 무료 DNS 호스팅, 애니 캐스트, 10 개 지역
    cloudns.net — 무제한 레코드로 최대 3 개의 도메인을 호스팅하는 무료 DNS
    ns1.com — 데이터 기반 DNS, 자동 트래픽 관리, 백만 개의 무료 쿼리
    zonewatcher.com — 자동 백업 및 DNS 변경 모니터링. 1 개의 도메인 무료
    namecheap.com — 무료 DNS. 도메인 수 제한 없음
    dynu.com — 무료 동적 DNS 서비스
    noip — 30 ​​일마다 확인을 통해 최대 3 개의 호스트 이름을 무료로 제공하는 동적 DNS 서비스
    freenom.com — 무료 도메인 제공 업체. FQDN을 무료로 받으십시오.
    duckdns.org — 프리 티어에서 최대 5 개의 도메인이있는 무료 DDNS. 다양한 설정을위한 구성 안내서 포함.
    1984.is — API가 포함 된 무료 DNS 서비스 및 기타 많은 무료 DNS 기능이 포함되어 있습니다.
    Cloudflare- 무료 DNS. 무제한 도메인 수.
    biz.mail.ru — 최대 5,000 명의 사용자를위한 무료 이메일 및 DNS 호스팅
    pointhq.com — Heroku에서 무료 DNS 호스팅.
    dnspod.com — 무료 DNS 호스팅.
    entrydns.net — 동적 DNS 지원을 통한 무료 DNS 호스팅 서비스.
    web.gratisdns.dk — 무료 DNS 호스팅. 

IaaS

    backblaze.com — Backblaze B2 클라우드 스토리지. 무제한 10 시간 동안 무료 10GB (Amazon S3 유사) 객체 스토리지 

DBaaS

    ibm.com — IBM에서 호스트 한 데이터베이스, 1GB 무료
    redislabs.com — 서비스로 Redis, 30MB 및 30 개의 동시 연결 무료
    redsmin.com — Redis, 1 Redis 인스턴스 무료 온라인 실시간 모니터링 및 관리 서비스
    graphstory.com — GraphStory는 서비스로서 Neo4j (그래프 데이터베이스)를 제공합니다
    elephantsql.com — PostgreSQL 서비스, 20MB 무료
    graphenedb.com — 서비스로서 Neo4j, 최대 1,000 개의 노드 및 10,000 개의 관계 무료
    MongoDB Atlas — 프리 티어에 512MB 제공
    scalingo.com — 주로 PaaS이지만 512MB의 프리 티어 MySQL, PostgreSQL 또는 MongoDB를 제공합니다
    skyvia.com — Cloud Data Platform, 프리 티어 제공 및 베타 기간 동안 모든 요금제 무료 제공
    airtable.com — 스프레드 시트처럼 보이지만 관계형 데이터베이스, 무제한 기본, 기본 행 1,200 개 및 월별 API 요청 1,000 개
    FaunaDB — FaunaDB는 분산, 다중 모델, ACID 호환 및 전 세계적으로 확장 가능한 데이터베이스이며 프리 티어는 5GB를 제공합니다 

STUN, WebRTC, 웹 소켓 서버 및 기타 라우터

    scaledrone.com — 푸시 메시징 서비스. 최대 20 개의 동시 연결 및 100,000 개의 메시지 / 일 무료
    pusher.com — 실시간 메시징 서비스. 최대 100 개의 동시 연결 및 200,000 개의 메시지 / 일 무료
    stun : stun.l.google.com : 19302 — Google STUN
    기절 : global.stun.twilio.com : 3478? transport = udp — Twilio STUN
    segment.com — 이벤트를 다른 타사 서비스로 번역하고 라우팅하는 허브. 100,000 이벤트 / 월 무료
    ngrok.com — 터널을 통해 로컬로 실행중인 서버를 공개 URL에 노출합니다.
    cloudamqp.com — 서비스로서의 RabbitMQ. 작은 여우 원숭이 계획 : 최대 백만 메시지 / 월, 최대 20 개의 동시 연결, 최대 100 개의 큐, 최대 10,000 개의 큐 메시지, 다른 AZ의 여러 노드
    serveo.net — SSH 터널을 사용하여 서보 하위 도메인의 공용 인터넷에 로컬 포트를 신속하게 노출합니다. HTTP를 통해 요청을 재생하는 SSH GUI가 포함되어 있습니다.
    ZeroTier — 서비스로 FOSS 관리 가상 이더넷. 무료 요금제로 100 개 클라이언트의 무제한 종단 간 암호화 네트워크. 데스크탑 / 모바일 / NA 용 클라이언트; 개인 네트워크에서 사용자 지정 라우팅 규칙 구성 및 새 클라이언트 노드 승인을위한 웹 인터페이스.
    Hamachi — LogMeIn Hamachi는 LAN과 같은 네트워크를 분산 된 팀으로 안전하게 확장 할 수있는 호스팅 VPN 서비스입니다. 최대 5 명까지 무제한 네트워크를 사용할 수 있습니다.
    webhookrelay.com — 모든 웹 후크 를 공용 또는 내부 (예 : localhost) 대상으로 관리, 디버그, 팬 아웃 및 프록시합니다. 또한 공개 HTTP 엔드 포인트 ( https://yoursubdomain.webrelay.io <----> http://localhost:8080 )를 가져와 터널을 통해 개인 네트워크에서 실행중인 서버를 노출 https://yoursubdomain.webrelay.io <----> http://localhost:8080 . 

이슈 트래킹 및 프로젝트 관리

    bitrix24.com — 무료 인트라넷 및 프로젝트 관리 도구
    pivotaltracker.com — Pivotal Tracker, 공개 프로젝트 무료
    kanbantool.com — Kanban 보드 기반 프로젝트 관리. 더 많은 옵션이있는 무료 유료 플랜
    kanbanflow.com — 보드 기반 프로젝트 관리. 더 많은 옵션이있는 무료 프리미엄 버전
    zenhub.io — GitHub 내부의 유일한 프로젝트 관리 솔루션입니다. 공공 리포지토리, OSS 및 비영리 단체에 무료
    trello.com — 보드 기반 프로젝트 관리. 비어 있는
    clickup.com — 프로젝트 관리. 클라우드 스토리지가있는 무료 프리미엄 버전. 모바일 애플리케이션 및 Git 통합 가능
    LeanBoard — GitHub 문제에 대한 스티커 메모가있는 협업 화이트 보드 (예제 매핑 및 기타 기술에 유용)
    huboard.com — GitHub 문제에 대한 즉각적인 프로젝트 관리, 무료 오픈 소스
    taiga.io — 스타트 업 및 민첩한 개발자를위한 프로젝트 관리 플랫폼, 무료 오픈 소스
    jetbrains.com — FOSS 프로젝트를위한 무료 호스팅 YouTrack (InCloud), 개인 프로젝트 (10 명의 사용자는 무료)
    github.com — Git 스토리지 기능 외에도 GitHub는 기본적인 문제 추적 기능을 제공합니다
    asana.com — 공동 작업자와의 비공개 프로젝트 무료
    acunote.com — 최대 5 명의 팀원을위한 무료 프로젝트 관리 및 SCRUM 소프트웨어
    gliffy.com — 온라인 다이어그램 : 플로우 차트, UML, 와이어 프레임 등 ... Jira 및 Confluence 용 플러그인. 5 개의 다이어그램과 2MB의 여유 공간
    cacoo.com — 실시간 온라인 다이어그램 : 플로우 차트, UML, 네트워크. 최대 무료 15 명 /도, 25 매
    draw.io — Google 드라이브, OneDrive 또는 Dropbox에 로컬로 저장된 온라인 다이어그램. 모든 기능 및 스토리지 수준에 대해 무료
    Azure DevOps — 무제한 무료 개인 코드 리포지토리; 버그, 작업 항목, 피드백 등을 추적
    testlio.com — 문제 추적, 테스트 관리 및 베타 테스트 플랫폼. 개인용 무료
    vivifyscrum.com — 애자일 프로젝트 관리를위한 무료 도구입니다. 스크럼 호환
    targetprocess.com — Kanban 및 Scrum에서 거의 모든 운영 프로세스에 이르는 시각적 프로젝트 관리. 무제한 사용자, 최대 1,000 개의 데이터 엔터티 무료 { 자세한 내용 }
    taskulu.com — 역할 기반 프로젝트 관리. 최대 5 명의 사용자를 확보하십시오. GitHub / Trello / Dropbox / Google Drive와 통합
    contriber.com — 사용자 정의 가능한 프로젝트 관리 플랫폼, 무료 시작 계획, 5 개의 작업 공간
    planitpoker.com — 무료 온라인 플래닝 포커 (예상 도구)
    ubertesters.com — 테스트 플랫폼, 통합 및 크라우드 테스터, 2 프로젝트, 5 회원
    jetbrains.com — 시간 추적, Agile Board의 첨부 파일 및 기타 여러 개선 사항을 기반으로 검색합니다. 10 명의 사용자 5GB 무료
    plan.io — 리포지토리 호스팅 및 mor 옵션을 사용한 프로젝트 관리. 10 명의 고객과 500MB의 스토리지를 보유한 2 명의 사용자에게 무료
    taskade.com — 팀을위한 실시간 협업 작업 목록 및 개요
    zenkit.com — 프로젝트 관리 및 협업 도구. 최대 5 명의 회원, 5GB의 첨부 파일을 무료로 제공합니다.
    Instabug — 모바일 앱을위한 포괄적 인 버그보고 및 인앱 피드백 SDK입니다. 최대 1 개의 앱과 1 개의 멤버까지 무료 플랜.
    Office 365 개발자 — 개발 / 테스트를위한 1 년 무료 Office 365 E3 구독.
    senseitool.com — 민첩한 회고 도구-무료.
    Gitlab- 프로젝트에 대한 기본 이슈 추적을 제공합니다. 

저장 및 미디어 처리

    redbooth.com — P2P 파일 동기화, 최대 2 명의 사용자 무료
    cloudinary.com — 루비, 파이썬, 자바, PHP, Objective-C 등을위한 라이브러리와 함께 이미지 업로드, 강력한 조작, 사이트 및 앱의 저장 및 제공. 영구 프리 티어는 월 7,500 개 이미지, 2GB 스토리지, 5GB 대역폭을 포함합니다.
    gumlet.com — 이미지 크기 조정 서비스. 또한 이미지를 최적화하고 CDN을 통한 전달을 수행합니다. 프리 티어에는 1 년 동안 매월 1GB의 대역폭과 무제한의 이미지 처리가 포함됩니다.
    plot.ly — 데이터를 그래프로 만들고 공유하십시오. 프리 티어에는 무제한 공개 파일과 10 개의 비공개 파일이 포함됩니다
    transloadit.com — 비디오, 오디오, 이미지, 문서의 파일 업로드 및 인코딩을 처리합니다. 오픈 소스 및 기타 수행자에게는 무료입니다. 상용 애플리케이션은 테스트 구동을 위해 1GB를 무료로 제공
    podio.com — 최대 5 명으로 구성된 팀과 함께 Podio를 사용하고 사용자 관리를 제외하고 기본 계획의 기능을 시험해 볼 수 있습니다
    shrinkray.io — GitHub 저장소의 무료 이미지 최적화
    kraken.io — 서비스로 웹 사이트 성능을위한 이미지 최적화, 최대 1MB 파일 크기의 무료 요금제
    placeholder.com — 빠르고 간단한 이미지 자리 표시 자 서비스
    placekitten.com — 자리 표시 자로 사용할 고양이 사진을 가져 오는 빠르고 간단한 서비스
    embed.ly — 웹 페이지에 미디어를 포함하고 반응 형 이미지 크기를 조정하며 웹 페이지에서 요소를 추출하기위한 API를 제공합니다. 초당 15 개의 요청으로 최대 5,000 개의 URL을 무료로 제공합니다.
    otixo.com — 모든 클라우드 저장소 파일을 한 곳에서 암호화, 공유, 복사 및 이동합니다. 기본 계획은 최대 250MB의 무제한 파일 전송을 제공합니다. 파일 크기 및 5 개의 암호화 된 파일 허용
    tinypng.com — PNG 및 JPEG 이미지를 압축 및 크기 조정하는 API로 매월 500 회 압축 제공
    filestack.com — 파일 선택기, 변환 및 전달, 250 개 파일, 500 개 변환 및 3GB 대역폭 무료
    packagecloud.io — YUM, APT, RubyGem 및 PyPI를위한 호스팅 된 패키지 리포지토리입니다. 제한된 무료 요금제, 오픈 소스 요금제 요청 가능
    image-charts.com — 워터 마크가 포함 된 무제한 이미지 차트 생성
    jsonbin.io — 무료 JSON 데이터 스토리지 서비스로 소규모 웹 앱, 웹 사이트, 모바일 앱에 이상적입니다. 

디자인과 UI

    landen.co — 스타트 업을위한 멋진 웹 사이트 및 방문 페이지를 생성, 편집 및 게시합니다. 코드없이 모두. 프리 티어를 사용하면 하나의 웹 사이트를 만들 수 있으며 웹에서 완전히 사용자 정의하고 게시 할 수 있습니다.
    pixlr.com — 상용 수준의 무료 온라인 브라우저 편집기
    imagebin.ca — 이미지 용 Pastebin
    cloudconvert.com — 무엇이든 변환하십시오. 비디오를 GIF로 포함한 208 지원 형식
    resizeappicon.com — 앱 아이콘의 크기를 조정하고 관리하는 간단한 서비스
    vectr.com — 웹 + 데스크탑 용 무료 디자인 앱
    clevebrush.com — 무료 그래픽 디자인 / 사진 콜라주 앱으로 구성 요소로 유료 통합을 제공합니다
    walkme.com — 엔터프라이즈 급지도 및 참여 플랫폼, 무료 플랜 3 도보 최대 5 걸음 / 걸음
    marvelapp.com — 디자인, 프로토 타이핑 및 협업, 3 개의 프로젝트에 대해 무료로 제한
    Zeplin — 디자이너 및 개발자 협업 플랫폼. 디자인, 자산 및 스타일 가이드를 보여줍니다. 1 개 프로젝트 무료.
    figma.com — 팀을위한 온라인 협업 디자인 툴; 프리 티어에는 최대 2 명의 편집자와 3 개의 프로젝트가있는 무제한 파일 및 뷰어가 포함됩니다.
    designer.io — UI, 일러스트레이션 등을위한 디자인 도구입니다. 기본 앱이 있습니다. 비어 있는
    photopea.com — PSD, XCF 및 스케치 형식 (Adobe Photoshop, Gimp 및 Sketch App)을 지원하는 Adobe Photoshop UI가 포함 된 무료 고급 온라인 디자인 편집기입니다.
    pexels.com- 상업용 무료 사진. 키워드별로 사진을 검색 할 수있는 무료 API가 있습니다. 

지도상의 데이터 시각화

    opencagedata.com — OpenStreetMap 및 기타 오픈 지오 소스를 집계하는 지오 코딩 API. 하루 2,500 건의 무료 쿼리
    graphhopper.com 라우팅, 경로 최적화, 거리 매트릭스, 지오 코딩, 맵 매칭을 위해 개발자를위한 무료 패키지가 제공됩니다.
    datamaps.co — 데이터 맵으로 시각화를 생성하기위한 무료 플랫폼
    geocod.io — API 또는 CSV 업로드를 통한 지오 코딩. 하루 2,500 건의 무료 쿼리
    gogeo.io — 사용하기 쉬운 API 및 빅 데이터 지원을 제공하는지도 및 지리 공간 서비스
    carto.com — 데이터 및 공개 데이터에서지도 및 지리 공간 API 생성
    giscloud.com — 온라인으로 지리 데이터를 시각화, 분석 및 공유
    mapbox.com —지도 데이터를 표시하기위한지도, 지리 공간 서비스 및 SDK
    osmnames — 지오 코딩, 관련 Wikipedia 페이지의 인기에 의해 순위가 매겨진 검색 결과
    maptiler.com —지도 시각화를위한 벡터지도,지도 서비스 및 SDK. 주간 업데이트 및 4 가지 맵 스타일의 무료 벡터 타일.
    여기 —지도 및 위치 인식 앱을위한 API 및 SDK. 한 달에 2 만 건의 거래가 무료로 제공됩니다. 

패키지 빌드 시스템

    build.opensuse.org — 여러 배포판 (SUSE, EL, Fedora, Debian 등)을위한 패키지 빌드 서비스
    copr.fedorainfracloud.org — Fedora 및 EL을위한 모의 기반 RPM 빌드 서비스
    help.launchpad.net — 우분투 및 데비안 빌드 서비스 

IDE 및 코드 편집

    codenvy.com — 브라우저의 IDE 및 자동화 된 개발자 작업 영역, 공동 작업, Git / SVN 통합, 사용자 정의 가능한 Docker 기반 러너 (무료 계층 포함 : 3GB RAM, 여러 머신을 동시에 실행할 수있는 기능 포함)에서 앱 빌드 및 실행 Google Apps에 통합 배포
    Visual Studio Community — 수천 개의 확장 기능, 크로스 플랫폼 앱 개발 (iOS 및 Android 용 Microsoft 확장 프로그램 다운로드 가능), 데스크톱, 웹 및 클라우드 개발, 다국어 지원 (C #, C ++, JavaScript, Python, PHP 등)
    ide.goorm.io goormIDE는 클라우드의 전체 IDE입니다. 다중 언어 지원, 모든 기능을 갖춘 웹 기반 터미널을 통한 Linux 기반 컨테이너, 포트 포워딩, 사용자 정의 URL, 실시간 협업 및 채팅, 공유 링크, Git / Subversion 지원. 더 많은 기능이 있습니다 (프리 티어에는 컨테이너 당 1GB RAM 및 10GB 스토리지, 5 컨테이너 슬롯 포함)
    cocalc.com (구 : cloud.sagemath.com의 SageMathCloud) — 클라우드에서의 공동 계산. Python, LaTeX, Jupyter Notebooks, SageMath, scikitlearn 등 수학, 과학, 데이터 과학, 사전 설치를위한 기본 제공 협업 및 무료 소프트웨어를 통해 풀 우분투에 대한 브라우저 액세스
    wakatime.com — 텍스트 편집기 플러그인을 사용한 코딩 활동에 대한 정량화 된자가 측정
    apiary.io — 인스턴트 API 모의 및 생성 된 문서가 포함 된 협업 디자인 API (무제한 API 설계도 및 하나의 관리자 계정 및 호스팅 된 문서를 가진 무제한 사용자에게는 무료)
    mockable.io — Mockable은 RESTful API 또는 SOAP 웹 서비스를 모방하기위한 간단한 구성 가능한 서비스입니다. 이 온라인 서비스를 통해 REST API 또는 SOAP 엔드 포인트를 빠르게 정의하고 JSON 또는 XML 데이터를 리턴 할 수 있습니다.
    fakejson.com — FakeJSON을 사용하면 API를 사용하여 가짜 데이터를 빠르게 생성 할 수 있습니다. 원하는 것과 원하는 방법을 설명하는 API 요청을하십시오. API는 JSON으로 모두 반환합니다. 아이디어에 대한 시장 프로세스로 이동하여 아이디어를 만들 때까지 속일 수 있습니다.
    JSONPlaceholder 일부 가짜 API 데이터를 JSON 형식으로 반환하는 일부 REST API 엔드 포인트. 서버를 로컬로 실행하려는 경우 소스 코드도 사용할 수 있습니다.
    jetbrains.com — 생산성 도구, IDE 및 배포 도구. 학생, 교사, 오픈 소스 및 사용자 그룹을위한 무료 라이센스
    codepen.io — CodePen은 웹 프런트 엔드를위한 놀이터입니다
    repl.it — 다양한 프로그램 언어를위한 클라우드 코딩 환경
    codesandbox.io — React, Vue, Angular, Preact 등을위한 온라인 놀이터
    stackblitz.com — 각도 및 반응을위한 온라인 VS 코드 IDE
    cacher.io — 100 개 이상의 프로그래밍 언어를 지원하는 레이블이있는 코드 스 니펫 구성
    코더 — Visual Studio Code를 중심으로 전체 개발 환경을 구축하는 플랫폼입니다. 프리 티어에서는 2GB의 프로젝트와 2GB의 컨테이너 공간과 5 시간의 빠른 시간을 확보 할 수 있습니다 (사용 가능한 경우 컨테이너를 동적으로 확장).
    gitpod.io — GitHub 프로젝트를위한 즉각적이고 코딩 가능한 개발자 환경. 오픈 소스 무료.
    Katacoda — 개발자가 배우고 회사의 채택을 늘리도록 도와주는 소프트웨어 엔지니어를위한 대화식 학습 및 교육 플랫폼. 

분석, 이벤트 및 통계

    analytics.google.com — Google 웹 로그 분석
    www.heatlyanalytics.com — UI / UX를 이해하기위한 무료 히트 맵 도구입니다.
    heap.io — iOS 또는 웹 앱의 모든 사용자 작업을 자동으로 캡처합니다. 월 최대 5,000 회 방문 무료
    sematext.com — 최대 50K 작업 / 월, 1 일 데이터 보존, 무제한 대시 보드, 사용자 등을 위해 무료
    usabilityhub.com — 실제 사람들의 디자인과 모형을 테스트하고 방문자를 추적합니다. 한 명의 사용자에게 무료, 무제한 테스트
    mixpanel.com — 귀하의 사이트에 배지가있는 25,000 포인트 또는 200,000 무료
    진폭 .com — 1 백만 달 이벤트, 최대 2 개의 앱
    keen.io — 데이터 수집, 분석 및 시각화를위한 맞춤형 분석. 50,000 이벤트 / 월 무료
    metrica.yandex.com — 무제한 무료 분석
    hotjar.com — 사이트 당 : 하루 2,000 페이지 조회수, 3 개의 히트 맵, 3 개월 동안 저장된 데이터 ...
    imprace.com — 이탈률을 개선하기위한 제안이있는 방문 페이지 분석. 무료 방문 페이지 / 도메인 5 개
    optimizely.com — A / B 테스팅 솔루션, 무료 스타터 플랜, 1 웹 사이트, 1 iOS 및 1 안드로이드 앱
    expensify.com — 비용보고, 무료 개인보고 승인 워크 플로우
    Moesif — REST 및 GraphQL에 대한 API 분석. (최대 500,000 API 호출 무료) 

방문자 세션 기록

    inspectlet.com — 1 개의 웹 사이트에 대해 100 회 / 월 무료
    mousestats.com — 1 개의 웹 사이트에 대해 100 회 / 월 무료
    hotjar.com — 사이트 당 : 하루 2,000 페이지 조회수, 3 개의 히트 맵, 3 개월 동안 저장된 데이터 ...
    usersurge.com — 개인을위한 매월 250K 세션. 

국제 휴대폰 번호 확인 API 및 SDK

    cognalys.com — SMS 게이트웨이를 사용하는 것보다 혁신적이고 안정적인 방법을 통한 프리미엄 휴대폰 번호 확인. 무료 10 회 시도 및 15 회 검증 / 일
    numverify.com — 전 세계 전화 번호 확인 및 조회 JSON API. 한 달에 250 번의 API 요청 

결제 / 청구 통합

    braintreepayments.com — 신용 카드, 페이팔, 벤모, 비트 코인, 애플 페이, 통합. 단일 및 반복 결제. 최초 USD 50,000 무료
    currencylayer.com — 비즈니스를위한 안정적인 환율 및 환율 변환, 월 1,000 건의 API 요청 무료
    vatlayer.com — 즉시 부가가치세 번호 검증 및 EU 부가가치세 API, 월 100 회 무료 API 요청
    fraudlabspro.com — 판매자가 지불 사기 및 지불 거절을 방지하도록 도와줍니다. 한 달에 500 번의 쿼리로 제공되는 무료 마이크로 요금제.
    currencystack.io — 154 통화에 대한 생산량 기준 실시간 환율입니다. 

도커 관련

    Docker Hub — Docker 이미지를 빌드하고 저장하기위한 하나의 무료 개인 저장소 및 무제한 공용 저장소
    quay.io — 무제한 무료 공용 저장소를 사용하여 컨테이너 이미지를 빌드하고 저장합니다
    canister.io — 개발자를위한 20 개의 무료 개인 저장소, 팀이 Docker 이미지를 빌드하고 저장할 수있는 30 개의 무료 개인 저장소
    고래 — 무료로 응용 프로그램을 자동으로 고정하는 도구입니다.
    PWD — Docker로 재생합니다. Docker를 배울 수있는 간단하고 대화 형의 재미있는 놀이터
    Gitlab- 저장소 별 컨테이너 레지스트리. 10GB 제한 

유랑 관련

    vagrantbox.es — 대체 공개 박스 인덱스 

여러 가지 잡다한

    docsapp.io — 오픈 소스를 위해 무료로 문서를 게시하는 가장 쉬운 방법
    fullcontact.com — 앱에 소셜 프로필을 추가하여 사용자가 연락처에 대해 더 많이 알 수 있도록 도와줍니다. 한 달에 500 개의 무료 Person API 일치
    formlets.com — 온라인 양식, 무제한 단일 페이지 양식 / 월, 100 건의 제출 / 월, 이메일 알림
    superfeedr.com — 실시간 PubSubHubbub 호환 피드, 내보내기, 분석. 적은 사용자 정의로 무료
    screenshotlayer.com — 모든 웹 사이트의 사용자 정의가 가능한 스냅 샷을 캡처합니다. 월 100 회 무료 스냅 샷
    screenshotmachine.com — 홈페이지뿐만 아니라 전체 길이 캡처를 포함하여 100 스냅 샷 / 월, png, gif 및 jpg 캡처
    readme.com — 오픈 소스를 위해 무료로 제공되는 아름다운 문서 : 여기를 참조 하십시오 .
    formaholic.com — 간단한 형태의 엔드 포인트. 정적 사이트에 적합
    http2.pro — HTTP / 2 프로토콜 준비 테스트 및 클라이언트 HTTP / 2 지원 감지 API.
    Formspree.io — HTTP POST 요청을 사용하여 이메일을 보냅니다. 프리 티어는 한 달에 1000 건으로 제한되며 API 호출에 이메일 주소를 공개해야합니다.
    Formcarry.com -HTTP POST 양식 엔드 포인트, 무료 계획은 한 달에 100 건의 제출을 ​​허용합니다.
    Typeform.com — 웹 사이트에 아름답게 디자인 된 양식을 포함 시킵니다 . 무료 계획은 양식당 10 개의 필드와 한 달에 100 개의 응답 만 허용합니다.
    SurveyMonkey.com — 온라인 설문 조사를 만듭니다. 결과를 온라인으로 분석하십시오. 무료 플랜은 설문 당 10 개의 질문과 100 개의 응답 만 허용합니다. 

기타 무료 자료

    github.com — 개발자 용 FOSS — 개발자를위한 무료 및 오픈 소스 소프트웨어 허브
    getawesomeness — GitHub에서 놀라운 기능을 모두 검색합니다.
    education.github.com — 학생들을위한 무료 서비스 모음. 등록 필요
    Framacloud — 프랑스 비영리 Framasoft 의 무료 / 리버 오픈 소스 소프트웨어 및 SaaS 목록입니다. 
    
