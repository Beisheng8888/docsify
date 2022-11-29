![logo](_media/java_icon.svg)

# 北省的Java文档 <small>0.0.1</small>

> 先选一个你喜欢的主题吧

<div class="demo-theme-preview" >
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



[博客](http://anqi520.com)
[GitHub](#🎁readme)
[查看文档](#🎁readme)


