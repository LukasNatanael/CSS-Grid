# CSS Grid

## Grid
- Biodimensional
- Divisão de toda a página em linhas e colunas
- Colocar elementos onde quiser nessa divisão

---

## Grid ou Flexbox
- Grid: Duas dimensões (colunas e linhas)
- Flexbox: Uma dimensão (coluna ou linha)
- Se complementam

---

## Propiedades
Vamos separar em 2 grupos:
`container` e `item(s)`

### Container
- display:grid;
- grid-template-columns;
- grid-template-rows;
- grid-gap
    - grid-row-gap
    - grid-column-gap
- grid-template-areas;

... e mais 4 propriedades e **alinhamento**

### Item(s)
- grid-column
    - grid-column-start
    - grid-column-end
- grid-row
    - grid-row-start
    - grid-row-end
- grid-area

... e mais 2 propriedades e **alinhamento**

---

## Grid: alinhamento

Existem 6 propriedades para alinhamento:
1. `justify-content`
1. `align-content`
1. `justify-items`
1. `align-items`
1. `justify-self`
1. `align-self`

Vamos separar em 2 grupos:
1. `justify` e `align`
1. `content`, `items` e `self`

---

## Justify e Align

Sabendo que o grid é **bidimensional**, nós temos **dois eixos**, **x** e **y**

* **eixo x**: posicionamento horizontal, da esquerda para a direita

* **eixo y**: posicionamento vertical, de cima para baixo

## Content, Items e Self

Juntando `justify` ou `align`, com esses elementos: `content`, `items` `self`; nós observamos nossa propriedades

## Content

`justify-content` e `align-content` nos permite alinhar o próprio grid, relativo ao espaço fora do grid.

O uso dessa propriedades são raras, pois só é aplicado caso o grid seja menor que a área definida.

Por exemplo, quando usamos o tamnho em px do grid, poderemos terminar com um grid pequeno, para o tamanho da área do grid.

Podemos usar **7 valores**:

1. start
1. end
1. center
1. stretch
1. space-between
1. space-arround
1. space-evenly

---

## Items

`justify-items` e `align-items` nos permite alinhar os items do nosso frid, em qualquer espaço disponível, na cédula que ele habitar.

Podemos usar **4 valores**:

1. start
1. end
1. center
1. stretch

---

## Self

`justify-self` e `align-self` nos permite alinhar o item em sí mesmo.

Faz a mesma coisa que `justify-items` e `align-items`, porém, aplicado diretamente no item de um grid.

