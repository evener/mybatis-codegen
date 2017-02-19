# mybatis-codegen

mybatis-generator配置生成Model和mapper已经sqlmap文件

运行代码 `src/test/java/org/mybatis/mbg/MybatisGeneratorMain.java`

自定义生成注释，CustomCommentGenerator

```
public class CustomCommentGenerator implements CommentGenerator {
    // 
}
```

生成效果

```
/**
 * 
 * @tableName sys_user
 * @author Bruce
 * @date 2017-02-19
 */
public class User implements Serializable {
    /** ID */
    private Long id;

    /** 用户名 */
    private String username;

    /** 密码 */
    private String password;

    /** 昵称 */
    private String nickName;

    /** 电话 */
    private String phone;
    
    // getter
    
    // setter
    
 }

```
