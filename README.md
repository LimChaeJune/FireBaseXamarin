# FireBaseXamarin   
  FCM (FireBase Chrome Message)를 통해 Xamarin Android 애플리케이션에 알림 Push를 구현합니다.   

## 개요   
  - FireBase Console Setting
  - Xamarin APP
  - C# To Fcm Batch 프로젝트    
---

  ### FireBase Conosle
  1. [Firebase](https://console.firebase.google.com/) 사이트에 접속해 프로젝트를 생성합니다.
  2. 프로젝트로 들어가 Android 애플리케이션을 생성합니다. 여기서 Android 패키지의 이름은 Xamarin APP의 패키지 이름과 동일시 합니다.
  3. App을 생성하면서 google-serivce.json 파일을 다운로드 합니다. Xamarin 앱에서 이 프로젝트를 연결, 인증하는데 필요합니다.
  4. App 설정이 완료 되었으면, 프로젝트 설정 -> 서비스 계정 으로 가 비공개 키를 생성하여 저장합니다.

  ### Xamarin APP
  1. NotiXamarin이란 이름의 안드로이드 앱을 생성합니다.
  2. 프로젝트 설정으로 들어가 Android 매니페스트에서 패키지 이름을 FireBase Console에서 생성한 앱과 동일한 패키지 이름으로 변경해줍니다.
  3. FireBase에서 저장한 google-service.json 파일에 프로젝트에 포함합니다. 
  4. FireBase에 메시징을 보내기 위한 SDK를 다운로드합니다.    
    `Xamarin.GooglePlayServices.Base`   `Xamarin.Firebase.Messaging`
  5. google-service.json 파일의 속성에서 빌드작업을 GoogleServicesJson으로 변경해줍니다. 
  6. Message를 Recived해줄 핸들러를 MainActivity.cs를 수정합니다.
  
  ### C# To FCM Batch
 
   
   
   
 
 
  
