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
