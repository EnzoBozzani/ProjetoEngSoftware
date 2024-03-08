# Servicify - Assistência Residencial

<p>
    O Servicify é uma plataforma inovadora que conecta Prestadores de Serviço especializados em diversas áreas, como pintura, reforma, montagem de móveis, manutenção, faxina, cozinha, entre outros, a Usuários Contratantes que buscam soluções personalizadas para suas necessidades. A plataforma oferece uma experiência transparente e eficiente, garantindo a qualidade e a confiabilidade em cada transação.
</p>

<h3>Processos de Negócio</h3>

1. **Cadastro de Usuários**

| Atividade                                    | Entrada                                                                         | Saída                                                          |
| -------------------------------------------- | ------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| Iniciar cadastro                             | -                                                                               | - Pedido de cadastro                                           |
| Analisar pedido de cadastro                  | - Pedido de cadastro                                                            | - Formulário de contratante/Formulário de prestador de serviço |
| Enviar formulário de contratante             | - Pedido de formulário de Contratante                                           | - Formulário de contratante enviado                            |
| Preencher formulário de contratante          | - Nome, CPF, Endereço, número de contato                                        | - Formulário de contratante preenchido                         |
| Enviar formulário de prestador de serviço    | - Pedido de formulário de Prestador de serviço                                  | - Formulário de prestador de serviço enviado                   |
| Preencher formulário de prestador de serviço | - Nome, CPF, Endereço, número de contato, serviços que está disposto a realizar | - Formulário de prestador de serviço preenchido                |
| Analisar formulário                          | - Formulário preenchido                                                         | - Cadastro realizado/ Cadastro negado                          |

<!--EndFragment-->

2. **Publicação de Serviços:**

| Atividade                                    | Entrada                                                 | Saída                                            |
| -------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------ |
| Escolher uma categoria                       | - Cadastro realizado<br>-Lista de categorias de serviço | - Categoria de serviço selecionada               |
| Enviar formulário para publicação de serviço | - Categoria de serviço selecionada                      | - Formulário de publicação de serviço aberto     |
| Preencher formulário com uma breve descrição | - Dados referentes ao serviço solicitado                | - Formulário de publicação de serviço preenchido |
| Estipular uma faixa de preço                 | - Faixa de preço que o contratante deseja gastar        | - Faixa de preço estipulada                      |
| Publicar o serviço                           | - Todas informações do serviço no sistema               | - Serviço publicado no sistema                   |

3. **Propostas, Negociação e Acordo**

| Atividade                                  | Entrada                                                                                                                         | Saída                                                                                                                           |
| ------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| Fazer proposta pelo serviço                | - Leitura do serviço disponível<br>-Descrição do serviço<br>- Range de preço do serviço<br>                                     | - Dados do prestador (nome, categoria, avaliação)<br>- Dados da proposta (valor pedido, mensagem com perguntas sobre o serviço) |
| Enviar proposta                            | - Dados do prestador (nome, categoria, avaliação)<br>- Dados da proposta (valor pedido, mensagem com perguntas sobre o serviço) | - Adição da proposta ao sistema                                                                                                 |
| Ler proposta e iniciar negociação          | - Proposta com valor e perguntas                                                                                                | - Início (ou não) da negociação                                                                                                 |
| Negociar termos e tirar dúvidas do serviço | - Início da negociação                                                                                                          | - Acordo (ou não) de termos                                                                                                     |
| Solicitar pagamento                        | - Acordo de termos<br>- Dados de pagamento feito pelo contratante                                                               | - Status de pagamento (pago ou não)<br>- Salva a transação no sistema                                                           |
| Retém pagamento e envia dados do serviço   | - Status de pagamento concluído<br>- Valor monetário                                                                            | - Dados do serviço (endereço, prazo, valor, tipo de serviço)                                                                    |
| Recebe dados para realizar o serviço       | - Dados do serviço (endereço, prazo, valor, tipo de serviço)                                                                    | - Emissão do contrato                                                                                                           |

4. **Realização do Serviço e Finalização**

| Atividade                           | Entrada                                                                                                                                                             | Saída                                                                                                                                  |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| Realização do Serviço               | - Contrato de serviço (endereço, prazos, valor, tipo de serviço) <br>                                                                                               | - Serviço concluído <br> - Relatório de serviço (detalhando as atividades realizadas)                                                  |
| Confirmação da Conclusão do Serviço | - Relatório de serviço <br> - Aprovação do cliente                                                                                                                  | - Confirmação da conclusão do serviço (pendente ou concluída) <br> - Pagamento liberado (pendente ou liberado)                         |
| Liberação do Pagamento              | - Valor final <br> - Aprovação do pagamento (pelo cliente ou sistema financeiro)                                                                                    | - Status do depósito (pendente ou realizado)                                                                                           |
| Feedback                            | Questionário de feedback (satisfação com o serviço, qualidade do serviço, atendimento ao cliente, tempo de entrega, preço) <br> - Comentários adicionais do cliente | - Feedback do serviço (satisfeito ou insatisfeito) <br> - Sugestões de melhorias <br> - Elogio (opcional) <br> - Reclamação (opcional) |
| Suporte                             | Solicitação de suporte (descrição do problema)                                                                                                                      | - Solução do problema <br> - Resolução do problema (pendente ou resolvido)                                                             |

<br />
<hr />
<br />

<strong>Membros do Grupo</strong>

Adriel Henrique Foppa Lima - 24.122.096-1

Alan Mantelatto Mlatisuma - 24.122.015-1

Enzo Bozzani Martins - 24.122.020-1

Luca Anequini Antoniazzi - 24.122.032-6
