# Link-bio

Projeto de página Link-bio desenvolvido com HTML e CSS para centralizar links pessoais em uma interface simples e moderna.

---

# Sobre o Projeto

A aplicação reúne links importantes em um único lugar, funcionando como uma página de apresentação pessoal.

Os links disponíveis são:
- Portfólio
- Instagram
- GitHub
- Spotify

---

# Tecnologias Utilizadas

- HTML5
- CSS3

---

# Estrutura do Projeto

```txt
projeto/
│
├── index.html
├── style.css
│
├── img/
│   ├── fundo.png
│   ├── portfolio.webp
│   ├── instagram.png
│   ├── github.png
│   └── spotify.png
│
└── font/
    └── Story_Script/
        └── StoryScript-Regular.ttf
```

---

# Estrutura HTML

O arquivo `index.html` contém:

- Cabeçalho com nome do usuário
- Cards clicáveis
- Imagens para cada rede social
- Links externos

Exemplo de card:

```html
<a href="https://github.com/Rianoliveira-ofc">
    <div class="cards">
        <img src="img/github.png" alt="github" width="50px">
        <p>GitHub</p>
    </div>
</a>
```

---

# Estilização CSS

O arquivo `style.css` é responsável por:

- Background personalizado
- Fonte customizada
- Efeito hover nos cards
- Centralização dos elementos
- Animações suaves

Exemplo do efeito hover:

```css
.cards:hover {
    transform: scale(1.05) translateY(-15px);
    box-shadow: 0px 0px 10px 1px white;
}
```

---

# Funcionalidades

- Interface moderna
- Cards interativos
- Navegação rápida
- Fonte personalizada
- Background estilizado

---

# Melhorias Futuras

- Modo escuro e claro
- Foto de perfil
- Animações adicionais
- Integração com APIs

---

# Como Executar

Acesse o Link: "###"
---

# Autor

Desenvolvido por Rian Oliveira.