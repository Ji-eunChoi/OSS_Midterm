#open Source Software Mid Term

##외부 라이브러리 사용 방법

1. 해당 프로젝트를 본인 프로젝트 위치에서 clone

2. 프로젝트에 MidTermJar 폴더 생성 확인

3. 메이븐 프로젝트 pom.xml 파일에 아래에 dependency 추가

    <dependency>
      <groupId>mid_term</groupId>
      <artifactId>problem1</artifactId>
      <version>0.0.1-SNAPSHOT</version>
      <scope>system</scope> 
      <systemPath>${basedir}/MidTermJar/problem1-0.0.1-SNAPSHOT.jar</systemPath>
    </dependency>
 
라이브러리 설명

import mid_term.problem1.RegularExpression;

class RegularExpression()

public boolean check(String sentence, String pattern)\n
    sentence에서 pattern이 존재하면 true return, 그렇지 않으면 false return
    
