# 방송대 소프트웨어 경진대회 개발일지

## 2024년 7월 15일 월요일
### 개발 내용
- 내 컴퓨터에 Xcode 프로젝트 세팅
- 홈 화면에 네비게이션 컨트롤러 및 친구 리스트 구현

### 개발 중 이슈/고민 또는 해결한 내용
- Package.resolved file is corrupted or malformed 에러 해결 ▶️ Momentrack.xcodeproj/project.xcworkspace/xcshareddata/swiftpm/Package.resolved 제거 
- showing all messages binary target 'absl' could not be mapped to an artifact with expected name 'absl' 와 같은 패키지 오류 해결 ▶️ ~/Library/Developer/Xcode/DerivedData/{해당 프로젝트 파일} 제거 
