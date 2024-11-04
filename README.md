# Atividade 04 - Talento Cloud

Este projeto faz parte do curso **Talento Cloud**, oferecido pela **Proz** em parceria com a **AWS**. Atualmente, estou no módulo **Preparação para HTML/CSS**. Nesta atividade, vou atualizar o array de produtos da loja de cosméticos, fazendo algumas alterações e impressões. O código foi desenvolvido no **Google Colab** (Pode ser acessado aqui: https://colab.research.google.com/drive/1Xd5XPL5u3jNnBrs6J2bANNcy_InA-3m7?usp=sharing).

## Descrição da Atividade

Nesta atividade, o objetivo é atualizar a lista de produtos de uma loja de cosméticos. As mudanças necessárias são:

1. Substituir "batons" por "rímel".
2. Substituir "loções" por "cremes hidratantes".
3. Remover "delineadores" da lista.
4. Imprimir a nova lista no terminal para verificar as alterações.

Como desafio, também é solicitado que sejam adicionados dois novos produtos à escolha.

## Estrutura do Código

O código contém as seguintes etapas:

1. Declaração da lista `lista_produtos` com os produtos da loja.
2. Atualização dos produtos conforme solicitado.
3. Remoção do produto "delineadores" da lista.
4. Adição de dois novos produtos.
5. Impressão da nova lista no terminal.

## Código

```python
# Declaração da lista de produtos da loja de cosméticos
lista_produtos = ['máscaras faciais', 'batons', 'esmaltes', 'perfumes', 
                  'loções', 'xampus', 'sabonetes', 'delineadores']

# Atualização da lista de produtos
lista_produtos[1] = 'rímel'               # Substituindo 'batons' por 'rímel'
lista_produtos[4] = 'cremes hidratantes'  # Substituindo 'loções' por 'cremes hidratantes'
lista_produtos.pop(7)                     # Removendo 'delineadores'

# Adicionando dois novos produtos
lista_produtos.append('cremes para mãos')  # Novo produto
lista_produtos.append('protetor solar')    # Novo produto

# Impressão da nova lista no terminal
for produto in lista_produtos:
    print(f'Temos {produto} à venda!')
```

## Resultado Esperado

Ao rodar este código, o terminal deverá exibir:

```
Temos máscaras faciais à venda!
Temos rímel à venda!
Temos esmaltes à venda!
Temos perfumes à venda!
Temos cremes hidratantes à venda!
Temos xampus à venda!
Temos sabonetes à venda!
Temos cremes para mãos à venda!
Temos protetor solar à venda!
```

## Tecnologias Utilizadas

- **Python**: Linguagem de programação usada para realizar a atividade.
- **Google Colab**: Ambiente de desenvolvimento onde o código foi executado.

## Sobre o Projeto Talento Cloud

Este projeto faz parte da formação em programação promovida pela Proz em parceria com a AWS, através do programa Talento Cloud, que visa capacitar alunos com competências em programação e desenvolvimento de software.
