# Projeto1_Devops
Neste projeto, será containerizado um website estático (HTML, CSS e JavaScript) usando Docker e implantado manualmente em uma instância EC2 na AWS, utilizando o Amazon ECR (Elastic Container Registry) para gerenciamento de imagens.
## Índice
## Visão Geral
Neste projeto, será containerizado um website estático (HTML, CSS e JavaScript) usando Docker e implantado manualmente em uma instância EC2 na AWS, utilizando o Amazon ECR (Elastic Container Registry) para gerenciamento de imagens.

Por que isso é importante?
- Portabilidade: Seu site funcionará da mesma forma em qualquer ambiente
- Isolamento: Elimina problemas de "funciona na minha máquina"
- Escalabilidade: Base para futuras implementações mais complexas
- Padrão da Indústria: Docker é amplamente utilizado no mercado

## Pré-requisitos
### Ferramentas Necessárias

1. Docker Ubuntu
- Baixe em [docker.com/products/docker-desktop](https://docs.docker.com/engine/install/ubuntu/)
* Linux: Instale via terminal:

```
curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh
```
Para verificar a instalação:
```
docker --version
```
<img width="1280" height="72" alt="image" src="https://github.com/user-attachments/assets/51891312-1a00-4125-902f-c7bc316542a6" />
