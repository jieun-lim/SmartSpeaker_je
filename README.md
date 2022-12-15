<table>
<thead>
  <tr>
    <th>카테고리</th>
    <th>세부 카테고리</th>
    <th>피쳐 종류</th>
    <th>데이터 설명</th>
    <th>데이터 예시</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td rowspan="6">스피커-사용자 설문 대화 데이터</td>
    <td>대화 길이&nbsp;&nbsp;</td>
    <td>whole_conv_length(sec)</td>
    <td>설문 1회당 소요 시간(초)</td>
    <td>1</td>
  </tr>
  <tr>
    <td>대화 속도 </td>
    <td>dixit_response_rate</td>
    <td>딕싯 그림 설명 사용자 답변 속도, (답변 텍스트 길이)/(답변길이)</td>
    <td></td>
  </tr>
  <tr>
    <td rowspan="4">정신 건강 설문 답변</td>
    <td>phq2_result</td>
    <td>사용자 우울증 상태,  우울증이 있을 확률이 높으면(PHQ2 점수 3점 이상) 1, 아니면 0.  </td>
    <td></td>
  </tr>
  <tr>
    <td>gad2_result</td>
    <td>사용자 불안 장애 상태, 불안 장애가 있으면(GAD2 점수가 3점이상) 1, 아닐 경우 0</td>
    <td></td>
  </tr>
  <tr>
    <td>stress_result</td>
    <td>스트레스 유무, 스트레스가 평균 이상이면 1, 아니면 0</td>
    <td></td>
  </tr>
  <tr>
    <td>posNeg_result</td>
    <td>긍부정 감정 정도, 부정적인 감정 상태면 1, 아니면 0</td>
    <td></td>
  </tr>
  <tr>
    <td rowspan="6">센서 데이터</td>
    <td rowspan="6">가정 환경 내 센서 데이터 </td>
    <td>dB</td>
    <td>설문 시작 직전 1분 평균 데시벨</td>
    <td></td>
  </tr>
  <tr>
    <td>Temperature</td>
    <td>설문 시작 직전 1분 평균 온도</td>
    <td></td>
  </tr>
  <tr>
    <td>Humidity</td>
    <td>설문 시작 직전 1분 평균 습도</td>
    <td></td>
  </tr>
  <tr>
    <td>CO2</td>
    <td>설문 시작 직전 1분 평균 CO2 농도</td>
    <td></td>
  </tr>
  <tr>
    <td>TVOC</td>
    <td>설문 시작 직전 1분 평균 공기질 오염도</td>
    <td></td>
  </tr>
  <tr>
    <td>Light</td>
    <td>설문 시작 직전 1분 평균 조도값</td>
    <td></td>
  </tr>
  <tr>
    <td rowspan="13">사용자 실험 사전 설문</td>
    <td rowspan="2">성별</td>
    <td>F</td>
    <td>여자면 1, 아닐 경우 0</td>
    <td></td>
  </tr>
  <tr>
    <td>M</td>
    <td>남자면 1, 아닐 경우 0</td>
    <td></td>
  </tr>
  <tr>
    <td rowspan="5">성격 유형(Big-5 모델 기반)</td>
    <td>Extroversion</td>
    <td>외향성, 외향적일 수록 10에 가까운 점수(0~10)</td>
    <td></td>
  </tr>
  <tr>
    <td>Neuroticism</td>
    <td>신경질적 성향, 해당 성향이 높을 수록 10에 가까운 점수(0~10)</td>
    <td></td>
  </tr>
  <tr>
    <td>Conscientiousness</td>
    <td>성실성, 해당 성향이 높을 수록 10에 가까운 점수(0~10)</td>
    <td></td>
  </tr>
  <tr>
    <td>Agreeable</td>
    <td>해당 성향이 높을 수록 10에 가까운 점수(0~10)</td>
    <td></td>
  </tr>
  <tr>
    <td>Openness</td>
    <td>개방성, 해당 성향이 높을 수록 10에 가까운 점수(0~10)</td>
    <td></td>
  </tr>
  <tr>
    <td rowspan="6">사전 사용자 정신 건강 상태</td>
    <td>depression_or_not</td>
    <td>사용자의 기존 우울증 유무(PHQ9 설문 기반, 점수 총합이 10점 이상이면 주목할 만한 우울증)</td>
    <td></td>
  </tr>
  <tr>
    <td>anxietyDisorder_or_not</td>
    <td>사용자의 기존 불안 장애 유무(GAD7 설문 기반, 점수 총합이 6점이면 불안 장애)</td>
    <td></td>
  </tr>
  <tr>
    <td>PSS_pos_score</td>
    <td>Perceived Stress Scale(PSS) 설문 중 긍정 문항 점수 총합</td>
    <td></td>
  </tr>
  <tr>
    <td>PSS_neg_score</td>
    <td>Perceived Stress Scale(PSS) 설문 중 부정 문항 점수 총합</td>
    <td></td>
  </tr>
  <tr>
    <td>PSS_score</td>
    <td>Perceived Stress Scale(PSS) 설문 총합</td>
    <td></td>
  </tr>
  <tr>
    <td>PSS_stress_or_not</td>
    <td>사용자 기존 스트레스 정도(문항 총점이 13점 이상이면, 스트레스 정도가 정상이 아니라고 판단)</td>
    <td></td>
  </tr>
  <tr>
    <td>음성 데이터</td>
    <td></td>
    <td>before_audio</td>
    <td>before audio 설명</td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td></td>
    <td>after_audio</td>
    <td>after_audio 설명 </td>
    <td></td>
  </tr>
</tbody>
</table>
