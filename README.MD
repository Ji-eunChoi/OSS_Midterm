Open Source Software Mid Term

외부 라이브러리 사용 방법

1. 해당 프로젝트를 clone

2. 압축 해제 이후, 본인의 프로젝트에 .jar 파일 이동

3. 메이븐 프로젝트 pom.xml 파일에 아래에 dependency 추가

    <dependency>
      <groupId>mid_term</groupId>
      <artifactId>problem1</artifactId>
      <version>0.0.1-SNAPSHOT</version>
      <scope>system</scope> 
      <systemPath>${basedir}/problem1-0.0.1-SNAPSHOT.jar</systemPath>
    </dependency>
    
