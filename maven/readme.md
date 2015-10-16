# 创建java项目
mvn archetype:generate
-DgroupId=com.xiaojuese
-DartifactId=xxx 
-DarchetypeArtifactId=maven-archetype-quickstart 
-DinteractiveMode=false
# 引用系统变量
${project.artifactId} 获取 artifactId 