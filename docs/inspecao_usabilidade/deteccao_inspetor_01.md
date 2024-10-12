# Inspeção de Usabilidade - Fase 1 - Detecção (Inspetor 01)

| Localização | ID Defeito | Inspetor | Descrição do problema | Heurística | Nome Heurística | Severidade |
| :---:       | :---:      | :---:    | ---                   | :---:      | ---             | ---        |
| Capa | 1 | Inspetor 01 | Ao entrar no site pela primeira vez, a "div" de aviso sobre os "cookies" é exibida, porém a formatação do texto não está padronizada. | H8 |	Estética e Design Minimalista	Cosmético | Cosmético |
| Capa | 2 | Inspetor 01 | Ao clicar no botão "ver mais ofertas", comumente o site deveria mostrar no mesmo local essas novas ofertas, mas redireciona o usuário para uma página de busca com menos ofertas do que a página principal mostra. | H4 | Consistência e Padrões |	Pequeno |
| Capa | 3 | Inspetor 01 | Na pesquisa de destinos, o campo "Data de ida" está auto preenchido com "00/00/0000", mas quando abre o calendário já vem marcado o dia atual. Este campo para facilitar a ajudar o usuário, já poderia vir preenchido com a data atual. | H7 | Flexibilidade e eficiência de uso | Cosmético |
| Capa | 4 | Inspetor 01 | Na primeira vez que entramos no site, o site solicita permissão para consultar a localização. Mesmo quando concedida tal permissão, na busca de destinos o campo "Origem" não vem auto preenchido com a cidade que o usuário está, o que é comum em outros sites que possuem a mesma funcionalidade. | H7 | Flexibilidade e eficiência de uso | Cosmético |
| Capa | 5	| Inspetor 01 |	Logo abaixo da busca, existem 3 imagens, "Parcele sua compra", "Sua compra 100% segura com a gente" e "Compre suas passagens com o melhor preço". Ao passar o mouse sobre tais imagens, a primeira informa no "tooltip", "Parcele sua viagem em até 6x", a segunda também, "Parcele sua viagem" e na terceira nada é exibido. | H4 |	Consistência e Padrões | Cosmético |
| Capa | 6 | Inspetor 01 |	Há na capa 5 imagens para diferentes áreas, "Fidelidade", "Espaço melhor idade", "Espaço mulher", etc. Destas 5 imagens, as 3 primeiras levam o usuário a uma determinada área, porém as duas últimas mais a direita, apesar de aparecer o ícone de "click" com o mouse, não há ação nenhuma ao clicar. | H4 |	Consistência e Padrões | Pequeno |
| Capa | 7 | Inspetor 01 | Na seção "Melhores ofetas" as ofertas são visualizadas com fundo preto e ao clicar em "Ver mais ofertas" o usuário é levado a outra página com as ofertas em fundo "cinza claro" |	H8 | Estética e Design Minimalista | Cosmético |
| Capa | 8 | Inspetor 01 | Na seção "Os ônibus da eucatur tem", o eucatur está em minúsculo, uma vez que é o nome da empresa deveria estar Eucatur, além de que a imagem "Tomadas USB" mostra um ícone de tomada elétrica e não USB que possui um ícone padão para tal finalidade. |	H8 | Estética e Design Minimalista | Cosmético |
| Capa | 9 | Inspetor 01 | Na seção de ofertas, cada oferta possui 3 ícones "Facebook, WhatsApp e Anchor(link)", mas para que são? Um tooltip é exibido ao passar o mouse "Eucatur a qualquer destino", o que isso quer dizer? Mas ao clicar ele na verdade é um compartilhamento da oferta em tal plataforma ou no cado o "anchor" copia o link da oferta para compartilhar onde o usuário quiser. Poderia o tooltip explicar o que é como por exemplo, "compartilhar esta oferta". | H4 | Consistência e Padrões | Pequeno |
| Ver Mais Ofertas | 10 | Inspetor 01 | Baseado no defeito ID 9, na página de "Ver mais ofertas", os mesmos ícones sequer possuem o tooltip explicando para que servem tais botões. |	H4 | Consistência e Padrões | Pequeno |
| Capa | 11 | Inspetor 01 |	Na seção "depoimentos", 4 depoimentos são exibidos, porém se o usuário quiser ver mais depoimentos, não há uma área específica ou botão que forneça ao usuário tal informação. | H4 | Consistência e Padrões |	Pequeno |
| Cadastro de Usuário |	12 | Inspetor 01 | Ao preencher o campo senha, não há informação alguma sobre como deve ser esta senha, porém ao digitar 3 caracteres por exemplo, o sistema avisa que ainda faltam 5 caracteres. | H5 | Prevenção de Erros | Grande |
| Login |	13 | Inspetor 01 | Ao efetuar o login, novamente existe um "checkbox" para aceitar os termos e política de privacidade. Não há esta necessidade para todo o Login que o usuário efetuar, uma vez que no cadastro de usuário os termos de uso e política de privacidade já foram aceitos | H4 |	Consistência e Padrões | Pequeno |
| Login	| 14 | Inspetor 01 | Ao efetuar o primeiro login, o sistema pergunta "Você concede esses privilégios de acesso? Primeiro Nome, Sobrenome, Data de Nascimento, etc...", mas para quê isso? Não há nenum texto explicativo de "o porquê dessa solicitação ao usuário, sendo mostrado um botão de "não" e "sim", se eu aptertar em não, o que acontece? | H10 | Ajuda e Documentação |	Grande |
| Login |	15 | Inspetor 01 | Após aceitar o acesso aos dados, o site efetua o Login, mostra uma mensagem de "login efetuado com sucesso" porém o site abre dentro desta mesma janela de login que está em tamanho menor, mesmo podendo redimensionar, ficando o usuário com duas janelas abertas. Sendo que o site funciona com o usuário autenticado nessa nova janela e não na anterior que estava.	| H7 | Flexibilidade e eficiência de uso | Grande |
| Todo o site | 16 | Inspetor 01 | A cada intervalo de tempo, uma "pop-up" é mostrada, no caso da inspeção é em referência ao "Outubro Rosa", porém ao fechar, em um determinado tempo ela volta a aparecer, tirando a atenção do usuário na tarefa a ser executada e se tornando incomoda. | H3 |	Controle e Liberdade do Usuário |	Pequeno |
| Pesquisa | 17 |	Inspetor 01 |	O sistema de pesquisa deixa pesquisar uma data anterior a data da pesquisa, o que pode causar problemas de compra indevida, pois não faz sentido comprar uma passagem para um dia que já passou. | H9 |	Reconhecer, diagnosticar e corrigir erros | Grande |
| Capa do site | 18 |	Inspetor 01	| Ao clicar em "minhas viagens" o site redireciona para o login ocorrendo o problema já reportado no defeito 15 e ao conectar o site entra na pesquisa e o  link "minhas viagens" some não existindo mais. | H4 | Consistência e Padrões | Pequeno |
| Capa do site | 19 |	Inspetor 01 |	Os menus acima e direita logo após fazer o login dizem "olá, porém sem dizer o nome de quem está conectado. Ao mesmo tempo o menu disponível é "não é você? Sair" sendo que não mostra quem está conectado. | H5 |	Prevenção de Erros |	Pequeno |
| Sistema | 20 | Inspetor 01 | Ao entrar na janela "complete seu cadastro" é uma DIV que não possui o botão de fechar, cancelar ou algo que o usuário possa cancelar a ação. |	H3 | Controle e Liberdade do Usuário | Grande |
| Sistema | 21 | Inspetor 01 | Ao clicar em "Gerenciar minhas notificações por e-mail em "Ajustes" o botão voltar não funciona | H3 |	Controle e Liberdade do Usuário |	Pequeno |
| Sistema | 22 | Inspetor 01 | Alterar senha, novamente não possui instruções clara de como deve ser a configuração da senha. | H5 |	Prevenção de Erros | Grande |
| Sistema | 23 | Inspetor 01 | Ao tentar excluir um passageiro cadastrado o sistema não pergunta se realmente o usuário quer realizar a exclusão e faz diretamente a ação de excluir, mesmo que o usuário tenha clicado acidentalmente no botão excluir. | H5 |	Prevenção de Erros |	Pequeno |
| Sistema | 24 | Inspetor 01 | A excluir um passageiro a mensagem de sucesso na operação é apresentada ao usuário, porém a operação não é realizada e o passageiro continua aparecendo na tela. |	H5 | Prevenção de Erros |	Grande |
| Sistema | 25 | Inspetor 01 | Ao tentar alterar os dados do passageiro que tentamos excluir, mostra todos os dados, mas ao clicar em "salvar" aparece uma mensagem que "não foi possível identificar o passageiro", ou seja, não se pode excluir nem alterar mais os dados mas o sistema continua mostrando tais dados. | H5 |	Prevenção de Erros | Grande |
| Carrinho | 26 |	Inspetor 01 |	No carrinho o botão "excluir poltronas" abre uma pequena janela que possui um botão "remover" ao lado da poltrona, porém esta ação não solicita nenhuma confirmação do usuário. |	H5 | Prevenção de Erros |	Grande |
















