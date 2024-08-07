
<!DOCTYPE html>

<script src="./scripts/app.js"></script>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!--=============== FAVICON ===============-->
    <link rel="shortcut icon"
        href="./image/avatar.jpg"
        type="image/x-icon">

    <!--=============== REMIX ICONS ===============-->
    <link href="./fonts/remixicon.css" rel="stylesheet">

    <!--=============== CSS ===============-->
    <link rel="stylesheet" href="./css/styles.css">

    <title>Profile</title>
</head>

<body>

    <div class="snowflakes" aria-hidden="true">
        <div class="snowflake">🥹</div>
        <div class="snowflake">🥲</div>
        <div class="snowflake">☠️</div>
        <div class="snowflake">🐧</div>
        <div class="snowflake">🐸</div>
        <div class="snowflake">🙉</div>
        <div class="snowflake">🙈</div>
        <div class="snowflake">🐸</div>
        <div class="snowflake">🐧</div>
        <div class="snowflake">😘</div>
        <div class="snowflake">😍</div>
        <div class="snowflake">😻</div>
    </div>

    <!--=============== HEADER ===============-->
    <header class="profile container">
        <!-- Theme button -->
        <i class="ri-moon-line change-theme" id="theme-button"></i>

        <div class="profile__container grid">
            <div class="profile__data">
                <div class="profile__border">
                    <div class="profile__perfil">
                        <!-- Insert your image, according to the example size of the portfolio -->
                        <img src="./image/avatar.jpg" alt="" style="width: 540px;
  
      height: 120px;">
                    </div>
                </div>

                <h2 class="profile__name">Lê Quang Dương<i data-visualcompletion="css-img" aria-label="Tài khoản đã xác minh" class="" role="img" style="background-image: url(&quot;https://static.xx.fbcdn.net/rsrc.php/v3/yf/r/AOac759jBKZ.png&quot;); background-position: -168px -153px; background-size: auto; width: -5px; height: 16px; background-repeat: no-repeat; display: inline-block;"></i>
                </h2>

                <h3 class="profile__profession">Ăn Bám Gia đình</h3>

                <ul class="profile__social">
                    <a href="https://fb.me/idolfifai2007" target="_blank" class="profile__social-link">
                        <i class="ri-facebook-fill"></i>
                    </a>
                    <a href="https://zalo.me/0375892307" target="_blank" class="profile__social-link">
                        <i class="ri-question-answer-fill"></i>
                    </a>
                </ul>
            </div>

            <div class="profile__info grid">
                <div class="profile__info-group">
                    <h3 class="profile__info-number">11/01/2007</h3>
                    <p class="profile__info-description">
                        Ngày sinh<br>
                    </p>
                </div>
                <div class="profile__info-group">
                    <h3 class="profile__info-number">2k+</h3>
                    <p class="profile__info-description">
                        Follow
                    </p>
                </div>
                <div class="profile__info-group">
                    <h3 class="profile__info-number">Bình Dương</h3>
                    <p class="profile__info-description">Vị Trí <br> </p>
                </div>
            </div>
            <div class="profile__buttons">
                <div class="profile__buttons-small">
                    <!-- Insert your brand name or profile -->
                    <a href="https://facebook.com/messages/t/idolfifai2007" target="_blank" class="button button__small button__gray">
                        <i class="ri-messenger-line"></i>
                    </a>
                </div>
                <div class="profile__buttons-small">
                    <!-- Insert your brand name or profile -->
                    <a href="https://github.com/Duongle5633" target="_blank" class="button button__small button__gray">
                        <i class="ri-github-line"></i>
                    </a>
                </div>
                <div class="profile__buttons-small">
                    <!-- Insert your brand name or profile -->
                    <a href="https://youtube.com/@KhanhNguyen9872_Official_v2" target="_blank" class="button button__small button__gray">
                        <i class="ri-youtube-line"></i>
                    </a>
                </div>
                <div class="profile__buttons-small">
                    <!-- Insert your brand name or profile -->
                    <a href="https://t.me/Fox11012007" target="_blank" class="button button__small button__gray">
                        <i class="ri-telegram-line"></i>
                    </a>
                </div>
                <div class="profile__buttons-small">
                    <!-- Insert your brand name or profile -->
                    <a href="https://youtu.be/dQw4w9WgXcQ?si=qr14hEFm0XBspCBy" target="_blank" class="button button__small button__gray">
                        <i class="ri-google-line"></i>
                    </a>
                </div>
            </div>
        </div>
    </header>

    <!--=============== MAIN ===============-->
    <main class="main">
        <section class="filters container">
            <!--=============== FILTERS TABS ===============-->

            <ul class="filters__content">
                <button class="filters__button filter-tab-active" data-target="#projects">
                    Website     
                </button>

                <button class="filters__button" data-target="#skills">
                    Kỹ Năng
                </button>

                <button class="filters__button" data-target="#learn">
                    Trình độ học vấn
                </button>

                <button class="filters__button" data-target="#myself">
                    Bản thân
                </button>

            </ul>

            <div class="filters__sections">

                <!--=============== PROJECTS ===============-->
                <!-- Insert your image in a rectangular format (Ex: 600 x 400, 1000 x 800, 1200 x 1000, etc) -->

                <div class="skills__content grid" data-content id="myself">
                    <div class="skills__area">
                        <h3 class="skills__title">Tóm tắt</h3>

                        <div class="skills__box">
                            <div class="skills__group">
                                <div>
                                    <h3 class="skills__name">Đam mê ngành công nghệ thông tin từ khi còn cấp 2</h3>
                                </div>
                                <div>
                                    <h3 class="skills__name">Sống điềm tĩnh, thích ứng nhanh với môi trường mới, hứng thú với công việc và tìm ra vấn đề giải quyết cho vấn đề</h3>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="skills__area">
                        <h3 class="skills__title">Định hướng nghề nghiệp</h3>

                        <div class="skills__box">
                            <div class="skills__group">
                                <div class="skills__data">
                                    <i class="ri-checkbox-circle-line"></i>
                                    <div>
                                        <h3 class="skills__name">Ngắn hạn</h3>
                                        <span class="skills__level">Có công việc ổn định, tích lũy thêm nhiều kinh nghiệm</span>
                                    </div>
                                </div>

                                <div class="skills__data">
                                    <i class="ri-checkbox-circle-line"></i>
                                    <div>
                                        <h3 class="skills__name">Dài hạn</h3>
                                        <span class="skills__level">Có cơ hội được làm nhân viên cấp cao</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="skills__content grid" data-content id="learn">
                    <div class="skills__area">
                        <h3 class="skills__title">THPT Lê Lợi</h3>

                        <div class="skills__box">
                            <div class="skills__group">
                                <div class="skills__data">
                                    <i class="ri-checkbox-circle-line"></i>

                                    <div>
                                        <h3 class="skills__name">Tình trạng</h3>
                                        <span class="skills__level">Đã Tốt Nghiệp</span>
                                    </div>
                                </div>

                                <div class="skills__data">
                                    <i class="ri-checkbox-circle-line"></i>

                                    <div>
                                        <h3 class="skills__name">Tốt nghiệp</h3>
                                        <span class="skills__level">Loại khá</span>
                                    </div>
                                </div>

                                <div class="skills__data">
                                    <i class="ri-checkbox-circle-line"></i>

                                    <div>
                                        <h3 class="skills__name">Thời gian</h3>
                                        <span class="skills__level">09/2021 - 08/2024</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="skills__area">
                        <h3 class="skills__title">Chưa tốt nghiệp</h3>

                        <div class="skills__box">
                            <div class="skills__group">
                                <div class="skills__data">
                                    <i class="ri-checkbox-circle-line"></i>

                                    <div>
                                        <h3 class="skills__name">Tình trạng</h3>
                                        <span class="skills__level">Chưa tốt nghiệp</span>
                                    </div>
                                </div>

                                <div class="skills__data">
                                    <i class="ri-checkbox-circle-line"></i>

                                    <div>
                                        <h3 class="skills__name">Ngành học</h3>
                                        <span class="skills__level">Kỹ thuật phần mềm</span>
                                    </div>
                                </div>

                                <div class="skills__data">
                                    <i class="ri-checkbox-circle-line"></i>

                                    <div>
                                        <h3 class="skills__name">Thời gian</h3>
                                        <span class="skills__level">Chưa tốt nghiệp</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="projects__content grid filters__active" data-content id="projects">

                    <article class="projects__card">
                        <img src="./image/post000.jpg" alt="" class="projects__img">

                        <div class="projects__modal">
                            <div>
                                <span class="projects__subtitle">Discord</span>
                                <h3 class="projects__title">FoxVôTri#4884</h3>
                                <a href="https://discord.com/invite/gsF2MDqpW3"
                                    class="projects__button button button__small">
                                    <i class="ri-eye-fill"></i>
                                </a>
                            </div>
                        </div>
                    </article>

                    <article class="projects__card">
                        <img src="./image/post001.png" alt="" class="projects__img">

                        <div class="projects__modal">
                            <div>
                                <span class="projects__subtitle">Tài Khoản Instagram</span>
                                <h3 class="projects__title">Không Có gì Đâu mà xem=))</h3>
                                <a href="https://www.instagram.com/lqd.1102207?igsh=cTl2ejhqb2g3NWp2"
                                    class="projects__button button button__small">
                                    <i class="ri-eye-fill"></i>
                                </a>
                            </div>
                        </div>
                    </article>
                </div>

                <!--=============== skills ===============-->
                <div class="skills__content grid" data-content id="skills">
                    <div class="skills__area">
                        <h3 class="skills__title">Ngôn ngữ kịch bản</h3>

                        <div class="skills__box">
                            <div class="skills__group">
                                <div class="skills__data">
                                    <i class="ri-checkbox-circle-line"></i>

                                    <div>
                                        <h3 class="skills__name">Batch script</h3>
                                        <span class="skills__level">Cơ bản</span>
                                    </div>
                                </div>

                                <div class="skills__data">
                                    <i class="ri-checkbox-circle-line"></i>

                                    <div>
                                        <h3 class="skills__name">Bash script</h3>
                                        <span class="skills__level">Nâng cao</span>
                                    </div>
                                </div>

                                <div class="skills__data">
                                    <i class="ri-checkbox-circle-line"></i>

                                    <div>
                                        <h3 class="skills__name">Powershell</h3>
                                        <span class="skills__level">Cơ bản</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="skills__area">
                        <h3 class="skills__title">Ngôn Ngữ Lập Trình</h3>

                        <div class="skills__box">
                            <div class="skills__group">
                                <div class="skills__data">
                                    <i class="ri-checkbox-circle-line"></i>

                                    <div>
                                        <h3 class="skills__name">PHP</h3>
                                        <span class="skills__level">Cơ bản</span>
                                    </div>
                                </div>

                                <div class="skills__data">
                                    <i class="ri-checkbox-circle-line"></i>

                                    <div>
                                        <h3 class="skills__name">Python</h3>
                                        <span class="skills__level">Trung bình</span>
                                    </div>
                                </div>
                            </div>

                            <div class="skills__group">
                                <div class="skills__data">
                                    <i class="ri-checkbox-circle-line"></i>

                                    <div>
                                        <h3 class="skills__name">C/C++ </h3>
                                        <span class="skills__level">Trung Bình</span>
                                    </div>
                                </div>

                                <div class="skills__data">
                                    <i class="ri-checkbox-circle-line"></i>

                                    <div>
                                        <h3 class="skills__name">Java</h3>
                                        <span class="skills__level">Cơ bản</span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

            </div>
            </div>
        </section>
    </main>
    </div>
    </div>
    </section>

    </main>


    <footer class="footer container">
        <span class="footer__copy">
                Copyright © 2024 <a href='https://fb.me/idolfifai2007'> Lê Quang Dương</a>. All Rights Reserved.
            </span>
    </footer>

    <!--=============== SCROLLREVEAL ===============-->
    <script src="./scripts/scrollreveal.min.js"></script>

    <!--=============== MAIN JS ===============-->
    <script src="./scripts/main.js"></script>
</body>

</html>

<style>
    @-webkit-keyframes snowflakes-fall {
        0% {
            top: -10%
        }

        100% {
            top: 100%
        }
    }

    @-webkit-keyframes snowflakes-shake {

        0%,
        100% {
            -webkit-transform: translateX(0);
            transform: translateX(0)
        }

        50% {
            -webkit-transform: translateX(80px);
            transform: translateX(80px)
        }
    }

    @keyframes snowflakes-fall {
        0% {
            top: -10%
        }

        100% {
            top: 100%
        }
    }

    @keyframes snowflakes-shake {

        0%,
        100% {
            transform: translateX(0)
        }

        50% {
            transform: translateX(80px)
        }
    }

    .snowflake {
        color: #fff;
        font-size: 1em;
        font-family: Arial, sans-serif;
        text-shadow: 0 0 5px #000;
        position: fixed;
        top: -10%;
        z-index: 9999;
        -webkit-user-select: none;
        -moz-user-select: none;
        -ms-user-select: none;
        user-select: none;
        cursor: default;
        -webkit-animation-name: snowflakes-fall, snowflakes-shake;
        -webkit-animation-duration: 10s, 3s;
        -webkit-animation-timing-function: linear, ease-in-out;
        -webkit-animation-iteration-count: infinite, infinite;
        -webkit-animation-play-state: running, running;
        animation-name: snowflakes-fall, snowflakes-shake;
        animation-duration: 10s, 3s;
        animation-timing-function: linear, ease-in-out;
        animation-iteration-count: infinite, infinite;
        animation-play-state: running, running;
    }

    .snowflake:nth-of-type(0) {
        left: 1%;
        -webkit-animation-delay: 0s, 0s;
        animation-delay: 0s, 0s
    }

    .snowflake:nth-of-type(1) {
        left: 10%;
        -webkit-animation-delay: 1s, 1s;
        animation-delay: 1s, 1s
    }

    .snowflake:nth-of-type(2) {
        left: 20%;
        -webkit-animation-delay: 6s, .5s;
        animation-delay: 6s, .5s
    }

    .snowflake:nth-of-type(3) {
        left: 30%;
        -webkit-animation-delay: 4s, 2s;
  
