# Sorteio de Amigo Secreto Alura / ONE
Atráves de um desafio proposto pela alura, de criar com os conceitos aprendidos um sorteio de amigo secreto.

## :hammer: Funcionalidades

- Sorteio de amigo secreto.
- Função para garantir que o sorteio vai ser realizado se tiver mais de dois nomes.
- Função otimizada de embaralhamento da lista de pessoas.
- Função de limpar o input assim que for escrito o nome.
- Botão de reiniciar o jogo, limpando os nomes.

##  Linguagens utilizadas
Javascript, HTML, CSS...


#### Função de voz

```javascript
 if ('speechSynthesis' in window) {
        let utterance = new SpeechSynthesisUtterance(`O amigo sorteado é ${amigoSorteado}`);
        utterance.lang = 'pt-BR'; 
        utterance.rate = 1.2; 
        window.speechSynthesis.speak(utterance); 
    } else {
        console.log("Web Speech API não suportada neste navegador.");
    }
```
