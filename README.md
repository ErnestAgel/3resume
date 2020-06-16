# -
百度前端学习的第5、6天实现3种简历
————————————————————html部分——————————————————
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>r3sume</title>
    <!-- <link rel="stylesheet" href="css/style_1.css"> -->
    <!-- <link rel="stylesheet" href="css/style_2.css"> -->
    <link rel="stylesheet" href="css/style_3.css">
    
</head>
<body>
    <!-- 头部 -->
    <div class="head ">
        <h1>简历</h1>
    </div>
    
    <!-- 基本信息 -->
    <div class="basicinfo">
        <h2>基本信息</h2>
        <div  class="binfo">
            <ul>
                <li>姓名<span>张三</span></li>
                <li>性别<span>男</span></li>
                <li>应聘职位<span>Web前端工程师</span></li>
            </ul>
        </div>
        
    </div>
    <!-- contact -->
    <div class="contact">
        <h2>联系方式</h2>
        <ul class="phone">
            <li>手机<span>12312341234</span></li>
            <li>Email <a href="#">Joinefe@baidu.com</a></li>
            <li>个人主页 <a href="#">Github</a></li>
        </ul>
    </div>
    <!-- 能力描述 -->
    <div class="ability">
        <h2>能力描述</h2>
        <ul class="dis">
            <li>技术能力<br><span>熟练掌握HTML，CSS，JavaScript</span></li>
            <li>综合能力<br><span>良好的沟通，主动积极，努力勤奋</span></li>
        </ul>
    </div>
    <!-- 教育背景 -->
    <div class="eduback">
        <h2>教育背景</h2>
        <ul class="back">
            <li>本科<span>百度前端技术学院小薇学院</span></li>
            <li>硕士<span>百度前端技术学院大斌学院</span></li>
        </ul>
    </div>
    <!-- 项目经历 -->
    <div class="project">
        <h2>项目经历</h2>
        <ul class="pj">
            <li>小度小度<span>作为前端工程师角色参与了ABC组件的开发</span></li>
            <li>SAN Doc <span>作为文档工程师参与了SAN Doc编写</span></li>
        </ul>
    </div>
</body>
</html>
