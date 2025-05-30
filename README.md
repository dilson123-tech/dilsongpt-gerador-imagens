# 🎨 Dilsongpt Gerador de Imagens com IA

Um projeto full stack de geração de imagens usando Inteligência Artificial via API da OpenAI. Desenvolvido como parte do plano de estudos intensivo do criador **Dilson**, focado em aplicações reais com IA, backend e frontend.

## 🚀 Funcionalidades

- Geração de imagens realistas a partir de prompts de texto
- Backend com FastAPI
- Integração com a API da OpenAI (DALL·E)
- Frontend simples em HTML/CSS/JavaScript para testes manuais
- Projeto modularizado para evolução futura (ex: autenticação, histórico, estilos de arte)

## 🧠 Tecnologias

- Python 3.10+
- FastAPI
- Uvicorn
- OpenAI SDK
- HTML5 / CSS3 / JS (vanilla)
- Git + GitHub

## 📁 Estrutura do Projeto

dilsongpt-gerador-imagens/
├── backend/
│ ├── main.py # API FastAPI com rota /gerar-imagem
│ ├── gerar.py # Função de geração de imagem
│ └── .env # (opcional) chave da OpenAI
├── frontend/
│ ├── index.html # Página web para testes
│ ├── style.css
│ └── script.js
├── requirements.txt
└── README.md


## ⚙️ Como rodar localmente

### 1. Clone o repositório

```bash
git clone https://github.com/dilson123-tech/dilsongpt-gerador-imagens.git
cd dilsongpt-gerador-imagens/backend

python -m venv venv
source venv/bin/activate  # No Windows use: venv\Scripts\activate
pip install -r requirements.txt

uvicorn main:app --reload

"Um robô professor explicando programação em uma sala futurista"


---

⚡ Agora é só:

1. Copiar esse conteúdo
2. Criar o arquivo na raiz do projeto:

```bash
cd ~/projetos/dilsongpt-gerador-imagens
touch README.md
nano README.md

