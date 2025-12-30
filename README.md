# SEDU – Sistema Educacional Digital Unificado

Repositório: [https://github.com/Ballaur/Projeto-SEDU](https://github.com/Ballaur/Projeto-SEDU)

Projeto web desenvolvido com foco em **aplicação prática**, **organização de código** e **empregabilidade**, simulando um sistema educacional funcional.

O SEDU foi pensado para representar, em escala reduzida, um sistema digital para gestão educacional, utilizando **HTML, CSS e Python**, com integração a banco de dados SQL e layout responsivo para desktop, tablets e celulares.

---

## 🎯 Objetivo do Projeto

- Aplicar conhecimentos de desenvolvimento web em um projeto integrado  
- Estruturar código de forma organizada e profissional  
- Integrar backend com banco de dados SQL  
- Criar layout responsivo  
- Demonstrar habilidades práticas para portfólio e vagas de desenvolvimento  

---

## ⚙️ Funcionalidades

- Estrutura funcional de um sistema educacional web  
- Integração com banco de dados SQL (`escola.sql`)  
- Layout responsivo adaptável a diferentes tamanhos de tela  
- Separação clara entre frontend (`static/` e `templates/`) e backend (`app.py`)  

---

## 🛠️ Tecnologias Utilizadas

- **Frontend:** HTML, CSS  
- **Backend:** Python  
- **Banco de dados:** SQL  
- **Versionamento:** Git / GitHub  

---

## 📂 Estrutura do Projeto

```text
projeto-sedu/
├── static/        # Arquivos estáticos (CSS, imagens)
├── templates/     # Templates HTML
├── app.py         # Backend principal
├── escola.sql     # Script do banco de dados SQL
├── requirements.txt  # Dependências Python
├── .venv/         # Ambiente virtual (não subir no GitHub)
├── __pycache__/   # Cache Python (não subir no GitHub)
└── README.md


## ▶️ Como executar o projeto

```bash
# clone o repositório
git clone https://github.com/Ballaur/Projeto-SEDU.git

# acesse a pasta do projeto
cd Projeto-SEDU

# crie e ative o ambiente virtual
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
.venv\Scripts\activate     # Windows

# instale as dependências
pip install -r requirements.txt

# execute a aplicação
python app.py

> Certifique-se de criar o banco de dados utilizando o arquivo `escola.sql` antes de rodar o projeto.
