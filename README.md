# hyewon<!doctype html>
<html lang="ko">
<head>
	<title>온라인 프로필</title>
	<meta charset="utf-8">
  <link rel="stylesheet" href="css/style.css">
  <style>
    table {
      width:70%;  /* 표의 너비 */
      border:1px solid #222; /* 1픽셀짜리 표 테두리 */
      border-collapse: collapse; /* 중복되는 표와 셀의 테두리를 한 줄로 표시 */
    }
    thead {
      background:#eee;  /* 제목 행의 배경 색 */
    }
    th, td {
      border:1px solid #ccc; /* 1픽셀짜리 셀 테두리 */
      padding:5px;  /* 셀 테두리와 셀 내용 사이의 여백(패딩) */
      font-size:0.8em;  /* 셀의 글자 크기 */
    }
    a, a:visited {
      color:#222;   /* 글자색 */
      text-decoration: none;  /* 밑줄 없앰 */
    }
    #sns > ul {
     padding-left:0;  /* 목록 들여쓰지 않기 */
    }
    #sns > ul > li {     
      display:inline-block;   /* 항목을 가로로 배열 */
      width:80px;   /* 각 항목의 너비 */
    }
  </style>
</head>

<body>
    <div id="container">
        <!-- 사이드바 -->
        <aside>
            <div id="namecard">
                <img src="images/pf.jpg" alt="">
                <h1>Kyunghee Ko</h1>    
                <p>오늘은 남은 인생이 시작되는 첫째날</p>
            </div>
            <div id="detail">
                <p>Jeju, Korea</p>
                <p>funcom@gmail.com</p>                                 
            </div>
            <div id="sns">
                <h2>SNS</h2>
                <ul>                    
					<li>
						<a href="https://www.facebook.com/funnycom">github</a>
					</li>
					<li>
						<a href="https://www.twitter.com/funnycom">google</a>
					</li>
				</ul>  
            </div>           
        </aside>
        <div id="main">
            <!-- 자기 소개 -->
            <section>
                <h2 class="subtitle">Who am I?</h2>
                <p><mark>나는 음악듣기</mark>에 관심이 많습니다. <br>현재 영광의 한 시골 마을에서 코딩 중입니다.</p>
            </section>

            <!-- 관심사 -->
            <section>
                <h2 class="subtitle">Experience</h2>
                <ul>
                    <li>미스터트롯
                        <ul>
                            <li>잉영웅</li>
                            <li>김희재</li>
                            <li>정동원</li> 
                        </ul>
                    </li>
                    <li>달이뜨는강
                        <ul>
                            <li>나인우</li>
                            <li>김소현</li>
                        </ul>                        
                    </li>
                </ul>             
            </section>

            <!-- 숙련도 -->
            <section>
                <h2 class="subtitle">Skills</h2>

            </section>

            <!-- 학력 -->
            <section>
                <h2 class="subtitle">Education</h2>
                <table>
                  <caption>가족관계</caption>
                  <thead>
                      <tr>
                          <th>부모님</th>
                          <th>조부모님</th>
                          <th>언니</th>
                          <th>여동생</th>
                      </tr>
                  </thead>
                  <tbody>
                      <tr>
                          <td>49살,46살</td>
                          <td>75살,68살</td>
                          <td>20살</td>
                          <td>11살</td>
                      </tr>
                      <tr>
                          <td>목사님,사모님</td>
                          <td>내가 제일 좋아하는 사람</td>
                          <td>전남대학교</td>
                          <td>함평신광초등학교</td>
                      </tr>
                  </tbody>
                </table>
            </section>
        </div>        
    </div>
</body>
</html>
