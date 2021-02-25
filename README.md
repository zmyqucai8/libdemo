# libdemo
上传library到远程仓库的配置
<br>

步骤：
<br>
1、在根目录build.gradle文件中加入classpath
<br>
2、在mylibrary下添加文件bintray.gradle ，并在build.gradle下引用：apply from: './bintray.gradle'
<br>
3、在gradle.properties文件下配置仓库信息
<br>
4、在local.properties文件下配置仓库key
<br>
5、发布：在Terminal执行
<br>

  {gradlew install
  <br>
  gradlew bintray}
