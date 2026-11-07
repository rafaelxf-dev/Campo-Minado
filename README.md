# 💣 Campo Minado (Minesweeper GUI) em Python

Implementação completa do clássico jogo de lógica **Campo Minado**, desenvolvida em Python com suporte a múltiplos idiomas (Português/English), diferentes níveis de dificuldade, painel de controle flutuante e recursos visuais personalizados com Tkinter.

---

## 📌 Funcionalidades e Recursos

- **Suporte Multilíngue:** Configuração inicial de idioma integrada via diálogos interativos (`pyautogui`).
- **Níveis de Dificuldade Dinâmicos:**
  - *Fácil:* Tabuleiro 9x9 com 10 bombas.
  - *Médio:* Tabuleiro 16x16 com 40 bombas.
  - *Difícil:* Tabuleiro 16x30 com 99 bombas.
- **Janela de Controle Secundária (`Info e botões`):** Painel flutuante com contagem regressiva/atualizada de bandeiras/bombas, botão de reinício rápido, ativação de bandeiras (*Flag ON/OFF*) e opção de resetar marcações.
- **Lógica de Jogo Robusta:** 
  - Geração dinâmica de bombas no primeiro clique (evitando morte imediata).
  - Revelação em cadeia de áreas vazias (zeros).
  - Tratamento de cliques em células numeradas e verificação automática de vitória ou derrota.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Python 3
- **Interface Gráfica (GUI):** [Tkinter](https://docs.python.org/3/library/tkinter.html)
- **Automação & Diálogos:** [PyAutoGUI](https://pyautogui.readthedocs.io/)

---

## 📂 Estrutura de Pastas

O projeto organiza seus assets visuais e scripts da seguinte forma:
```text
campo_minado/
│
├── imagens/
│   ├── N1.png até N8.png
│   ├── bandeira.png
│   ├── bomba.png
│   ├── bombaErrada.png
│   ├── bombaPerda.png
│   ├── botaoNada.png
│   └── icone campo minado.png
│
└── campo_minado_tkinter.py
```

## 🚀 Como Executar o Projeto
Pré-requisitos
Certifique-se de ter o Python 3 e a biblioteca pyautogui instalados no seu computador.

### 1. Clonar o repositório
```
git clone [https://github.com/rafaelxf-dev/Campo-Minado.git](https://github.com/rafaelxf-dev/Campo-Minado.git)
cd campo-minado
```

### 2. Instalar as dependências necessárias
```
pip install pyautogui
```

### 3. Executar a aplicação
Certifique-se de que a pasta imagens/ está no mesmo diretório do script principal e execute:

```
python campo_minado_tkinter.py
```
