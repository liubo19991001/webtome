<template>
<div>
      <!-- 顶部搜索框开始 -->
        <div>
            <mt-search dixed v-model="value"  ></mt-search>
         </div>
       <!--顶部搜索框结束  -->
       <!--顶部选项开始  -->
       <div class="fixed">
        <mt-navbar >
                <mt-tab-item >美食</mt-tab-item>
                <mt-tab-item >超市</mt-tab-item>
                <mt-tab-item >饮品</mt-tab-item>
                <mt-tab-item >精选</mt-tab-item>
            </mt-navbar>
        </div>
       <!--顶部选项结束  -->
     </div>  
</template>
<style scoped>
.container{
  margin-top:40px;
}
</style>
