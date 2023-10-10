## Atividade criação de containers com mapeamento de volumes

### 1 - Criar um diretório, e dentro do diretório criar um arquivo index.html com o conteúdo abaixo:
``` 
<h1>Hello World</h1>
```

### 2 - Subir um container com NGINX mapeando o diretório criado com o arquivo index.html no passo "1" para o diretório "/usr/share/nginx/html/" e usar a porta do host 9092 para a 80 do container.

### 3 - Acessar o serviço NGINX no container e capturar o log de acesso.

### 4 - Construir uma imagem usando o Dockerfile adicionando o arquivo criado no passo "1" dentro da imagem base no diretório /usr/share/nginx/html/ dentro do container, e a imagem terá o nome atv_01_nginx:v1.

### 5 - Alterar a imagem criado no passo "4" para atv_01_nginx:v2, e agora o arquivo "index.html" deve ter o conteúdo abaixo:
```
<h1>Atividade Docker - 01 </h1>
```

> [!NOTE]
> Essa alteração deve usar o "RUN" para alterar o conteúdo do arquivo no build.