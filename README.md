from pathlib import Path

clean_readme = """
<h1 align="center">Olá! Eu sou o Fabrício Júnior 👨‍💻</h1>
<p align="center">
  Desenvolvedor de software apaixonado por transformar ideias em produtos digitais úteis.<br>
  <b>Especializado em soluções web, automações inteligentes e interfaces modernas.</b>
</p>

---

## 🚀 Sobre mim

- 🎓 Estudante e profissional da área de tecnologia e desenvolvimento de sistemas
- 💡 Apaixonado por resolver problemas reais com código
- 📱 Criador do app <a href="https://github.com/Fabricioj-r/juntai-vida-em-harmonia"><b>Juntaí</b></a> — finanças e tarefas colaborativas
- 🛠️ Foco em <code>React</code>, <code>TypeScript</code>, <code>Python</code>, <code>Firebase</code> e <code>Vite</code>

---

## 🧰 Tecnologias & Ferramentas

<p align="left">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github" />
</p>

---

## 📌 Projetos em destaque

### 📱 [Juntaí - Vida em Harmonia](https://github.com/Fabricioj-r/juntai-vida-em-harmonia)
> App para controle financeiro e tarefas compartilhadas — construído com React, Firebase e Vite

### 📊 [NCM](https://github.com/Fabricioj-r/NCM)
> Automação de consultas fiscais com Python + API

### 🏦 [BankEase](https://github.com/Fabricioj-r/BankEase---Sistema-bancario)
> Sistema bancário educacional com HTML/CSS

---

## 📬 Contato

- [LinkedIn](https://www.linkedin.com/in/fabriciojunior)
- 📧 fabriciojunior383@gmail.com

---

<p align="center"><i>✨ Sempre em busca de evolução e inovação através da tecnologia.</i></p>
"""

path = Path("/mnt/data/README_PROFISSIONAL.md")
path.write_text(clean_readme.strip(), encoding="utf-8")
path.name
