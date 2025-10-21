# Controle de Estoque de Comidas Nordestinas

Este é um sistema desenvolvido em Python utilizando a biblioteca Tkinter para interface gráfica. O sistema tem como objetivo a gestão de entradas, saídas e cadastro de comidas típicas da região nordestina do Brasil.

## Funcionalidades

- Login de usuários: permite que diferentes usuários acessem o sistema com autenticação.
- Cadastro, consulta, edição e exclusão de comidas típicas da culinária nordestina.
- Registro e histórico detalhado das movimentações no estoque (entradas e saídas).
- Alertas visuais para avisar quando o estoque de um alimento está abaixo do nível mínimo definido.

## Execução

1. Execute o arquivo `db_init.sql` para criar o banco de dados com suas tabelas e dados iniciais, ou deixe o sistema criar automaticamente no primeiro uso.
2. Execute o arquivo `main.py` para iniciar o sistema e acessar a interface gráfica.

## Estrutura de arquivos

- `main.py` : Arquivo principal que inicializa o sistema e gerencia as telas principais.
- `db.py` : Responsável pela conexão e inicialização do banco de dados SQLite.
- `login.py` : Tela e lógica de autenticação dos usuários.
- `comidas.py` : Cadastro, edição, exclusão e exibição das comidas típicas.
- `estoque.py` : Gestão das quantidades no estoque e registro das movimentações.
- `utils.py` : Funções auxiliares diversas, como centralização de janelas e ordenação.
- `db_init.sql` : Script SQL para criação do banco de dados com tabelas e dados iniciais.
- `README.md` : Este arquivo, com orientações e informações gerais sobre o sistema.

**Requisitos:** Python 3.12 ou superior, Tkinter e SQLite.

## Tela de login 
<img width="554" height="407" alt="Captura de tela 2025-10-21 095644" src="https://github.com/user-attachments/assets/acf356fc-dc46-4413-a4a2-9ac63d7635f6" />

## Tela incial 
<img width="1623" height="718" alt="Captura de tela 2025-10-21 095735" src="https://github.com/user-attachments/assets/5e1f8731-e15a-4e29-a56b-0cf04a81094a" />

## Tela de Cadastro de comidas
<img width="1866" height="263" alt="Captura de tela 2025-10-21 095750" src="https://github.com/user-attachments/assets/c2797ac3-6322-4aa8-8cff-18973f00d9c3" />

## Tela adicionar novas comidas
<img width="737" height="602" alt="Captura de tela 2025-10-21 095816" src="https://github.com/user-attachments/assets/b9da0720-a82d-4994-bf82-836e7057ba7b" />

## Tela estoque 
<img width="1861" height="343" alt="Captura de tela 2025-10-21 095852" src="https://github.com/user-attachments/assets/f6cbdb04-6452-4d0c-b074-9220b76ace1e" />

