# ALCUK-PracticeChecker
알쿡 과제 채점프로그램
www.acmicpc.net 사이트에서 연습 현황을 긁어 붙여넣으면 입력한 커트라인에 따라 과제 수행여부를 판단하고 반별로 나누어 미달자를 출력해줌


<strong>V0.1 </strong>
<h1></h1>
<p><b>issue</b></p>
과제를 한문제도 제출하지 않은 과제 미수행자는 기록에서 누락됨. -> map에 공간을 하나 더 두어서 체크 형태로 수정해야함
과제 해결수가 10개를 넘어갈경우 1의 자리만 체크됨 -> 다른 기준으로 숫자 잘라오기
<h1></h1>  
<p><b>todo</b></p>
과제의 유형(ex)대회, 시니어/시니어기초/주니어과제) 에따른 채점 대상의 반을 구분하여 체크하는 선택기능 필요
과제를 한문제도 풀지않은 인원에 대한 정보 출력 필요


<strong>V0.2 </strong>
<h1></h1>
<p><b>update</b></p>
과제를 한문제도 제출하지 않은 과제 미수행자는 기록에서 누락되는 문제 해결
과제 해결수가 10개를 넘어갈경우 1의 자리만 체크됨 -> 10개인경우만 해결
과제의 종류에따른 대상되는 반의 정보만 출력하게됨
<h1></h1>  
<p><b>issue</b></p>
과제 해결수가 10개를 초과할 경우 숫자를 판별하지 못함.
<h1></h1>  
<p><b>todo</b></p>
10개를 초과하는 과제수에대한 문제 해결 필요...
