## <h3 style="color: #48c;">**Cenários Automatizados**</h3>

<div>
<br>
  A automação de testes deste projeto abrange diversos cenários, organizados dentro do diretório de testes no projeto. Abaixo está uma documentação detalhada dos principais cenários desenvolvidos:
</div>

## <h3 style="color: #48c; margin: 38px 0;">**Comercial**</h3>

#### **Interessados**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>Cadastro de interessado com produto principal:
    <ul>
      <li>Domínio Start</li>
      <li>Domínio Plus</li>
      <li>Domínio Premium</li>
    </ul>
  </li>
<br>
  <li>Cadastro de interessado importando:
    <ul>
      <li>Por planilha XLS</li>
      <li>Dados do CNPJ através do botão <code>Importar Dados</code></li>
    </ul>
  </li>
<br>
  <li>Cadastro de interessado manual:
    <ul>
      <li>Sem CNPJ – Teste validando bloqueio do sistema</li>
      <li>Usando CPF e validando listagem dos dados</li>
    </ul>
  </li>
<br>
  <li>Cadastro de interessado via endpoint do site:
    <ul>
      <li>Sendo cliente ou não</li>
      <li>Realizando trâmites até interessado ficar qualificado</li>
      <li>Gerando atividades</li>
      <li>Editando e atribuindo o interessado a outro vendedor</li>
    </ul>
  </li>
<br>
  <li>Atribuição de interessado a um vendedor:
    <ul>
      <li>Acesso a listagem corretamente</li>
      <li>Atribuição de um vendedor ao interessado via listagem pelo botão 'Atribuir Vendedor'</li>
      <li>Validação da inclusão correta do vendedor ao interessado</li>
    </ul>
  </li>
</div>

<br>

#### **Prospects**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>Cadastrar Prospect padrão via interessado, para cenários de contrato.</li>
  <li>Cadastrar Prospect avulso, utilizando o botão para importar dados.</li>
  <li>Cadastrar Prospect e editar todos os campos do perfil, além de qualificar o prospect.</li>
</div>

<br>

#### **Oportunidades**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>Cadastrar uma oportunidade para os Contratos Contábil:
    <ul>
        <li>Domínio Start</li>
        <li>Domínio Plus</li>
        <li>Domínio Premium</li>
        <li>Domínio Empresarial</li>
        <li>Domínio Personalizado</li>
    </ul>
  </li>
<br>
  <li>Cadastrar uma oportunidade para Adendos:
    <ul>
      <li>Ampliação</li>
      <li>Redução</li>
    </ul>
  </li>
<br>
  <li>Cadastrar uma oportunidade para os seguintes periféricos:
    <ul>
      <li>Auditor Kolossus</li>
      <li>Busca NF-e</li>
      <li>Conteúdo Contábil Tributário</li>
      <li>Onvio Messenger</li>
      <li>Onvio Processos</li>
    </ul>
  </li>
</div>

<br>

#### **Contratos**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>Contrato contábil Domínio Start:
    <ul>
      <li>Contrato padrão via assinatura Eletrônica Docusign</li>
      <li>Abaixo da tabela</li>
    </ul>
  </li>
<br>
  <li>Contrato contábil Domínio Plus:
    <ul>
      <li>Contrato padrão via assinatura Eletrônica Docusign</li>
      <li>Tipo Convênio/Escola</li>
      <li>Para Ex Cliente</li>
    </ul>
  </li>
<br>
  <li>Contrato contábil Domínio Premium via assinatura Eletrônica Docusign.</li>
  <li>Contrato contábil Domínio Empresarial via assinatura Eletrônica Docusign.</li>
  <li>Contrato contábil Domínio Personalizado via assinatura Eletrônica Docusign.</li>
</div>

<br>

#### **Contratos - Periféricos**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>Contratação do periférico Auditor Kolossus.</li>
  <li>Contratação do periférico Busca NF-e.</li>
  <li>Contratação do periférico Conteúdo Contábil Tributário.</li>
  <li>Contratação do periférico Onvio Messenger.</li>
  <li>Contratação do periférico Onvio Processos.</li>
</div>

<br>

#### **Adendos**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>Adendos de Ampliação e Redução - Contrato Domínio Start.</li>
  <li>Adendos de Ampliação e Redução - Contrato Domínio Plus.</li>
  <li>Adendos de Ampliação e Redução - Contrato Domínio Premium.</li>
  <li>Adendos de Ampliação e Redução - Contrato Domínio Personalizado.</li>
  <li>Adendos de Ampliação e Redução - Contrato Domínio Empresarial.</li>
</div>

## <h3 style="color: #48c; margin: 38px 0;">**Domínio Atendimento**</h3>

#### **Contratação de Periféricos**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>
    Contratação dos periféricos disponibilizados para os seguintes produtos principais:
    <ul>
      <li>Start</li>
      <li>Plus</li>
      <li>Premium</li>
      <li>Empresarial</li>
      <li>Personalizado</li>
    </ul>
  </li>
<br>
  <li>
    Validações realizadas:
    <ul>
      <li>Realização da contratação de cada periférico disponível do Domínio Atendimento</li>
      <li>Validação do processamento de todos os periféricos</li>
      <li>Verificação da replicação dos bundles e ativação dos produtos</li>
      <li>Verificação do acesso ao Domínio Web</li>
    </ul>
  </li>
</div>

<br>

#### **Solicitações de Suporte (SSC)**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>
    Cadastro de SSC via Domínio Atendimento
  </li>
<br>
  <li>Validação do dados mostrados no registro da SSC, logo após o cadastro</li>
  <li>Validação da listagem da SSC no Domínio Atendimento, utilizando filtros da tela para realizar a consulta</li>
  <li>Validação da SSC dentro do SGD, verificando que a replicação foi feita corretamente</li>
</div>

<br>

#### **TRIA**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li> Testes de validação das respostas da TRIA nos seguintes Chats:
    <ul>
      <li>Folha de pagamento</li>
      <li>Escrita Fiscal</li>
      <li>Contabilidade</li>
      <li>Honorários</li>
    </ul>
  </li>
</div>

<br>

#### **Central de Soluções**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li> Testes na Central de Soluções no Domínio Atendimento, validando seguintes pontos:
    <ul>
      <li>Realizar consulta de um registro na Central de Soluções</li>
      <li>Validar listagem de registros relacionados a consulta realizada</li>
      <li>Validar os dados da solução e abertura do video vinculado</li>
    </ul>
  </li>
</div>

## <h3 style="color: #48c; margin: 38px 0;">**Endpoints**</h3>

#### **Clientes**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>
    Validação nos endpoints de clientes:
    <ul>
      <li>Realiza validação em diversos clientes com produtos diferentes</li>
      <li>Confere estrutura do cliente listado</li>
      <li>Listagem correta de todos os clientes inclusos no endpoint</li>
    </ul>
  </li>
</div>

<br>

#### **Solicitações de Suporte (SSC)**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>
    Cadastro de uma SSC usando os endpoints do Domínio 2:
    <ul>
      <li>Vinculando anexo</li>
      <li>Validando posteriormente no SGD o cadastro correto dela</li>
    </ul>
  </li>
</div>

<br>

#### **Interessados**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>
    Cadastro de interessado via os endpoints do Site:
    <ul>
      <li>Cadastro de um interessado como cliente</li>
      <li>Cadastro de outro interessado como não cliente</li>
      <li>Validando posteriormente o cadastro correto dos dois registros no SGD</li>
    </ul>
  </li>
</div>

## <h3 style="color: #48c; margin: 38px 0;">**Performance**</h3>

#### **Testes de performance ao acessar telas**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>
    Testes de Performance ao acessar alguns links do sistema:
    <ul>
      <li>Validando o tempo de acesso</li>
      <li>Registrando nos bancos de dados</li>
      <li>Realizando uma média dos últimos 3 meses de registros</li>
      <li>Validando se o tempo está de acordo ou não com as médias calculadas</li>
    </ul>
  </li>
</div>

## <h3 style="color: #48c; margin: 38px 0;">**Operações**</h3>

#### **Análise do cliente**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>Gerar análise do cliente, validando que os dados estão de acordo com o esperado.</li>
  <li>Incluir Pós-venda via análise do cliente, validando cadastro correto dela.</li>
</div>

<br>

#### **Atendimentos e Implantações**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>Preenchimento da passagem de bastão comercial e técnica.</li>
  <li>Cadastro e validação de um agendamento na implantação.</li>
  <li>Validação dos botões auxiliares listados na tela de implantação.</li>
  <li>Edição e cancelamento de uma programação.</li>
</div>

<br>

#### **Relatórios**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>Geração e validação de relatório - Perda de Clientes Novos.</li>
</div>

## <h3 style="color: #48c; margin: 38px 0;">**SGSAI**</h3>

#### **Fluxo de versão**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>
    Fluxo de versão Domínio Web:
    <ul>
      <li>Cadastro de uma versão</li>
      <li>Tramitações</li>
      <li>Cadastro de SAI</li>
      <li>Realização de trâmites até a aprovação da SAI</li>
      <li>Finalização e conclusão da versão</li>
    </ul>
  </li>
<br>
  <li>
    Fluxo de versão Onvio BR:
    <ul>
      <li>Cadastro de uma versão</li>
      <li>Tramitações</li>
      <li>Cadastro de SAI</li>
      <li>Realização de trâmites até a aprovação da SAI tanto em DEMO quanto em QED</li>
      <li>Finalização e conclusão da versão</li>
    </ul>
  </li>
</div>

<br>

#### **SAI - Validação dos botões auxiliares**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>Validação dos seguintes botões auxiliares:
    <ul>
      <li>Reclassificar</li>
      <li>Editar</li>
      <li>Alterar Equipe</li>
      <li>Previsão</li>
      <li>Prioridade Estimativa</li>
      <li>Imprimir</li>
      <li>Retorno Parcial</li>
      <li>Tipo de Teste</li>
      <li>Vinculo de Projeto existente</li>
    </ul>
</div>

<br>

#### **Notificação de Erro**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>Cadastro de uma Notificação de Erro.</li>
  <li>Validação dos trâmites e listagem nas consultas.</li>
  <li>Validação da SSC gerada automaticamente.</li>
</div>

<br>

#### **Solicitação de Alteração Legal**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>Cadastro de uma Solicitação de Alteração Legal.</li>
  <li>Validação dos trâmites e listagem nas consultas.</li>
  <li>Validação da SSC gerada automaticamente.</li>
</div>

<br>

#### **Solicitação de Implementação Legal**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>Cadastro de uma Solicitação de Implementação Legal.</li>
  <li>Validação dos trâmites e listagem nas consultas.</li>
  <li>Validação da SSC gerada automaticamente.</li>
</div>

<br>

#### **Pré-SAI**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>Cadastro de uma Solicitação de Melhoria.</li>
  <li>Cadastro de uma Pré-SAI.</li>
  <li>Cadastro de uma SAI via Pré-SAI, validando trâmites e listagens dos registros.</li>
</div>

## <h3 style="color: #48c; margin: 38px 0;">**SGSC**</h3>

#### **Ocorrências**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>Cadastro de uma Ocorrência e Sub-Ocorrência, validando os seguintes trâmites:
    <ul>
      <li>Em Análise</li>
      <li>Aguardando resposta</li>
      <li>Respondido</li>
      <li>Concluído</li>
    </ul>
  </li>
  <li>Validação de todos os filtros da tela de Ocorrências</li>
</div>

<br>

#### **Liberação TRIA/Chat Humano**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>Verificando o funcionamento correto da tela, validando seguintes pontos:
    <ul>
      <li>Validação dos filtros e consultas da tela</li>
      <li>Validação do funcionamento da troca das checkboxs e botões auxiliares</li>
      <li>Validação da atualização de registros já existentes</li>
      <li>Validação da paginação da tela, trocando de páginas e validando registros</li>
    </ul>
  </li>
</div>

<br>

#### **Solicitações de Suporte (SSC)**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>Cadastro de SSC, executando os seguintes cenários:
    <ul>
      <li>Domínio Contábil - Validando trâmites e listagem nas telas de consultas</li>
      <li>Domínio Inova - Validando trâmites e listagem nas telas de consultas</li>
    </ul>
  </li>
  <li>Cadastro de SS via SSC, validando os seguintes pontos:
    <ul>
      <li>Cadastro e validação do registro da SS, além de validações relacionadas ao vinculo à SSC</li>
      <li>Validar os seguintes trâmites: Em Análise, Aguardando Resposta, Respondido, Aguardando Resposta TI, Aguardando Resposta - Parceiro, Concluído</li>
    </ul>
  </li>

  <li>Validação da ordenação dos registros pelo último trâmite na tela de solicitações de suporte.</li>
</div>

<br>

#### **Chat Plug Social**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>Realizar acesso no Chat Plug Social, verificando componentes nas seguintes abas após o login:
    <ul>
      <li>Aba Dashboard</li>
      <li>Aba Chat</li>
      <li>Aba Contatos</li>
      <li>Aba Histórico SGD</li>
      <li>Aba Configurações > Clientes</li>
    </ul>
  </li>
</div>

<br>

#### **Central de Soluções**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li> Testes na Central de Soluções, validando seguintes pontos:
    <ul>
      <li>Cadastro de uma Solução, editando e incluido anexos</li>
      <li>Validar listagem da solução cadastrada na tela "SGSC > Gerenciar > Central de Soluções"</li>
      <li>Validar listagem da solução cadastrada na tela "SGSC > Central de Soluções"</li>
    </ul>
  </li>
</div>

<br>

#### **Filtros - Tela de Pesquisar Clientes**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>Verificando o funcionamento dos filtros da tela de Pesquisar Clientes, validando os seguintes Filtros:
    <ul>
      <li>Nome</li>
      <li>Número de série</li>
      <li>Telefone</li>
      <li>CNPJ</li>
      <li>Código</li>
    </ul>
  </li>
</div>

## <h3 style="color: #48c; margin: 38px 0;">**SGSUN**</h3>

#### **Solicitações de Suporte (SS)**

<br>

<div style="border: 1px solid #ccc; padding: 10px; margin: 10px 0;">
  <li>Cadastro de Notificação de Erro via SS, validando os seguintes pontos:
    <ul>
      <li>Cadastro da Notificação de Erro, validando os campos esperados no cadastro</li>
      <li>Validação dos detalhes da Notificação de Erro cadastrada</li>
      <li>Validação dos vínculos da SS com a Notificação de Erro</li>
    </ul>
  </li>
</div>

<br>