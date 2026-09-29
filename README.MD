# **Projeto em PYTHON para calcular médias**
#### Projeto que calcula as médias dos alunos e traz o resultado se está aprovado ou nao.
---

### Tecnologias utilizadas

#### Linguagem utilizada somente Python
#### Editor Visual code
#### Extensão do app base 3.12.7

---

### Como instalar e executar
#### Usar uma IDE de sua prerencia

### Exemplo de uso ou demonstração

```
#Projeto exemplo: Calcular média do aluno

def calcular_media(nota1, nota2):
    return(nota1 + nota2) /2

print("=== Sistemas de Notas do Aluno ===")
n1 = float(input("digite a primeira nota:"))
n2 = float(input("Digite a segunda nota:"))
media = calcular_media(n1, n2)
print(f"A media final é: {media:.2f}")
if media >= 7.0:
    print("Status: APROVADO!")
else:
    print("Status: REPROVADO") 
```

### Autor e contato
#### Leandro de Paiva
#### Github: https://github.com/Leandrodepaiva91/Introducion
#### Linkedin: https://www.linkedin.com/in/leandrodepaiva/