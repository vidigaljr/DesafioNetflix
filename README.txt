# DESAFIO 01

Objetivo: Desenvolver uma SPA (SINGLE PAGE APPLICATION) apenas com HTML5, CSS3, e Javascript, com base no json da Netflix que foi gerado.

Passos:
	ok1. Criar a página HTML contendo uma tabela para cada gênero, uma abaixo da outra separando as tabelas pelo titulo do gênero com uma tag h1;
	
	ok2. As tabelas deverão seguir o padrão <table> do html, e conter as seguintes colunas referentes ao filme: (Id, Nome, Classificação Etária, Avaliação, Ativo, Data de Criação, Imagem, Assistir);
	
	ok3. A primeira linha da tabela onde ficam os titulos das colunas, deverá estar com um background color e cor de fonte diferente para destacar, e com o texto centralizado e em negrito;
	
	ok4. A coluna de Avaliação deverã exibir estrelinhas amarelas, de acordo com a número da avaliação;
	
	ok5. Caso a classificação etária seja de 18 anos, a célula "<td>" da classificação deverá ser marcada com um background color preto e cor do texto branca em negrito;
	
	ok6. Caso o filme esteja Inativo (ativo = false) pintar toda a linha "<tr>" de cinza bem claro;

	ok7. Na coluna "Assistir" colocar um icone de Play para cada filme; 	

	8. Ao clicar no icone de play de um determinado filme, consultar a chave "filmeExecutando" no Local Storage do navegador, e caso algum filme já esteja sendo executado, abrir uma jabela do tipo "javascript confirm dialog" com a frase "Deseja pausar o filme "<NOME DO FILME>" e iniciar o Filme "<NOME DO FILME>" agora?",
	mas caso a chave "filmeExecutando" nem exista ou esteja sem um Id "null" exibir a frase "Deseja iniciar o Filme "<NOME DO FILME>" agora?".
	
	8.1 O Confirm Dialog deverá ter dois botões "Sim | Não";

	9. Caso clique em "Sim", salvar no Local Storage do navegador a Key chamada "filmeExecutando" com value "Id" do filme que está sendo assistido, e fechar a janela do confirm dialog;
	
	ok10. Caso clique em não, apenas feche a janela;
	
	11. O icone de play de um filme que esteja sendo assistindo, assim que clicar no "Sim", alterar para o icone de "Pausa";
	12. Ao clicar no icone de pausa, voltar o icone de Play e alterar o valor da chave local storage "filmeExecutando" para null.
	
	ok13. A Data de Criação, exibir no padrão Brasileiro, por exemplo "10/05/2022" sem horas.

==============================

