# Copyright (C) 2024 GloryKim (glory@keti.re.kr)

## Folder_Architecture
1. nodejs
    - 240921_2230 : NodeJS기반 메인서버, WebRTC 서버 이식 + 해당 서버에 각종 로그를 남길 예정이며, 추후에는 메인 서버를 별도로 구축할 계획에 있음
    - 240921_0139 : go측에서 45만개의 xyz 배열을 1초에 한번씩 보내는 걸 소화 (app.use(bodyParser.json({ limit: '100mb' }));) 기능으로 해결
2. rust+blockchain
    - 240921_2248 : 작업 증명, 트랜잭션, 디지털 서명 등 기능이 미포함
3. go+sendRequest
    - 240921_2303 : node 서버에 무차별로 연락을 보내는 코드
    - 240921_0139 : node로 45만개의 xyz 배열을 1초에 한번씩 보내는 기능 구현 반영 (post)

---

## Next Step
1. Node 코드 forever log save 기능을 통해 log 정리
2. 기존 js 서버 일부 요소 반영