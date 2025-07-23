# 🛡️ Projeto Para Demonstracao CI/CD

Um sistema moderno desenvolvido em **Java**, com infraestrutura baseada em **Docker**, automação de pipelines via **GitHub Actions**, deploy completo em **AWS** e cobertura de testes com **JUnit**. Este projeto entrega CI/CD completo com qualidade, segurança e escalabilidade.

---

## 🚀 Tecnologias

- 💻 **Java 21**
- 🐳 **Docker**
- ☁️ **AWS (EC2, S3, RDS, IAM)**
- 🔁 **GitHub Actions** (CI/CD completo)
- ✅ **JUnit 5** para testes automatizados

---

## ⚙️ CI/CD

Este projeto utiliza **GitHub Actions** para automatizar todo o ciclo de vida:

1. **Build** automatizado do projeto
2. **Execução de testes unitários**
3. **Docker build & push**
4. **Deploy automático na AWS**

CI/CD 100% funcional, desde o push até a produção.

---

## 🧪 Testes

- Implementados com **JUnit 5**
- Rodados automaticamente na pipeline de CI
- Garantem qualidade e confiança no código

---

## 🐳 Docker

Todos os serviços são conteinerizados:

```bash
docker-compose up --build
