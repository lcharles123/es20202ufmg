# gerenciadorIOT
Sistema para gerenciamento de dispositivos IoT (internet das coisas)

# Equipe:
Gustavo Santos, Lecio Charlles, Marcos Vinícius, Wender Carvalho

# Escopo
- Funcional: 
    O sistema consiste de um site e um backend para receber e enviar requisicoes de/para dispositivos usando protocolos de rede estruturados ou nao, tais requisicoes serao armazenadas para posteriormente serem analizadas e respondidas. O sistema funcionara como um servico em um servidor na web ou pode ser instalado em uma maquina local, para uso em lugares de conectividade ruim.

- Tecnologico: 
    Frontend e Backend: alguma framework e bibliotecas em Python, i.e Django, flask podendo conter elementos em JavaScript;
    Banco de dados: SQlite;
    Outros: github para o gerenciamento e whatsapp para comunicacao.

# Quadro de tarefas:

https://github.com/lcharles123/es20202ufmg/projects/1

# Instalacao:

```
git clone https://github.com/lcharles123/gerenciadorIOT.git gerenciadorIOT
cd gerenciadorIOT
pip install -r requeriments.txt
cd src
python manage.py runserver


