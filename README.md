# 🚀 Projeto DIO - App Base com Kubernetes

Este projeto foi desenvolvido como parte do bootcamp da Digital Innovation One (DIO), utilizando Node.js e Kubernetes. A aplicação foi personalizada por mim para demonstrar o deploy em um cluster usando arquivos YAML.

## 🛠️ Tecnologias

- Node.js
- HTML/CSS
- Docker
- Kubernetes (Minikube ou GKE)
- Git e GitHub

## 💡 Funcionalidades

- Página simples com layout personalizado
- Backend Node.js básico
- Deploy completo no Kubernetes
- Estrutura pronta para produção

## ⚙️ Como Executar

### 1. Clonar o projeto
```bash
git clone https://github.com/seu-usuario/k8s-meu-projeto-dio.git
cd k8s-meu-projeto-dio
```

### 2. Rodar localmente
```bash
cd app
npm install
node server.js
```

### 3. Rodar no Kubernetes
Com o Minikube iniciado:
```bash
kubectl apply -f k8s/
kubectl get pods
kubectl get svc
```

Depois, acesse via NodePort no navegador.

## 💾 Banco de Dados
O arquivo `banco.sql` contém um exemplo de estrutura de banco caso necessário.

## ✍️ Autora
[Damares Lourenço](https://github.com/DamaresLourenco)
