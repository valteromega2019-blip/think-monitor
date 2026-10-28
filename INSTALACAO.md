# Instalar Think Monitor 0.22.0

Distribuição para Windows 10/11 de 64 bits por instalador executável. Todos os componentes necessários do aplicativo acompanham o assistente. Não distribua apenas o executável interno da pasta instalada.

1. Baixe ThinkMonitor-Setup-0.22.0.exe na página Releases de https://github.com/valteromega2019-blip/think-monitor e confira o SHA-256 em SHA256SUMS.txt.
2. Feche a versão anterior pelo ícone próximo ao relógio → Sair. Execute o instalador e autorize o UAC usando sua conta de administrador.
3. Mantenha o destino protegido em Arquivos de Programas. O PawnIO oficial 2.2.0 incluído será instalado somente quando não houver uma instalação compatível. Se for solicitado reinício, reinicie antes de usar os sensores dependentes.
4. Abra Think Monitor no menu Iniciar. Em Configurações, mantenha Iniciar com o Windows e segundo plano habilitados para iniciar minimizado, com privilégios elevados, pela tarefa vinculada à sua própria conta.

## RGB e Overlay

O aplicativo pode detectar, conectar e restaurar os dispositivos salvos ao iniciar. Em Ferramentas → Integração, confira os componentes e escolha o modo individual, sincronizado ou por grupos. A restauração depende do app em execução; gravação permanente no firmware não está disponível. ASUS Aura, Corsair iCUE e OpenRGB exigem os respectivos serviços/SDKs compatíveis; Razer Chroma está em teste. Esses aplicativos de terceiros não acompanham o instalador Think.

Personalize o Overlay na página Overlay. É possível acompanhar o tema do aplicativo ou usar cores independentes e transparências separadas. Jogos em tela cheia exclusiva ou com restrições próprias podem não exibir o Overlay.

## Atualização e remoção

A atualização preserva as preferências da instalação existente. O caminho interno ThinkExplode e a pasta Think Explode são conservados para compatibilidade. Para remover o aplicativo, use Aplicativos instalados do Windows. O PawnIO pode ser compartilhado com outros programas e não é removido automaticamente.

## Integridade, licenças e suporte

O instalador e o aplicativo Think ainda não possuem certificado de assinatura de código do editor. O PawnIO oficial mantém a assinatura do seu fornecedor. Não desative proteções do Windows; se aparecer um alerta, registre seu texto e a identificação da detecção.

Relate problemas em https://github.com/valteromega2019-blip/think-monitor/issues, removendo informações pessoais de anexos. Consulte THIRD-PARTY-NOTICES.md, LICENSE e licencas para atribuições e termos das dependências. Os documentos em origem/historico-* são registros antigos, não instruções para instalar a versão atual.
