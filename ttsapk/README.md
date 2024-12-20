# 2021년 3월 패치 이후 tts 여성1 음성 버그 와 최신버전 tts 음성 딜레이 문제. 


## 삼성 TTS 대기 모드에서 끊김 현상.
---

https://r1.community.samsung.com/t5/%EA%B0%A4%EB%9F%AD%EC%8B%9C-s/tts-%EB%81%8A%EA%B9%80-%ED%98%84%EC%83%81/m-p/20028619/highlight/true#M845391

이리저리 찾아보다가 위 문의글을 찾았습니다. 

삼성측에서 답변한 내용으로 시도 해보시는 것도 좋은 방법 일듯 합니다. 

---


## 개발자 어플 설명 

---

[TTS TextViewer apk 다운로드](https://github.com/khjde1207/khjde1207.github.io/releases/download/apk/app-release.apk)

* 플레이스토어 를 이용하여 설치 가 안된다는 제보가 종종 있었습니다.   
* 만약 일부 이북리더기 에서 설치가 안될경이 위 링크에서 apk 를 다운받아 설치 해보시기 바랍니다.

[TTS TextViewer 플레이 스토어로 이동](https://play.google.com/store/apps/details?id=com.khjde.opentextview)

---


## 이 apk 는 기존 엔진 이 업데이트 되더라도 영향을 받지 않도록 어플의 이름을 변경하였습니다. 


3월 이후 에 나온 TTS 엔진 부터 한국어 [여성 음성 1] 남녀 목소리가 섞여 나오는 현상이 있었습니다. 

22 년 8 월에 해당 현상이 수정 되었습니다. 

하지만 몇가지 문제가 추가로 발생하여 이 APK 를 유지 하도록 하겠습니다. 

1. 백그라운드 에서 TTS 재생시 딜레이가 발생 하는 현상이 있습니다. 
2. 음성이 기존 버전보다 먹먹한 현상이 있습니다. 
3. 음성 재생시 글자 갯수가 일정이상 넘어가면 위치 추적이 안되는 버그가 있습니다.  
4. 속도를 보통 보다 느리게 할 경우 중얼 중얼 되는 듯한 느낌의 음성이 출력 됩니다. 

패치를 발견하고 제가 따로 제작한 apk 를 지웠었지만, 위 에 나열한 문제 때문에 다시 올려 놓겠습니다. 

구글 TTS 과거 버전에서 이름을 tGoogleTts 로 변경(앞에 t 만 추가) 하여 apk 를 다시 만들었습니다. 


[수정한 부분 확인](https://github.com/khjde1207/opentextviewdatas/blob/main/ttsapk/backup.txt)


## 설치 방법 

### 하단 설명을 다 읽고 설치 해주시기 바랍니다. 


---
## 다운로드 : 
[클릭 하여 apk 다운로드](https://github.com/khjde1207/opentextviewdatas/raw/main/ttsapk/tgoogle-tts.apk)

---
1. 위 바로 가기를 눌러 apk 파일 을 다운로드 합니다. 

<p align='center'>
    <img src="https://github.com/khjde1207/opentextviewdatas/raw/main/ttsapk/img/1.png" />
</p>

2. 확인 을 누른뒤 잠시 기다리면 열기 버튼으로 변경 됩니다. 열기 버튼을 우르면 아래와 같은 메세지가 출력 됩니다. 

<p align='center'>
    <img src="https://github.com/khjde1207/opentextviewdatas/raw/main/ttsapk/img/2.png" />
</p>

3. 설정 을 누르면 창이 변경 되면서 아래 그림이 보이실겁니다. (만약 위 메세지가 출력 되지 않았다면 그냥 무시 하시고 5번 단계로 이동 하세요. )

<p align='center'>
    <img src="https://github.com/khjde1207/opentextviewdatas/raw/main/ttsapk/img/3.png" />
</p>

4. 이 출처 허용 을 눌러 주세요. 


<p align='center'>
    <img src="https://github.com/khjde1207/opentextviewdatas/raw/main/ttsapk/img/4.png" />
</p>

5. 설치를 눌러주세요. 

<p align='center'>
    <img src="https://github.com/khjde1207/opentextviewdatas/raw/main/ttsapk/img/5.png" />
</p>

6. 잠시 기다리시면 그림과 같이 팝업이 뜨게 되는데. [무시하고 설치]를 눌러 주세요.

설치가 완료 되면 구글에 정보를 보내 겠다는 메세지가 나오는데. [전송 안함]을 눌러 주세요. 


<p align='center'>
    <img src="https://github.com/khjde1207/opentextviewdatas/raw/main/ttsapk/img/6.png" />
</p>

<p align='center'>
    <img src="https://github.com/khjde1207/opentextviewdatas/raw/main/ttsapk/img/7.png" />
</p>

<p align='center'>
    <img src="https://github.com/khjde1207/opentextviewdatas/raw/main/ttsapk/img/8.png" />
</p>

7. 설정 -> 접근성 -> 스크린 리더 -> 설정 -> tGoogle TTS 엔진 으로 변경 해 주세요.
