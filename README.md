# TailwindCSS Explorer

Este projeto é um ambiente de experimentação com o [Tailwind CSS](https://tailwindcss.com/). Aqui, estou explorando classes utilitárias de fonte, cor, espaçamento e outros recursos oferecidos pelo framework.

## 🛠 Tecnologias utilizadas

- HTML5  
- Tailwind CSS (via CLI)

## 🚀 Como executar o projeto

1. Clone o repositório:

```bash
git clone git@github.com:JyojiTenguam/TailWindCSS-explorer.git
```

2. Instale as dependências (caso tenha `package.json`):

```bash
npm install
```

3. Inicie o Tailwind em modo watch:

```bash
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
```

4. Abra o arquivo `index.html` no navegador.

## 💡 O que estou testando

- 🔠 **Tamanhos de fonte** (`text-xs` até `text-9xl`)
- 🎨 **Cores** (`text-red-500`, `bg-gray-100`, etc.)
- 📏 **Espaçamento** (`p-4`, `m-7`, `space-y-4`, etc.)
- 🟦 Bordas (`border-2`, `border-yellow-400`, `rounded-t-lg`, etc.)
- 🖱️ Botão estilizado com `ring`, `bg-blue-400`, `text-white`
- 🌈 Backgrounds e gradientes (`bg-*`, `bg-gradient-to-*`, `from-*`, `to-*`)
- 📐 Largura e altura (`w-screen`, `h-screen`, etc.)
- 🧱 **Flexbox** e controle de layout (`flex`, `justify-*`, `items-*`, `space-x-*`)
  - 🔄 Comportamento de crescimento (`flex-grow`, `flex-shrink`, etc.)
- 🧮 **Grid layout** (`grid`, `grid-cols-*`, `gap-*`, `col-span-*`)
  - 📊 Testando diferentes divisões de coluna e como os elementos se adaptam
- 📱 **Responsividade** (`sm:`, `md:`, `lg:`, `xl:`, `2xl:`)
- 🌀 **Estados interativos** (`hover:`, `focus:`, `group-hover:`)
- 🎨 Cores personalizadas via `input.css` (`bg-brand-100`, `text-brand-200`, etc.)
- 🌑 **Modo Escuro** (`dark`)
  - 🌒 **Utilização do modo escuro com Tailwind CSS** aplicando a classe `.dark` para alterar a aparência de elementos.
- 🧰 **Classes customizadas com `@apply`**
  - 🛠️ Criando classes utilitárias personalizadas com `@layer utilities`
  - 💎 Exemplo: `.laravue` com `bg-brand-100` e `font-bold`
- 🧩 **Combinações de utilitários** para entender melhor o sistema do Tailwind

## 📁 Estrutura de pastas

```
projeto/
├── src/
│   ├── index.html                # Página HTML principal
│   ├── input.css                 # Arquivo de entrada do Tailwind
│   └── output.css                # Arquivo gerado com os estilos compilados
├── .gitignore                    # Arquivos e pastas ignoradas pelo Git
├── package-lock.json            # Controle de versões exatas das dependências
├── package.json                 # Configurações do projeto e dependências
└── README.md                    # Documentação do projeto
```

---

## 📌 Observações

Este projeto é apenas um playground para aprendizado e testes com Tailwind CSS. Sinta-se à vontade para clonar e brincar com ele também!
