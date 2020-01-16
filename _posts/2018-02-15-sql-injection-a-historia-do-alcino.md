---
title: "SQL Injection: A historia do Alcino"
layout: post
image: /assets/images/sql-injection-olimpio.png
tag:
- security
star: true
category: blog
author: olimpio
description: Alcino é um jovem dos seus 21 anos e administrador de redes de computadores e aspirante a programador.
---
![SQL Injection: A historia do Alcino](/assets/images/sql-injection-olimpio.png)

Alcino é um jovem dos seus 21 anos e administrador de redes de computadores e aspirante a programador. Alcino trabalha numa instituição de ensino privada na cidade de Maputo onde tem a função de manter a rede e os computadores em funcionamento. OKEEY. Até ai Tudo Cool. Alcino teve a ideia de automatizar as tarefas internas da instituição usando os seus skills de web development desenvolvendo um Sistema de Gestão Escolar para a instituição.

O jovem não teve nenhuma formação profissional em Web Develpment nem mesmo participou em trainings da MOZDEVZ (risos).. Tudo self-studying. LOL… O sistema criado esta funcionando sem sobressaltos e até facilitou o trabalho da Dona Marta que tinha que entrar sala por sala a exigir que os professores entreguem a pauta a tempo e que os alunos submetam as (fotos tipo passe) na secretaria para validar as inscrições… O diretor até aumentou o salario do jovem…
Tudo correndo bem. O Alcino satisfeito, a instituição satisfeita, e todos satisfeito. Até que: entrou um novo estudante aspirante a hacker na instituição …. E

É manhã de segunda-feira ao chegar no job o Alcino recebe reclamações dos professores que não conseguiam ter acesso aos dados dos alunos e nem mesmo as respectivas pautas. Mas como? Tudo sumiu!!!! Sumiu!!! Mas como sumiu? Depois de inspecionar a database o Alcino descobriu que a tabela contendo todas as informações dos alunos sumiu… E pra piorar a situação o jovem não tem backup da database. Nem um pra contar historia. Alcino está ferrado.

É com base nessa estória que vou iniciar a serie SQL Injection onde partilharei pouco daquilo que vou aprendendo sobre esse ataque onde o invasor pode inserir ou manipular consultas criadas pela aplicação, que são enviadas diretamente para o banco de dados.
