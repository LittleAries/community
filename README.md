## LY社区

## 资料
[Spring 文档](https://spring.io/guides)    
[Spring Wed](https://spring.io/guides/gs/serving-web-content)   
[es](https://elasticsearch.cn/explore)   
[Github deploy key](https://developer.github.com/v3/guides/managing-deploy-keys/#deploy-keys)  
[Bootstrap](https://v3.bootcss.com/getting-started)  
[Github OAuth](https://developer.github.com/apps/building-oauth-apps/creating-an-oauth-app/)

## 工具
[Git](https://git-scm.com/downloads)  
[Visual Paradigm](https://www.visual-paradigm.com)  
[okhttp](https://square.github.io/okhttp/)

## 脚本
```sql
create table USER
(
    ID           INTEGER  auto_increment,
    ACCOUNT_ID   VARCHAR(100),
    NAME         VARCHAR(50),
    TOKEN        CHAR(36),
    GMT_CREATE   BIGINT,
    GMT_MODIFIED BIGINT,
    constraint USER_PK
        primary key (ID)
);

```