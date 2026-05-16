🔎Proposta da atividade 1 (métodos de dicionário): 

Siga os seguintes passos em ordem:

1) Crie um dicionário chamado "notas" com esses valores iniciais:
    - "Alice": 85
    - "Bob": 90
    - "Charlie": 78

2) Imprima todos os nomes dos alunos e notas usando essas instruções exatas:
    - print("Estudantes: ", notas.key())
    - print("Notass: ", notas.values())

3) Adicione uma nova aluna "Diana" com nota 92;

4) Use o método get() para buscar a nota de Bob e armazene-a em uma variável notas_bob e imprima-a;

5) Remova Charlie do dicionário usando o método pop() e imprima o dicionário atualizado.



RESOLUÇÃO:

```python
notas = {
    "Alice" : 85,
    "Bob" : 90,
    "Charlie": 78
}

print("Estudantes: ", notas.key())
print("Notas: ", notas.values())

notas["Diana"] = 92

notas_bob = notas.get("Bob")
print("A nota de Bob é:", notas_bob)

notas.pop("Charlie")

print("Notas atualizadas:", notas)
```



🔑Proposta de atividade 2 (Verificando chaves):

Dado um dicionário com o nome e funções de um funcionário, faça o que é proposto:

1) Verifique se o nome "Alice" é uma chave do dicionário. Se for imprima "Alice está na empresa.";

2) Verifique se o nome "John" **NÃO ESTÁ** nas chaves do dicionário. Se não estiver, imrpima "John não faz parte da empresa.".

```python
empregados = {"Alice" : "RH", "Bernardo" : "Engenheiro", "Diego" : "Marketing"}

if "Alice" in empregados:
    print("Alice está na empresa.")
else:
    print("Alice não faz parte da empresa.")

if "John" in empregados:
    print("John está na empresa.")
else:
    print("Alice não faz parte da empresa.")
```


🔑Proposta de atividade 3 (Verificando chaves):

Crie uma função com dois parâmetros: *inventário* que é um dicionário e *item* que é uma string que representa um item a ser verificado. A função deve:

1) Verificar se *item* é uma chave do dicionário *inventário*;

2) Se existir, retornar a string "'*item*' está no estoque. Quantidade: 'quantidade'";

3) Caso o item não existir, retornar a string "'*item*' não está no estoque";

```python
def checagem_inventario (inventario, item):
    if item in inventario:
        return f"{item} está no estoque. Quantidade: {quantidade}.")
    else:
        return f"{item} não está no estoque.")
```   
