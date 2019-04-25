<template>
    <div class="header">
        <div class="headerCard"></div>
        <div class="avatar">
            <img src="static/img/1.jpeg">
        </div>
         <div class="info">
                    <div class="title">
                       <h2>文超</h2>
                    </div>
                    <div class="desc"><b>web前端开发工程师</B></div>
                    <div class="desc">
						   <p>
							  我是一名web前端前端工程师，我热爱web开发。 <br/>
							  我喜欢通过自己双手敲击出的漂亮页面，专注用户体验<br/>
							  我希望通过自己的代码，让网站变的更美观. </p>
					</div>
                </div>

    </div>
</template>

<script>
export default {
    name:'HomeHeader'
}
</script>

<style scoped>
 .header{
    position: relative;
    padding: 0;
    overflow: hidden;
    text-align: center;
    background-color: #03A9F4;
    margin: 0;
 }
 .headerCard{
    background-size: cover;
    height: 210px;
    background: #0797d8;
 }
 .avatar{
    position: relative;
    top: -80px;
    width: 150px;
    height: 150px;
    max-width: 150px;
    max-height: 150px;
    right: 0px;
    left: 0px;
    margin: 0 auto;
    overflow: hidden;
    border-radius: 50%;
    border: 5px solid rgba(255,255,255,0.5);
 }
 .avatar > img {
    width: 165px;
    height: auto;
    max-width: 150px;
    margin-left: 1px;
    margin-top: -25px;
 }
 .info{
    padding: 0 8px 22px;
    top: -50px;
    position: relative;
 }
.title{
    margin-bottom: 10px;
    font-size: 26px;
    line-height: 1;
    color: #ffffff;
    vertical-align: middle;
}
.desc{
    overflow: hidden;
    font-size: 14px;
    line-height: 22px;
    color: rgba(255, 255, 255, 0.77);
    text-overflow: ellipsis;
}
.desc > b{
      color: #00608b;
      font-size: 16px;
}
.desc > p{
     margin-top: 25px;

}
</style>
