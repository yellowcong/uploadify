# uploadify
uploadify 这个版本的在原先的基础上，修改了一下他名字累加的问题

##参考文档
http://blog.csdn.net/zhichao2001/article/details/46662705/

##修改多个页面使用uploadify导致名字问题
  //名称重复  SWFUpload.movieCount++不能有效累加导致出现重名现象
  this.movieName = "SWFUpload_" + parseInt(100*Math.random());
    

