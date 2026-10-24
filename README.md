# 🚚 APS - DeliveryExpress (Testes Automatizados com Jest)

Este repositório contém a suíte de testes automatizados e a implementação das funções do software **DeliveryExpress**, desenvolvidos para APS.

---

## 👥 Integrantes da Equipe
* Gabriel da Silva Frazão - Matricula: 1-2025200046

---

## 📋 Resumo do Projeto
O objetivo da APS foi construir 20 casos de teste (CT-01 a CT-20) com critérios de aceitação no formato **DADO / QUANDO / ENTÃO**, utilizando a biblioteca **Jest**, e implementar 5 funções em JavaScript para atender às regras de negócio com 100% de cobertura de código:

1. **`autenticar`**: Autenticação de credenciais de usuários ativos.
2. **`forcaSenha`**: Classificação de força de senha (`fraca`, `media`, `forte`).
3. **`podeLogar`**: Controle de tentativas incorretas de login e status do usuário.
4. **`calcularFrete`**: Cálculo progressivo do valor de entrega por quilometragem.
5. **`aplicarCupom`**: Aplicação de descontos e validação de cupons promocionais.

---

## 🚀 Como Executar os Testes

1. **Instalar as dependências:**
   ```bash
   npm install