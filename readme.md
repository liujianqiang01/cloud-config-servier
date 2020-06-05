#启动：
nohup java  -Xms64m -Xmx128m -XX:PermSize=64M -XX:MaxPermSize=128M -jar cloud-config-server-0.0.1-SNAPSHOT.jar
 --spring.profiles.active=dev &