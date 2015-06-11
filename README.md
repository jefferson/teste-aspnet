# Teste

Neste teste prático serão avaliados raciocínio lógico, criatividade, conhecimento técnico e interpretação. Não existem restrições sobre versões de framework ou bibliotecas.

## Entrega 01
### Etapa presencial. 

Requisitos enviados pelo cliente:
- Quero um site trilingue (português, inglês e espanhol) em asp.net mvc. O site principal (raiz) deve ser o site em português/PT (idioma default). Os sites em inglês e espanhol deve estar em "/en" e "/es" respectivamente.
- Os sites serão "single page", havendo apenas a página inicial em cada idioma. 
- Ao acessar o site pela primeira vez, o site deve obter a lista de idiomas preferenciais do navegador a fim de indicar, dentre os 3 idiomas disponíveis (pt, en e es) o mais apropriado ao usuário. Caso os idiomas utilizados pelo usuário no navegador não estejam entre os 3 disponíveis no site (navegador em francês ou alemão por exemplo), o site deverá tentar buscar dentre os próximos idiomas nas preferências do navegador. Caso não seja encontrado, o idioma default do site será utilizado.
- O usuário deve ser capaz de efetuar a troca do idioma manualmente através de um elemento "dropdown" no site.
- O site em português deve possuir background AMARELO, o inglês LARANJA e o espanhol VERDE. 




## Entrega 02
#### Esta etapa deve ser entregue em até 24 horas após o desenvolvimento da Entrega 01 via pull request. 
Novos requisitos foram enviados com urgência pelo cliente:
- O site deve possuir acesso restrito para um Administrador. 
- Administradores poderão cadastrar novos usuários dos tipos PROGRAMADOR ou DESIGNER, devendo ser possível cadastrar pelo menos nome, login e senha.
- Administradores poderão cadastrar Skills (campo "Nome").
- Administradores poderão atribuir/relacionar usuários (de ambos os tipos) com skills.
- Os usuários dos tipos PROGRAMADOR e DESIGNER devem ser capazes de fazer login no site. Estes usuários não podem cadastrar nenhum outro tipo de usuário - não possuem a permissão de um Administrador.
- Ao efetuar login no site, usuários do tipo PROGRAMADOR devem ver o site com background AZUL, e do tipo DESIGNER com background VERMELHO.
