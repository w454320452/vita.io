<template>

    <div class="homeNav border-bottom ">
            <div class="nav">
             <a  @click="returnTop">首页</a>
             <a  @click="returncontent">个人简介</a>
             <a  @click="returnTech">技术栈</a>
             <a  @click="returnProject">项目经验</a>
         
            </div>
        </div>
    
</template>
<script>
export default {
    name:'HomeNav',
    mounted () {
        
      window.addEventListener('scroll', this.watchScroll);
    },
    methods:{
         watchScroll () {
        var scrollTop = window.pageYOffset || document.documentElement.scrollTop || document.body.scrollTop
        
        //  当滚动超过 50 时，实现吸顶效果
        if (scrollTop > 500) {
          this.navBarFixed = true
        } else {
          this.navBarFixed = false
        }

     },
    returnTop(){
            document.querySelector(".header").scrollIntoView(true);
    },
     returncontent(){
            document.querySelector(".content").scrollIntoView(true);
    },
     returnTech(){
            document.querySelector(".tech").scrollIntoView(true);
    },
     returnProject(){
            document.querySelector(".project").scrollIntoView(true);
    }

        }
    }
</script>

<style scoped>
.navBarWrap {

  }
.homeNav{
    background:#232323 ;
    width: 100%;
    height: 50px;
    text-align: center;
    position:fixed;
    top:0;
    z-index:999;

   
}
.nav{
    padding-top: 15px;
}
.nav > a{
    margin-left: 15px;
    
}
</style>

