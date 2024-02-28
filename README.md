```
fatorial = int(input("digite um número para calcular o seu fatorial"))
def somar_fatorial(fatorial):
  antecessor = fatorial -1
  resultado = 0
  while antecessor != 0:
  resultado_1 = resultado + fatorial * antecessor
  antecessor -= 1
  while antecessor != 0: 
  resultado_1 = resultado_1 * antecessor
  antecessor -= 1
  return resultado
resultado = somar_fatorial(10)
print(resultado)
```

```markdown

Digite aqui...

```

