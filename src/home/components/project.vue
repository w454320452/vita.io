 <template>
     <div class="project">
            <h1>项目经验</h1>
            <div class="project_info">
                <el-collapse v-model="activeName" accordion>
                    <el-collapse-item title="旅游网站模块开发" name="1">
                        <div class="info"> 
                            <div class="info_div">技术栈：html+css+vue+vuex+vue-router+axios</div>
                            <div class="info_div">采用vue开发的单页面应用程序，主要针对移动端开发。采用了mint-ui开发开发界面，使用Json进行了数据Mock。
                            </div>
                            <a href="http://w454320452.github.io">作品链接</a>
                        </div>
                       
                                <div class="img_div"><img src="static/img/2.jpg" ></div>
                            
                        
                    </el-collapse-item>
                     <el-collapse-item title="Vue商城应用开发" name="2">
                        <div class="info"> 
                            <div class="info_div">技术栈：html+css+vue+vuex+vue-router+axios</div>
                            <div class="info_div">单页面应用，采用Vue开发，使用vue相关生态圈技术如vue-router/vuex等等。项目基于组件化开发。采用webpack打包工具进行打包。</div>
                        </div>
                       
                                <div class="img_div"><img src="static/img/3.jpg" ></div>
                            
                        
                    </el-collapse-item>
                     <el-collapse-item title="仿QQ音乐官方播放界面" name="3">
                        <div class="info"> 
                            <div class="info_div">技术栈：html+css+JQuery+ajax</div>
                            <div class="info_div">能够完成本地音乐加载并且播放，能够实现音乐切换、音乐删除。采用高斯背景虚化，背景随音乐不同而切换等功能。主要是使用的JQuery实现的</div>
                            <a href="http://w454320452.github.io">作品链接</a>
                        </div>
                       
                                <div class="img_div"><img src="static/img/4.jpg" ></div>
                            
                        
                    </el-collapse-item> 
                    <el-collapse-item title="管理系统设计" name="4">
                        <div class="info"> 
                            <div class="info_div">管理系统设计与制作，采用java语言开发，使用mvc设计模式，数据库使用sqlsever。</div>
                        </div>
                       
                                <div class="img_div"><img src="static/img/5.jpg" ></div>
                            
                        
                    </el-collapse-item>
                     <el-collapse-item title="打地鼠小游戏" name="5">
                        <div class="info"> 
                            <div class="info_div">打地鼠小游戏制作，采用DIV+CSS进行布局，动物出现与消失，主要是用JQuery对DOM进行操作，通过获取图片下标，切换不同的图片，做出一个动画效果。然后监听鼠标点击事件，对游戏进行操作。</div>
                        </div>
                       
                                <div class="img_div"><img src="static/img/6.jpg" ></div>
                            
                        
                    </el-collapse-item>
                </el-collapse>
            </div>
         
     </div>
 </template>

 <script>
 export default {
     name:'HomeProject',
      data() {
      return {
        activeName: '1',
        
      };
     
      }
 }
 </script>
 
<style scoped>
.project{
    background: #232323;
}
.project_info{
    width: 60%;
    height: auto;
    margin: 0 auto;

}
h1{
    text-align: center;
    font-size: 30px;
    color: #eee;
    padding: 20px;
}

img{

    width: 20%;
    height: 20%;
}
.info{
    width: 80%;
    float: left;
}
.info_div{
    width: 100%;
    text-align: left;
    
}
</style>