# Java 23을 지원하는 Eclipse Temurin 이미지 사용
FROM eclipse-temurin:23-jdk

# 작업 디렉토리 설정
WORKDIR /app

# 빌드된 JAR 파일을 컨테이너로 복사
COPY build/libs/*.jar app.jar

# 애플리케이션 실행
ENTRYPOINT ["java", "-jar", "app.jar"]