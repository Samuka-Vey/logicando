# Diversão Binária

## Descrição
Dada uma sequência de caracteres alfanuméricos, produza uma nova sequência onde **letras** são representadas por **0** e **dígitos** por **1**.

Exemplo:  
`a b c d 1 9 4 3` → `0 0 0 0 1 1 1 1`.

---

## Entrada
- A primeira linha contém um inteiro **N** (1 ≤ N ≤ 10⁵), o tamanho da sequência.  
- A segunda linha contém **N** tokens, cada um sendo **uma letra [A–Z|a–z]** ou **um dígito [0–9]**.  

> Observação: apenas caracteres ASCII alfanuméricos; sem acentos ou símbolos.

---

## Saída
Imprima uma linha com **N** números (`0` ou `1`) separados por espaço, onde:  
- `0` representa **letra**;  
- `1` representa **dígito**.  

---

```js
8
a b c d 1 9 4 3
```


**Saída**
```js
0 0 0 0 1 1 1 1
```

---

## Exemplo 2

**Entrada**

```js
5
A z 0 b 7
```


**Saída**
```js
0 0 1 0 1
``


