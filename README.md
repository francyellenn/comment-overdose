<div align="center">

  <!-- Header Banner -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7e57c2,100:9575cd&height=180&section=header&text=academic-overkill%20📜🎓&fontSize=38&animation=fadeIn" width="100%"/>

  <p><i>"Se o professor pedir para explicar o código, eu já escrevi um livro dentro dos comentários."</i></p>

  <!-- Badges do Projeto -->
  <img src="https://img.shields.io/badge/Comentários-200%25-brightgreen?style=for-the-badge&logo=read-the-docs" />
  <img src="https://img.shields.io/badge/Nota_do_Professor-10%2F10-purple?style=for-the-badge&logo=academia" />
  <img src="https://img.shields.io/badge/Linhas_de_Código-50%25_Texto-blue?style=for-the-badge" />

</div>

<br>

## 📌 Sobre o Projeto

O **`academic-overkill`** é um projeto completo desenvolvido como trabalho de curso. É um site funcional, responsivo e cheio de detalhes visuais, mas o verdadeiro astro aqui é o **código-fonte**.

Levei a instrução *"comentem o código"* **RIDICULAMENTE a sério**. Cada tag HTML, cada regra de CSS e cada função JavaScript tem uma explicação tão detalhada que até a minha avó conseguiria entender o que a função `addEventListener()` está fazendo.

---

## 🔬 Amostra do Nível de Detalhamento

Para você ter uma ideia do que te espera dentro dos arquivos:

```javascript
// ========================================================
// FUNÇÃO: Mudar a cor do botão ao passar o mouse
// MOTIVO: Ficou bonito e o professor pediu interatividade
// ========================================================
function hoverEffect() {
  // Aqui pegamos a div no HTML pelo ID 'btn-submit' (que é o botão roxo)
  const button = document.getElementById('btn-submit'); 
  
  // Adicionamos um ouvinte de eventos. Ele fica "esperando" o mouse passar
  button.addEventListener('mouseover', () => {
    // Se o mouse passou, muda a cor para roxo pastel. Não mude esse hex sem me avisar.
    button.style.backgroundColor = '#9575cd'; 
  });
}
```
🚀 Como Visualizar

Não precisa de npm install, não precisa de servidor, não precisa de Docker. É a boa e velha web raiz!

    Clone o repositório:

    Bash 

    $ git clone https://github.com/francyellenn/academic-overkill.git

    Dê um duplo clique no arquivo index.html e seja feliz!
    Abra o arquivo no VS Code e leia o livro de comentários! 📖

🎓 Objetivo Acadêmico

    Entregar o trabalho no prazo.
    Garantir que o professor não tenha NENHUMA dúvida sobre o que eu fiz.
    Não chorar tentando alinhar os elementos na tela.
    Tirar nota máxima.

<div align="center"> <sub>Documentado até o último ponto e vírgula por <a href="https://github.com/francyellenn">Francyellen P.</a> 💜</sub> </div> ```
