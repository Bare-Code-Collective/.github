🚀 Baré Code Collective - Manual de Engenharia
"Do coração da Amazônia, construindo código de padrão global."

Bem-vindos ao nosso laboratório! Este documento serve para alinhar como trabalhamos, o que valorizamos e como garantimos que nossos projetos (iFood, Netflix, Serasa) sejam vistos como engenharia de verdade, e não apenas "clones de curso".

🎯 Nossa Missão
Não somos apenas um grupo de estudos. Somos um coletivo focado em Engenharia Reversa e Evolução de Sistemas. Nosso objetivo é desconstruir funcionalidades do dia a dia e propor melhorias técnicas, documentando cada desafio superado.

✅ O que FAZER (Cultura de Engenharia)
Commits Semânticos: Sempre use o padrão tipo: descrição.

feat: para novas funcionalidades.

fix: para consertar bugs.

docs: para documentação e README.

Trabalhar em Branches: Nunca dê push direto na main. Crie uma branch (ex: feat/filtro-restaurante) e abra um Pull Request.

Code Review: Antes de aceitar um código na main, pelo menos um colega deve revisar e comentar. Isso é onde mais aprendemos!

Documentar o "Porquê": No código, comente a lógica de decisões difíceis (ex: "escolhemos PostGIS pela precisão em Manaus").

❌ O que NÃO FAZER (Pecados Capitais)
Subir Segredos: Nunca coloque senhas de banco ou chaves de API no código. Use arquivos .env e coloque-os no .gitignore.

Commits "Linguicinha": Evite fazer 50 alterações e subir tudo com a mensagem "ajustes". Faça commits pequenos e frequentes.

Ghosting: Se travar em um bug por mais de 24h, peça ajuda no grupo. O erro de um é o aprendizado de todos.

Código Sujo: Evite funções gigantescas. Se a função tem mais de 50 linhas, ela provavelmente deveria ser dividida em duas.

🛠️ Nosso Fluxo de Trabalho (O "Save Game")
Sincronize: git pull origin main (pegue o que os outros fizeram).

Crie sua sala: git checkout -b feat/nome-da-tarefa.

Codifique: Faça sua mágica.

Salve: git add . -> git commit -m "feat: sua mensagem".

Suba: git push origin feat/nome-da-tarefa.

Integre: Abra um Pull Request no GitHub e chame o grupo para revisar.

🚀 Nossos Projetos Atuais
iFood Clone Engine: Focado em geolocalização e sistemas de recomendação.

(Próximos em breve: Netflix, Serasa...)
