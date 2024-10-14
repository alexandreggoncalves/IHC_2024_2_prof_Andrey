# PRODUTO 8 - AVALIAÇÃO DE UX
## Avaliação pela ferramenta [Lighthouse](https://developer.chrome.com/docs/lighthouse/overview?hl=pt-br)

* As tabelas abaixo demonstram a avaliação feita pela feramente em que notamos tanto em dispositivos Mobile quanto em dispositivos Desktop baixos desempenhos de performance e carregamento do site.
* O LCP em Mobile chegou a 17.180ms quanto a 3.990ms em Desktop, ocasionado principalmente pela imagem principal do site e pelo serviço de aviso de cookies.
* A ferramenta ainda aponta diversos pontos tanto de CSS quando de JAVASCRIPT não utilizados e sendo carregados desnecessáriamente pelo site, ou seja, existe bem provavelemnte um CSS e um JS único e não por área do site que carrega elementos desnecessários a navegação do usuário.
* No CLS, foram encontradas duas trocas de layout, o que não é recomendado pois pode confundir o usuário quanto a confiabilidade no site.
* O FCP avisa o mesmo do LCP, conteúdos carregados desnecessáriamente que impactam na velocidade em que as informações aparecem para o usuário.
* Ainda existe códigos interpretados de terceiros, que impactam na velocidade de carregamento.
* Em resumo o ponto crítico do site é desempenho, na casa de apenas 32%, acessibilidade reduzida (76%), assim como as práticas de desenvolvimento (71%), como API obsoletas e tem pontos positivos no SEO (92%), que são os indicadores para ferramentas de pesquisa.

### Desempenho para dispositivos Mobile
![image](https://github.com/user-attachments/assets/663bee6d-fcde-4b95-9af4-f4041856422b)

### Desempenho dos tempos de resposta para dispositivos Mobile
![image](https://github.com/user-attachments/assets/1bf9ba7f-2fc8-4698-97a5-ec083efba178)


### Desempenho para dispositivos Desktop
![image](https://github.com/user-attachments/assets/543375c6-4824-4109-ab8f-f45a0c40cc09)

### Desempenho dos tempos de resposta para Desktop
![image](https://github.com/user-attachments/assets/cc92f4c0-ba4e-4c02-a726-57b3c5e6663f)
