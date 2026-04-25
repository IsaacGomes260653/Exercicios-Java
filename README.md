# 🔐 Java — Segurança Cibernética | CEUB

Repositório com os projetos e atividades de **Java** desenvolvidos durante as aulas de **Segurança Cibernética** no CEUB.  
Os projetos exploram conceitos reais de segurança da informação implementados com Java.

---

## 📁 Estrutura do repositório

```
📦 Java-Seguranca
 ┣ 📂 crack-de-senhas/       # Simulador de ataque de força bruta com threads
 ┗ 📄 README.md
```

---

## 🛠 Tecnologias utilizadas

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SHA-256](https://img.shields.io/badge/SHA--256-333333?style=flat-square&logoColor=white)
![Threads](https://img.shields.io/badge/Multithreading-0A66C2?style=flat-square&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 📚 O que você vai encontrar aqui

- 🔑 **Crack de Senhas** — simulador de ataque de força bruta que utiliza múltiplas threads para testar combinações de senhas hasheadas em **SHA-256**
  - Ataque numérico (0 a 1 bilhão)
  - Ataque alfabético minúsculo (4, 5 e 6 letras)
  - Ataque alfabético maiúsculo (4 letras)
- 🔒 Hashing com `MessageDigest` (SHA-256)
- 🧵 Programação concorrente com `Thread` e `Runnable`
- 🗺 Uso de `HashMap` para mapeamento de hashes

---

## 🧠 Como funciona o Crack de Senhas

```
1. Um mapa de hashes SHA-256 é carregado com usuários e suas senhas criptografadas
2. Cada thread testa uma faixa de combinações de senhas em paralelo
3. Para cada tentativa, calcula o hash e compara com o mapa
4. Se encontrar correspondência, exibe o usuário e a senha descoberta
```

> ⚠️ **Aviso:** Este projeto tem fins **exclusivamente educacionais**, desenvolvido em ambiente acadêmico controlado no CEUB. Não utilize para fins ilegais.

---

## 🔄 Status do repositório

> 📖 **Em andamento** — sendo atualizado conforme avanço nas aulas.

---

## 👨‍💻 Sobre

Estudo **Ciência da Computação** no CEUB, Brasília, e este repositório reúne projetos práticos da disciplina de Segurança Cibernética.  
Sinta-se à vontade para explorar e trocar uma ideia!

---

## 📬 Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/isaac-gomes-de-moraes-107198365)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:Isaacgm260653@gmail.com)

---

<div align="center">
  <sub>// segurança começa pelo conhecimento 🔐</sub>
</div>
