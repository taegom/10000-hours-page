# 10000-hours-page
desktop 버전과 mobile 버전 두가지 

<!DOCTYPE html>
<html lang="ko-KR">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="./css/10000hours.css" />
    <link rel="stylesheet" href="./css/reset.css" />
    <link rel="icon" href="./img/favicon.ico" />
    <title>10000 hours</title>

    <style>
      @font-face {
        font-family: "Noto Sans KR";
        font-style: normal;
        font-weight: 400;
        src: url("https://fonts.gstatic.com/ea/notosanskr/v2/NotoSansKR-Regular.woff2")
            format("woff2"),
          url("https://fonts.gstatic.com/ea/notosanskr/v2/NotoSansKR-Regular.woff")
            format("woff"),
          url("https://fonts.gstatic.com/ea/notosanskr/v2/NotoSansKR-Regular.otf")
            format("opentype");
      }

      @font-face {
        font-family: "OTEnjoystoriesBA";
        src: url("https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_two@1.0/OTEnjoystoriesBA.woff")
          format("woff");
        font-weight: normal;
        font-style: normal;
      }

      @font-face {
        font-family: "GmarketSansBold";
        src: url("https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_2001@1.1/GmarketSansBold.woff")
          format("woff");
        font-weight: normal;
        font-style: normal;
      }

      @font-face {
        font-family: "GmarketSansMedium";
        src: url("https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_2001@1.1/GmarketSansMedium.woff")
          format("woff");
        font-weight: normal;
        font-style: normal;
      }

      .foster {
        width: 1920px;
        height: 1963px;
        background-color: #5b2386;
      }

      .title {
        width: 564px;
        height: 112px;
        margin-top: 139px;
        margin-left: 618px;
        padding: 60px;
        background-image: url(./img/clock.png);
        background-repeat: no-repeat;

        background-position: center;
      }

      .quotation {
        width: 486px;
        height: 40px;
        margin-top: 65px;
        margin-left: 717px;
        font-family: "OTEnjoystoriesBA";
        font-size: 36px;
        font-weight: 700;
        line-height: 39.6px;
        text-align: center;
        color: #f5df4d;
      }

      .explanation {
        width: 373px;
        height: 85px;
        margin-top: 78px;
        margin-left: 654px;
        color: #fff;
        text-align: center;
        justify-content: center;
        line-height: 24px;
        padding-left: 120px;
        padding-right: 120px;

        background-image: url(./img/quotes.png);
        background-repeat: no-repeat;
        background-size: 493px;
        background-position: center;
      }

      .subject {
        font-family: "GmarketSansBold";
        font-size: 24px;
        font-weight: 700;
      }

      .subject1,
      .subject2,
      .subject3 {
        font-family: "GmarketSansMedium";
        font-size: 18px;
        font-weight: 400;
        white-space: nowrap;
      }

      .resolve1 {
        width: 514px;
        height: 57px;
        margin-top: 102px;
        margin-left: 703px;
        text-align: center;
        color: #fff;
        font-family: "GmarketSansMedium";
        font-size: 24px;
        font-weight: 400;
        line-height: 24px;
      }

      .job {
        width: 228px;
        height: 57px;
        border-radius: 7px;
        font-family: "GmarketSansMedium";
        font-size: 24px;
        font-weight: 400;
        line-height: 24px;
        text-align: center;
      }

      .resolve2 {
        width: 765px;
        height: 57px;
        margin-top: 27px;
        margin-left: 578px;
        font-family: "GmarketSansMedium";
        font-size: 24px;
        font-weight: 400;
        line-height: 24px;
        text-align: center;
        color: #fff;
      }

      .resolve3,
      .resolve4 {
        display: inline;
      }

      .hours {
        width: 228px;
        height: 57px;
        border-radius: 7px;
        font-family: "GmarketSansMedium";
        font-size: 24px;
        font-weight: 400;
        line-height: 24px;
        text-align: center;
      }

      .click {
        width: 565px;
        height: 66px;
        margin-top: 115px;
        margin-left: 678px;
        padding: 21px 49px 21px 49px;
        gap: 10px;
        border-radius: 56px;

        background-color: #fcee21;

        font-family: "GmarketSansMedium";
        font-size: 24px;
        font-weight: 700;
        line-height: 24px;
        text-align: center;
        color: #5b2386;
        white-space: nowrap;
      }

      .explanation2 {
        width: 663px;
        height: 72px;
        margin-top: 147px;
        margin-left: 629px;
        gap: 12px;

        color: #fff;

        font-family: "GmarketSansMedium";
        font-size: 24px;
        font-weight: 400;
        line-height: 24px;
        text-align: left;
      }

      .subject5 {
        font-size: 72px;
        font-weight: 700;
        line-height: 72px;
        text-align: left;
      }

      .explanation3 {
        width: 541px;
        height: 72px;
        margin-top: 17px;
        margin-left: 690px;
        gap: 12px;

        color: #fff;

        font-family: "GmarketSansMedium";
        font-size: 24px;
        font-weight: 400;
        line-height: 24px;
        text-align: left;
      }

      .subject7 {
        font-family: "GmarketSansMedium";
        font-size: 72px;
        font-weight: 700;
        line-height: 72px;
        text-align: left;
      }

      .ad {
        display: flex;
        justify-content: center;
        align-items: center;
        gap: 10px;
      }

      .gogo {
        width: 356px;
        height: 66px;
        margin-top: 127px;
        border-radius: 56px;
        background-color: #fcee21;
        font-family: "GmarketSansMedium";
        font-size: 24px;
        font-weight: 700;
        line-height: 24px;
        color: #5b2386;
        justify-content: center;
        align-items: center;
        flex-wrap: nowrap;
      }

      .share {
        width: 191px;
        height: 66px;
        border-radius: 56px;
        font-family: "GmarketSansMedium";
        font-size: 24px;
        font-weight: 700;
        line-height: 24px;
        color: #5b2386;
        justify-content: center;
        align-items: center;
        margin-top: 127px;
      }

      .logo {
        width: 125px;
        height: 25px;
        margin-top: 130px;
        margin-left: 897px;
      }

      .copyright {
        width: 365px;
        height: 34px;
        margin-top: 20px;
        margin-left: 778px;
        white-space: nowrap;
        justify-content: center;
        align-items: center;
      }

      footer {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        text-align: center;
      }

      .logo {
        width: 125px;
        height: 25px;
        margin-top: 130px;

        margin-left: 0;
      }

      .copyright {
        width: 365px;
        height: 34px;
        margin-top: 20px;

        margin-left: 0;
        text-align: center;
      }

      .word1,
      .word2 {
        font-family: "Noto Sans KR";
        font-size: 12px;
        font-weight: 400;
        line-height: 17.38px;
        flex-wrap: nowrap;
        color: #fff;
        text-align: center;
      }

      @media (max-width: 480px) {
        body {
          height: 1176px;
          border: 1px;
          justify-content: center;
        }

        .title {
          width: 267px;
          height: 53px;
          margin-top: 65px;
          margin-left: 0px;
          justify-content: center;
          background-size: 125px 126px;
        }

        .quotation {
          width: 297px;
          height: 24px;
          margin-top: 31px;
          margin-left: 32px;
          font-family: "OTEnjoystoriesBA";
          font-size: 22px;
          font-weight: 700;
          line-height: 24.2px;
          justify-content: center;
          text-align: center;
          color: #f5df4d;
        }

        .explanation {
          width: 290px;
          height: 68px;
          margin-top: 62px;
          margin-left: 35px;
          font-family: "GmarketSansMedium";
          font-size: 14px;
          font-weight: 700;
          line-height: 24px;
          text-align: center;
          justify-content: center;
          padding-left: 0px;

          background-position: left;
          background-size: 302px 14px;
        }

        .subject {
          font-family: "GmarketSansBold";
          font-size: 14px;
          font-weight: 700;
          text-align: center;
        }

        .subject1,
        .subject2,
        .subject3 {
          font-family: "GmarketSansMedium";
          font-size: 14px;
          font-weight: 400;
          white-space: nowrap;
        }

        .resolve1 {
          width: 311px;
          height: 37px;
          margin-top: 62px;
          margin-left: 25px;

          text-align: center;
          color: #fff;
          font-family: "GmarketSansMedium";
          font-size: 14px;
          font-weight: 400;
          line-height: 14px;
          white-space: nowrap;
        }

        .job {
          width: 156px;
          height: 37px;

          border-radius: 7px;
          font-family: "GmarketSansMedium";
          font-size: 14px;
          font-weight: 400;
          line-height: 14px;
          text-align: center;
          color: #babcbe;
        }

        .resolve2 {
          margin-left: 0px;
          width: 160px;
          height: 37px;
          margin-top: 27px;
          margin-left: 0px;
        }

        .resolve3 {
          width: 160px;
          height: 14px;
          font-size: 14px;
          text-align: center;

          white-space: nowrap;
          margin-left: 100px;
          margin-top: 17px;
        }

        .resolve4 {
          width: 156px;
          height: 37px;

          border-radius: 7px;
          font-family: "GmarketSansMedium";
          font-size: 14px;
          font-weight: 400;
          line-height: 14px;
          text-align: center;
          margin-left: 43px;
          white-space: nowrap;
          margin-top: 19px;
        }

        .hours {
          width: 156px;
          height: 37px;
          font-size: 14px;
          color: #babcbe;
        }

        .click {
          width: 241px;
          height: 68px;
          border-radius: 13px;
          padding: 23px 49px 21px 49px;
          gap: 10px;
          background-color: #fcee21;
          box-shadow: 0px 0px 10px 0px #00000080;
          color: #5b2386;
          font-size: 14px;
          line-height: 14px;
          font-weight: 700;
          text-align: center;

          margin-left: 56px;
          margin-top: 49px;
          white-space: wrap;
        }

        .explanation2 {
          width: 303px;
          height: 24px;
          margin-left: 29px;
          margin-top: 64px;
        }

        .subject4 {
          font-size: 14px;
          line-height: 14px;
        }

        .subject5 {
          font-size: 24px;
          line-height: 24px;
        }

        .explanation3 {
          width: 276px;
          height: 24px;
          margin-left: 42px;
          margin-top: 15px;
        }

        .subject6 {
          font-size: 14px;
          line-height: 14px;
        }

        .subject7 {
          font-size: 24px;
          line-height: 24px;
        }

        .ad {
          width: 360px;
          margin-left: 0px;
        }

        .gogo {
          width: 186px;
          height: 40px;
          margin-left: 31px;
          margin-top: 55px;
          font-size: 14px;
          line-height: 14px;
        }

        .share {
          width: 92px;
          height: 40px;
          font-size: 14px;
          line-height: 14px;
          margin-left: 13px;
          margin-top: 55px;
        }

        footer {
          width: 360px;
          display: flex;
          flex-direction: column;
          align-items: center;
          justify-content: center;
        }

        .logo {
          width: 91px;
          height: 18px;
          margin-top: 83px;
          justify-content: center;
          align-items: center;
        }

        .copyright {
          margin-top: 10px;
          width: 274px;
          height: 26px;
          text-align: center;
        }

        .word1,
        .word2 {
          font-size: 9px;
          line-height: 13.03px;
          text-align: center;
          margin-left: 0;
          margin-top: 5px;
          white-space: nowrap;
        }
      }
    </style>
  </head>
  <body>
    <div class="foster">
      <div class="header">
        <img src="./img/title.png" alt="1만 시간의 법칙" class="title" />
      </div>

      <div class="main">
        <div class="quotation">
          <q>"연습은 어제의 당신보다 당신을 더 낫게 만든다."</q>
        </div>

        <section class="explanation">
          <p class="subject">1만 시간의 법칙<span class="subject1">은</span></p>
          <p class="subject2">어떤 분야의 전문가가 되기 위해서는</p>
          <p class="subject3">최소한 1만 시간의 훈련이 필요하다는 법칙이다.</p>
        </section>

        <div class="resolve1">
          나는
          <input type="text" class="job" placeholder="예)프로그래밍" /> 전문가가
          될 것이다.
        </div>

        <div class="resolve2">
          <p class="resolve3">그래서 앞으로 매일 하루에</p>
          <p class="resolve4">
            <input type="text" class="hours" placeholder="예)5시간" /> 시간씩
            훈련할 것이다.
          </p>
        </div>

        <section>
          <button class="click">
            나는 며칠 동안 훈련을 해야 1만 시간이 될까?
          </button>

          <img src="./img/click.png" alt="클릭하는 모양" />
        </section>

        <section class="explanation2">
          <p class="subject4">
            당신은
            <span class="subject5">프로그래밍</span>
            전문가가 되기 위해서
          </p>
        </section>

        <section class="explanation3">
          <p class="subject6">
            대략
            <span class="subject7">5110</span>
            일 이상 훈련하셔야 합니다!:)
          </p>
        </section>

        <div class="ad">
          <button class="gogo">훈련하러 가기 GO!GO!</button>

          <button class="share">공유하기</button>
        </div>
      </div>

      <footer>
        <img src="./img/logo.png" alt="위니브 로고" class="logo" />
        <div class="copyright">
          <p class="word1">
            ※ 본 서비스 내 이미지 및 콘텐츠의 저작권은 주식회사 WeNiv에
            있습니다.
          </p>

          <p class="word2">
            수정 및 재배포, 무단 도용 시 법적인 문제가 발생할 수 있습니다.
          </p>
        </div>
      </footer>
    </div>
  </body>
</html>
