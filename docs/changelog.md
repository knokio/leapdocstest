# Changelog

## v1.11.202-g4a4ef65-1447266564

### Bug
- [PL-2718] - Hotfix: caso o serviço do DSI de verificação do NIF/BI esteja em baixo, deve ser apresentada uma mensagem

## v1.11.188-g7833a6e-1447150413
2015-11-11

### Templates
Atualizados templates Aluno e Professor, PT e BR, Windows e Linux

- offline_library-20151110-14h40-linux-c4a8d30.tpl
- offline_library-20151110-14h40-windows-c4a8d30.tpl
- offline_library-20151110-14h54-linux-37c4ba2.tpl
- offline_library-20151110-14h54-windows-37c4ba2.tpl
- offline_library-20151110-14h59-linux-5b48e3d.tpl
- offline_library-20151110-14h59-windows-5b48e3d.tpl
- offline_library_drm-20151110-15h20-linux-5b48e3d.tpl
- offline_library_drm-20151110-15h20-windows-5b48e3d.tpl
- wlessons-20151110-14h31-linux-c4a8d30.tpl
- wlessons-20151110-14h31-windows-c4a8d30.tpl
- wlessons-20151110-14h45-linux-37c4ba2.tpl
- wlessons-20151110-14h45-windows-37c4ba2.tpl
### Story
- [PL-2591] - #2 No registo deve existir validação de BI e NIF repetidos
- [PL-2592] - #3 No registo deve ser mostrado erro quando não existe comunicação
- [PL-2593] - (#24938) #4 No registo deve ser validado se está a ser inserido BI e/ou NIF duplicado
### Task
- [PL-2669] - #25038 Unificação do ficheiro de tradução online&offline
- [PL-2677] - (#24612) Atualizar traduções produto offline/online (commit d7dcf02)
- [PL-2684] - #25124 Mensagem erro com "actual"
- [PL-2685] - #25125 Mensagem erro com "actual"
- [PL-2686] - #25020 BRASIL - Atualizar termos de aceitação
- [PL-2687] - #25027 BRASIl - Atualizar ficheiros de ajuda
- [PL-2689] - #25029 BRASIL - Atualizar texto de entrada
- [PL-2705] - Atualizar dados do Mandrill do AGIRE
- [PL-2715] - #25061 Paginador: Cada página da Biblioteca deve ter 30 projetos e não 10
### Bug
- [PL-2545] - #24869 Novo commit ficheiro de traduções
- [PL-2673] - #25066 (QA) Exportar teste resulta em mensagem de erro


## v1.11.173-gb35fb38-1446576932
2015-11-04

### Improvement
- [PL-2428] - Integrar otimização das ligações dos URI resolvers ao JCR
- [PL-2675] - Melhorias na instalação de produtos no catálogo
### Story
- [PL-2590] - (#24937) #1 Deve ser alterado o campo perfil e mostrada uma frase de aviso quando é escolhida a opção Professor
### Bug
- [PL-2262] - #20872 Mediabox: aumentar a área clicável da cruz
- [PL-2671] - Ao atualizar uma publicação (com páginas romanas numeradas) não são atualizadas as labels das páginas

## v1.11.155-g6dc021d-1446047283
2015-10-28
### Improvement
- [PL-1257] - A área de testes deve poder actualizar os títulos dos testes (a partir da última versão)
- [PL-2160] - #24893 Optimizar a importação de questões da Biblioteca
- [PL-2257] - #23921 Questões de escolha múltipla: cotação parcial seleccionada por omissão
- [PL-2297] - #20624 "Peso" ou "Ponderação" na coluna onde se edita o peso de cada questão
- [PL-2298] - #20619 Arredondamento das cotações das questões
- [PL-2348] - (API) Otimizar ligações dos URI resolvers ao JCR
- [PL-2429] - #24650 OFFLINE: mensagem de alerta do URL
- [PL-2462] - #18294 Edição dos slides de uma aula (texto/ficheiro/link)
- [PL-2481] - #24913 Actualizar a caixa de login AGIRE - gerar template novo
- [PL-2483] - Adicionar as propriedades MODULE_ID, MODULE_NAME aos eventos
- [PL-2511] - #24892 Users com permissões ao KLIENTO mas sem permissões ao CLAVES
- [PL-2512] - #24878 Licenças revogadas não devem acumular na lista do utilizador
- [PL-2513] - #24871 Colocar o paginador alinhado à direita
- [PL-2525] - As licenças LeyaEdu revogadas devem ser removidas do sistema
- [PL-2528] - #21265 Ícone do hotspot LEAP BR: mão rosa em vez do localizador preto
- [PL-2530] - Ao editar hotspots no Visus, é apresentado o PDF ao invés do thumbnail, de forma a dar mais fidelidade ao processo
- [PL-2540] - Pesquisa utilizando AND entre parametros
- [PL-2568] - Visus: refresh automático nos logs de instalação do produto
- [PL-2599] - Melhorias das filas de mensagens Leya Educação
- [PL-2601] - Melhoramentos à publicação de Assessments e Lessons
- [PL-2602] - Refactor a alguma lógica dos geradores de produtos
### Story
- [PL-2508] - Análise para disponibilizar o template para MAC
- [PL-2574] - Import de questões da biblioteca para o WTestes (no branch de refactor)
- [PL-2600] - Permitir pesquisa por "uid_consumer" nas licenças DRM
### Task
- [PL-2416] - Configurar SSL para Backoffices de Prody
- [PL-2417] - Configurar SSL para Catalogs/Urepos em Prody
- [PL-2482] - Criar credenciais OAuth para Diretor e Wizard
- [PL-2506] - Executar query para perceber hotspots com height a 0
- [PL-2529] - Atribuir acesso ao role DRM Admin
- [PL-2532] - Análise ao merge do development da UI: offline/online
- [PL-2534] - #24932 Alteração tradução do SSO
- [PL-2535] - #24888 Commit com alteração de texto SSO: 033bb9a
- [PL-2536] - #24936 OFFLINE: Actualizar Director v1, v2 e v3
- [PL-2537] - #24755 Adicionar textos SSO pt-BR no bitbucket
- [PL-2541] - KLIENTO: Pesquisa com filtragem por perfis Leya Educação
- [PL-2546] - Configurar um novo ambiente de testes online (QA)
- [PL-2553] - SSO - Confirmação de estado de acesso
- [PL-2560] - Validar credenciais kliento/claves em QA
- [PL-2564] - Ativar os scripts para desligar os backoffices/QA durante a noite
- [PL-2565] - Atualizar o AGIRE para a útima versão do LEAP
- [PL-2566] - Atualização template PT - 20_aula_digital_aluno_windows (v1.8.3)
- [PL-2572] - #24978 Validar conta de professora com as licenças revogadas
- [PL-2596] - Atualização template PT - 20_aula_digital_professor_windows (v1.8.3)
- [PL-2597] - Atualização template BR - 10_escola_digital_professor_windows (v1.8.3)
- [PL-2598] - Atualização template BR - 10_escola_digital_aluno_windows (v1.8.3)
### Bug
- [PL-1496] - Lista de produtos no Visus só mostra os 10 primeiros itens (árvores) criados
- [PL-2225] - #24044 MacOS/Chrome: visualizar os recursos em modo thumbnail
- [PL-2377] - #24533 PDF com erro de páginas com peso superior a 3Mb
- [PL-2378] - #24547 Offline "20 Aula Digital Aluno" não apresenta janela de alerta de perda de dados
- [PL-2379] - #24469 Duplicação de índices no Dossier e Testes em PROD-PT
- [PL-2412] - #24638 Não é possível alterar o nome do produto
- [PL-2420] - #24639 Activação offline: regresso à janela de autenticação após activação ok
- [PL-2421] - #24642 Hotspots editados em PROD-PT surgem deslocados na Biblioteca
- [PL-2466] - # 24868 Hotspot invisível no Visus mas presente no Produto offline
- [PL-2475] - Visus não consegue processar publicações vazias quando está a publicar um produto
- [PL-2480] - Projectos revogados
- [PL-2494] - #24804 linha transversal fora de sítio nas respostas (separador enunciado/respostas?)
- [PL-2496] - #24889 Projecto não permite acesso a nenhuma das secções - Visus
- [PL-2519] - #24884 Retirar link para ativação de código/chave na entrada do produto
- [PL-2524] - Licenças de professores não estão a atualizar
- [PL-2533] - Botão de "continuar" deve ser apresentado como botão
- [PL-2543] - #24919 Flash adicionado a aula surge como downloadable
- [PL-2554] - #24735 Download incorreto de ficheiro .doc como .rtf
- [PL-2555] - Conta inativa migrada (ALima)
- [PL-2559] - #24939 Director V1 não corre
- [PL-2567] - #24967 Chrome: Página de recuperação de palavra-passe não apresenta texto
- [PL-2575] - #24748 Corrigir textos sem acordo ortográfico
- [PL-2588] - #25010 Testes que quando adicionados dão erro (e não gravam) na aula

## v1.11.85-g68607d8-1444327348
2015-10-08
### Improvement
- [PL-1831] - #18671 Biblioteca_A exportação de um teste não apresenta o nome respectivo, word com e sem correcção
- [PL-1936] - A primeira vez que é aberto o Visus, os projectos devem ser mostrados
- [PL-1939] - Botão "Go" devia estar inactivo enquanto decorre "loading" dos repositórios
- [PL-2088] - Chrome/Android: inserir áudio
- [PL-2149] - #21211 Melhorar o drag&drop dos slides numa aula
- [PL-2240] - #24098 #18751 Poder criar pastas com menos de 2 caracteres no título
- [PL-2425] - Melhorar o feedback de estado de instalação de produtos no catálogo
- [PL-2435] - Na lista de recursos, adicionar atalho para testes
- [PL-2436] - Detectar os timeouts ao gravar um produto
- [PL-2444] - Atualizar os eventos da Biblioteca
- [PL-2461] - #24019 Possível criar uma pasta apenas com 1 caracter no título
- [PL-2465] - Ordenar as licenças do utilizador por ordem decrescente de criação
- [PL-2471] - Ao editar um teste, consigo clicar diretamente numa questão para abrir o seu detalhe/página edição
### Story
- [PL-1825] - #WTestes# IE: O resize de imagens não funciona
- [PL-1965] - Quaestio: ao publicar, considerar o erro 504 Gateway Timeout
- [PL-2282] - Actualizar Director v1 e v2 nos backoffices
- [PL-2399] - Melhoria no módulo Entrada
### Task
- [PL-1507] - Criar dashboard com os ambientes da Amazon
- [PL-2143] - 20 Agosto - Deploy novas tipologias PROD PT
- [PL-2384] - Script para ligar e desligar as máquinas de Backoffices automáticamente durante a noite
- [PL-2415] - Migrar os repositorios JCR das máquinas de PRODY para um disco que não o root e configurar os grupos do Foreman para apontar para lá
- [PL-2434] - Aumentar a versão mínimo do Chrome para acesso aos Backoffices
- [PL-2438] - Testar dump de dados para a migração de utilizadores
### Bug
- [PL-1750] - #19612 Quaestio inline choice - o texto inserido desaparece quase sempre
- [PL-1938] - Botão de Quaestio e Lesson não apresenta "Go"
- [PL-1951] - Não há mensagem de alerta ao sair do teste sem o submeter, clicando no logo "20"
- [PL-2038] - Firefox_escolher o tipo de questão num teste
- [PL-2117] - #23823 #23825 Desenho em página dupla
- [PL-2129] - #20366 Visualização de recursos no Mediabox - imagens não carregam
- [PL-2375] - #24485 Drag nas listas de aulas/testes
- [PL-2388] - #24483 Recursos na Biblioteca não reflectem o Índice da publicação
- [PL-2419] - #24649 OFFLINE: utilização das setas depois de abrir um recurso por hotspot
- [PL-2433] - Validar que a ativação do produto é possível
- [PL-2442] - Problema no toggle no modo de visualização de slides em lições
- [PL-2453] - #23770 Ao criar um 2º slide de texto numa aula, o campo do título não permite edição
- [PL-2455] - #24537 Modal de adição de recursos às aulas: produtos por ordem alfabética