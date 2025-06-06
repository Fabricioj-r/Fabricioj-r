from pathlib import Path

readme_content = """
<h1 align="center">Olá! Eu sou o Fabrício Júnior 👨‍💻</h1>
<p align="center">
  <i>Desenvolvedor de software apaixonado por transformar ideias em produtos digitais úteis.</i><br>
  <b>Especializado em soluções web, automações inteligentes e interfaces modernas.</b>
</p>

---

### 🚀 Sobre mim

- 🎓 Estudante e profissional da área de tecnologia e desenvolvimento de sistemas
- 🧠 Apaixonado por resolver problemas reais com código
- 🧩 Criador do app <b><a href="https://github.com/Fabricioj-r/juntai-vida-em-harmonia">Juntaí</a></b> — um app de finanças e tarefas colaborativas
- 🛠️ Foco em <code>React</code>, <code>TypeScript</code>, <code>Python</code> e <code>Firebase</code>

---

### 🧰 Tecnologias e Ferramentas
<p>
  <img src="https://img.shields.io/badge/-React-20232A?style=flat&logo=react" />
  <img src="https://img.shields.io/badge/-TypeScript-3178C6?style=flat&logo=typescript" />
  <img src="https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python" />
  <img src="https://img.shields.io/badge/-Firebase-FFCA28?style=flat&logo=firebase" />
  <img src="https://img.shields.io/badge/-GitHub-181717?style=flat&logo=github" />
  <img src="https://img.shields.io/badge/-Vite-646CFF?style=flat&logo=vite" />
</p>

---

### 📌 Repositórios em destaque

<table>
<tr>
<td width="50%">
  <h4><a href="https://github.com/Fabricioj-r/juntai-vida-em-harmonia">📱 Juntaí - Vida em Harmonia</a></h4>
  <p>App para controle financeiro e tarefas compartilhadas (React + Firebase + Vite)</p>
</td>
</tr>
<tr>
<td width="50%">
  <h4><a href="https://github.com/Fabricioj-r/NCM">📊 NCM</a></h4>
  <p>Automação de consultas fiscais usando Python e API</p>
</td>
</tr>
<tr>
<td width="50%">
  <h4><a href="https://github.com/Fabricioj-r/BankEase---Sistema-bancario">🏦 BankEase</a></h4>
  <p>Sistema bancário educacional com HTML/CSS</p>
</td>
</tr>
</table>

---

### 📬 Contato

- [LinkedIn](https://www.linkedin.com/in/fabriciojunior)
- 📧 Email: fabriciojunior383@gmail.com

---

<p align="center">✨ Sempre em busca de evolução e inovação através da tecnologia.</p>
"""

readme_path = Path("/mnt/data/README.md")
readme_path.write_text(readme_content.strip(), encoding="utf-8")
readme_path.name
