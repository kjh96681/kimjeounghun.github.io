<!DOCTYPE html>

<html>
	<head>
		<meta charset="utf-8"/>

		<title>Kihoon`s HomePage</title>
		<style type="text/css">
		/* reset */
body,div,dl,dt,dd,ul,ol,li,h1,h2,h3,h4,h5,h6,pre,code,form,fieldset,legend,textarea,p,blockquote,th,td,input,select,textarea,button {margin:0;padding:0}
fieldset,img {border:0 none}
dl,ul,ol,menu,li {list-style:none}
blockquote, q {quotes: none}
blockquote:before, blockquote:after,q:before, q:after {content:'';content:none}
input,select,textarea,button {vertical-align:middle}
button {border:0 none;background-color:transparent;cursor:pointer}
body {background:#fff}
body,th,td,input,select,textarea,button {font-size:12px;line-height:1.5;font-family:'돋움',dotum,sans-serif;color:#333} /* color값은 디자인가이드에 맞게사용 */
a {color:#333;text-decoration:none}
a:active, a:hover {text-decoration:underline}
address,caption,cite,code,dfn,em,var {font-style:normal;font-weight:normal}
#wrap {width: 1000px; height: 800px; margin-left: auto;
			margin-right: auto;}
            .form li {float:  left; width: 100%; height: 25px;}
			.form li span {float: left; width: 100px; height:  25px; padding-left: 15px; line-height: 25px; background-color:  #ccc;}
			#see {float: none;}
		</style>
	</head>

	<body>
	<div class="form" id="wrap">
		<form method="post" action="#">
		<li>
			<span>학교</span>
			<input type="text" name="school"/>
			<input type="button" name="btn_search_school" value="학교찾기 "/>
			</li>
		<li>
			<span>담당학년</span>
			<select name="grade"></select>학년
			<select name="class_number"></select>반
			</li>
		<li>
			<span>학교전화</span>
			<select name="school_head_call_num"></select>
			<input type="text" name="school_middle_call_num" />
			<input type="text" name="school_last_call_num" />
			</li>
		<li>
			<span>휴대전화</span>
			<select name="phone_number"></select>
			<input type="text" name="phone_number_first" />
			<input type="text" name="phone_number_second" />
			</li>
		<li>
			<span>교사인증</span>
			<input type="file" name="teacher"/>

			<span id = "see"><a href="#">[자세한 방법 보기]</span>
			</li>
		<li>
			<span>간단한 인사 및 소개</span>
			<textarea name="user_input"></textarea>
			</li>

		<div>
			<input type="submit" value="확인" />
			<input type="reset" value="취소" />
		</div>
		</form>
	</div>
	</body>
</html>
