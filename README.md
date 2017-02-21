<p># demo-editor</p>
<p>富文本编辑器
  
  Editor v1.0</p>
<p>以 Bootstrap 为皮肤编辑器，不依赖第三方js库，最低支持IE8</p>
<p>使用<strong>方</strong>法：</p>
<p>初始化：var editor = Editor('editor-wrap');
  高度300：var editor = Editor('editor-wrap',{ height:300 });
  
  初始化提供2个参数，第一个是demo元素的ID名，第二个是编辑器的配置项参数
  
  {
  height:200, //编辑器高度
  toolbarButtons:[], //自定义工具条按钮
  skinClassName:null, //自定义皮肤样式名
  oninitialized:null //编辑器初始化完成后执行的方法
  };
  
  toolbarButtons:'full'
  toolbarButtons:'simple'
  toolbarButtons:'mini'
  
  编辑器对外提供了7个方法：
  editor.getSource() //获取源码
  editor.setSource(source) //设置源码
  editor.toggleFullScreen(true) //显示全屏
  editor.toggleFullScreen() //切换全屏
  editor.toggleSource(true) //显示源码
  editor.toggleSource() //切换源码
  editor.destroy() //销毁编辑器
  
  
  演示地址：<a href="http://gongshunkai.github.io/demo/%E5%AF%8C%E6%96%87%E6%9C%AC%E7%BC%96%E8%BE%91%E5%99%A8/test.html">http://gongshunkai.github.io/demo/%E5%AF%8C%E6%96%87%E6%9C%AC%E7%BC%96%E8%BE%91%E5%99%A8/test.html</a>
  
</p>