# libdemo
上传library到远程仓库的配置


步骤：
1、在根目录build.gradle文件中加入classpath、
2、在mylibrary下添加文件bintray.gradle ，并在build.gradle下引用：apply from: './bintray.gradle'
3、在gradle.properties文件下配置仓库信息
4、在local.properties文件下配置仓库key
5、发布：在Terminal执行

  gradlew install
  gradlew bintray
