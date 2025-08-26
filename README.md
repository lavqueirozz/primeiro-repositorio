# 🇬🇷 Card de Receitas Clássicas Gregas

Bem-vindo ao repositório **Card de Receitas Clássicas Gregas**!  
Este projeto tem como objetivo criar uma interface interativa e visualmente atraente para exibir receitas tradicionais da culinária grega, como Moussaka, Gyros, Tzatziki, Spanakopita, entre outras.

---

## 📸 Preview

![Screenshot do Card de Receitas](link-da-imagem-ou-gif-aqui)

---

## 🧾 Funcionalidades

- Exibição de receitas clássicas da culinária grega.
- Card interativo com nome, imagem, ingredientes e modo de preparo.
- Layout responsivo e design inspirado em elementos visuais mediterrâneos.
- Alternância de receitas ao clicar ou navegar.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura do projeto.
- **CSS3**: Estilização e responsividade.
- **JavaScript**: Interatividade do card.
- *(Opcional)* **React.js** ou **Vue.js**: Para uma versão mais dinâmica e componentizada.
- *(Opcional)* **JSON**: Armazenamento das receitas.

---

## 📁 Estrutura de Diretórios

```bash
greek-recipe-card/
├── index.html
├── style.css
├── script.js
├── assets/
│   ├── images/
│   │   ├── moussaka.jpg
│   │   ├── gyros.jpg
│   │   └── ...
│   └── fonts/
├── data/
│   └── recipes.json   # (opcional)
├── README.md
📦 Instalação e Uso
1. Clone o repositório
bash
Copiar código
git clone https://github.com/seu-usuario/greek-recipe-card.git
cd greek-recipe-card
2. Abra o arquivo index.html no navegador
Você pode abrir diretamente o arquivo no seu navegador preferido:

bash
Copiar código
open index.html
Ou no Windows:

bash
Copiar código
start index.html
🔄 Alternativas de Execução (Local com Live Server)
Para uma melhor experiência de desenvolvimento, use o Live Server do VS Code:

Instale a extensão Live Server no VS Code.

Clique com o botão direito em index.html → Open with Live Server.

🧪 Testes
Caso o projeto utilize JavaScript avançado ou frameworks, os testes podem ser incluídos com:

Jest (para JavaScript)

Vitest (para Vue)

React Testing Library (para React)

🚀 Deploy
Você pode hospedar o projeto usando:

GitHub Pages

Vercel

Netlify

Exemplo com GitHub Pages
Faça push do projeto para o GitHub.

Vá em Settings → Pages

Selecione a branch main e o diretório /root.

Acesse o link gerado.

🧑‍🍳 Exemplo de Receita (Estrutura JSON)
json
Copiar código
{
  "nome": "Moussaka",
  "imagem": "assets/images/moussaka.jpg",
  "ingredientes": [
    "500g de carne moída",
    "2 berinjelas grandes",
    "Molho branco",
    "Queijo parmesão",
    "Sal e pimenta a gosto"
  ],
  "modo_de_preparo": [
    "Corte as berinjelas em fatias e grelhe levemente.",
    "Refogue a carne com temperos.",
    "Monte camadas de berinjela, carne e molho branco.",
    "Finalize com queijo e leve ao forno por 30 minutos."
  ]
}
