### Proto4j (Protocols for Java)

This small Project using the Java language contains different utility modules that provide a specific service. The `Objection` project for example can be used to serialize and de-serialize Java classes. Code provided here is free to use under the terms of the MIT-License.

- 👯 Collaborators: [@MatrixEditor](https://github.com/MatrixEditor/)
- 💬 How to Collaborate: Open up an issue or a pull request on new features
- 🔭 Current Project: `proto4j-redis` A module to turn a java interface with annotations into a database worker
  - Preview:
  ````java
  @SQL(MySQLService.class)
  @Validator(MySQLValidator.class)
  public interface Storage {

    @AutoType
    @SQL.Select("select * from {table}")
    public List<User> getUsersFromTable(@Param("table") String parameter);
  //...
  ````

<!--
**Proto4j/Proto4j** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
