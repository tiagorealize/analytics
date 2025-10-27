# Logo do Projeto

## 📁 Localização
Coloque seu arquivo `logo.svg` na pasta `public/` do projeto.

## 📐 Especificações Recomendadas
- **Formato**: SVG (vetorial, escala perfeita)
- **Tamanho**: 150x75 pixels de referência (escala automaticamente)
- **Estilo**: Retangular horizontal, preferencialmente com fundo transparente
- **Nome do arquivo**: `logo.svg`

## 🎨 Como Funciona
O logo será exibido:
- No sidebar desktop (lado esquerdo)
- No sidebar mobile (quando aberto)
- Tamanho de 150x75 pixels
- Com `object-contain` para manter proporção
- Escala perfeita em qualquer resolução (vantagem do SVG)

## 📝 Exemplo de Estrutura
```
public/
├── logo.svg          ← Seu logo aqui (SVG)
└── favicon.ico       ← Ícone do navegador (opcional)
```

## 🔄 Fallback
Se o arquivo `logo.svg` não existir, será exibido um espaço vazio onde o logo deveria aparear.

## ✨ Vantagens do SVG
- Escala perfeita em qualquer tamanho
- Arquivo menor que PNG
- Qualidade impecável em telas de alta resolução
- Ideal para logos e ícones
