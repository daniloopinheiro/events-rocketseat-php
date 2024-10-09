# Rocketseat - Curso Online de PHP

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
```

3.  Reinicie seu computador se solicitado.

### Instalar o Homebrew

1.  Abra o terminal WSL (Ubuntu ou outra distribuição que você tenha instalado).
    
2.  Execute o seguinte comando para instalar o Homebrew:
    
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```    

### Instalar o Laravel Herd via CLI

Com o Homebrew instalado, execute o seguinte comando no terminal WSL:

```bash
brew tap laravel/legacy
brew install laravel/herd/herd` 
```

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

### Criar um Novo Projeto Laravel via CLI

![image](https://github.com/user-attachments/assets/20fffad0-3b41-442d-ac17-f005abc1ed0c)
![image](https://github.com/user-attachments/assets/0f952be9-881c-4833-8632-d44a81c36da5)
![image](https://github.com/user-attachments/assets/749ce8c2-c190-486f-9a35-bfc95794092e)
![image](https://github.com/user-attachments/assets/8ef61af1-f155-4a13-bf0c-b3b58adc0634)
![image](https://github.com/user-attachments/assets/b5515019-3e93-49a0-aa8c-16a06612527a)

### Criar um Novo Projeto Laravel default

![image](https://github.com/user-attachments/assets/fb9e8fca-0276-46ac-b4a4-5a8b86b57a04)
![image](https://github.com/user-attachments/assets/f564daa6-2f2f-4a55-9615-cdb0bd54bfd3)
![image](https://github.com/user-attachments/assets/f4586410-ec2a-47c9-bfce-3f799524ea14)
![image](https://github.com/user-attachments/assets/f3545cc3-4400-4018-930f-1e7a25864e10)
![image](https://github.com/user-attachments/assets/014922dc-6f0e-402a-878d-102318f9210f)
![image](https://github.com/user-attachments/assets/2a749956-aa95-4806-821d-853d5fb77ffc)
![image](https://github.com/user-attachments/assets/2d1bbe51-0edd-4db1-b6bc-58106a55c9f5)
![image](https://github.com/user-attachments/assets/92806f02-35ad-4889-b600-1190310f6e8d)
![image](https://github.com/user-attachments/assets/be96ae8a-db74-4ea5-b504-bddf7f2c9825)
![image](https://github.com/user-attachments/assets/25d1b215-9f32-41f9-8a19-162afb5fa39d)

👀 - Durante a execução do projeto, encontrei um erro informando que a porta especificada já estava em uso. Isso geralmente acontece quando outra aplicação ou serviço está utilizando a mesma porta. Minha solução foi a seguinte:

![image](https://github.com/user-attachments/assets/da6a7fb6-6167-4ae7-a143-1f02b5f8ab11)
![image](https://github.com/user-attachments/assets/66cd3afb-7323-4b48-b4ad-e5e67ef3cee4)
![image](https://github.com/user-attachments/assets/6a8645d3-0900-40f8-ad34-a4dcd210c730)
![image](https://github.com/user-attachments/assets/5f4ccc09-de43-4c51-aab0-6e1ff01e2fc8)

#### Abrir o Projeto pelo ´Herd´

![image](https://github.com/user-attachments/assets/8e1d34d0-9d42-47ee-baca-3c9dfee0c05e)

### Iniciar o Servidor via CLI

Para iniciar o servidor local, acesse a pasta do seu projeto e execute:

![image](https://github.com/user-attachments/assets/e0a645e0-fae2-49ee-9738-8f270d0cca23)
![image](https://github.com/user-attachments/assets/3fad61eb-d26d-4afb-b067-c7aba5106ed0)

O servidor deve estar disponível em `http://localhost:8000`.

### Iniciar o Servidor default

![image](https://github.com/user-attachments/assets/6ddf2ae3-a6ae-4a67-a7fa-9bcf21d1bf53)

### Instalar [livewire](https://laravel-livewire.com/docs/2.x/quickstart)

![image](https://github.com/user-attachments/assets/6ca7e3a9-64a8-4c41-81d6-1e2f3f0dc233)
![image](https://github.com/user-attachments/assets/899935af-bcc7-45ec-9a6c-c1af41f706c3)
![image](https://github.com/user-attachments/assets/8cdb7d5b-2e35-48b2-9aeb-099080a8f670)
![image](https://github.com/user-attachments/assets/b3a47f3d-bcaa-49d2-8692-4564e823fbdd)


#### Para Instalar 'Versões'

![image](https://github.com/user-attachments/assets/e009c2c4-11e6-4aa0-be09-c523e16768bc)
![image](https://github.com/user-attachments/assets/5869e756-73f7-4ed5-92af-436bd320a5dd)

## Dúvidas e Suporte

Se você tiver dúvidas, sinta-se à vontade para perguntar no grupo da comunidade [Rocketseat no Discord](https://discord.com/channels/327861810768117763/1292817017044340766) ou nos fóruns da Rocketseat.

*Developer Instructor*  
*[Rocketseat](https://app.rocketseat.com.br/?type=ALL)*    
*[LinkedIn](https://www.linkedin.com/in/daniloopinheiro/)*
