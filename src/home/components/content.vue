<template>
    <div class="content">
        <h1 class="content_title">个人简介</h1>
            <div class="content_info">
                <div class="left">
                      <dt>姓名:</dt>
                        <dd>文超</dd><br>

                        <dt>民族:</dt>
                        <dd>汉</dd><br>

                        <dt>地址:</dt>
                        <dd>成都</dd><br>

                        <dt>学历:</dt>
                        <dd>本科</dd><br>

                        <dt>邮箱:</dt>
                        <dd>454320452@qq.com</dd><br>

                         
                </div>
                <div class="right">
                    <dt>兴趣爱好：</dt>
                        <dd>
                            <el-tag>跑步</el-tag>
                            <el-tag type="success">健身</el-tag>
                            <el-tag type="info">听音乐</el-tag>
                            <el-tag type="warning">羽毛球</el-tag>
                            <el-tag type="danger">游泳</el-tag>
                        </dd>
                </div>
                
            </div>
    </div>
</template>
<script>
export default {
    name:'HomeContent'
}
</script>

<style scoped>
.content{
    
    background: #232323;
}
.title{
    text-align: center;
    font-size: 30px;
    color: #eee;
    padding: 20px;
}
.content_info{
    width: 60%;
    height: 300px;
    margin: 0 auto;
}

.left{
    text-align: left;
    float: left;
 
}
.right{
    float: left;
}
dt{
      display: inline-block;
      color: #afafaf;
      font-size: 20px;
      margin-top: 15px;
     
}
dd{
    display: inline-block;
    color: #888888;
    font-size: 18px;
}
.grid-content {
    width: 50%;
}

</style>

