### Hi there 👋

<!--
**FelpsMinozzo/FelpsMinozzo** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<style>
@keyframes typing {
  from { width: 0 }
  to { width: 100% }
}

@keyframes blink-caret {
  from, to { border-color: transparent }
  50% { border-color: orange; }
}

#paragraph1 {
  width: 100%;
  overflow: hidden;
  white-space: nowrap;
  animation: typing 2s steps(30, end), blink-caret 0.5s step-end infinite;
}

#paragraph2 {
  opacity: 0;
  animation: fadeIn 1s 2s forwards;
}

@keyframes fadeIn {
  0% { opacity: 0; }
  100% { opacity: 1; }
}
</style>
<p>
  <span id="paragraph1">Opa, tudo bom?</span>
  <span id="paragraph2">Me chamo Eduardo Felipe!</span>
</p>

<script>
  const paragraph2 = document.getElementById('paragraph2');
  paragraph2.style.animationDelay = (2 * 1000) + "ms";
</script>


<h2>Linguagens que estou estudando:</h2>
<ul>
    <li><a href="https://nextjs.org/">NextJS</a></li>
    <li><a href="https://reactjs.org/">ReactJS</a></li>
    <li><a href="https://www.python.org/">Python</a></li>
    <li><a href="https://www.java.com/">Java</a></li>
</ul>

<h2>Idiomas:</h2>
<ul>
    <li>Português</li>
    <li>Inglês</li>
</ul>

<h2>Sobre mim:</h2>
<p>Sou estudante de Técnico em Desenvolvimento de Sistema, atualmente no 3º e último Módulo do curso. Estou
    focado em aprimorar minhas habilidades de programação e desenvolvimento de software nas linguagens mencionadas
    acima. No momento, estou particularmente interessado em trabalhar com o framework NextJS e a biblioteca ReactJS
    para a criação de aplicações web modernas e dinâmicas. Também estou aprofundando meus conhecimentos em Python
    e Java, duas linguagens versáteis e amplamente utilizadas na indústria de desenvolvimento de software.</p>
    
