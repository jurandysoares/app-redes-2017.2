# HTTP

## Telnet

## Curl
Ver [material](https://github.com/lrlucena/webapp/blob/master/conteudo/http.md) do professor [Leonardo Lucena](https://github.com/lrlucena).

## Python

## Oulu

1. Criar seu próprio site na Oulu: `sudo cria-meu-sitio`

2. Publicar algum conteúdo: 
```
/var/www/nome-sobrenome/html/
         \____________/
           Seu usuário

Ou /var/www/$USER/html
```

3. Criar algum script: 
```
/var/www/nome-sobrenome/cgi-bin/
         \____________/
           Seu usuário

Ou /var/www/$USER/cgi-bin/
```

3. Configurar sua agenda local de endereços IP:

  * Linux/Mac: `/etc/hosts`
  * Windows: `C:\Windows\System32\Drivers\etc\hosts`
  
  Conteúdo: 
  /```
# <IP>          <Nome>
10.210.X.Y     nome-sobrenome.ifrn.lab
                 \____________/
                   Seu usuário
  ```
 
4. Acessar seu navegador Web: 

```
http://nome-sobrenome.ifrn.lab
       \____________/
        Seu usuário
```
