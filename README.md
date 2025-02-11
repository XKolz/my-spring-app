1. First, verify Java installation:
   java -version

2. Install Spring Boot CLI (Command Line Interface):
   brew tap spring-io/tap
   brew install spring-boot

3. Create a new Spring Boot project using Spring Initializer CLI:
   spring init --build=maven --java-version=17 --dependencies=web my-spring-app
   cd my-spring-app

4. Run the application:
   mvn spring-boot:run

5. Run this to update dependencies:
   mvn clean install

For Testing - H2(Hypersonic 2) Database in Spring Boot is an embedded, open-source, and in-memory database. It is a relational database management system written in Java

Great! 🚀 Since you're using H2 (in-memory database), by default, the data is stored in memory and disappears when the application restarts. However, you can view and persist the database in different ways.
