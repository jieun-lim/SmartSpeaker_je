

## 데이터 전처리 및 멘탈 상태 예측 모델 생성 (지은)
데이터 수집 플랫폼에서 수집된 데이터를 기반으로 정신 건강 상태(스트레스 및 긍/부정 감정)분류를 위한 모델 생성 및 검증하고자 함. 사용자 멘탈 상태 분류 모델 생성을 위해 수집된 센서 데이터에서 피처를 추출하고 사용자의 ESM 정신 건강 설문  답변(스트레스, 긍부정 질문)을 타겟 레이블로 지정함.


**데이터 통합 및 전처리

실험용 스마트폰, 스마트 스피커 등의 다양한 소스에서 수집되는 원본 데이터를 통합하고 전처리함. 각 데이터 소스 별 전처리 과정은 다음과 같음.

## 1. 스마트 스피커 답변 원본 데이터(Dataset/response_data_2022-08-31_2022-09-08.json)
2022년 8월 31일 ~ 2022년 9월 8일까지 10명 스마트 스피커 설문 대화 관련 로그가 포함이 되어 있음. 전처리 과정을 통해, 다음과 같은 피쳐를 추출함.

<답변 길이>
('phq1(sec)'~dixit(sec)) : 각 질문 별 시작 시각(startTimes) 및 완료 시각(endTimes)를 기반으로 각 설문 답변 별 대화 시간을 계산
whole_conv_length : 각 설문 별 전체 대화 길이

interaction_methods(binary) :

dixit_response_rate :  딕싯 대화 기준 발화 속도 (딕싯 답변 텍스트 길이/답변 시간)

<설문 답변 관련>
각 질문 별 답변을 기준으로 PHQ RESULT --> BINARY
- phq2_result : phq2 총점 계산하여, 우울증 여부 0 or 1으로 저장
- gad2_result
- stress_result
- posNeg_result

<table class="tg">
<thead>
  <tr>
    <th class="tg-0pky">카테고리</th>
    <th class="tg-0pky">test</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky">asdf</td>
    <td class="tg-0pky">d</td>
  </tr>
  <tr>
    <td class="tg-0pky">d</td>
    <td class="tg-0pky">d</td>
  </tr>
  <tr>
    <td class="tg-0pky">d</td>
    <td class="tg-0pky">d</td>
  </tr>
</tbody>
</table>

---
### 3. 사용자 스마트폰에서 수집되는 데이터
* 데이터 파일 경로: [Dataset/K-Emophone Logger](https://github.com/youngji-koh/LGE-Project/tree/main/Dataset/K-Emophone%20Logger)
* 수집되는 데이터 타입 별로 csv파일 존재

<table>
  <thead>
    <tr>
      <th>카테고리</th>
      <th>데이터 종류</th>
      <th>데이터 필드</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="4">스마트폰 사용 데이터</td>
      <td>사회적 상호 작용 데이터</td>
      <td> 전화 송/수신 횟수 및 통화 시간 <br/> SMS/메신저/SNS 앱 사용 횟수 <br/> 시간 및 알림 기록(메세지 등 콘텐츠 는 저장하지 않으며, 메타 정보만 수집)</td>
    </tr>
     <tr>
      <td>네트워크 및 기기 상태 데이터</td>
      <td>와이파이/블루투스/셀룰러 데이터 연결 <br/> 데이터 송/수신 바이트 양 <br/> 전원 여부 <br/> 알림 모드 <br/> 배터리 레벨/충전 상태 여부 </td>
    </tr>
    <tr>
      <td>키보드 및 미디어 데이터</td>
      <td>키보드 종류 <br/> 입력 문자 종류 <br/> 키 간 거리 <br/> 카메라 사용 이벤트 <br/> 마이크 기록(실제 입력 정보는 수집하지 않고, 메타 정보만 수집) </td>
    </tr>
    <tr>
      <td>활동 데이터</td>
      <td>활동 타입(예: 걷기, 뛰기 등) </td>
    </tr>
  </tbody>
</table>





---


## 데이터 분석 및 모델 검증 결과 (영지)
