
 <!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <link rel="stylesheet" type="text/css" href="css/style.css">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
    <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet" type="text/css">
    <link href="https://fonts.googleapis.com/css?family=Lato" rel="stylesheet" type="text/css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
    <script type="text/javascript">

    </script>
    <style>
        .navbar {
            margin-bottom: 0;
            background-color: #7effef;
            z-index: 9999;
            border: 0;
            font-size: 12px !important;
            line-height: 1.42857143 !important;
            letter-spacing: 4px;
            border-radius: 0;
            font-family: 'Malgun Gothic';
        }

            .navbar li a, .navbar .navbar-brand {
                color: #777 !important;
            }

        .navbar-nav li a:hover, .navbar-nav li.active a {
            color: #7fd3c8 !important;
            background-color: #68b2a8 !important;
        }

        .navbar-default .navbar-toggle {
            border-color: transparent;
            color: #777 !important;
        }

        .contents {
            padding: 85px 60px;
        }

        .footer {
            background-color: #72d1e6;
            text-align: center;
        }
        .cirno
        {
            background-color:#acacac;
            color:#ffffff;
        }
        .hadan {
            background-color: #808080;
        }

        .copyright {
            color: azure;
        }
        .background {
        }
    </style>
    <title>오늘 뭐 들었지?</title>
</head>
<body>
        <nav class="navbar navbar-default navbar-fixed-top">
            <div class="container">
                <div class="navbar-header">
                    <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                        <span class="icon-bar"></span>
                    </button>
                    <a class="navbar-brand" href="about.html">내일 뭐 들었지</a>
                </div>
                <div class="collapse navbar-collapse" id="myNavbar">
                    <ul class="nav navbar-nav navbar-right">
                        <li><a href="todaytable.html">오늘 시간표</a></li>
                        <li><a href="weektable.html">주간 시간표</a></li>
                        <li><a href="weather.html">날씨</a></li>
                        <li class="dropdown">
                            <a href="#" class="dropdown-toggle" data-toggle="dropdown">
                                <span>테마 변경</span>
                                <span class="caret"></span>
                            </a>
                            <ul class="dropdown-menu">
                                <li><a href="about.html">나는 노말한 프렌즈에요.</a></li>
                                <li><a href="about_theme_kemono.html">케모노 프렌즈</a></li>
                                <li><a href="about_theme_newgame.html">뉴 게임</a></li>
                                <li><a href="about_theme_quest.html">크루세이더 퀘스트</a></li>
                            </ul>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    <div class="background">
        <div id="contents" class="contents">
            <div id="content-I" class="cont_1">
                <div class="cirno"><h3>야, 내일 뭐 들었지?</h3></div>
                <h4>이제 물어보지 않아도 됩니다.</h4>
                <p>하던 수행평가의 제출이 다음 영어시간인데 진행도는 0%. </p>
                <p>급하게 떠올라 친구들에게 내일 영어가 들었냐고 물어봐도 친구들은 다 잠들어 있는 상황.</p>
                <p>혼자 내일 영어가 들었는지 안 들었는지 고민하는 상황에서 급히 시간표를 알 수 있는 사이트입니다.<strong><br>"아 내일 안 들었네."</strong></p>
            </div>
            <hr />
            <div id="content-II" class="cont_2">
                <div class="cirno"><h3>편하게 볼 수 있습니다.</h3></div>
                <h4>일일히 찾아갈 필요 없습니다.</h4>
                <p>한 번 자신의 학과를 정해두면 일일히 자신의 학과를 찾아 들어가지 않아도 지정해둔 학과의 시간표를 출력합니다.<strong><br>"아이 편해."</strong></p>
            </div>
			<hr />
			<div id="content-III" class="cont_3">
                <div class="cirno"><h3>다른 반 시간표의 체크까지.</h3></div>
                <p> 체육복이나 책을 옆 반 친구에게 빌려야 할 때에 옆 반 친구가 나에게 빌려줄 여건의 시간표 체크가 될까요?<strong><br>"당연하죠"</strong></p>
            </div>
        </div>
        <div id="footer-1">
            <p align="center">17시가 될 때마다 내일 시간표로 갱신됩니다.</p>
        </div>
        <div id='foot'>
            <footer class="container-fluid text-center hadan">
                <div><img width="200" src="./img/환상향_하양.png" /></div>
               <div class="copyright">copyright@gensokyo, The Solidarity of Kim-Sang-Gueon, #AirKORAIL all rights reserved </div>
                </footer>
        </div>
    </div>
</body>
</html>
