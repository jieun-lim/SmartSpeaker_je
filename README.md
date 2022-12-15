<thead>
  <tr>
    <th class="tg-0pky">카테고리</th>
    <th class="tg-0pky">세부 카테고리</th>
    <th class="tg-0pky">피쳐 종류</th>
    <th class="tg-0pky">데이터 설명</th>
    <th class="tg-0pky">데이터 예시</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky" rowspan="6">스피커-사용자 설문 대화 데이터</td>
    <td class="tg-0pky">대화 길이&nbsp;&nbsp;</td>
    <td class="tg-0pky">whole_conv_length(sec)</td>
    <td class="tg-0pky">설문 1회당 소요 시간(초)</td>
    <td class="tg-0pky">1</td>
  </tr>
  <tr>
    <td class="tg-0pky">대화 속도 </td>
    <td class="tg-0pky">dixit_response_rate</td>
    <td class="tg-0pky">딕싯 그림 설명 사용자 답변 속도, (답변 텍스트 길이)/(답변길이)</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky" rowspan="4">정신 건강 설문 답변</td>
    <td class="tg-0pky">phq2_result</td>
    <td class="tg-0pky">사용자 우울증 상태,  우울증이 있을 확률이 높으면(PHQ2 점수 3점 이상) 1, 아니면 0.  </td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">gad2_result</td>
    <td class="tg-0pky">사용자 불안 장애 상태, 불안 장애가 있으면(GAD2 점수가 3점이상) 1, 아닐 경우 0</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">stress_result</td>
    <td class="tg-0pky">스트레스 유무, 스트레스가 평균 이상이면 1, 아니면 0</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">posNeg_result</td>
    <td class="tg-0pky">긍부정 감정 정도, 부정적인 감정 상태면 1, 아니면 0</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky" rowspan="6">센서 데이터</td>
    <td class="tg-0pky" rowspan="6">가정 환경 내 센서 데이터 </td>
    <td class="tg-0pky">dB</td>
    <td class="tg-0pky">설문 시작 직전 1분 평균 데시벨</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Temperature</td>
    <td class="tg-0pky">설문 시작 직전 1분 평균 온도</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Humidity</td>
    <td class="tg-0pky">설문 시작 직전 1분 평균 습도</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">CO2</td>
    <td class="tg-0pky">설문 시작 직전 1분 평균 CO2 농도</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">TVOC</td>
    <td class="tg-0pky">설문 시작 직전 1분 평균 공기질 오염도</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Light</td>
    <td class="tg-0pky">설문 시작 직전 1분 평균 조도값</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky" rowspan="13">사용자 실험 사전 설문</td>
    <td class="tg-0pky" rowspan="2">성별</td>
    <td class="tg-0pky">F</td>
    <td class="tg-0pky">여자면 1, 아닐 경우 0</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">M</td>
    <td class="tg-0pky">남자면 1, 아닐 경우 0</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky" rowspan="5">성격 유형(Big-5 모델 기반)</td>
    <td class="tg-0pky">Extroversion</td>
    <td class="tg-0pky">외향성, 외향적일 수록 10에 가까운 점수(0~10)</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Neuroticism</td>
    <td class="tg-0pky">신경질적 성향, 해당 성향이 높을 수록 10에 가까운 점수(0~10)</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Conscientiousness</td>
    <td class="tg-0pky">성실성, 해당 성향이 높을 수록 10에 가까운 점수(0~10)</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Agreeable</td>
    <td class="tg-0pky">해당 성향이 높을 수록 10에 가까운 점수(0~10)</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">Openness</td>
    <td class="tg-0pky">개방성, 해당 성향이 높을 수록 10에 가까운 점수(0~10)</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky" rowspan="6">사전 사용자 정신 건강 상태</td>
    <td class="tg-0pky">depression_or_not</td>
    <td class="tg-0pky">사용자의 기존 우울증 유무(PHQ9 설문 기반, 점수 총합이 10점 이상이면 주목할 만한 우울증)</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">anxietyDisorder_or_not</td>
    <td class="tg-0pky">사용자의 기존 불안 장애 유무(GAD7 설문 기반, 점수 총합이 6점이면 불안 장애)</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0pky">PSS_pos_score</td>
    <td class="tg-0pky">Perceived Stress Scale(PSS) 설문 중 긍정 문항 점수 총합</td>
    <td class="tg-0pky"></td>
  </tr>
  <tr>
    <td class="tg-0lax">PSS_neg_score</td>
    <td class="tg-0lax">Perceived Stress Scale(PSS) 설문 중 부정 문항 점수 총합</td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-0lax">PSS_score</td>
    <td class="tg-0lax">Perceived Stress Scale(PSS) 설문 총합</td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-0lax">PSS_stress_or_not</td>
    <td class="tg-0lax">사용자 기존 스트레스 정도(문항 총점이 13점 이상이면, 스트레스 정도가 정상이 아니라고 판단)</td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-0lax">음성 데이터</td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax">before_audio</td>
    <td class="tg-0lax">before audio 설명</td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-0lax"></td>
    <td class="tg-0lax"></td>
    <td class="tg-0lax">after_audio</td>
    <td class="tg-0lax">after_audio 설명 </td>
    <td class="tg-0lax"></td>
  </tr>
</tbody>
</table>
