<h2># demo-editor</h2>
<p>富文本编辑器 Editor v1.0</p>
<p>以 Bootstrap 为皮肤编辑器，不依赖第三方js库，最低支持IE8</p>
<p><b>演示地址：</b><a href="http://gongshunkai.github.io/demo/%E5%AF%8C%E6%96%87%E6%9C%AC%E7%BC%96%E8%BE%91%E5%99%A8/test.html">http://gongshunkai.github.io/demo/%E5%AF%8C%E6%96%87%E6%9C%AC%E7%BC%96%E8%BE%91%E5%99%A8/test.html</a></p>
<p><b>使用方法：</b></p>
<p>初始化：var editor = Editor('editor-wrap');</p>
<p>高度300：var editor = Editor('editor-wrap',{ height:300 });</p>
<p>初始化提供2个参数，第一个是demo元素的ID名，第二个是编辑器的配置项参数</p>
<p>{<br>&nbsp;&nbsp;&nbsp;&nbsp;
  height:200, //编辑器高度<br>&nbsp;&nbsp;&nbsp;&nbsp;
  toolbarButtons:[], //自定义工具条按钮<br>&nbsp;&nbsp;&nbsp;&nbsp;
  skinClassName:null, //自定义皮肤样式名<br>&nbsp;&nbsp;&nbsp;&nbsp;
  oninitialized:null //编辑器初始化完成后执行的方法<br>
  };</p>
<p> toolbarButtons:'full'
  <br>
  toolbarButtons:'simple'<br>
  toolbarButtons:'mini'  </p>
<p><b>编辑器对外提供了7个方法：</b>  </p>
<p>editor.getSource() //获取源码<br> 
  editor.setSource(source) //设置源码
    <br>
  editor.toggleFullScreen(true) //显示全屏
  <br>
  editor.toggleFullScreen() //切换全屏
  <br>
  editor.toggleSource(true) //显示源码<br>
editor.toggleSource() //切换源码<br>
editor.destroy() //销毁编辑器</p>