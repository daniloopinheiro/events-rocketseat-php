# Rocketseat - Curso Online de PHP

## Introdução

Bem-vindo à primeira aula do curso de PHP da Rocketseat! Nesta aula, vamos configurar o ambiente de desenvolvimento no Windows, focando na instalação do Laravel Herd.

## Pré-requisitos

Antes de começarmos, certifique-se de ter os seguintes itens instalados:

1. **Node.js**
   - **Instalação**: Baixe e instale a versão mais recente do [Node.js](https://nodejs.org/).
   - **Verificação**: Após a instalação, você pode verificar se o Node.js está instalado corretamente rodando o comando no terminal:
     ```bash
     node -v
     ```
   - **npm**: O Node Package Manager (npm) é instalado junto com o Node.js. Verifique a versão do npm:
     ```bash
     npm -v
     ```

2. **PHP**
   - **Instalação**: Baixe e instale a versão mais recente do [PHP](https://www.php.net/downloads). Dependendo do seu sistema operacional, você pode usar gerenciadores de pacotes como `apt` no Ubuntu ou `brew` no macOS.
   - **Verificação**: Após a instalação, verifique se o PHP está instalado corretamente rodando:
     ```bash
     php -v
     ```

3. **Composer**
   - **Instalação**: O Composer é um gerenciador de dependências para PHP. Você pode instalá-lo seguindo as instruções em [getcomposer.org](https://getcomposer.org/download/).
   - **Verificação**: Após a instalação, verifique se o Composer está funcionando:
     ```bash
     composer -v
     ```

4. **Laravel**
   - **Instalação**: Para criar novos projetos Laravel, você pode usar o Composer. Execute o seguinte comando para instalar o instalador do Laravel globalmente:
     ```bash
     composer global require laravel/installer
     ```
   - **Verificação**: Após a instalação, você pode verificar se o Laravel foi instalado corretamente:
     ```bash
     laravel --version
     ```

5. **Livewire**
   - **Instalação**: Para usar o Livewire em um projeto Laravel existente, execute o seguinte comando dentro do diretório do seu projeto:
     ```bash
     composer require livewire/livewire
     ```
   - **Verificação**: Após a instalação, você pode verificar se o Livewire está funcionando corretamente ao criar um componente:
     ```bash
     php artisan make:livewire NomeDoComponente
     ```

## Aulda 2

![image](https://github.com/user-attachments/assets/2b423b68-15ff-4025-86c2-23a491f35a4e)


```json
Table users {
  id integer [primary key, increment]
  name string
  avatar string
  rating int
}

Table projects {
  id int [primary key, increment]
  title string
  description text
  created_at datetime
  ends_at datetime
  status string
  tach_stack json
  created_by fk [ref: < users.id]
}


Table proposls {
  id int [primary key, increment]
  email varchar
  hours int
  project_id fk [ref: < projects.id]
}     
```

![image](https://github.com/user-attachments/assets/a9da839d-9762-4f39-ab42-c34e4bbac729)
![image](https://github.com/user-attachments/assets/ac5e198b-4446-416c-aaa0-d8952f9c0aa3)

![image](https://github.com/user-attachments/assets/7fc1da98-b570-4351-bf02-823539bb420b)
![image](https://github.com/user-attachments/assets/7bbdc949-1ebe-41ca-9119-029b0cc55d06)
![image](https://github.com/user-attachments/assets/dc0c7c9f-77e4-4cc3-b02b-28c3f28dc3ac)
![image](https://github.com/user-attachments/assets/6b256fdc-1b2e-491e-829c-028ed9e8ea31)
![image](https://github.com/user-attachments/assets/c24f97a7-1474-4e2a-9565-23bd88dcf40a)
![image](https://github.com/user-attachments/assets/1a63a2f5-70bb-44b3-9d22-17b75584d113)







