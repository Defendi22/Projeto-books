# 📚 AluraBooks

Um site moderno e responsivo de livraria online para a plataforma Alura, desenvolvido com HTML, CSS e JavaScript.

## 🎯 Sobre o Projeto

AluraBooks é uma plataforma de e-commerce de livros focada em títulos de desenvolvimento, infraestrutura, design e negócios. O site oferece uma experiência intuitiva com carrosséis de produtos, categorias de livros e um espaço para descobrir autores em destaque.

## ✨ Funcionalidades

- **Navegação intuitiva** com menu hamburguer responsivo
- **Carrosséis de produtos** com Swiper.js para "Últimos lançamentos" e "Mais vendidos"
- **Categorias de livros** (Programação, Front-end, Infraestrutura, Business, Designer e UX)
- **Busca de livros** com campo de pesquisa
- **Cards destacados** com recomendações personalizadas
- **Seção de tópicos visitados** para fácil acesso
- **Newsletter** para inscrição de usuários
- **Responsivo** para dispositivos móveis, tablets e desktops
- **Menu de usuário** com Favoritos, Estante pessoal e Perfil

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização e design responsivo
- **JavaScript** - Interatividade
- **Swiper.js** - Carrosséis de produtos
- **Google Fonts** - Tipografias (Inter, Josefin Sans, Poppins)

## 📁 Estrutura do Projeto

```
alura-books/
├── index.html          # Página principal
├── style.css           # Estilos gerais
├── reset.css           # Reset CSS padrão
├── assets/             # Imagens e ícones
│   ├── Logo.svg
│   ├── ApacheKafka.svg
│   ├── Angular.png
│   └── ...
└── Assets Footer/      # Imagens do rodapé
    ├── CasaDoCodigo.svg
    ├── Alura.svg
    └── ...
```

## 🚀 Como Usar

1. **Clone o repositório**
   ```bash
   git clone https://github.com/seu-usuario/alura-books.git
   ```

2. **Navegue até o diretório do projeto**
   ```bash
   cd alura-books
   ```

3. **Abra o arquivo `index.html` no navegador**
   - Clique duas vezes em `index.html`, ou
   - Use uma extensão como Live Server (VS Code)

4. **Certifique-se de que os arquivos de assets estão no lugar correto**
   - A pasta `assets/` deve estar no mesmo nível que `index.html`
   - A pasta `Assets Footer/` deve estar no mesmo nível que `index.html`

## 📱 Responsividade

O site é totalmente responsivo e funciona perfeitamente em:
- 📱 Dispositivos móveis (320px+)
- 📱 Tablets (768px+)
- 💻 Desktops (1024px+)

## 🎨 Seções Principais

### Header
Menu de navegação com logo, categorias e opções de usuário (Favoritos, Estante, Perfil).

### Banner
Seção chamativa com título, descrição e campo de pesquisa.

### Carrosséis
Dois carrosséis principais:
- Últimos lançamentos
- Mais vendidos

### Cards de Destaque
Recomendações personalizadas e autor do mês com botões de ação.

### Tópicos Visitados
Links rápidos para categorias frequentemente acessadas.

### Newsletter
Área de inscrição para atualizações de e-books e promoções.

### Rodapé
Links para outras plataformas Alura (Casa do Código, Caelum, Music Dot, etc).

## 🔧 Customizações

### Mudar cores
Edite o arquivo `style.css` para alterar as cores principais do site.

### Adicionar novos livros
Adicione novas imagens na pasta `assets/` e atualize os `<div class="swiper-slide">` nos carrosséis.

### Modificar categorias
Atualize a lista de categorias no menu e na seção de tópicos no `index.html`.

## 📝 Notas de Desenvolvimento

- As imagens dos livros devem estar em formato SVG para melhor qualidade
- O Swiper.js é carregado via CDN
- As fontes são importadas do Google Fonts
- O site utiliza uma estrutura BEM (Block Element Modifier) para nomenclatura CSS

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:
1. Fazer um fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona MinhaFeature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abrir um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 👨‍💻 Autor

**Fernando Defendi**

## 📧 Contato

Para dúvidas ou sugestões sobre o projeto, abra uma issue no repositório.

## 🙏 Agradecimentos

- Alura pela inspiração e conteúdo de qualidade
- Swiper.js pela biblioteca de carrosséis
- Google Fonts pelas tipografias utilizadas

---

⭐ Se este projeto foi útil para você, considere deixar uma estrela!
