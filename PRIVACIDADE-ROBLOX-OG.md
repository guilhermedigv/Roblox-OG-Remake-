# Política de Privacidade — Roblox OG

**Edição:** Roblox OG 4.5.1 — PT-BR  
**Responsável pela edição brasileira:** Guilherme Gv (@guilhermedigv)  
**Última atualização:** 5 de novembro de 2026

## 1. Sobre a extensão

Roblox OG é uma edição comunitária de uma extensão que aprimora a experiência de navegação no site Roblox. Ela não é oficial, não é operada pela Roblox Corporation e não possui afiliação, patrocínio ou endosso da empresa.

Esta política descreve os dados que a extensão pode acessar, processar, armazenar e sincronizar. O responsável pela edição brasileira não opera um servidor próprio para receber o histórico de atividade, o conteúdo de conversas ou os dados de navegação dos usuários.

## 2. Dados acessados e processados

Para oferecer as funções descritas na loja e na interface, a extensão pode processar:

- **Identificadores e informações de conta:** IDs de contas Roblox, nomes de usuário, nomes de exibição e informações de perfil.
- **Atividade na plataforma:** listas de amizades, seguidores e solicitações, presença/estado online, experiências em que contas aparecem, alterações de amizade, mudanças em perfis e eventos de jogos e comunidades que o usuário escolhe acompanhar.
- **Conteúdo do site:** textos, imagens, links e informações de perfis, avatares, inventários, jogos, grupos/comunidades, itens, catálogo, servidores e métricas necessárias às ferramentas.
- **Comunicações pessoais:** metadados de mensagens privadas do Roblox, como identificadores e estado de leitura, para a função opcional de marcar mensagens como lidas. Quando o usuário abre a ferramenta de busca de uma conversa, a extensão consulta mensagens daquela conversa para permitir a pesquisa e a navegação até resultados. O conteúdo dessas conversas é mantido em memória durante o uso da ferramenta e não é adicionado ao histórico de atividade.
- **Informações de autenticação:** solicitações autenticadas podem utilizar a sessão Roblox já aberta no navegador, por meio das credenciais de sessão que o próprio navegador anexa às solicitações, e um token anti-CSRF fornecido pelo Roblox. A extensão não solicita a senha do usuário.
- **Saldo virtual de Robux:** quando os recursos correspondentes estão ativados, a extensão lê o saldo de Robux que o próprio Roblox apresenta na interface da conta e pode guardar localmente o último valor para mostrá-lo enquanto o saldo atual carrega. Esse valor é armazenado no armazenamento local da página Roblox; não é enviado ao responsável pela edição.
- **Dados técnicos de diagnóstico:** quando ocorre um erro da própria extensão, o registro local pode conter data e hora, versão, navegador, mensagem técnica, rastreamento de execução e o caminho da página Roblox em que o erro ocorreu. A extensão não cria uma lista geral de todas as páginas visitadas.

Os recursos de acompanhamento são usados para apresentar ao usuário o histórico e as alterações das contas, jogos e comunidades que ele escolheu acompanhar.

## 3. Como os dados são armazenados

As configurações e preferências são armazenadas no armazenamento local da extensão. Quando a opção de sincronização de configurações está ativada, as configurações compatíveis e listas de identificadores usadas pelos recursos podem ser sincronizadas por meio de `chrome.storage.sync`, serviço de sincronização do navegador associado à conta do usuário. A sincronização pode ser desativada nas configurações da extensão.

O histórico de presença e eventos de atividade é armazenado localmente no banco de dados IndexedDB do navegador, neste dispositivo. O histórico detalhado de atividade não é enviado ao responsável pela edição e não faz parte da sincronização de configurações.

O saldo de Robux em cache fica no armazenamento local da página Roblox. A busca de mensagens mantém os resultados em memória enquanto a ferramenta está em uso; o conteúdo das conversas não é guardado no banco de histórico de atividade.

A extensão oferece funções manuais de exportação e restauração. Os arquivos de backup podem conter configurações, listas acompanhadas e registros de atividade, inclusive informações sobre outras contas Roblox. O usuário deve manter esses arquivos privados e compartilhá-los apenas se desejar.

## 4. Comunicação com serviços externos

A extensão faz solicitações às páginas e APIs oficiais do Roblox e aos domínios de distribuição de conteúdo do Roblox para obter informações e executar as funções solicitadas pelo usuário. Essas solicitações podem incluir identificadores de contas e dados necessários para consultar perfis, amizades, presença, itens, jogos, servidores, conversas abertas ou estado de leitura de mensagens.

Quando uma função exige autenticação, as solicitações podem utilizar a sessão Roblox já aberta no navegador. Um token anti-CSRF fornecido pelo Roblox pode ser mantido temporariamente em memória para solicitações protegidas. A extensão não solicita a senha e não envia deliberadamente cookies de sessão ou tokens ao responsável pela edição brasileira.

Quando a sincronização de configurações está ativada, os dados de configuração correspondentes são tratados pelo serviço de sincronização do navegador, conforme a conta e as configurações do próprio navegador.

O Roblox OG não possui um servidor próprio de análise, telemetria ou armazenamento de atividade operado por Guilherme Gv. O responsável pela edição não vende dados pessoais, não usa os dados para publicidade personalizada e não recebe automaticamente o histórico de atividade, o conteúdo das conversas ou relatórios de erro.

## 5. Relatórios de erro e caminhos de páginas

A extensão pode manter até um conjunto limitado de registros técnicos de erros localmente para ajudar a diagnosticar falhas. Um registro pode incluir o caminho (pathname) da página Roblox em que ocorreu o erro, sem a parte de consulta da URL. Isso não constitui um histórico geral de navegação: caminhos são incluídos apenas nos registros de erros da extensão.

Se o usuário optar por exportar ou compartilhar um relatório, ele poderá conter a versão da extensão, informações do navegador, data e hora, mensagens técnicas, rastros de execução e caminhos de páginas. O usuário deve revisar o conteúdo antes de compartilhá-lo. Nenhum relatório é enviado automaticamente ao responsável pela edição.

## 6. Dados que a extensão não solicita

A extensão não solicita que o usuário digite sua senha Roblox, número de cartão, dados bancários, documentos, endereço residencial, coordenadas de GPS ou informações de saúde. A extensão pode usar a sessão Roblox já iniciada no navegador para realizar as solicitações necessárias, sem pedir a senha ao usuário.

## 7. Uso limitado e compartilhamento

Os dados são tratados apenas na medida necessária para fornecer, manter e melhorar as funcionalidades descritas na loja e na interface da extensão. As solicitações a serviços do Roblox são necessárias para consultar ou atualizar informações da própria plataforma. A sincronização de configurações, quando ativada pelo usuário, ocorre pelo serviço de sincronização do navegador.

Os dados não são vendidos, não são usados para publicidade personalizada ou direcionada e não são transferidos para finalidades não relacionadas ao propósito da extensão. O responsável pela edição brasileira não permite que pessoas leiam dados pessoais ou conversas dos usuários, exceto quando o próprio usuário decide compartilhar voluntariamente um relatório ou arquivo de backup para receber suporte.

## 8. Controles do usuário

O usuário pode desativar recursos de acompanhamento, remover contas e itens das listas acompanhadas, limpar registros de atividade, desativar a sincronização de configurações, exportar ou restaurar backups e desinstalar a extensão nas configurações do navegador.

A desinstalação da extensão pode não remover automaticamente arquivos de backup exportados para o computador. O saldo de Robux em cache pode ser removido limpando os dados locais do site Roblox.

## 9. Alterações nesta política

Esta política será atualizada caso o tratamento de dados ou as funcionalidades da extensão mudem. A versão publicada deve corresponder ao pacote efetivamente enviado à loja.

## 10. Contato

Responsável pela edição PT-BR: **Guilherme Gv**  
Identificador público: **@guilhermedigv**

---

## English summary

Roblox OG is an unofficial community-made Roblox website enhancement extension. It may process Roblox account IDs, usernames and profile information; friends, followers, requests, presence and selected account/game/community activity; Roblox page content; private-message IDs and read status for the optional mark-as-read feature; and messages from a conversation when the user opens the chat-search tool. Chat-search results are held in memory while the feature is used and are not added to the activity database. When enabled, the extension reads the user's displayed virtual Robux balance and stores the last value locally in Roblox page storage so it can be shown while the current balance loads. Authenticated requests may use the existing Roblox browser session and a Roblox-provided anti-CSRF token temporarily in memory. The extension does not ask for the user's password or deliberately send session cookies or tokens to the Brazilian edition maintainer. Settings are stored locally and compatible settings/watch lists may sync through `chrome.storage.sync` if enabled. Detailed activity history is stored in local IndexedDB and is not synced. Error records may include a Roblox page path only when an extension error occurs; the extension does not keep a general browsing history. The maintainer does not operate an analytics server, does not sell user data, does not use data for personalized advertising, and does not automatically receive activity history, chat content or error reports. Contact: Guilherme Gv — @guilhermedigv.
