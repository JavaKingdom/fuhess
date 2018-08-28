<template>
  <div class="list-footer">
    <ul>
      <li>
        <router-link to="/home" class="link">
          <i class="icon iconfont icon-shouye"></i>
          <p>首页</p>
        </router-link>
      </li>
      <li>
        <router-link to="/home" class="link">
          <i class="icon iconfont icon-leibieguanli"></i>
          <p>类别</p>
        </router-link>
      </li>
      <li>
        <router-link to="/home" class="link">
          <i class="icon iconfont icon-gouwuche"></i>
          <p>购物车</p>
        </router-link>
      </li>
      <li>
        <router-link to="/home" class="link">
          <i class="icon iconfont icon-ren"></i>
          <p>我的</p>
        </router-link>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'FootNav',
  methods: {
    goTo(){
      alert();
    }
  }
}
</script>

<style scoped>
  @import "../common/css/reset.css";
  @import "../common/css/iconfont.css";
  .list-footer {
    position: relative;
  }
  .list-footer ul{
    list-style: none;
    position: fixed;
    margin: 0;
    padding: 0;
    left: 0;
    right: 0;
    bottom: 0;
    text-align: center;
  }
  .list-footer ul:after{
    content: "";
    display: block;
    clear: both;
  }
  .list-footer ul li{
    float: left;
    background: #226bbb;
    width: 25%;
    height: 2.5rem;
    position: relative;
  }

  .link{
    text-decoration: none;
    padding: 1rem;
    color: #fff;
    text-align: center;
  }
  .link i{
    text-align: center;
    font-size: 1rem;
    position: absolute;
    left: 50%;
    top:.4rem;
    margin-left: -.5rem;
  }
  .link p{
    margin-top: .1rem;
    font-size: 0.5rem;
  }
</style>
