# Templates 

> 차트 시각화를 위한 Data Formatter Node와 개인 클라우드의 파일을 읽기 위한 File Cloud Node를 활용한 예시 Flow



### kcal.json

- 음식별 칼로리에 대한 엑셀 파일을 구글 드라이브에 저장하였으며 File Cloud Node를 통해 해당 파일을 읽어 Data Formatter Node에 전달합니다. 이후 Data Formatter Node에서는 엑셀 형태의 데이터를 Javascript Object로 변환하여 HTML-OUT 노드의 chart.js로 전달합니다. 이를 통해 시각화된 음식별 칼로리를 볼 수 있습니다.
- 이를 위해 구글 드라이브 또는 원드라이브에 첨부된 `kcal.xlsx`를 업로드 해야합니다. 또한 구글 드라이브 또는 원드라이브를 사용하기 위한 KEY를 발급받은 후에 입력해야 합니다.



### outing.json

- OPEN API와 File Cloud Node에서 받아온 데이터를 Data Formatter Node로 연결하여 기온, 강수량, 코로나 확진자 수, 지하철 혼잡도, 미세먼지를 시각화하여 웹 페이지에 렌더링하는 플로우입니다.
- 이를 위해 구글 드라이브 또는 원드라이브에 첨부된 `서울역 상선 혼잡도.xlsx`를 업로드 후에 사용해야 합니다.
