# PJAM — MovieManager 🎬

Aplicação móvel de gestão pessoal de filmes, desenvolvida em Flutter.

**Autor:** Nuno Ricardo Matos da Silva (2022113056)
**Unidade curricular:** Projeto de Aplicações Móveis (PJAM)
**Curso:** Mestrado em Engenharia Informática — Universidade Fernando Pessoa
**Ano letivo:** 2026/2027

## Tema

Aplicação ao estilo IMDb/MyAnimeList, onde o utilizador pode pesquisar
filmes, consultar os seus detalhes e organizá-los em listas pessoais
("Vistos" e "Planeio ver"), com nota pessoal e estatísticas de perfil.
Os dados dos filmes são obtidos a partir da API pública do TMDB
(The Movie Database). Conforme o enunciado, o foco do projeto é o front-end.

## Funcionalidades (planeadas)

- Home com filmes em destaque, populares e novidades
- Pesquisa por título e navegação por género
- Detalhe do filme (sinopse, elenco, nota, semelhantes)
- Listas pessoais: "Vistos" e "Planeio ver"
- Perfil com estatísticas (nº de filmes vistos, nota média)
- Tema claro/escuro
- Persistência local no dispositivo

## Stack

- Flutter (front-end)
- API: TMDB (The Movie Database)
- Persistência local: sqflite / Hive (a definir)

## Como executar

```
flutter pub get
flutter run
```
