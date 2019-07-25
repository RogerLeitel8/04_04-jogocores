# Jogo das Cores

## Linguagens utilizadas
- HTML
- CSS
- JAVASCRIPT
---
### Ferramentas das linguagens
- Utilizamos em `CSS` display flex e propiedades simples de edição
- Em `JavaScript`, utilizamos `FOR`, `MATH` e `FUNCTION`.
---
**Ex: Resetar Jogo**
~~~
function resetarJogo(){
    for(let quadrado of quadradinhos){
        quadrado.style.backgroundColor = "unset";
    }
    resposta.innerHTML = "Jogo resetado !";
}
botao.ondblclick = resetarJogo;
~~~

