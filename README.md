<h1 align="center">Modelagem Banco de Dados - Gestão de Dados-UFPI
</h1>

<p align="center">
  <img alt="logo" title="" src="https://github.com/gama07/Modelagem-de-Dados--Trab-I-UFPI/blob/main/foto%20capa.jpg" width="500px"/>
</p>

---

# 
## 📝 Introdução

Este repositório apresenta o trabalho desenvolvido no primeiro período do curso de Gestão de Dados da Universidade Federal do Piauí (UFPI), na disciplina de Banco de Dados. O objetivo central deste projeto é realizar a modelagem de um banco de dados, aplicando os conceitos e técnicas aprendidos durante a disciplina.

---

## 📝Descrição

O trabalho proposto tem como foco a criação de um modelo de banco de dados para um sistema de recomendação de animes e músicas destinado a universitários. O projeto inclui um dicionário de dados e um modelo entidade-relacionamento (MER), ambos elaborados para personalizar as recomendações com base nas preferências e perfil de cada usuário.

---

## 💻 Funcionalidades

### Cadastro de Dados pelo Administrador

- O administrador é responsável por inserir informações sobre animes, músicas e perfis de alunos nas tabelas do sistema.

### Recomendações para o Aluno

- Ao acessar o aplicativo, o aluno recebe sugestões personalizadas de animes e músicas, que podem ou não estar relacionadas ao anime sugerido.

### Recomendação de Animes

- A seleção de animes considera os seguintes atributos do aluno:
  - Idade
  - Filtro_limit_temp (indica a necessidade de informar o limite de temporadas)
  - Área_curso
- O atributo Qtd_indicações também é considerado. Se especificado, o aluno recebe a quantidade definida de recomendações; caso contrário, recebe uma indicação padrão.

### Recomendação de Músicas

- A recomendação de músicas leva em conta os seguintes atributos do perfil do aluno:
  - Estilo_musical
  - Idade
- O processo de recomendação de músicas segue os passos de análise do perfil do aluno, consulta ao banco de dados, aplicação de filtros e regras, ordenação das recomendações e apresentação ao aluno.

---

## 📝 Considerações Finais e Melhorias Futuras

- **Generalização do Perfil**: Modificar a entidade "Aluno" para "Usuário" e adicionar um atributo "Perfil_usuario", permitindo perfis como "admin" e "aluno".
  
- **Interatividade do Usuário**: Implementar a opção de gerar recomendações apenas quando o aluno clicar no botão "Gerar Recomendação", alterando a cardinalidade entre as relações.

- **Personalização das Recomendações**: Oferecer ao aluno a opção de escolher entre receber recomendações apenas de músicas, apenas de animes ou de ambos. Segmentar o atributo Qtd_indicacoes em Qtd_indicacoes_anime e Qtd_indicacoes_musica para maior precisão.

- **Melhorias nas Recomendações**: Implementar filtros adicionais, como Nota_imdb, Qtd_episodios e termos da Sinopse, para refinar ainda mais as recomendações.

---

## 📜 Referências

- HOPPEN, Joni. PRATES, Wlademir. SANTOS, Marcos. *Aquarela: O que é um dicionário de dados de Data Analytics*, c2017. [Link](https://aquare.la/o-que-e-um-dicionario-de-dados-de-data-analytics/). Acesso em: 16 de junho de 2023.

- HOPPEN, Joni. *Aquarela: Natureza dos Dados e estruturação para Data Science*, c2017. [Link](https://aquare.la/natureza-dos-dados-e-estruturacao-para-data-science/). Acesso em: 16 de junho de 2023.

- CRUNCHYROLL. *Aplicativo de animes*. [Link](https://www.crunchyroll.com/pt-br/videos/popular). Acesso em: 16 de junho de 2023.

- BANCO DE DADOS. *Dicionário de dados*. [Link](https://consultabd.wordpress.com/2018/11/26/dicionario-de-dados/). Acesso em: 17 de junho de 2023.

---

## 👩🏽‍💻👩🏽‍💻Autoras 👩🏽‍💻👩🏽‍💻

- Bruna Lorena
- Kedma Freire
- Lorena Silva
- Mariana Borges
<br><br>
## 📜 Licenças

Este projeto está sob as licenças:

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)


