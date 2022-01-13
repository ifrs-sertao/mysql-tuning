# Coletânea de estudos e comando com fofo em performance MySQL/MariaDB

## Check, Repara e Otimiza uma tabela de um banco Mysql com MYSQLCHECK

mysqlcheck -u root -p --auto-repair --optimize NOME_DO_BANCO NOME_TABELA

```shell
mysqlcheck -u root -p --auto-repair --optimize bitnami_moodle mdl_question
```

## MYSQLTUNER
Verificação de perfomance e segurança com script [MYSQLTUNER](https://github.com/major/MySQLTuner-perl).

### Execução simples no localhost do banco
Vai solicitar usuário senha do administrador do mysql.
```shell
perl mysqltuner.pl --host 127.0.0.1
```

# Referências

[MYSQLCHECK - Doc. Oficial](https://dev.mysql.com/doc/refman/8.0/en/mysqlcheck.html)

[Projeto MYSQLTUNER](https://github.com/major/MySQLTuner-perl)
