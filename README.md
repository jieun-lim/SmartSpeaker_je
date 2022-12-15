<table>
<thead>
  <tr>
    <th>카테고리</th>
    <th>세부 카테고리</th>
    <th>피쳐 종류</th>
    <th>데이터 설명</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="6">스피커-사용자 설문 대화 데이터</td>
    <td>대화 길이&nbsp;&nbsp;</td>
    <td>whole_conv_length(sec)</td>
    <td>설문 1회당 소요 시간(초)</td>
  </tr>
  <tr>
    <td>대화 속도 </td>
    <td>dixit_response_rate</td>
    <td>딕싯 그림 설명 사용자 답변 속도, (답변 텍스트 길이)/(답변길이)</td>
  </tr>
  <tr>
    <td rowspan="4">정신 건강 설문 답변</td>
    <td>phq2_result</td>
    <td>사용자 우울증 상태,  우울증이 있을 확률이 높으면(PHQ2 점수 3점 이상) 1, 아니면 0.  </td>
  </tr>
  <tr>
    <td>gad2_result</td>
    <td>사용자 불안 장애 상태, 불안 장애가 있으면(GAD2 점수가 3점이상) 1, 아닐 경우 0</td>
  </tr>
  <tr>
    <td>stress_result</td>
    <td>스트레스 유무, 스트레스가 평균 이상이면 1, 아니면 0</td>
  </tr>
  <tr>
    <td>posNeg_result</td>
    <td>긍부정 감정 정도, 부정적인 감정 상태면 1, 아니면 0</td>
  </tr>
  <tr>
    <td rowspan="6">센서 데이터</td>
    <td rowspan="6">가정 환경 내 센서 데이터 </td>
    <td>dB</td>
    <td>설문 시작 직전 1분 평균 데시벨</td>
  </tr>
  <tr>
    <td>Temperature</td>
    <td>설문 시작 직전 1분 평균 온도</td>
  </tr>
  <tr>
    <td>Humidity</td>
    <td>설문 시작 직전 1분 평균 습도</td>
  </tr>
  <tr>
    <td>CO2</td>
    <td>설문 시작 직전 1분 평균 CO2 농도</td>
  </tr>
  <tr>
    <td>TVOC</td>
    <td>설문 시작 직전 1분 평균 공기질 오염도</td>
  </tr>
  <tr>
    <td>Light</td>
    <td>설문 시작 직전 1분 평균 조도값</td>
  </tr>
  <tr>
    <td rowspan="13">사용자 실험 사전 설문</td>
    <td rowspan="2">성별</td>
    <td>F</td>
    <td>여자면 1, 아닐 경우 0</td>
  </tr>
  <tr>
    <td>M</td>
    <td>남자면 1, 아닐 경우 0</td>
  </tr>
  <tr>
    <td rowspan="5">성격 유형(Big-5 모델 기반)</td>
    <td>Extroversion</td>
    <td>외향성, 외향적일 수록 10에 가까운 점수(0~10)</td>
  </tr>
  <tr>
    <td>Neuroticism</td>
    <td>신경질적 성향, 해당 성향이 높을 수록 10에 가까운 점수(0~10)</td>
  </tr>
  <tr>
    <td>Conscientiousness</td>
    <td>성실성, 해당 성향이 높을 수록 10에 가까운 점수(0~10)</td>
  </tr>
  <tr>
    <td>Agreeable</td>
    <td>해당 성향이 높을 수록 10에 가까운 점수(0~10)</td>
  </tr>
  <tr>
    <td>Openness</td>
    <td>개방성, 해당 성향이 높을 수록 10에 가까운 점수(0~10)</td>
  </tr>
  <tr>
    <td rowspan="6">사전 사용자 정신 건강 상태</td>
    <td>depression_or_not</td>
    <td>사용자의 기존 우울증 유무(PHQ9 설문 기반, 점수 총합이 10점 이상이면 주목할 만한 우울증)</td>
  </tr>
  <tr>
    <td>anxietyDisorder_or_not</td>
    <td>사용자의 기존 불안 장애 유무(GAD7 설문 기반, 점수 총합이 6점이면 불안 장애)</td>
  </tr>
  <tr>
    <td>PSS_pos_score</td>
    <td>Perceived Stress Scale(PSS) 설문 중 긍정 문항 점수 총합</td>
  </tr>
  <tr>
    <td>PSS_neg_score</td>
    <td>Perceived Stress Scale(PSS) 설문 중 부정 문항 점수 총합</td>
  </tr>
  <tr>
    <td>PSS_score</td>
    <td>Perceived Stress Scale(PSS) 설문 총합</td>
  </tr>
  <tr>
    <td>PSS_stress_or_not</td>
    <td>사용자 기존 스트레스 정도(문항 총점이 13점 이상이면, 스트레스 정도가 정상이 아니라고 판단)</td>
  </tr>
  <tr>
    <td>음성 데이터</td>
    <td></td>
    <td>before_audio</td>
    <td>before audio 설명</td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>after_audio</td>
    <td>after_audio 설명 </td>
  </tr>
</tbody>
</table>

-----------


<table style="undefined;table-layout: fixed; width: 812px">
<colgroup>
<col style="width: 92.88889px">
<col style="width: 148.88889px">
<col style="width: 246.88889px">
<col style="width: 323.77778px">
</colgroup>
<thead>
  <tr>
    <th></th>
    <th>카테고리</th>
    <th>세부 카테고리</th>
    <th>데이터 설명</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="16">스마트폰 사용 데이터</td>
    <td rowspan="5">사회적 상호 작용 데이터</td>
    <td>APP_USAGE_EVENT</td>
    <td>모바일 앱 내 이벤트 발생 시간 및 유형 기록<br>- type : 앱 이벤트 타입, 앱 꺼짐, 켜짐 등의 정보를 나타냄. </td>
  </tr>
  <tr>
    <td>CALL_LOG</td>
    <td>통화 기록<br>- type : 수신/발신 여부,  수신 거부 여부 등을 나타냄<br>- duration : 통화  시간</td>
  </tr>
  <tr>
    <td>DEVICE_EVENT</td>
    <td>스마트 폰 기기 이벤트 발생<br>- type : 이벤트 유형, 스크린 켜짐/꺼짐(SCREEN_OFF/SCREEN_ON) 등의 정보</td>
  </tr>
  <tr>
    <td>MESSAGE</td>
    <td>메세지 관련 정보<br>- type : 메세지가 발신/수신(SENT/INBOX) 여부 </td>
  </tr>
  <tr>
    <td>NOTIFICATION</td>
    <td>어떤 종류의 알림(메세지, 전화, 에러 등)이 발생했는지 기록</td>
  </tr>
  <tr>
    <td rowspan="5">네트워크 및 기기 상태</td>
    <td>BATTERY</td>
    <td>배터리 레벨 및 충전여부(DISCHARGING/CHARGING)</td>
  </tr>
  <tr>
    <td>BLUETOOTH</td>
    <td>블루투스 연결여부(NONE, BONEDE) </td>
  </tr>
  <tr>
    <td>DATA TRAFFIC</td>
    <td>데이터 트래픽 양(rxBytes 와 txBytes 단위로 나타냄)</td>
  </tr>
  <tr>
    <td>INSTALLED APP</td>
    <td>설치된 앱 정보(id로 기록) </td>
  </tr>
  <tr>
    <td>WIFI</td>
    <td>와이파이 연결되어 있을 경우 어떤 Access Point 에 접근했는지 정보</td>
  </tr>
  <tr>
    <td rowspan="2">키보드 및 미디어 데이터 </td>
    <td>KEY_LOG</td>
    <td>키보드 사용 시 키보드 사용 정보(키보드 종류 등) 나타냄</td>
  </tr>
  <tr>
    <td>MEDIA</td>
    <td>사진/동영상 다운로드 하였을 때, 관련 시간 및 미디어 파일 종류(gif, jpeg, png, mp4 등)를 나타냄</td>
  </tr>
  <tr>
    <td rowspan="4">활동 데이터</td>
    <td>FITNESS</td>
    <td>사용자 걸음수, 이동 거리</td>
  </tr>
  <tr>
    <td>LOCATION</td>
    <td>사용자 현재 위치의 위도, 경도, 고도, 속도 기록</td>
  </tr>
  <tr>
    <td>PHYSICAL_ACTIVITY</td>
    <td>사용자액티비티 유형(뛰기, 걷기, 자전거 탑승 등) </td>
  </tr>
  <tr>
    <td>PHYSICAL_ACTIVITY_TRANLATION</td>
    <td>사용자 액티비티 상태 변화를 기록(뛰기, 걷기, 자전거 탑승 등)</td>
  </tr>
</tbody>
</table>
