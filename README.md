# Landing Page - Estética Automotiva (template genérico)

Página única, responsiva, tema escuro, sem build. É só abrir o `index.html` no navegador ou hospedar.
Feita para ser mostrada a vários estúdios de estética automotiva: conteúdo genérico e fácil de trocar.

## Como personalizar

### 1. Bloco `CONFIG` (final do `index.html`, dentro do `<script>`)
| Campo | O que é |
|---|---|
| `nome` | Nome do estúdio |
| `whatsapp` | Número com país + DDD, só dígitos. Ex: `5511988887777` |
| `telefone` | Telefone como aparece na tela |
| `endereco` | Endereço completo (também monta o mapa do Google sozinho) |
| `instagram` | Link do Instagram |
| `msgPadrao` | Texto que já vem preenchido no WhatsApp ao clicar nos botões |

Todos os botões verdes de WhatsApp, telefone, endereço, Instagram e o mapa são preenchidos a partir daí.

### 2. Textos
Procure e substitua no HTML:
- `Studio Detail` → nome do estúdio (logo, título da aba, rodapé)
- `Site desenvolvido por Sua Empresa` no rodapé → sua marca
- Estatísticas do topo (`+8 anos`, `4,9 ★`, `Garantia`)
- Seções **Sobre**, **Serviços** (deixe só os que o estúdio faz), **Depoimentos** (use os do Google), **FAQ**
- Horário de atendimento (seção Contato e rodapé)

### 3. Imagens
Fundo do topo (`hero-bg`), imagem da seção **Sobre** (`about-media`) e as 6 fotos da **galeria**.
As atuais são do Unsplash (placeholder). Troque pelas fotos reais de antes e depois dos serviços.

### 4. Cores
No `:root` do `<style>`: `--brand` (azul), `--accent` (laranja dos botões), `--bg` e `--surface` (tons do fundo escuro).

## Publicação
O site está no GitHub Pages. Depois de editar, rode `git commit -am "..."` e `git push`
que o Pages reconstrói a página em 1 a 2 minutos.
