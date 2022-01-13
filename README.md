# Coletânea de estudos e comando com fofo em performance MySQL/MariaDB

## Check, Repara e Otimiza uma tabela de um banco Mysql

mysqlcheck -u root -p --auto-repair --optimize NOME_DO_BANCO NOME_TABELA

```shell
mysqlcheck -u root -p --auto-repair --optimize bitnami_moodle mdl_question
```

# Referências

[MYSQLCHECK - Doc. Oficial](https://dev.mysql.com/doc/refman/8.0/en/mysqlcheck.html)
