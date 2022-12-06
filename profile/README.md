# 🐤GIMMEDUCK🐤

![image](https://user-images.githubusercontent.com/101383358/203829025-6f71babe-fc32-42cf-afe1-c1ec6e6e9452.png)

> ‘Gimme-Duck’ 서비스는 NFT를 활용하여 기부투명성을 보장하는 블록체 인 기반 기부 플랫폼이다. 기부를 원하는 사용자는 서비스에서 나만의 NFT 를 커스터마이징 하고 자신이 속한 팬덤 이름으로 기부금을 전달한다.


## 💡 GIMMEDUCK 사용해보기
- 웹 배포 주소 : http://52.79.244.89
- 시연 영상 : https://www.youtube.com/watch?v=-Zb7AD4dmGI&t=8s


## 💡 GIMMEDUCK 설치 방법



### [1️⃣ GimmeDuck_Main Clone](https://github.com/GimmeDuck/GimmeDuck_Main)

> GimmeDuck_Main을 Clone 받습니다.
```
git clone https://github.com/GimmeDuck/GimmeDuck_Main.git
```

### [2️⃣ GimmeDuck_Main으로 이동] 

```
cd GimmeDuck_Main
```

### [3️⃣ GimmeDuck_Front 파일 삭제] 

> Clone 받은 GimmeDuck_Back 파일 내부에 있는 GimmeDuck_Front 파일을 삭제합니다.
```
rmdir GimmeDuck_Front
```

### [4️⃣ GimmeDuck_Front Clone](https://github.com/GimmeDuck/GimmeDuck_Front) 

> Clone 받은 GimmeDuck_Back 파일 내부에 GimmeDuck_Front를 Clone 받습니다. 
```
git clone https://github.com/GimmeDuck/GimmeDuck_Front.git
```

### [5️⃣ npm install ]

> GimmeDuck_Main 내부에서 npm install 명령어를 통해 필요한 npm을 설치받습니다. 

### [6️⃣ GimmeDuck_Front로 이동] 

```
cd GimmeDuck_Front
```

### [7️⃣ npm install ]

> GimmeDuck_Front 내부에서 npm install 명령어를 통해 필요한 npm을 설치받습니다. 

### [8️⃣ GimmeDuck_Main으로 이동] 

```
cd ..
```

### [9️⃣ npm start]

> npm start 명령어를 통해 프로젝트를 실행합니다.

---

## 💡 GIMMEDUCK 기능 

![image](https://user-images.githubusercontent.com/81505421/205809608-cfd9f4cd-b130-4cab-92fb-b048f5da6354.png)


#### 1️⃣ HOME 
- 사용자는 NFT제작을 시작하기 앞서 자신의 Klip 지갑을 통해 로그인

#### 2️⃣ NFT 커스터마이징 및 송금
- 자신이 원하는 아이템으로 NFT 제작
- Klip 지갑을 통해 기부금 송금


#### 3️⃣ NFT 민팅 완료
- 송금이 완료되면, NFT가 자동 민팅
- 민팅 완료 시 기부 증서 제공

#### 4️⃣ History
트랜잭션 조회 창 Klaytn scope 이동
-> 블록체인에 기록된 기부금 흐름 확인




## 💡 GIMMEDUCK 개발환경 및 구조도

![image](https://user-images.githubusercontent.com/81505421/205808979-dc211e76-fe1d-465b-aff4-90a06bd7295e.png)


## 💡 GIMMEDUCK 팀원 소개 

<table>
  <tbody>
    <tr>
      <td align="center"><img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/aa99ccf0-e175-46ba-a4c6-ade85e54be13/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20221206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20221206T040557Z&X-Amz-Expires=86400&X-Amz-Signature=38a384bf609d9b99766408f9001265983c89f0a7a6ec52ed096b6116ade81347&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22Untitled.png%22&x-id=GetObject" width="150px;" alt=""/></td>
      <td align="center"><img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/c9a2a310-b560-4c23-8432-088cebf9fb6e/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20221206%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20221206T040612Z&X-Amz-Expires=86400&X-Amz-Signature=41dd7be1be629a30cfafbe4b0613cfb9be6ebe05cfa2d385bbf9ac50e7f5d0e0&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22Untitled.png%22&x-id=GetObject" width="150px;" alt=""/></td>
      <td align="center"><img src="https://www.notion.so/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F70a5eedc-98c5-4b55-ad77-98be8c009218%2FUntitled.png?id=2c60062e-dd5c-4506-a1d6-fc8ddd7b4d31&table=block&spaceId=5a005ae8-89eb-4dd0-85d8-c75b9920e972&width=2000&userId=d0a8105a-992f-4475-ad2a-ffbf098b1e11&cache=v2" width="150px;" alt=""/></td>
    </tr>
    <tr>
      <td align="center"><b> 윤규빈 </b><br /><sub>프론트엔드 개발, 백엔드 개발, web3 api 연동 </sub></td>
      <td align="center"><b> 조승희 </b><br /><sub>프론트엔드 개발, 스마트컨트랙트 개발 </sub></td>
      <td align="center"><b> 김서현 </b><br /><sub>프론트엔드 개발, UI 디자인, 캐릭터 디자인</sub></td>
    </tr>
  </tbody>
</table>


