# Tokens

Tokens são a base técnica para transformar a identidade visual da WAI em produto consistente.

Este arquivo define a intenção dos tokens. Os valores finais devem ser consolidados antes de virar package consumível por aplicações.

## Categorias

- color
- typography
- spacing
- radius
- shadow
- border
- z-index
- motion

## Nomenclatura recomendada

Use nomes por função, não por aparência.

Bom:

```txt
color.background.primary
color.text.secondary
color.action.primary
color.border.subtle
```

Ruim:

```txt
blue-500
cyan-card
black-bg
```

## Motivo

Tokens por função permitem trocar valores visuais sem quebrar a semântica do produto.

## Regra

Toda decisão visual repetida em mais de um produto deve virar token.

Toda exceção deve ser justificada.
