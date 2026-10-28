# Think Monitor / Think Control 0.22.0

## Biblioteca e ferramentas

- Jogos sem capa válida mostram o ícone do executável; quando ele não está disponível, usam um ícone de jogo. A extração é local, assíncrona e limitada; não inicia executáveis nem altera como o jogo é iniciado.
- Novo bloco Biblioteca de jogos no Início, com até seis títulos, jogos em execução primeiro e botões Jogar, Detalhes e Abrir biblioteca. O bloco pode ser movido, redimensionado, recolhido e ocultado. Os layouts existentes são preservados.
- Ferramentas → Desinstalador lista aplicativos desktop e MSI. Primeiro executa o desinstalador oficial, verifica o registro e permite analisar pastas residuais específicas. A revisão começa sem itens selecionados; apenas os escolhidos são enviados à Lixeira. Documentos, jogos salvos, diretórios compartilhados e links são preservados. Aplicativos da Microsoft Store são encaminhados às Configurações do Windows. Chaves do Registro não são apagadas por aproximação de nome.

## RGB e Overlay

- Conexão RGB automática ao iniciar, restauração de estilos individuais, sincronizados e por grupos, favoritos de cores e paleta saturada. A migração ativa a automação solicitada pelo usuário; opções posteriores de desativar permanecem respeitadas.
- Reconexão em segundo plano com tentativas progressivas, inclusive minimizado. Sessões saudáveis não são interrompidas. ASUS Aura e OpenRGB não disputam o mesmo controlador. A devolução manual do controle pausa a automação até nova aplicação.
- Leitura de sensores continua para efeitos RGB por temperatura/carga quando necessário, sem redesenhar todos os painéis enquanto a janela está minimizada.
- Overlay sincronizado com as cores do app ou com cores independentes. Transparência separada para fundo, blocos e gráfico, mantendo os textos opacos. Edição em tempo real, prévia e persistência automática.

## Instalação e integridade

- PawnIO oficial 2.2.0 incluído sem modificação, com SHA-256 e assinatura do fornecedor verificados. O instalador verifica uma instalação compatível antes de executar a dependência, valida registro/biblioteca/serviço após a instalação e informa falhas ou reinício necessário. O PawnIO compartilhado não é removido ao desinstalar o Think Monitor.
- Reparo pelo app usa o instalador oficial incluído, em vez de abrir comandos no terminal.
- Scripts auxiliares de instalação usam política RemoteSigned apenas no processo, sem alterar políticas globais, Defender ou SmartScreen.
- Ferramentas de auditoria e assinatura preparadas; a assinatura pública do Think Monitor continua pendente de certificado válido, que o usuário informou não possuir. Não foi criado certificado autossinado nem removida a marca de origem dos arquivos.
- Validador de instalação em Windows limpo em validation/Test-CleanWindows.ps1. Preparado e verificado sintaticamente; não foi executado em Windows limpo porque esse ambiente não está disponível neste host.

## Limites de validação

Os relatórios de software estão em evidencias. Testes de RGB usam backends simulados; não comprovam suporte de cada dispositivo físico. A assinatura e a reputação do instalador são etapas distintas. Não houve envio aos fornecedores de segurança nem confirmação de falso positivo. O certificado e um ambiente Windows limpo continuam necessários para concluir essas etapas.
