# springSecu1
1. 인증 필요할 경우 Spring Security는 Security Context라는 저장소에서 Authentication객체를 확인한다 없으면 로그인페이지 진입
2. 로그인 시도 시 입력한 유저 아이디로 UserDetails객체를 읽어온뒤 가지고 온 패스워드 비교 후 맞으면  Security Context라는 저장소에서 Authentication넣어주고
가려던 URL로 보내줌