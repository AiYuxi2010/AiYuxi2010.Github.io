<!doctype html>
<html>

<head>
    <?php
    $webname = '艾玉熙的网站';
    $eg = 'Hello World';
    $g = '“你好，世界”';
    $eg1 = 'Life is short, I use Python';
    $g1 = '“人生苦短，我用Python”';
    $gn1 = '天气预报';
    $gn2 = '小游戏';
    $gn3 = '工具下载';
    $gnu1 = 'weather';
    $gnu2 = 'game';
    $gnu3 = 'download';
    ?>
    <meta charset='utf-8'>
    <title><?php echo $webname ?></title>
    <link rel='stylesheet' href='https://zenglingkun.cn/css/index.css'>
    
    <script src='https://zenglingkun.cn/js//jquery.min.js' ></script>
    <script src='https://zenglingkun.cn/js//skel.min.js' ></script>
    <script src='https://zenglingkun.cn/js//util.js' ></script>
    <script src='https://zenglingkun.cn/js//main.js' ></script>
    <script src='https://zenglingkun.cn/js//su.js'></script>
</head>

<body>
    
    <div class='content'>
        <img src='https://zenglingkun.cn/img/ch.jpg' alt=''>
        <div class='content_r clearfix'>
            <div class='content_l clearfix'>
                <h2>Hi~ 欢迎来到
                <?php
                echo $webname 
                ?></h2>
                
                <p class='cc'>欢迎来到我的网站~</p>
                
                <br>
                <p class='color_1'><?php echo $eg ?></p>
                <p class='color_1'><?php echo $g ?></p>
                <br>
                <p class='deeppink'><?php echo $eg1 ?></p>
                <p class='deeppink'><?php echo $g1 ?></p>
                <div class='link'>
                    <a href='<?php echo $gnu1 ?>' class='dodgerblue' target='_blank'><?php echo $gn1 ?></a>
                    <a href='<?php echo $gnu2 ?>' class='deeppink_1' target='_blank'><?php echo $gn2 ?></a>
                    <a href='<?php echo $gnu3 ?>' class='magenta' target='_blank'><?php echo $gn3 ?></a>
                    <a href='<?php echo $gnu4 ?>' class='orange' target='_blank'><?php echo $gn4 ?></a>
                </div>
                
            </div>
        </div>
    </div>
    <div id='a'>
    </div>
</body>
<script src="https://player.lzti.com/player/js/jquery.min.js" type="text/javascript"></script>
<script src="https://player.lzti.com/api/player/166977737993" id="myhk" key="166977737993" m="1"></script>
</html>
