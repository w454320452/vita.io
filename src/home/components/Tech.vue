<template>
    <div class="tech">
        <h1 > 技术栈</h1>
        <div class="block">
            <el-timeline>
                <el-timeline-item
                class="item"
                v-for="(activity, index) in activities"
                :key="index"
                :icon="activity.icon"
                :type="activity.type"
                :color="activity.color"
                :size="activity.size"
                :timestamp="activity.timestamp">
                {{activity.content}}
                <el-progress 
                :text-inside="true" 
                :stroke-width="18" 
                :percentage="activity.progress"></el-progress>
                </el-timeline-item>

            </el-timeline>
        </div>
    </div>
</template>

<script>
export default {
    name:'HomeTech',
     data() {
      return {
        activities: [{
          content: 'Html',
          size: 'large',
          type: 'primary',
          icon: 'el-icon-more',
          progress:80
        }, {
          content: 'CSS',
          color: '#0bbd87',
          progress:80
        }, {
          content: 'JQuery',
          color: '#0bbd87',
          size: 'large',
           progress:70
        }, {
          content: 'JS',
           color: '#0bbd87',
           progress:70
        }
        , {
          content: 'vue',
           color: '#0bbd87',
           progress:70
        }
        , {
          content: 'vue-router',
           color: '#0bbd87',
           progress:70
        }
        , {
          content: 'vuex',
           color: '#0bbd87',
           progress:60
        }
        , {
          content: 'mui-ui',
           color: '#0bbd87',
           progress:70
        }
        , {
          content: 'mint-ui',
           color: '#0bbd87',
           progress:70
        }
        , {
          content: 'element-ui',
           color: '#0bbd87',
           progress:80
        }
        , {
          content: 'MySql',
           color: '#0bbd87',
           progress:60
        }
        , {
          content: 'C语言',
           color: '#0bbd87',
           progress:60
        }]
      };
     }
}
</script>
<style scoped>
.tech{
     background: #232323;
     
}
h1{
    text-align: center;
    font-size: 30px;
    color: #eee;
    padding: 20px;
}
.block{
    width: 60%;
    height: auto;
    margin: 0 auto;
}

.el-timeline-item__content {
  color:red!important;
}
</style>
