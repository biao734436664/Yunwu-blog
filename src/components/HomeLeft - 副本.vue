<template>
  <div class="uk-sticky-placeholder" style="height: 513px; margin: 0px;">
    <div id="head" data-uk-sticky="{boundary: true,top:80}" class="uk-sticky-init uk-active" style="position: fixed; top: 80px; width: 187px;">
      <div id="op_head">
        <div class="uk-panel bs" id="op_hed">
          <div class="tx">
            <div class="avatar_"><img src="https://blog.dbdl.cc/wp-content/uploads/2017/12/头像.png"></div>
          </div>
          <h1 class="uk-panel-title">
            <a href="https://blog.dbdl.cc">云雾迷蒙</a>
          </h1>
          <span>生活总让人措手不及</span>
          <div class="my uk-grid-collapse uk-grid uk-grid-width-1-3">
            <div>
              <span>26</span>
              <span>
                <i class="uk-icon-file-text"></i>
              </span>
              <a href="https://blog.dbdl.cc/%e6%96%87%e7%ab%a0" data-uk-tooltip="{pos:'bottom'}"></a>
            </div>
            <div>
              <span>4</span>
              <span>
                <i class="uk-icon-folder"></i>
              </span>
              <a href="https://blog.dbdl.cc/%e5%88%86%e7%b1%bb" data-uk-tooltip="{pos:'bottom'}"></a>
            </div>
            <div>
              <span>32</span>
              <span>
                <i class="uk-icon-tags"></i>
              </span>
              <a href="https://blog.dbdl.cc/%e6%a0%87%e7%ad%be" data-uk-tooltip="{pos:'bottom'}"></a>
            </div>
          </div>
          <a href="#s_s" class="s_s uk-navbar-toggle uk-hidden-large" data-uk-offcanvas=""></a>
          <ul id="nav-top" class="nav uk-nav uk-hidden-small">
            <li id="menu-item-273" class="">
              <a href="https://blog.dbdl.cc/" class="qzhai_bgc_hover">首页</a>
            </li>
            <li id="menu-item-274" class="">
              <a href="https://blog.dbdl.cc/web" class="qzhai_bgc_hover">前端</a>
            </li>
            <li id="menu-item-275" class="uk-active">
              <a href="https://blog.dbdl.cc/purple" class="qzhai_bgc_hover">紫晴</a>
            </li>
            <li id="menu-item-276" class="">
              <a href="https://blog.dbdl.cc/note" class="qzhai_bgc_hover">随笔</a>
            </li>
          </ul>
          <form role="search" class="s uk-form uk-hidden-small" id="searchform" method="get" action="https://blog.dbdl.cc/"><input class="uk-width-1-1 qzhai_bgc_hover " type="text" value="" name="s" id="s" placeholder="搜索" data-uk-tooltip="{pos:'bottom'}"></form>
        </div>
      </div>
      <div class="ft uk-hidden-small">
        <p>
          <a href="#" title="22222" data-uk-tooltip="{pos:'bottom'}">
            <i class="uk-icon-copyright"> </i> 2018 云雾迷蒙 </a>
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeLeft',
  data () {
    return {

    }
  }
}
</script>

<style scoped>
</style>
