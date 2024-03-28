<template>
  <div class="bg">
    <div class="head_1">
      <div class="to-game">
        <NuxtLink class="link-to-game">爱卡布，爱西游，冲啊</NuxtLink>
      </div>
    </div>
    <div class="head_2" />
    <div class="nav-bg">
      <div class="logo">
        <NuxtLink class="link-to-game">爱卡布，爱西游，冲啊</NuxtLink>
      </div>
      <div class="menu">
        <ul>
          <li class="nav_1">
            <a href="//www.4399.com/flash/48399.htm">4399卡布西游</a>
          </li>
          <li class="nav_2">
            <a href="//news.4399.com/kabuxiyou/yaoguaidaquan/"
              >卡布西游妖怪大全</a
            >
          </li>
          <li class="nav_3">
            <a href="//v.4399pk.com/kabuxiyou/">卡布西游视频</a>
          </li>
          <li class="nav_4">
            <a href="//news.4399.com/kabuxiyou/gonglve/">卡布西游攻略</a>
          </li>
          <li class="nav_5">
            <a href="//news.4399.com/kabuxiyou/jingyan/">卡布西游心得</a>
          </li>
          <li class="nav_6">
            <a href="//news.4399.com/kabuxiyou/zixun/">卡布西游最新资讯</a>
          </li>
          <li class="nav_7">
            <a href="//news.4399.com/kabuxiyou/xszn/">卡布西游新手指南</a>
          </li>
          <li class="nav_8 no_mar">
            <a href="//my.4399.com/forums-mtag-tagid-79936.html"
              >卡布西游论坛</a
            >
          </li>
        </ul>
      </div>
    </div>
    <div class="yg_t">
      <div class="yg-top">
        <div class="title_yg" />
        <div class="cl_3">
          <ul class="menu_att">
            <li class="cl_yg1">
              <a id="allcw" href="" class="on" rel="">全部妖怪</a>
            </li>
            <li class="cl_yg2">
              <a id="dawang" href="" rel="15">妖怪大全</a>
            </li>
            <li class="cl_yg3">
              <a id="xiyoucw" href="" rel="14">稀有妖怪</a>
            </li>
            <li class="cl_yg6">
              <a id="chaojinhua" href="" rel="36">超进化</a>
            </li>
            <li class="cl_yg7">
              <a href="" id="chaojinhua" rel="3738">珍宠神宠</a>
            </li>
            <li class="cl_yg4">
              <a id="vipyaoguai" href="" rel="20">VIP妖怪</a>
            </li>
            <li class="cl_yg5">
              <a
                href="//news.4399.com/kabuxiyou/NPCdaquan/"
                title="NPC大全"
                rel="NPC"
                >NPC大全</a
              >
            </li>
          </ul>
        </div>
      </div>

      <div class="zimu">
        <ul id="menu_zm">
            <li v-for="n in 21" :key="n" :class="`zm_${n}`"><a href="javascript:void(0);">{{ String.fromCharCode(64+n) }}</a></li>
        </ul>
      </div>

      <div class="xibie">
        <ul id="menu_xi">
          <li v-for="n of 21" :class="`xi_${n}`" :key="n"><a href="javascript:void(0);">全部</a></li>
          <!-- <li class="xi_1"><a href="javascript:void(0);">全部</a></li>
          <li class="xi_2"><a href="javascript:void(0);">火系</a></li>
          <li class="xi_3"><a href="javascript:void(0);">金系</a></li>
          <li class="xi_4"><a href="javascript:void(0);">木系</a></li>
          <li class="xi_5"><a href="javascript:void(0);">水系</a></li>
          <li class="xi_6"><a href="javascript:void(0);">土系</a></li>
          <li class="xi_7"><a href="javascript:void(0);">翼系</a></li>
          <li class="xi_8"><a href="javascript:void(0);">怪系</a></li>
          <li class="xi_9"><a href="javascript:void(0);">魔系</a></li>
          <li class="xi_10"><a href="javascript:void(0);">妖系</a></li>
          <li class="xi_11"><a href="javascript:void(0);">风系</a></li>
          <li class="xi_12"><a href="javascript:void(0);">毒系</a></li>
          <li class="xi_13"><a href="javascript:void(0);">雷系</a></li>
          <li class="xi_14"><a href="javascript:void(0);">幻系</a></li>
          <li class="xi_15"><a href="javascript:void(0);">冰系</a></li>
          <li class="xi_16"><a href="javascript:void(0);">灵系</a></li>
          <li class="xi_17"><a href="javascript:void(0);">机械</a></li>
          <li class="xi_18"><a href="javascript:void(0);">火风系</a></li>
          <li class="xi_19"><a href="javascript:void(0);">木灵系</a></li>
          <li class="xi_sx"><a href="javascript:void(0);" >圣系</a></li>
          <li class="xi_20"><a href="javascript:void(0);" >土幻系</a></li> -->
        </ul>
      </div>
    </div>

    <!-- 内容 -->
    <slot/>
    <!-- 结尾 -->
    <div class="yg_c">
      <div class="more_yg" id="showmorejingling">
        <a href=""><img src="../assets/images/more_yg.gif" /></a>
      </div>
    </div>
    <div class="yg_b" />
  </div>
</template>

<script setup lang="ts"></script>

<style scoped>
@import "../assets/css/yaoguaodaquan.css";
</style>
