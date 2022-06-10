# Heurísticas de Nielsen + WCAG + Slides

## O que são heurísticas?

Herísticas são como regras generalizadas. As heurísticas de Nielsen são normas focadas em estabelecer uma jornada de utilização do software para o usuário de forma não cansativa, intuitiva e quase, automática. São um conjunto de 10 regras que visam "evitar" a existência de um manual dos usuários.

## Exemplos de má aplicação

Um exemplo de má aplicação de algumas heurísticas é o site do SIGA. 

A heurística 4 (consistência e padrões) diz que um sistema deve abraçar convenções para não confundir o usuário e que as coisas não podem fugir de contexto. Na imagem abaixo, o botão de "sair" poderia ter sido melhor representado por um símbolo de "porta se abrindo", por exemplo, ao invés de "liga ou desliga", apesar de ainda fazer sentido. 


![image](https://user-images.githubusercontent.com/79228873/172876342-cc9a48fb-392b-4dde-89ed-6cce12d323bb.png)


Seguindo a mesma imagem como exemplo, outras heurísticas feridas são as 3 e 5, respectivamente: liberdade e controle do usuário e prevenção de erros. Uma diz respeito à liberdade do usuário de navegar como quiser. Se ele errar, deve poder voltar atrás no erro, de forma que o sistema não tome decisões por ele. Para aplicar isso pode-se adicionar um botão de "refazer ou desfazer". A outra refere-se à prevenção de coisas darem errado, através de um pop-up avisando sobre uma tentativa de "sair da página ou excluir algo", por exemplo. Ambos os casos não então presentes na plataforma acima.

A heurística 9, auxiliar usuários a reconhecer, diagnosticar e recuperar erros também não é bem aplicada. Uma forma de fazer isso poderia ser apresentando uma imagem de erro mais descritiva e direta indicando um erro, exemplo: "erro 404", porém os erros se apresentam da seguinte forma:


![image](https://user-images.githubusercontent.com/79228873/172985098-0be999d6-7b85-4c3d-a631-dde060575ec6.png)


Mais exemplos de má aplicação são das 8 e 10; "estética e design minimalista" e "ajuda e documentação", respectivamente. A primeira se trata de um sistema com a apresentação apenas das informações mais relevantes e de preferência com poucos e diretos textos informativos. A segunda é sobre pensar nas possíves confusões e dúvidas dos usuários sobre o sistema e apresentar soluções, uma tela de dúvidas frequentes por exemplo. Essa plataforma embora minimalista, apresenta uma estética um pouco confusa e um tanto dificil de se navegar, além de não apresentar uma tela de "dúvidas frequentes", instruções ou algo do tipo:


![image](https://user-images.githubusercontent.com/79228873/172986278-adaf786d-9c1c-48ee-89ae-84643895df11.png)


## Exemplos de boa aplicação


Heurística 4 (Google Apresentações) as imagens de impressora e lupa deixam claras as funções de imprimir e aumentar o zoom:


![image](https://user-images.githubusercontent.com/79228873/172990254-daa2bcd0-9523-4234-8310-9a6cba8b25ce.png)


Heurística 3 (Google Docs) os botões de "refazer" impedem que o usuário tenha uma perda de progresso caso cometa algum erro:


![image](https://user-images.githubusercontent.com/79228873/172990673-1a1a1f6d-c1e2-407c-a76c-1c54694c0221.png)


Heurística 5 (Google Docs) O pop-up que aparece faz com que o usuário pense duas vezes antes de cometer uma ação decisiva, como excluir um documento por exemplo:


![image](https://user-images.githubusercontent.com/79228873/172990806-94f835a6-54b6-4f3f-bcbc-7ab0b84f6e94.png)


Heurística 9 (Google) As informações que aparecem na tela descrevendo o erro são claras e descritivas, além de sugerirem alguns passos para tentar consertar o erro:


![image](https://user-images.githubusercontent.com/79228873/172990966-2085b4ca-2b0e-4cdf-a529-4ee55aae42bf.png)


Heurística 8 (Google) A home do Google é extremamente minimalista contendo apenas as coisas importantes; barra de pesquisa, sugestões, fazer login e etc: 


![image](https://user-images.githubusercontent.com/79228873/172991167-92bf2f16-c4cf-496f-bf1c-2e322376d757.png)


Heurística 10 (Google) Ainda sobre o Google, caso algum usuário fique em dúvida sobre como funciona a funcionalidade de pesquisa, ele pode receber instruções através da opção "como funciona a pesquisa":


![image](https://user-images.githubusercontent.com/79228873/172991313-76d27a34-e30a-4d74-908c-0d8d498fe296.png)


## Alguns princípios e técnicas de acessibilidade e design

É interessante que todo conteúdo visual possua alguma espécie de legenda que passe a mesma informação. Na imagem abaixo encontra-se a home do Firefox e ela possui sugestões de sites mais acessados, cada um deles, além de possuir a logo também apresenta o nome escrito embaixo, assim como a barra de pesquisa informa a possibilidade de pesquisar:


![image](https://user-images.githubusercontent.com/79228873/172992345-ebebe935-79a9-4587-98ad-f3e2b8a28fb6.png)


Para uma boa acessibilidade é importante que vídeos possuam elementos como legendas. Os vídeos no Youtube em sua grande maioria possuem essa ferramenta de ativar ou desativar as legendas, como mostrado abaixo:


![image](https://user-images.githubusercontent.com/79228873/172991584-a661ce4d-45ea-4950-aa78-adca1b24d379.png)


Uma outra forma de aumentar a inclusão é trazendo a possibilidade de aprensentar um conteúdo na linguagem de sinais. No site do governo brasileiro existe um botão com a funcionalidade de transmitir informações através da linguagem de sinais em Libras:


![image](https://user-images.githubusercontent.com/79228873/172992242-ec297593-5e56-4524-882b-b63e48ac86e2.png)


Na busca de um design mais amigável e associativo um elemento importante é a identificação de padrões já conhecidos. Desenhos geométricos simples são uma ótima ideia para ícones pois as pessoas facilmente reconhecerão aquele objeto e associarão à sua funcionalidade. No Microsoft Teams os ícones são desenhos geométricos simples e descritivos facilmente relacionados, como o calendário, a mochila e o telefone:


![image](https://user-images.githubusercontent.com/79228873/172992430-3364b64f-3279-4372-8577-9ed3a86fd430.png)


Alguns elementos visuais como cores e formatos são especialmente importantes quando se quer prender a atenção do usuário. Em um conjunto de esferas pretas aquela única que for branca chamará mais atenção, diferentemente de um conjunto de esferas coloridas pois nenhuma seria especialmente chamativa. Se a intenção for prender a atenção do usuário, é importante usar um padrão de cores e formatos que o faça focar naquilo. A página inicial do Google apresenta essas características, de forma que a logo da empresa seja o mais notável pois está em cores e fonte diferenciadas e centralizado, logo após percebe-se a barra de pesquisa que é o foco da ferramenta, também centralizada e longe de elementos menos importantes e não relacionados:

![image](https://user-images.githubusercontent.com/79228873/172992495-f02605a5-f1bf-4603-9c36-048ba81f3448.png)

