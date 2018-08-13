# Curso Flexbox: Posicione elementos na tela

## Aula 01 - Introdução ao flexbox e fazendo o cabeçalho

Na hora de definir o posicionamento dos elementos, devo olhar para o elemento pai e aplicar o flexbox nele. Por exemplo:

```css
.meu-elemento-pai {
	/*
		habilita o posicionamento flex
		os elementos filhos já ficam um do lado do outro
	*/
  display: flex;
  /*
  	align os filhos verticalmente no centro
	*/
  align-items: center;
  /*
  	automaticamente, distribui o espaço do vazio do pai entre os filhos
  	efeito: posiciona os filhos como se fosse com um float correto
  */
  justify-content: space-between;
}
```
