[![Gmail Mel](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:melissameira92@gmail.com)
[![LinkedIn Mel](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/melissa-perdomo/)
[![Instagram Mel](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/amelperdomo/)


### Ambiente docker que inicializa um servidor php 8.3 na porta 8000, via nginx.

# Requisitos
- [Docker Engine](https://docs.docker.com/engine/install/)
- Make
  - Debian/Ubuntu: (`sudo apt install make`)
  - MacOS: `xcode-select --install`
  - Windows: `choco install make`

# Instalação
- `sudo make build && sudo make run`

# Ligar/desligar o container
- Inicializar o container: `sudo make start`
- Parar o container: `sudo make stop`

# Uso
- Seus arquivos php podem ser acessados em http://localhost:8000
- Crie seus prórpios arquivos dentro da pasta `exercicios` e acesse-os como a seguir: http://localhost:8000/00/teste.php
