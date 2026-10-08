# cnation Audio Compressor

> **배포 도메인**: [https://cnation-ac.vercel.app](https://cnation-ac.vercel.app)  
> 브라우저 기반 고효율 오디오 일괄 압축(Opus WebM) 및 심리스 게임 BGM 루퍼 스튜디오

## ✨ 주요 기능
- **MP3 다중 일괄 압축**: 클라이언트 브라우저 내에서 여러 개의 MP3 파일을 Opus 코덱 기반의 초경량 `.webm` 파일로 일괄 변환.
- **자동 네이밍 규칙**: `[파일명]_[비트레이트]k_webm.webm` 형식으로 자동 생성 (예: `01_Title_48k_webm.webm`).
- **가변 비트레이트 선택**: 32kbps, 48kbps, 64kbps, 96kbps, 128kbps.
- **일괄 ZIP 다운로드**: 변환 완료된 모든 오디오 파일을 한 번의 클릭으로 압축파일(.zip)로 패키징.
- **심리스 오버랩 루프(Seamless Loop) 플레이어**: MP3 및 WebM 파일을 즉시 로드하고 틱 없는 무한 루프 청음 지원.
- **서버 비용 0원**: 클라이언트 100% Web Audio & MediaRecorder 처리.
- **iOS 고화질 앱 아이콘 포함**: `apple-touch-icon.png` (1024x1024 투명 모서리 라운드).

## 🚀 Vercel 배포 가이드 (`cnation-ac.vercel.app`)
1. 이 압축파일의 내용물을 GitHub 저장소(`cnation-ac`)에 푸시합니다.
2. [Vercel 대시보드](https://vercel.com)에서 **Add New... $	o$ Project**를 선택하고 저장소를 임포트합니다.
3. 빌드 설정은 기본값(정적 HTML) 그대로 두고 **Deploy**를 클릭합니다.
4. **Settings $	o$ Domains**에서 도메인을 `cnation-ac.vercel.app`으로 지정합니다.

## 📄 라이선스
MIT License
