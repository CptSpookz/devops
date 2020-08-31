# 1.2 Configuração do Ambiente

Neste capítulo veremos como instalar e configurar o ambiente do Docker + Docker Compose que será utilizado nos capítulos a seguir.

## Windows
- Faça o download do instalador do Docker Desktop [aqui](https://hub.docker.com/editions/community/docker-ce-desktop-windows/).
- Abra o instalador e siga as instruções **(Importante: deixe a opção "Enable Hyper-V Windows Features" ativa!)**
- Quando o processo de instalação terminar, reinicie o computador.
- Tanto o Docker quanto o Docker Compose estarão instalados na sua máquina, e podem ser testados abrindo uma janela do Powershell e inserindo comandos como `docker run hello-world`.

## Linux
- Ubuntu:
  - No terminal, instale os pacotes `docker` e `docker-compose` com `sudo apt install docker.io docker-compose`;
- Arch:
  - No terminal, instale os pacotes `docker` e `docker-compose` com `sudo pacman -S docker docker-compose`;
- Rode o comando `sudo usermod -aG docker $USER` para adicionar o usuário atual ao grupo do docker para poder rodar o comando sem ser root;
- Feche o terminal e abra de novo (talvez seja necessário reiniciar o computador para finalizar a instalação e ativar o daemon do docker);
- Rode o comando `docker run hello-world` para confirmar que a instalação aconteceu corretamente.

![Instalação no Linux](https://i.imgur.com/OQR8ByS.jpg)
