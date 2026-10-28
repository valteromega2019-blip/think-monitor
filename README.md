# Think Monitor

**Monitoramento, controle e personalização do seu PC em um só lugar.**

Think Control · Identidade Think — versão **0.22.0**, para **Windows 10 e Windows 11 de 64 bits**.

[**Baixar o instalador `.exe`**](https://github.com/valteromega2019-blip/think-monitor/releases/download/v0.22.0/ThinkMonitor-Setup-0.22.0.exe) · [Página de apresentação](https://valteromega2019-blip.github.io/think-monitor/) · [Versões](https://github.com/valteromega2019-blip/think-monitor/releases)

O Think Monitor reúne informações de hardware, iluminação RGB, Overlay para jogos e ferramentas de gerenciamento em uma interface inspirada no Windows. Escolha suas cores, ajuste as transparências e organize a tela inicial com os blocos que fazem sentido para você.

## O que você pode fazer

| Recurso | Como funciona |
| --- | --- |
| Monitoramento | Acompanhe temperaturas, utilização e outros sensores disponibilizados pelo hardware e pelos drivers compatíveis. |
| Início personalizável | Mova, redimensione, recolha ou oculte blocos e escolha as cores e a transparência do aplicativo. |
| Controle RGB | Use modos individual, sincronizado ou por grupos, cores RGB e HEX, favoritos e perfis. O app pode conectar dispositivos e restaurar as configurações salvas ao iniciar. |
| Overlay | Exiba métricas por cima dos jogos, sincronize as cores com o app ou escolha um tema independente, com transparências separadas. |
| Biblioteca de jogos | Organize seus jogos e abra os títulos pelo aplicativo. Jogos sem capa usam o ícone do executável, quando disponível; a biblioteca também tem um bloco na tela inicial. |
| Desinstalador | Execute o desinstalador oficial de um aplicativo e, após verificar a conclusão, revise pastas residuais específicas. Apenas os itens selecionados por você são enviados à Lixeira. |
| Inicialização do Windows | Configure a abertura minimizada junto ao Windows, com privilégios elevados pela tarefa vinculada à mesma conta de administrador. |

As integrações RGB incluem **ASUS Aura, Corsair iCUE e OpenRGB**; **Razer Chroma está em teste**. O suporte depende do dispositivo, dos serviços e dos SDKs disponíveis. Nem todo componente oferece os mesmos controles ou efeitos. A restauração é feita pelo aplicativo; o suporte a gravação permanente no hardware não é prometido.

## Instalação em três passos

1. Baixe **ThinkMonitor-Setup-0.22.0.exe** na versão publicada neste repositório.
2. Abra o instalador e autorize a solicitação de administrador do Windows na sua própria conta. Ele inclui o **PawnIO oficial 2.2.0**, verifica se já existe uma instalação compatível e instala a dependência quando necessário.
3. Conclua a instalação e abra o Think Monitor. Se o instalador solicitar reinício, reinicie o Windows antes de usar as funções dependentes do driver. Confira os dispositivos em **Ferramentas → Integração** e personalize o aplicativo como preferir.

Esta distribuição usa um **instalador executável**. A instalação em Arquivos de Programas e a configuração da tarefa de inicialização são necessárias para os recursos que dependem desse ambiente protegido. Não é necessário baixar o PawnIO separadamente quando ele já está incluído no instalador.

Para iniciar automaticamente, mantenha habilitada a opção correspondente nas Configurações do aplicativo. A inicialização do Windows usa o modo minimizado; abrir o aplicativo manualmente continua permitindo acessar sua janela normalmente.

## Requisitos e compatibilidade

- Windows 10 ou Windows 11, arquitetura x64.
- Conta com direitos de administrador para instalar dependências e configurar a inicialização elevada.
- Hardware e drivers que exponham as métricas desejadas.
- Serviços ou SDKs compatíveis para cada integração RGB utilizada. O app informa indisponibilidades; a compatibilidade não é universal.

O runtime necessário acompanha a distribuição. Mantenha os componentes instalados pelo assistente para preservar o funcionamento das integrações.

## Novidades da versão 0.22.0

- Conexão e restauração automática do RGB, com reconexão em segundo plano e paleta de cores mais saturadas.
- Favoritos de cores e preservação dos modos individual, sincronizado e por grupos.
- Personalização do Overlay com pré-visualização e transparências para fundo, blocos e gráfico.
- Ícones para jogos sem capa e novo bloco da biblioteca no Início.
- Desinstalador com revisão de resíduos e envio dos itens escolhidos à Lixeira.
- PawnIO oficial incluído, com verificação de integridade e validação da dependência.

## Integridade e estado da versão

Confira o arquivo **SHA256SUMS.txt** anexado à publicação para comparar o SHA-256 do instalador baixado. A assinatura do instalador oficial do PawnIO é preservada. **O executável e o instalador próprios da Think ainda não possuem assinatura digital de editor; o certificado está pendente.** Avisos do navegador ou do Windows devem ser avaliados pelo texto e pela detecção apresentados. Não desative o Defender, o SmartScreen ou outras proteções para instalar o aplicativo.

Esta versão passou por **255 cenários de teste de software**. Isso não representa certificação de todos os dispositivos físicos, de todos os jogos ou de instalação em Windows limpo. Os testes de integração física e os ambientes de destino continuam sujeitos às limitações de compatibilidade descritas acima.

Ao relatar um problema em [Issues do projeto](https://github.com/valteromega2019-blip/think-monitor/issues), informe a versão do app, a versão do Windows, o recurso afetado e o texto completo do erro. Remova dados pessoais de imagens e logs antes de publicá-los.

## Identidade e licenças

**Think Control · Identidade Think**  
Desenvolvido **Think**.  
Copyright © 2026 Think.

O Think Control é uma solução desenvolvida para monitoramento, gerenciamento e personalização de sistemas, oferecendo controle de hardware, desempenho e iluminação RGB em uma interface moderna e intuitiva.

A base original **ResetExplode**, de **GustavoReset**, e suas atribuições sob a licença MIT são preservadas. Os componentes de terceiros continuam sujeitos às respectivas licenças e aos avisos incluídos na instalação. A identidade Think não altera os direitos concedidos pelas licenças originais.
