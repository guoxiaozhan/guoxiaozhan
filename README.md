<!DOCTYPE html>

<head>
    <title>Lunar new year</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</head>

<body>
    <h1>
        <img src="images/1.jpg" alt="title_left" class="title-img" align="left">
        <b>2022 Chinese new year</b>
        <img src="images/1.jpg" alt="title_right" class="title-img" align="right">
    </h1>
    <hr style="background: rgb(202, 36, 36);">

    <div class="container">
        <ul class="nav nav-tabs" role="tablist">
            <li class="nav item">
                <a href="#Banquet" class="nav-link avtive" data-toggle="tab">Banquet</a>
            </li>
            <li>
                <a href="#LuckyMoney" class="nav-link" data-toggle="tab">LuckyMoney</a>
            </li>
            <li>
                <a href="#Traditions" class="nav-link" data-toggle="tab">Traditions</a>
            </li>
            <li>
                <a href="#Greeting" class="nav-link" data-toggle="tab">New Years Greeting</a>
            </li>
        </ul>

        <div class="tab-content">
            <div id="Banquet" class="container tab-pane active">
                <!-- <b class="Title1">Banquet</b> -->
                <br/>
                <p>
                    2022年1月31日为中国的除夕节。除夕这一天，家家户户都要准备丰盛的年夜饭。年夜饭也叫“团圆饭”“合家欢”，是一年中的最后一顿饭，全家围坐在一起共进晚餐，辞旧岁。在菜肴上尽最大努力而使其丰富，宁可将其剩下，为的是取“顿顿有余”、“年年有余”的口彩，使人有充足感，预示全年丰衣足食，席间还要多说吉利话，以图皆大欢喜，值得一提的是，年夜饭的餐桌上都少不了一道鱼，年年有“鱼”，一年有“余”，图个吉祥，图个喜庆。年夜饭既有对即将逝去的旧岁有留恋之情，也有对即将到来的新年怀有希望之意。
                </p>
                <img src="images/banquet.png" alt="banquet">
                <br/>
            </div>
    
            <div id="LuckyMoney" class="container tab-pane fade">
                <!-- <b class="Title1">LuckyMoney</b> -->
                <p>
                    压岁钱一般在正月走亲访友时由长辈发给晚辈，数额不定。 压岁钱一般用红色纸张包裹因此也被称为发红包。 传统观念中的“压祟钱”是可以起到镇压鬼祟的作用的，是长辈给予晚辈的新春祝福，小孩子拿到压岁钱也就可以在新的一年顺顺利利、平平安安的。
                </p>
                <img src="images/luckymoney.png" alt="luckymoney">
            </div>

            <div id="Traditions" class="container tab-pane fade">
                <p>
                    我国过年历史悠久，在传承发展中已形成了一些较为固定的习俗，有许多还相传，如买年货、扫尘、贴对联、吃年夜饭、守岁、拜岁、拜年、舞龙舞狮、拜神祭祖、祈福攘灾、游神、押舟、庙会、游锣鼓、游标旗、上灯酒、赏花灯等。 传统的节日仪式与相关习俗活动，是节日元素的重要内容，承载着丰富多彩的节日文化底蕴。
                </p>
                <img src="images/tradition1.png" width="25%"/>
                <img src="images/tradition2.png" width="25%"/>
                <br/>
                <img src="images/tradition3.png" width="25%"/>
                <img src="images/tradition4.png" width="25%"/>
            </div>

            <div id="Greeting" class="container tab-pane fade">
                <p>
                    111
                </p>
                <img src="images/tradition1.png"/>
            </div>

            <!--
                <b class="Title1">Less reunion</b>
                <b class="Title1">Stay where you are</b>
                <b class="Title1">Short distance trip</b>
            -->
        </div>
    </div>
</body>

<style>
    .title-img{
        max-width: 100px;
    }
    b,li,a{
        color: rgb(202, 36, 36);
    }
    h1{
        text-align: center;
    }
    p {
        background-color: white; color: black; line-height: 25px; text-align: justify;
    }
</style>
