# HelloSpring

這是一個基於 Spring Boot 的簡單 Hello World 範例專案，展示如何快速使用 Spring 生態系統搭建一個基本的 Web 應用。

## 專案介紹

- 使用 [start.spring.io](https://start.spring.io) 生成的 Spring Boot 專案骨架。
- 包含一個簡單的 REST 控制器，提供 `/hello` 路由，回傳 "Hello World!" 字串。
- 集成了 Spring Boot Actuator，提供應用監控功能。
- 使用 Maven 進行依賴管理與打包。

## 專案結構

- `src/main/java`：Java 程式碼，包括入口類和控制器。
- `src/main/resources`：配置文件目錄。
- `src/test/java`：測試代碼目錄。
- `pom.xml`：Maven 專案配置文件。

## 快速開始

1. 克隆專案：
   ```
   git clone <你的倉庫地址>
   cd HelloSpring
   ```

2. 編譯並打包：
   ```
   mvn clean package
   ```

3. 運行應用：
   ```
   java -jar target/helloSpring-0.0.1-SNAPSHOT.jar
   ```

4. 訪問測試：
   打開瀏覽器，訪問 [http://localhost:8080/hello](http://localhost:8080/hello)，應該會看到 "HelloSpring"。

## 進階說明

- Maven 使用了 Spring Boot 的依賴管理，確保依賴版本兼容。
- 打包生成的 jar 是可執行的 fat jar，包含所有依賴，方便部署。
- 如果需要自訂 Maven Parent，可以參考專案中的 `pom.xml` 配置。

## 參考資源

- [Spring Boot 官方網站](https://spring.io/projects/spring-boot)
- [start.spring.io](https://start.spring.io)
- [Spring Boot Actuator](https://docs.spring.io/spring-boot/docs/current/reference/html/actuator.html)