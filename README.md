# 📚 Miniguia de Estudos com NotebookLM – Python

## 📖 Sobre o Projeto

Este projeto consiste em um roteiro de estudos completo e uma base de documentação profissional focada na linguagem **Python**.

O objetivo é capacitar o estudante desde os fundamentos lógicos até o nível avançado e profissional, utilizando o **NotebookLM** como uma ferramenta de aprendizagem ativa.

Por meio da integração de **15 fontes**, incluindo livros renomados, documentação oficial do Python 3.14.6 e guias de estilo, foi possível sintetizar informações, comparar abordagens de ensino e gerar exercícios personalizados.

---

# 🎯 Objetivos de Aprendizagem

- Compreender profundamente a sintaxe e semântica do Python 3.14.6.
- Dominar estruturas de dados fundamentais.
- Aplicar boas práticas seguindo a PEP 8.
- Desenvolver habilidades em Programação Orientada a Objetos.
- Aprender automação de tarefas utilizando bibliotecas padrão.
- Preparar conhecimentos voltados ao mercado de trabalho.

---

# 📚 Curadoria de Fontes

| Fonte | Tipo | Principal contribuição | Nível |
|-------|------|------------------------|--------|
| Think Python | Livro | Desenvolvimento da lógica de programação | Iniciante |
| Documentação Oficial Python 3.14.6 | Documentação | Referência oficial da linguagem | Todos |
| PEP 8 | Guia de Estilo | Padronização e boas práticas | Profissional |
| Python Crash Course | Livro | Aprendizado baseado em projetos | Iniciante |
| Automate the Boring Stuff | Livro | Automação de tarefas reais | Iniciante / Intermediário |
| Fluent Python | Livro | Recursos avançados e código idiomático | Avançado |
| Effective Python | Livro | Boas práticas profissionais | Intermediário / Avançado |
| Exercism & HackerRank | Plataformas | Exercícios práticos | Todos |

## 📊 Análise Comparativa

### 👶 Para iniciantes

- Think Python possui excelente abordagem para desenvolver lógica.
- Python Crash Course acelera o aprendizado com projetos.

### 🚀 Para usuários avançados

- Fluent Python aprofunda o funcionamento interno da linguagem.
- Effective Python apresenta recomendações utilizadas no mercado.

### ⚙️ Projetos e Automação

- Automate the Boring Stuff é excelente para automações utilizando Python.

### 📖 Consulta e Boas Práticas

- Documentação Oficial do Python.
- PEP 8.

---

# 🤖 Engenharia de Prompts

Durante o estudo foram utilizados diversos tipos de prompts.

## Persona

Definir a IA como um mentor especializado em Python.

## Comparação entre fontes

Solicitar comparações entre livros e documentações.

## Aprendizagem Ativa

Aplicação de técnicas como:

- Active Recall
- Técnica de Feynman
- Spaced Repetition
- Learning by Doing

---

# 🔄 Evolução dos Prompts (Cicatrizes)

### Prompt inicial

```text
Explique o que são funções em Python.
```

### Prompt melhorado

```text
Explique funções comparando a abordagem do Think Python,
PEP 8 e Fluent Python.
```

### Resultado

Foi possível obter respostas mais completas, relacionando conceitos básicos, boas práticas e aplicações profissionais.

### Dificuldades Encontradas

- Respostas muito genéricas.
- Pouca comparação entre as fontes.

### Solução

Solicitar explicitamente que cada resposta utilizasse múltiplas fontes e destacasse diferenças entre elas.

---

# 📖 Miniguia de Estudos

## 📌 Fundamentos

### Resumo

Python é uma linguagem interpretada, de alto nível e com tipagem dinâmica.

### Exemplos

```python
nome = "Natan"
idade = 20

print(nome)
print(idade)
```

### Boas práticas

- Utilize nomes descritivos.
- Utilize `snake_case`.

### Erros comuns

- Confundir `=` com `==`.

---

## 📌 Estruturas de Dados

### Lista

```python
numeros = [1, 2, 3]
```

### Dicionário

```python
usuario = {
    "nome": "Natan",
    "idade": 20
}
```

### Tupla

```python
cores = ("azul", "verde", "vermelho")
```

### Boas práticas

Utilizar:

```python
usuario.get("nome")
```

ao invés de acessar diretamente quando a chave pode não existir.

---

## 📌 Controle de Fluxo

```python
if idade >= 18:
    print("Maior de idade")
else:
    print("Menor de idade")
```

```python
for numero in range(5):
    print(numero)
```

---

## 📌 Programação Orientada a Objetos

```python
class Pessoa:
    def __init__(self, nome):
        self.nome = nome

    def apresentar(self):
        print(f"Olá, meu nome é {self.nome}")
```

### Boas práticas

- Encapsulamento
- Herança quando necessária
- Classes pequenas e organizadas

---

## 📌 Bibliotecas Importantes

| Biblioteca | Utilização |
|------------|------------|
| math | Operações matemáticas |
| os | Sistema operacional |
| random | Valores aleatórios |
| collections | Estruturas avançadas |

---

# 📚 Glossário

| Termo | Definição |
|--------|-----------|
| PEP 8 | Guia oficial de estilo do Python |
| Dunder Methods | Métodos especiais como `__init__` |
| Imutabilidade | Objetos que não podem ser alterados |
| Refatoração | Melhorar o código sem alterar seu comportamento |

---

# 🧠 Roadmap de Estudos

```text
Fundamentos
      ↓
Variáveis e Tipos
      ↓
Controle de Fluxo
      ↓
Funções
      ↓
Estruturas de Dados
      ↓
POO
      ↓
Módulos
      ↓
Tratamento de Exceções
      ↓
Bibliotecas
      ↓
Projetos
      ↓
Testes
      ↓
APIs
      ↓
Automação
      ↓
Mercado de Trabalho
```

---

# 💻 Projetos Recomendados

| Projeto | Dificuldade |
|----------|-------------|
| Calculadora | ⭐ |
| Conversor de Temperatura | ⭐ |
| Agenda de Contatos | ⭐⭐ |
| Organizador de Arquivos | ⭐⭐⭐ |
| Dashboard em Python | ⭐⭐⭐⭐ |
| Automação de Planilhas | ⭐⭐⭐⭐⭐ |

---

# ❓ Perguntas para Revisão

- Qual a diferença entre listas e tuplas?
- O que é uma função?
- Quando utilizar um dicionário?
- O que significa tipagem dinâmica?
- Qual a função da PEP 8?
- O que é Programação Orientada a Objetos?

---

# 📝 Exercícios

## Fácil

Criar uma função que receba um nome e retorne uma saudação.

## Médio

Criar um programa que verifica se uma palavra é um palíndromo.

## Difícil

Implementar Fibonacci utilizando Memoization.

---

# 🚀 Prompts Reutilizáveis

```text
Explique este conceito utilizando exemplos simples.
```

```text
Compare este assunto entre todas as fontes.
```

```text
Crie exercícios sobre este tema.
```

```text
Faça perguntas para revisar este conteúdo.
```

```text
Explique utilizando analogias.
```

---

# 💡 Principais Aprendizados

- Legibilidade é prioridade no Python.
- Funções pequenas são mais fáceis de manter.
- Exceções tornam aplicações mais robustas.
- A documentação oficial é a principal referência da linguagem.
- Projetos práticos aceleram o aprendizado.

---

# ✅ Conclusão

O NotebookLM tornou o processo de aprendizagem mais organizado ao permitir reunir diversas fontes em um único ambiente, comparar abordagens, sintetizar conteúdos e produzir materiais personalizados para estudo.

Além de facilitar o aprendizado de Python, a ferramenta contribuiu para a criação deste miniguia, que pode servir como material de consulta, revisão e documentação para futuros projetos.
