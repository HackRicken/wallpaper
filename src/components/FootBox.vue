<template>
  <div class="footer">
      <div class="container">
        <p class="c">Copyright © {{new Date().getFullYear()}} · <a href="https://ricken.cn" style="display: inline;">RICKEN</a></p>
        <div class="c">
            <a href="https://beian.miit.gov.cn/"><img src="@/assets/images/icp.png"><span>粤ICP备2021082015号</span></a>
            <!-- <a href="https://beian.miit.gov.cn/"><span>粤ICP备2021082015号</span></a> -->
        </div>
      </div>
  </div>
  
</template>

<script>
export default {
    name: "FootBox"
}
</script>

<style lang="less" scoped>
.footer{
  position: relative;
  text-align: center;
  padding: 60px 0;
  .c {
    color: #fff;
    margin-top: 20px;
    font-size: 12px;
    letter-spacing: .1em;
    opacity: .8;
    a {
        color: #fff;
        display: flex;
        align-content: space-around;
        justify-content: center;
        img{height: 1rem; padding-right: 5px;}
    }
  }
}
</style>