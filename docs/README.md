## 🎁readme

> 🍬 书到用时方恨少。

## 📚简介

初心是上传 从Java基础、JavaSE、JavaWeb、框架部分。

## 🍑这里也可以切换主题

<div class="demo-theme-preview">
  <a data-theme="theme-simple">simple</a>
  <a data-theme="theme-simple-dark">simple-dark</a>
  <a data-theme="vue">vue</a>
  <a data-theme="buble">buble</a>
  <a data-theme="dark">dark</a>
  <a data-theme="pure">pure</a>
</div>

<style>
  .demo-theme-preview a {
    padding-right: 10px;
  }

  .demo-theme-preview a:hover {
    cursor: pointer;
    text-decoration: underline;
  }
</style>

<script>
  var preview = Docsify.dom.find('.demo-theme-preview');
  var themes = Docsify.dom.findAll('[rel="stylesheet"]');

  preview.onclick = function (e) {
    var title = e.target.getAttribute('data-theme');

    themes.forEach(function (theme) {
      theme.disabled = theme.title !== title;
    });
  };
</script>
