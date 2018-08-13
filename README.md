## Aula 06 - Reponsive

Ajustando para responsivo


```css

@media(max-width: 768px) {

  .cabecalhoPrincipal .container{
    direction:column;
    align-items: initial;
    text-align: center;
  }

  .cabecalhoPrincipal .container{
      flex-direction:column;
  }

  .conteudoPrincipal-cursos-link {
      width:100%;
  }

  .conteudoPrincipal-cursos {
      flex-direction: column;
  }

  .rodapePrincipal-navMap-list {
      height: auto;
  }

  .rodapePrincipal-patrocinadores-container {
      flex-direction: column;
      align-items: center;
  }
  .rodapePrincipal-patrocinadores .container{
    flex-direction: column;
  }
  .rodapePrincipal-contatoForm {
      width: 100%;
  }

  .rodapePrincipal-patrocinadores-list {
      margin: 0;
      width: 100%;
  }

  .rodapePrincipal-contatoForm-fieldset {
      justify-content:center
  }

  .cabecalhoPrincipal-nav {
    flex-direction: column;
  }

```
