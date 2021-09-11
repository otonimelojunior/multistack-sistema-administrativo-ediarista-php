## Projeto sistema administrativo da plataforma E-Diaristas

Desenvolvido no curso multi-stack da treinaweb

### Instalando o projeto

#### Clonar o repositório

```
git clone https://github.com/otonimelojunior/multistack-sistema-administrativo-ediarista-php.git
```

#### Instalar as dependências

```
composer instal
```

Ou em ambiente de desenvolvimento:

```
composer update
```

#### Criar arquico de conficurações de ambiente

Copiar o arquivo de exemplo `.env.example` para `.env` na raiz do projeto. Configurar os detalhes da aplicação e conexão com o banco de dados.

#### Criar a estrutura no bamco de dados

```
php artisan migrate
```

#### Criar o usuário adim

```
php artisan db:seed

Usuário: admin
Email: admin@admin.com
Senha: 123456789
```

#### Iniciar o servidor de desenvolvimento

```
php artisan serve
```
