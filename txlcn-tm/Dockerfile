FROM images.ihk.aa-bb.com/openjdk:8.debugger
ADD target/txlcn-tm-5.0.2.RELEASE.jar /tm.jar
ADD entrypoint.sh /entrypoint.sh
ENV JVM_OPTS "-Xms368m -Xmx368m"
ENV TZ Asia/Shanghai
ENTRYPOINT ["sh", "/entrypoint.sh"]
