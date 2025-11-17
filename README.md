<div align="center" >

# 🚀 Lista de Exercícios Javascript

Bem-vindo ao projeto da Lista de Exercícios sobre Funções Matemáticas em JavaScript! 🎉 Este repositório contém 10 funções essenciais, totalmente implementadas e testadas. 💪

</div>



---

## ✅ Status do Projeto

Este projeto está **COMPLETO** e todas as 10 funções matemáticas exigidas foram implementadas e verificadas.

**STATUS FINAL: APROVADO!** 

Todos os testes automatizados passaram com sucesso.

---

## 💻 Funcionalidades Implementadas (Funções)

O arquivo principal (`index.js`) implementa as seguintes funções, que cobrem operações básicas e conceitos de matemática:

| Questão | Função | Descrição | Reutilização |
| :---: | :--- | :--- | :--- |
| **1** | `somar(a, b)` | Realiza a soma simples de dois números. | Nenhuma |
| **2** | `multiplicar(a, b)` | Realiza a multiplicação simples de dois números. | Nenhuma |
| **3** | `subtrair(a, b)` | Realiza a subtração simples de dois números. | Nenhuma |
| **4** | `dividir(a, b)` | Realiza a divisão. **Lança um erro** se o divisor (`b`) for zero. | Nenhuma |
| **5** | `calcularMedia(...)` | Calcula a média de quatro notas, reutilizando a função `dividir()`. | `dividir()` |
| **6** | `elevarPotencia(...)` | Calcula a base elevada ao expoente (`Math.pow`). | Nenhuma |
| **7** | `calcularAreaRetangulo(...)` | Calcula a área de um retângulo, reutilizando a função `multiplicar()`. | `multiplicar()` |
| **8** | `verificarParOuImpar(...)` | Verifica se um número é "par" ou "ímpar" usando o operador módulo (`%`). | Nenhuma |
| **9** | `calcularRaizQuadrada(...)` | Calcula a raiz quadrada de um número (`Math.sqrt`). | Nenhuma |
| **10** | `calcularHipotenusa(...)` | Calcula a hipotenusa de um triângulo retângulo, reutilizando `somar()`, `elevarPotencia()` e `calcularRaizQuadrada()`. | Múltipla |

---

## ⚙️ Como realizar o exercício

### 1️⃣ - Clonar o repositório 🖥️

Para começar, você deve clonar este repositório na sua máquina. Abra o terminal e execute o seguinte comando:

```bash
git clone [https://github.com/profrafamatos/11-lista-js-1.git](https://github.com/profrafamatos/11-lista-js-1.git)
```

### 2️⃣ - Navegar até a pasta do repositório 📂

```bash 
cd 11-lista-js-1    
```

### 3️⃣ - Instalar as dependências 📦

Este projeto utiliza algumas dependências que precisam ser instaladas antes de rodar os testes. No terminal, execute o seguinte comando para instalar tudo direitinho:

```bash 
npm install
```
⚠️ Atenção: Isso irá instalar todas as dependências listadas no arquivo package.json.

### 4️⃣ - Resolver o exercício ✍️

A parte principal do exercício está no arquivo index.js. Abra-o no VSCode ou em seu editor de preferência e resolva as questões escrevendo o código nas áreas indicadas.

⚠️ Importante: Não altere o arquivo index.test.js. Esse arquivo contém os testes automatizados e não deve ser modificado.

### 5️⃣ - Rodar os testes automatizados ✅
Para verificar se sua solução está correta e passou em todos os requisitos:
```bash
npm test
```

- Resultado Esperado: Se todas as funções estiverem corretas (incluindo o tratamento de erro com throw new Error() na função dividir), você verá que todos os testes foram aprovados.