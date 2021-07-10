# springboot-jpa-noticeboard-oAuth2
Nice to meet you! If you have any questions, please leave a comment.

# This project has the following features
- noticeboard (CRUD) but no search, paging
- google or naver OAuth2

# Project Spec
- Java 8
- Gradle 4.x
- Spring Boot 2.1.x
- JPA

# precautions!!
- It does not work properly with Spring Boot 2.2.x and Gradle 5.x.

# How to setting?
1. Open IntelliJ
2. Open terminal and Enter the command 'gradlew wrapper --gradle-version 4.10.2'
3. Check if Gradle version 4. of 'gradle > wrapper > gradle-wrapper.properties' is correct.
4. After getting an oAuth from Naver and Google, enter the Client ID and Client Secret key in 'application-oauth.properties'.
5. install mariadb and Create a table by referring to 'taschema.sql'
6. src > main > java > com.neo.ex > 'Application' Click the right click and press the run button


# How to Operating?
1. You can register a post by changing the role to user in the [user] table
![role](https://user-images.githubusercontent.com/17843257/124391368-4bcd2580-dd2b-11eb-9752-22a6ba976769.png)

# Contact Us!
- email : yhsang2@naver.com
- If you have any questions, please leave a comment. Have a good day!
