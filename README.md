⚙️ Como Executar o Projeto
Siga os passos abaixo para configurar e executar o projeto localmente:

Pré-requisitos
Ter o Python instalado em sua máquina.

Passo a passo
Clone o repositório:

Bash
git clone [https://github.com/danilobrunorj/M3_Restaurante_sabor_divino.git](https://github.com/danilobrunorj/M3_Restaurante_sabor_divino.git)
cd M3_Restaurante_sabor_divino
Ative o ambiente virtual (.venv):

No Windows:

Bash
.venv\Scripts\activate
No macOS/Linux:

Bash
source .venv/bin/activate
Instale as dependências:

Bash
pip install -r requirements.txt
Execute as migrações do banco de dados:

Bash
python manage.py migrate
Inicie o servidor de desenvolvimento:

Bash
python manage.py runserver
Acesse no navegador:
Abra o navegador de sua preferência e acesse: http://127.0.0.1:8000/

👨‍💻 Autor
Desenvolvido por Danilo Bruno.
"""

with open("README_restaurante.txt", "w", encoding="utf-8") as f:
f.write(readme_content)


Olhando a imagem do repositório (**M3_Restaurante_sabor_divino**), este projeto também utiliza o **Django**, além de possuir pastas organizadas para arquivos estáticos (`static/images`), templates (`templates`) e controle de dependências (`requirements.txt`).


