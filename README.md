# 2021web
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=`, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="css/reset.css">
    <link rel="stylesheet" href="css/jquery.bxslider.css">

    <script src="js/jquery-3.1.1.min.js"></script>
    <script src="js/jquery.bxslider.js"></script>

    <script>
        $(document).ready(function(){
            $(".slider").bxSlider()
        });
    </script>
    <style>
        img.sliderImg{width: 100%;}
        .sliderWrap{width: 1200px;margin-left:100px;}
        .bx-wrapper {
            -moz-box-shadow: 0 0 0 #fff;
            -webkit-box-shadow: 0 0 0 #fff;
            box-shadow: 0 0 0 #fff;
            border: 0;
        }
        .bx-wrapper .bx-pager{
            bottom: 20px;
        }
        .sliderWrap .txtWrap{
            position: absolute;
            /* top:30%;
            left:50%;
            transform: translateX(-50%);
            text-align: center; */
            bottom:50px;right:50px;
            _width: 100%;
            text-align: right;
        }
        .sliderWrap .txtWrap h3{
            font-size: 2em;margin-bottom:10px;color:#fff;
            text-shadow: 0 0 10px #000;
        }
        .sliderWrap .txtWrap h3:after{
            content:"";display: block;width: 100px;height: 2px;
            background-color: #fff;margin-left: auto;margin-top: 10px;;
        }
        .sliderWrap .txtWrap p{font-size: 14px;color:#fff}
    </style>
</head>
<body>

    <div class="sliderWrap">
        <ul class="slider">
            <li>
                <img src="images/pc01.jpg" alt="" class="sliderImg">
                <div class="txtWrap">
                    <h3>Lorem, ih3sum dolor.</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor, quaerat.</p>
                </div>
            </li>
            <li>
                <img src="images/pc02.jpg" alt="" class="sliderImg">
                <div class="txtWrap">
                    <h3>Lorem, ih3sum dolor.</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor, quaerat.</p>
                </div>
            </li>
            <li>
                <img src="images/pc03.jpg" alt="" class="sliderImg">
                <div class="txtWrap">
                    <h3>Lorem, ih3sum dolor.</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor, quaerat.</p>
                </div>
            </li>
            
        </ul>
    </div>

</body>
</html>
