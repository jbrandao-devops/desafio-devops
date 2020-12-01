#### Alteracoes em 01/12/2020 ####
Desafio Técnico para DevOps Engineer

Parabéns por ter chegado até esta etapa do processo seletivo da Solvimm! Nessa etapa, teremos uma
simulação de um possível caso relacionado ao dia a dia do trabalho na empresa. É só seguir as instruções
abaixo no cenário proposta. Boa sorte no desafio!
Escopo do Desafio
O cliente Notícias da Nuvem precisa migrar a sua plataforma Wordpress de publicação de conteúdo para
a AWS. Segundo o diretor de TI da empresa, o Severino Santos, hoje estão na LocaWeb, com aplicação e
banco de dados em um único servidor com 8 CPU e 16 GB de RAM, mas normalmente utiliza na faixa de
30% dos recursos, tendo picos imprevisíveis que chegam a 100%, às vezes até ficando fora do ar, o que
fez a empresa perder cerca de 20% de visitantes nesse último ano. A aplicação possui 200 GB de disco,
sendo que 150 GB são de imagens e vídeos. O próximo lançamento começa em breve e eles precisam
ter o ambiente em produção dentro de 1 mês.
A empresa estruturou muitos novos conteúdos, que serão anunciados ao longo do próximos 6 meses,
tendo uma previsão de aumento de visitantes da ordem de 50% no final do ano, em relação ao início do
semestre. O diretor está preocupado com esse crescimento frente aos desafios que tiveram na LocaWeb
esse ano. Portanto, ele entrou em contato com a Amazon Web Services, o maior provedor de
computação em nuvem do mundo, para entender como a Notícias da Nuvem pode se beneficiar da
nuvem. A AWS nos encaminhou o cliente para que possamos projetar a jornada de adoção para a nuvem
da empresa e oferecermos uma solução para o Severino Santos.
Sendo assim, será importante planejar o processo de migração, e também planejar e dimensionar a
infraestrutura, podendo consultar a documentação da AWS. Para os elementos de infraestrutura, é
importante utilizar a nomenclatura da AWS, tanto para os serviços (Ex.: EC2) quanto para as
configurações (Ex.: EC2 de 1 CPU e 1 GB de RAM é a t2.micro).
É importante realizar uma estimativa de custos na AWS, utilizando a AWS Calculator.
Lembramos que será importante pensar nos princípios de segurança, disponibilidade, escalabilidade e
custo e explicar como eles compõem a arquitetura. Além disso, é preciso explicar como que o
Wordpress propriamente dito fará uso desses serviços, pois não basta só criar os elementos na
arquitetura da AWS, são necessárias algumas configurações no Wordpress para utilizar alguns serviços
específicos que são importantes nessa arquitetura.
Por fim, será preciso projetar uma solução de monitoramento dessa infraestrutura, bem como definir
como será feito o processo de atualização (deploy de novas versões) do Wordpress após implantação,
pois após a utilização em produção, o cliente espera que o sistema não saia do ar, mesmo quando
estiver ocorrendo uma atualização.

solvimm.com

Desafio Técnico para DevOps Engineer

Você pode enviar dúvidas sobre o escopo de desafio para o email desafio-vagas@solvimm.com dentro
do prazo para dúvidas.

ENTREGÁVEIS

● E-mail para o arquiteto que fará a validação da arquitetura proposta, com:
○ Desenho da arquitetura (sugerimos usar alguma ferramenta como o Draw.io)
○ Texto explicando o que representa cada elemento da solução e sua funcionalidade para
o sistema, bem como possíveis especificidades de integração com o Wordpress
○ Solução de monitoramento considerada para o projeto e a estratégia de atualização da
plataforma
● E-mail para o cliente, com:
○ Detalhamento de como será o processo de migração (as etapas envolvidas)
○ Estimativa de custos da infraestrutura na AWS
○ Cronograma
● Script em Terraform ou Cloudformation para a construção da infraestrutura definida na
arquitetura com elementos de rede, servidores, bancos de dados e storage de arquivos. Não é
necessário que o script instale ou configure o Wordpress. O script deve apenas criar os
elementos de infraestrutura.

No e-mail para o cliente, não é necessário falar de muitos detalhes técnicos com o cliente, mas é
importante deixar claro para o cliente as vantagens da arquitetura proposta e tranquilizá-lo quanto aos
problemas que ele possui no provedor atual. Por fim, é muito importante a cordialidade e o bom
atendimento ao cliente.
Esses dois entregáveis devem ser arquivos anexos enviados em um único e-mail para
desafio-vagas@solvimm.com com o assunto "[Nome do Candidato] Desafio de DevOps Engineer".

Prazos
● Dúvidas sobre o desafio: 4 dias
● Entrega do desafio: 7 dias
