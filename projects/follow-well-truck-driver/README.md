

<h1><a href="./../"> 🔙 </a> Follow well truck driver (Siga bem caminhoneiro)</h1>

## Objetivo do projeto

O projeto tem como objetivo ajudar estabelecimentos que estão à procura de um caminhão para levar suas entregas e ajudar um caminhoneiro que está a procura de bicos para ganhar um dinheiro extra.

**Para o estabelecimentos:**

Vamos fornecer um painel/App que ele consiga solicitar passando informações sobre a carga e destinatário, após passar essas informações será respondido quais caminhões tem disponíveis e seus respectivos valores para efetuar essa entrega, o mesmo poderá tomar a decisão a qual lhe agrada.

**Para o caminhoneiro:**

Vamos fornecer um App que ele consiga receber notificações sobre possíveis procuras feitas pelos os estabelecimentos que estão aguardando um orçamento para entrega de sua mercadoria, o caminhoneiro por sua vez terá a visibilidade de destino e custo dessa entrega, podendo informar o seu valor em cima disso.


## V1.0.0

### Requisitos funcionais

**Eu como #Estabelecimento:**

- [ ] Quero conseguir me cadastrar e logar no Aplicativo/Painel.
- [ ] Quero abrir uma solicitação de orçamento para uma entrega de X para Y
- [ ] Quero nesta solicitação informar as dimensões e pesos da mercadoria a ser levada.
- [ ] Quero nesta solicitação informar a data da possível Retirada/Entrega.
- [ ] Quero após preencher a solicitação enviar a mesma para todos os caminhoneiros que estiverem nas proximidades.
- [ ] Quero poder listar as propostas ordenando-as pelo valor ou pela pontuação dos caminhoneiros
- [ ] Quero poder aceitar e trocar mais informações com o dono da proposta #Caminhoneiro
- [ ] Quero poder caso o dono da proposta mude de idéia voltar a solicitação de orçamento e perguntar quem ainda tem interesse em fazer essa entrega.
- [ ] Quero poder deixar o valor pago para a plataforma, e a mesma disponibilizar o valor para o entregador após confirmação de entrega.


**Eu como #Caminhoneiro:**

- [ ] Quero poder me cadastrar e logar no Aplicativo
- [ ] Quero poder configurar as regiões aonde eu tenho disponibilidade de para fazer a retirada/entrega
- [ ] Quero poder receber solicitações de orçamento seguindo minhas configurações
- [ ] Quero poder ao receber a solicitação visualizar o custo do trajeto e sugestões de preços
- [ ] Quero poder enviar o valor da proposta ao estabelecimento e sugerir alterações de data e hora caso necessário
- [ ] Quero poder após enviar a proposta receber notificação caso o #estabelecimento aceite ou recuse a proposta



**Regras em comum:**

- [ ] Deve ser validado solicitações duplicadas
- [ ] Deve ser validado propostas duplicadas, cada caminhoneiro pode fazer só uma proposta por solicitação
- [ ] Ambos perfis podem receber avaliação no final da entrega podendo ser de 1 a 5
- [ ] Ambos cadastros devem passar por verificação de fraude tanto o #estabelecimento como #caminhoneiro

### Esboço de Arquitetura

<table>
    <tr>
        <td>
            <a href="./nivel1/">
                <img src="./nivel1/capa.png">
            </a>
        </td>
         <td>
            <a href="./nivel2/">
                <img src="./nivel2/capa.png">
            </a>
        </td>
         <td>
            <a href="./nivel2/">
                <img src="./nivel2/capa.png">
            </a>
        </td>
    </tr>
</table>