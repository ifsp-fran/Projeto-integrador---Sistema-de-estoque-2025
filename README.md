Sistema de Controle de Estoque

##  Descrição do Projeto
Sistema completo de gerenciamento de estoque desenvolvido em linguagem C, permitindo o controle eficiente de produtos, categorias, entradas/saídas e geração de relatórios.

Objetivos do Projeto
- Aplicar os conceitos aprendidos na disciplina de forma prática
- Desenvolver um sistema funcional e útil
- Demonstrar domínio da linguagem C
- Criar uma base sólida para projetos futuros

 Funcionalidades Implementadas

1.  Cadastro de Produtos
- Código único automático
- Validação de dados
- Categorização
- Controle de estoque mínimo

2.  Listagem Completa
- Visualização de todos os produtos
- Status do estoque (OK, Baixo, Esgotado)
- Valor total do estoque
- Formatação tabular

3.  Sistema de Busca
- Busca por código
- Busca por nome
- Resultados detalhados

4.  Controle de Estoque
- Entrada de mercadorias
- Saída controlada (com validação)
- Atualização em tempo real

5.  Relatórios Inteligentes
- Alertas de estoque baixo
- Produtos esgotados
- Sugestões de reposição

6.  Organização por Categoria
- Agrupamento automático
- Estatísticas por categoria
- Visão organizada do estoque

Tecnologias e Conceitos Utilizados

Ambiente de Desenvolvimento e Execução

- Linguagem: C (padrão C99)
- Ambiente de Teste: GDB Online
- Compilador: GCC  
- Plataforma: Desenvolvido e testado no GDB Online Compiler

Nota: Este projeto foi desenvolvido e testado especificamente no GDB Online Compiler, garantindo total funcionamento nesse ambiente. O código segue o padrão C99 para máxima compatibilidade.   https://www.onlinegdb.com/edit/iJpIyWc-NT 
shared link:  https://onlinegdb.com/HM78r2gTHQ


Conceitos Aplicados da Disciplina

| Conceito | Aplicação no Projeto |
|----------|---------------------|
| **Structs**         | Estrutura Produto com todos os campos necessários |
| **Arrays**          | Vetor de produtos com tamanho fixo |
| **Funções**       | Modularização em funções específicas |
| **Arquivos**       | Persistência em arquivo texto |
| **Strings**          | Manipulação de nomes e categorias |
| **Loops**            | for/while para listagens e buscas |
| **Condicionais** | Validações e controles de fluxo |
| **Operadores**   | Lógicos e relacionais para validações |

Estrutura do Código

```c
// Estrutura principal do produto
typedef struct {
    int codigo;
    char nome[50];
    char categoria[30];
    float preco;
    int quantidade;
    int estoque_minimo;
} Produto;



