yuntaoframework
===============
又一个国产敏捷项目开发框架，可以理解为类似于appfuse,springside的又一个java新项目脚手架,或者称为代码库。

<b>1. 为什么要开发yuntaoframework?</b>
<p/>
其实不应该叫开发，这个项目是作者多年积累的代码库，有非常多好用的工具，面对新项目时，用这个代码库可以实现非常快的开发速度。
<p/>
<b>2. yuntaoframework提供什么？</b><br/>
  1）提供了一套基于JPA的DAO封装，实现了大多数常用的数据库操作，实际上基于这个封装你可以跟DAO说拜拜了，基本上不需要你再写数据库代码。<br/>
  2）提供了一套访问MongoDB的DAO封装，API风格跟普通DAO保持一致，也就是说，可以用操作传统数据库的方式操作MongoDB了<br/>
  3）基于spymemcached提供了一套memcached的访问API，更简洁，更好用。<br/>
  4）基于Jedis提供了一套redis的访问API，同上，更简洁实用。<br/>
  5）基于curator提供了一套zookeeper的访问API，原因同上。<br/>
  6）提供了一套基于http的rpc调用库，不过不是soap协议，是更简洁的json协议。<br/>
  7）还有很多平时积累的工具，包括但不限于hotswap,shell命令执行,加密解密,图像处理等,这里就不一一描述了。  <br/>
  <p/>
<b>3. 这么多好东西，可以单独使用吗？</b>  <br/>
完全可以，所有代码都具有良好的组织，模块之间基本没有依赖性  <br/>
  <p/>
<b>4. 这些代码靠谱吗？</b>  <br/>
靠谱，在作者的工作经历中，这些代码已多次用于线上项目，其中不乏访问量过亿的互联网应用..  <br/>
<p/>
<b>5. 如果有问题怎么办，能获得帮助吗？</b>  <br/>
可以，请发送邮件到zyuntao@126.com，我会第一时间回复  <br/>
