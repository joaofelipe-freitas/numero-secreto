# 🔢 Jogo do Número Secreto

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/licen%C3%A7a-MIT-green?style=for-the-badge" alt="Licença MIT" />
</p>

<p align="center">
  Um jogo interativo de adivinhação de número secreto com múltiplos modos de dificuldade, feedback por voz, efeitos sonoros e muito mais!
</p>

---

## 🎮 Demonstração

> Abra o arquivo `index.html` diretamente no seu navegador para jogar.

---

## 📖 Sobre

O **Jogo do Número Secreto** é um projeto desenvolvido com HTML, CSS e JavaScript puro. O jogador deve descobrir um número secreto sorteado aleatoriamente dentro de um intervalo definido pela dificuldade escolhida. A cada tentativa, o jogo fornece dicas para guiar o jogador até a resposta correta.

---

## ✨ Funcionalidades

- 🎯 **4 níveis de dificuldade:** Fácil (1–10), Médio (1–50), Difícil (1–100) e Insano (1–1000)
- 🗣️ **Feedback por voz** em Português Brasileiro (via ResponsiveVoice)
- 🔊 **Efeitos sonoros** gerados pela Web Audio API
- ⏱️ **Cronômetro** com registro de tempo por partida
- 🏆 **Sistema de recordes** salvo localmente por dificuldade e modo
- 🏃 **Modo Speedrun:** cronômetro inicia junto com o jogo
- 🌡️ **Indicador quente/frio:** diz se você está perto ou longe do número
- 📊 **Barra de progresso** de proximidade
- 📋 **Histórico de tentativas** com dicas em tempo real
- 🎊 **Animação de confete** ao acertar
- 🌙 / ☀️ **Alternância entre tema escuro e claro**
- ⌨️ **Atalhos de teclado:** `Enter` para chutar, `Ctrl+R` para reiniciar
- 📱 **Layout responsivo** para dispositivos móveis

---

## 🕹️ Como Jogar

1. Escolha a **dificuldade** no seletor (padrão: Fácil)
2. Digite um número no campo de entrada
3. Clique em **Chutar** (ou pressione `Enter`)
4. Siga as dicas:
   - *"O número secreto é maior"* → tente um número maior
   - *"O número secreto é menor"* → tente um número menor
   - 🔥 **Quente** → muito perto! | 🟠 **Morno** → chegando lá | 🧊 **Frio** → longe ainda
5. Acertou? Veja seu tempo, tente bater o recorde e clique em **Novo jogo**!

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso |
|---|---|
| **HTML5** | Estrutura e semântica da página |
| **CSS3** | Estilização, animações e responsividade |
| **JavaScript (ES6+)** | Lógica do jogo, Web Audio API, LocalStorage |
| **ResponsiveVoice** | Síntese de voz em Português |
| **Google Fonts** | Tipografia (Chakra Petch + Inter) |

---

## 🚀 Como Executar Localmente

Não é necessário instalar nada! Basta:

```bash
# Clone o repositório
git clone https://github.com/joaofelipe-freitas/numero-secreto.git

# Entre na pasta
cd numero-secreto

# Abra o arquivo index.html no seu navegador preferido
```

> **Dica:** Para que o feedback por voz funcione corretamente, abra o projeto com um servidor local (ex: extensão **Live Server** do VS Code).

---

## 📁 Estrutura do Projeto

```
numero-secreto/
├── index.html      # Estrutura da página
├── style.css       # Estilos e animações
├── app.js          # Lógica do jogo
└── img/            # Imagens e recursos visuais
```

---

## 📄 Licença

Este projeto está licenciado sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

<p align="center">Feito com ❤️ por <a href="https://github.com/joaofelipe-freitas">João Felipe Freitas</a></p>
