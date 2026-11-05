# Política de Privacidade — Roblox OG

**Edição:** Roblox OG 4.5.1 — PT-BR  
**Responsável pela edição brasileira:** Guilherme Gv (@guilhermedigv)  
**Última atualização:** 5 de novembro de 2026

## 1. Sobre a extensão

Roblox OG é uma edição comunitária de uma extensão que aprimora a experiência de navegação no site Roblox. Ela não é oficial, não é operada pela Roblox Corporation e não possui afiliação, patrocínio ou endosso da empresa.

Esta política descreve os dados que a extensão pode acessar, usar, armazenar e sincronizar. A extensão não opera um servidor próprio para receber o histórico de navegação ou os registros de atividade.

## 2. Dados acessados e processados

Para fornecer seus recursos, a extensão pode acessar informações disponibilizadas pelas páginas e APIs oficiais do Roblox, incluindo:

- **Identificadores e informações pessoais da conta:** IDs de contas Roblox, nomes de usuário, nomes de exibição e informações de perfil.
- **Atividade:** listas de amizades, seguidores e solicitações, presença/estado online, jogos em que contas aparecem, alterações de amizade e mudanças em perfis de pessoas que o usuário escolhe acompanhar.
- **Conteúdo do site:** textos, imagens, links e informações de jogos, grupos/comunidades, itens, catálogo, servidores e métricas públicas necessárias às ferramentas de aprimoramento.
- **Comunicações pessoais:** metadados de mensagens privadas do Roblox, como IDs e estado de leitura, para a função opcional de marcar mensagens como lidas. Nas conversas de chat abertas pelo usuário, a extensão também processa dados das mensagens disponíveis na página para corrigir o carregamento, a atualização e a navegação do chat. O conteúdo das conversas não é adicionado ao histórico de atividade da extensão.
- **Informações de autenticação:** em solicitações autenticadas, a extensão pode utilizar a sessão já aberta no navegador e um token anti-CSRF disponibilizado pelo próprio Roblox. Esses dados são usados apenas nas solicitações destinadas aos serviços do Roblox; a extensão não solicita a senha do usuário.

Alguns desses dados podem identificar uma conta Roblox ou descrever sua atividade e comunicações na plataforma. Os recursos de acompanhamento e histórico só são usados para exibir as funcionalidades escolhidas pelo usuário.

## 3. Como os dados são armazenados

As configurações da extensão são mantidas no armazenamento do navegador. O histórico de presença e eventos de atividade é guardado localmente no banco de dados do navegador (IndexedDB), neste dispositivo.

O recurso de sincronização de configurações, quando ativado pelo usuário, utiliza a área de sincronização fornecida pelo próprio navegador (Chrome/Edge). Essa sincronização pode incluir valores de configuração e listas de identificadores necessárias aos recursos configurados. O histórico detalhado de atividade e o conteúdo das conversas não são incluídos nessa sincronização.

A extensão oferece funções manuais de exportação e restauração. Os arquivos de backup podem conter configurações, listas acompanhadas e registros de atividade, inclusive informações sobre outras contas Roblox. O usuário deve manter esses arquivos privados e compartilhá-los apenas se desejar.

## 4. Comunicação com serviços externos

A extensão faz solicitações às páginas e APIs do Roblox e aos domínios de distribuição de conteúdo do Roblox para obter as informações necessárias às funcionalidades.

Quando uma funcionalidade exige autenticação, as solicitações podem utilizar a sessão Roblox já aberta no navegador. Um token anti-CSRF fornecido pelo Roblox pode ser mantido temporariamente em memória para realizar solicitações protegidas, como atualizar o estado de leitura de mensagens. A extensão não solicita a senha, não exporta deliberadamente os cookies de sessão ou tokens para o responsável pela edição e não os envia a servidores operados por Guilherme Gv.

Quando a sincronização de configurações é ativada, os dados correspondentes são tratados pelo serviço de sincronização do navegador, conforme a conta e as configurações do próprio navegador.

O Roblox OG não possui um servidor próprio de análise, telemetria ou armazenamento de atividade operado por Guilherme Gv. A extensão não vende dados pessoais nem envia automaticamente o histórico de atividade ou o conteúdo das conversas ao responsável pela edição.

## 5. Relatórios de erro

A extensão pode manter registros técnicos de erros localmente para ajudar a diagnosticar falhas. Se o usuário optar por exportar ou compartilhar um relatório, ele poderá conter a versão da extensão, informações do navegador, mensagens técnicas, rastros de execução e referências de páginas. O usuário deve revisar o conteúdo antes de compartilhá-lo. Nenhum relatório é enviado automaticamente ao responsável pela edição.

## 6. Dados que a extensão não solicita

A extensão não pede que o usuário informe sua senha Roblox, dados de pagamento, documentos, endereço residencial ou informações de saúde.

## 7. Controles do usuário

O usuário pode desativar recursos de acompanhamento, remover contas e itens das listas acompanhadas, limpar registros de atividade, desativar a sincronização de configurações, exportar ou restaurar backups e desinstalar a extensão nas configurações do navegador.

A desinstalação da extensão pode não remover automaticamente arquivos de backup que o usuário tenha exportado para o computador.

## 8. Alterações nesta política

Esta política será atualizada caso o tratamento de dados ou as funcionalidades da extensão mudem. A versão publicada deve corresponder ao pacote efetivamente enviado à loja.

## 9. Contato

Responsável pela edição PT-BR: **Guilherme Gv**  
Identificador público: **@guilhermedigv**

---

## English summary

Roblox OG is an unofficial community-made Roblox website enhancement extension. It may process Roblox account identifiers and profile information; friends, followers and presence/activity data; Roblox website content; private-message metadata for the optional mark-as-read feature; and messages available in chat conversations opened by the user for chat repair and navigation. For authenticated Roblox requests, the extension may use the browser's existing Roblox session and a Roblox-provided anti-CSRF token temporarily in memory. It does not ask for the user's password or send session tokens to the extension maintainer. Settings are stored in browser storage and may be synchronized through the browser's own sync service if enabled. Detailed activity history and chat content are not included in settings sync. Activity records are stored locally in IndexedDB. The maintainer does not operate a server to receive activity history or chat content, does not sell personal data, and does not automatically send error reports to the maintainer. Contact: Guilherme Gv — @guilhermedigv.
