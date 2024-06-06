# O que são os Namespaces em PHP POO ?

 ## Namespaces são qualificadores que resolvem dois problemas diferentes:

- Eles permitem uma melhor organização agrupando classes que trabalham juntas para realizar uma tarefa;
- Eles permitem que o mesmo nome seja usado para mais de uma classe;

## Namespaces são declarados no início de um arquivo usando a namespace palavra-chave: 
```sh
<?php
namespace Html;
?>
```

> Note:  Uma namespace declaração deve ser a primeira coisa no arquivo PHP.

> O nome do namespace PHP e os nomes compostos que começam com esse nome (como PHP\Classes) são reservados para uso interno da linguagem e não devem ser usados no código criado pelo usuário.