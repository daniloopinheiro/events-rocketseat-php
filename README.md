# Rocketseat - Events PHP

## Introdução

Bem-vindo à primeira aula do curso de PHP da Rocketseat! Nesta aula, vamos configurar o ambiente de desenvolvimento no Windows, focando na instalação do Laravel Herd.

## Pré-requisitos

Antes de começarmos, certifique-se de ter os seguintes itens instalados:

1. **Windows**: Recomendado usar Windows 10 ou superior.
2. **WSL (Windows Subsystem for Linux)**: Você pode instalar o WSL para facilitar a execução de comandos do Linux. Siga as instruções em [Documentação do WSL](https://docs.microsoft.com/pt-br/windows/wsl/install).
3. **Homebrew**: Necessário para gerenciar pacotes no WSL. Se você ainda não tem, instale o Homebrew seguindo as instruções em [brew.sh](https://brew.sh/).

## Passos para Instalação do Laravel Herd

### Instalar o WSL

1. Abra o PowerShell como Administrador.
2. Execute o seguinte comando para instalar o WSL:

   ```bash
   wsl --install
3.  Reinicie seu computador se solicitado.

### Instalar o Homebrew

1.  Abra o terminal WSL (Ubuntu ou outra distribuição que você tenha instalado).
    
2.  Execute o seguinte comando para instalar o Homebrew:
    
    bash
    
    Copiar código
    
    `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"` 
    

### Instalar o Laravel Herd via CLI

Com o Homebrew instalado, execute o seguinte comando no terminal WSL:

bash

Copiar código

`brew tap laravel/legacy
brew install laravel/herd/herd` 

### Instalar o Laravel Herd default

![instalar-herd](https://github.com/user-attachments/assets/6b9025b8-8f0d-4799-94c3-8ff87cf959bb)

![instalar-herd-adm](https://github.com/user-attachments/assets/9ca3db40-f27b-4f6e-b17b-c4d2f6145956)

![image](https://github.com/user-attachments/assets/57066cf3-d934-4a03-bbf2-e4b1b4d7a5d3)

![image](https://github.com/user-attachments/assets/4d642b82-5c2b-440a-b9d8-bf7f437fbdee)


### Verificar a Instalação

Após a instalação, verifique se o Herd foi instalado corretamente:

bash

Copiar código

`herd --version` 

## Aula 1

### Criar um Novo Projeto Laravel

Para criar um novo projeto Laravel utilizando o Herd, use o comando:

bash

Copiar código

`herd new nome-do-projeto` 

Substitua `nome-do-projeto` pelo nome desejado.

### Iniciar o Servidor

Para iniciar o servidor local, acesse a pasta do seu projeto e execute:

bash

Copiar código

`cd nome-do-projeto
herd serve` 

O servidor deve estar disponível em `http://localhost:8000`.

## Aula 2 

## Aula 3

## Conclusão

Parabéns! Você configurou seu ambiente de desenvolvimento e está pronto para iniciar suas práticas em PHP com Laravel. Na próxima aula, exploraremos mais conceitos e práticas.

## Dúvidas e Suporte

Se você tiver dúvidas, sinta-se à vontade para perguntar no grupo da comunidade [Rocketseat no Discord](https://discord.com/channels/327861810768117763/1292817017044340766) ou nos fóruns da Rocketseat.
