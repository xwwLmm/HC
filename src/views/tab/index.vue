<template>
  <div :class="$style.container">
    <div>
      <img src="../../assets/search.png">
    </div>
    <div>
      <div>XXX培训机构</div>
      <div>xxx pei xun ji gou</div>
    </div>
    <div>
      <span>首页</span>
      <span>关于我们</span>
      <span>新闻资讯</span>
      <span>课程介绍</span>
      <span>联络我们</span>
    </div>
  </div>
</template>
<script>
  export default {
  }
</script>
<style lang="less" module>
  .container {
    background-color: #e14b3c;
    color: #fff;
    padding: 0 40px;

    > div {
      padding: 40px 0;
      display: table-cell;
      vertical-align: middle;
      white-space: nowrap;
    }

    > :nth-child(2) {
      width: 1000px;
      text-align: left;

      > :first-child {
        font-size: 36px;
      }
    }

    > :last-child {

      span {
        margin: 0 17.5px;
        color: #444;

        &:hover {
          cursor: pointer;
        }
      }
    }
  }
</style>
