# Guilherme Avelino

Repositório da página pessoal acadêmica de **Guilherme Avelino**, professor do Departamento de Computação da **Universidade Federal do Piauí (UFPI)**.

O site reúne, de forma simples e objetiva:

- apresentação profissional e trajetória acadêmica;
- linhas de pesquisa em Engenharia de Software e Inteligência Artificial;
- publicações, projetos e notícias;
- atividades de ensino e oportunidades de colaboração.

Site publicado em: [gavelino.github.io](https://gavelino.github.io)

## Tecnologias

Este projeto é construído com:

- [Jekyll](https://jekyllrb.com/);
- tema [al-folio](https://github.com/alshedivat/al-folio);
- [Docker](https://www.docker.com/) para desenvolvimento local.

## Estrutura do conteúdo

Os principais diretórios do repositório são:

- `_pages/`: páginas institucionais e de apresentação;
- `_news/`: notícias e atualizações;
- `_projects/`: projetos acadêmicos e de pesquisa;
- `_teachings/`: disciplinas e atividades de ensino;
- `_bibliography/`: referências e publicações;
- `assets/`: imagens, arquivos e recursos estáticos.

## Execução local

Para visualizar o site localmente com Docker:

```bash
docker compose pull
docker compose up
```

Depois, acesse `http://localhost:8080`.

## Personalização

As configurações principais do site ficam em `_config.yml`. O conteúdo pode ser atualizado diretamente nas coleções e páginas do repositório, especialmente em `_pages/`, `_news/`, `_projects/`, `_teachings/` e `_bibliography/`.
