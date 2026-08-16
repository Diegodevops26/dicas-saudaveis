cd ~/healthy_hints
cat << 'EOF' > README.md
# Healthy Hints Agent 🤖🌦️

Agente inteligente desenvolvido com o **Google Agent Development Kit (ADK)** e **Gemini API** para fornecer informações sobre clima e fuso horário.

---

## 🚀 Funcionalidades

- **Consulta de Clima:** Obtém o clima atual para cidades suportadas.
- **Consulta de Horário:** Retorna o horário local com precisão de fuso horário.
- **Integração LLM:** Orquestração dinâmica de ferramentas (*tool calling*) utilizando modelos Gemini.

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.12**
- **Google ADK (Agent Development Kit)**
- **Google GenAI SDK (Gemini 1.5 Flash)**

---

## ⚙️ Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/Diegodevops26/dicas-saudaveis.git](https://github.com/Diegodevops26/dicas-saudaveis.git)
   cd dicas-saudaveis


   python3 -m venv .venv

