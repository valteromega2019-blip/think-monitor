# Créditos e componentes de terceiros

Think Monitor / Think Control 0.22.0 inclui componentes de terceiros. Seus direitos autorais e licenças permanecem com os respectivos titulares. A marca Think e as alterações do aplicativo não substituem os avisos desses componentes.

## Origem do aplicativo

A base deriva de [GustavoReset/ResetExplode](https://github.com/GustavoReset/ResetExplode), revisão `ce1d9b30518bbe75bb5e6cb792d1b1e365aaddd6`. **Copyright (c) 2026 Gustavo (GustavoReset)**. O texto MIT original está em [licencas/ResetExplode-MIT.txt](licencas/ResetExplode-MIT.txt) e no arquivo `LICENSE` do aplicativo instalado. O aviso de copyright e a permissão original devem acompanhar as cópias ou partes substanciais dessa base.

## Monitoramento e acesso a dispositivos

As versões abaixo correspondem às dependências do aplicativo. Os binários de LibreHardwareMonitor, BlackSharp, DiskInfoToolkit, RAMSPDToolkit, HidSharp e Mono foram comparados por SHA-256 com os pacotes NuGet oficiais dessas versões e são idênticos aos respectivos arquivos distribuídos pelos fornecedores.

| Componente | Versão | Licença / texto incluído | Código-fonte do fornecedor |
| --- | --- | --- | --- |
| LibreHardwareMonitorLib | 0.9.6 | [MPL-2.0](licencas/MPL-2.0.txt), [avisos de terceiros](licencas/LibreHardwareMonitor-0.9.6-THIRD-PARTY-NOTICES.txt) | [Revisão 3d331e3](https://github.com/LibreHardwareMonitor/LibreHardwareMonitor/tree/3d331e3370efb858411f19511373eff65a218701) |
| BlackSharp.Core | 1.0.7 | [MPL-2.0](licencas/BlackSharp.Core-1.0.7-LICENSE.txt) | [Revisão c70b735](https://github.com/Blacktempel/BlackSharp/tree/c70b735c6cec123ee8a046ac4a0bc6c606f52cf0) |
| DiskInfoToolkit | 1.1.2 | [MPL-2.0](licencas/DiskInfoToolkit-1.1.2-LICENSE.txt) | [Revisão 25319ea](https://github.com/Blacktempel/DiskInfoToolkit/tree/25319eae5781e75bcf141e844ceab2afe94d40ea) |
| RAMSPDToolkit-NDD | 1.4.2 | [MPL-2.0](licencas/RAMSPDToolkit-NDD-1.4.2-LICENSE.txt) | [Revisão 3b47b96](https://github.com/Blacktempel/RAMSPDToolkit/tree/3b47b960e0830fef344624ad5e389675d5f0a1ce) |
| HidSharp | 2.6.4 | [Apache-2.0; Copyright 2010–2025 James F. Bellinger](licencas/hidsharp-2.6.4-LICENSE.txt) | [Projeto do fornecedor](https://software.seekye.com/hidsharp) |
| Mono.Posix.NETStandard | 1.0.0 | [Licenças e avisos do projeto Mono](licencas/Mono-LICENSE.txt) | [Pacote oficial](https://www.nuget.org/packages/Mono.Posix.NETStandard/1.0.0), [projeto Mono](https://github.com/mono/mono) |

O código-fonte dos componentes MPL está disponível nos endereços das revisões indicadas. As bibliotecas são distribuídas sem alterações; seus arquivos continuam sujeitos à MPL. O conjunto de avisos do LibreHardwareMonitor inclui os termos de componentes incorporados, entre eles **PawnIO.Modules**, sob a LGPL 2.1.

## PawnIO

O instalador inclui o **PawnIO oficial 2.2.0**, de namazso, sem modificar o arquivo assinado do fornecedor. Origem: [release oficial 2.2.0](https://github.com/namazso/PawnIO.Setup/releases/tag/2.2.0), [site oficial](https://pawnio.eu/), [código-fonte](https://github.com/namazso/PawnIO).

Os avisos do instalador do fornecedor permanecem preservados. O texto GPL distribuído com o código-fonte está em [PawnIO-COPYING.txt](licencas/PawnIO-COPYING.txt); a declaração do projeto com a exceção de comunicação pelo dispositivo está em [PawnIO-README-license-exception.md](licencas/PawnIO-README-license-exception.md). A cópia incluída não é a edição sem verificação de assinaturas.

## Gráficos e interoperabilidade

| Componente | Versão | Licença / texto incluído | Origem |
| --- | --- | --- | --- |
| Vortice.Direct3D11, Direct3D12, DirectX, D3DCompiler, DXGI e Dxc | 3.8.3 | [MIT; Amer Koleci e colaboradores](licencas/Vortice.Windows-3.8.3-LICENSE.txt) | [Vortice.Windows, revisão 9e609cb](https://github.com/amerkoleci/Vortice.Windows/tree/9e609cb9439c9872aa1b339f177e40ec96f77239) |
| Vortice.Mathematics | 2.1.0 | [MIT; Amer Koleci](licencas/Vortice.Mathematics-2.1.0-LICENSE.txt) | [Revisão fa05ec6](https://github.com/amerkoleci/Vortice.Mathematics/tree/fa05ec6dcba48f3f7331791da6dc7f3d866b2ad6) |
| SharpGen.Runtime e SharpGen.Runtime.COM | 2.4.2-beta | [MIT](licencas/SharpGenTools-2.4.2-beta-LICENSE.txt) | [SharpGenTools, revisão 6990bca](https://github.com/SharpGenTools/SharpGenTools/tree/6990bcafe124a4c22515ad19cee5a081da8db67b) |
| Vortice.Dxc.Native / DirectX Shader Compiler | 1.0.5 | [Termos Microsoft](licencas/vortice.dxc.native-1.0.5-LICENSE-MS.txt), [LLVM](licencas/vortice.dxc.native-1.0.5-LICENSE-LLVM.txt), [MIT](licencas/vortice.dxc.native-1.0.5-LICENSE-MIT.txt) | [Pacote oficial](https://www.nuget.org/packages/Vortice.Dxc.Native/1.0.5), [fonte DXC](https://github.com/microsoft/DirectXShaderCompiler/tree/327e67bcb739190a7acf035c6b700bdb6b00a544) |

## .NET e diagnóstico

O runtime **Microsoft .NET / Windows Desktop 8.0.32 para Windows x64** acompanha a instalação. Os textos foram obtidos dos pacotes oficiais da mesma versão:

- [.NET Runtime — licença](licencas/microsoft.netcore.app.runtime.win-x64-8.0.32-LICENSE.TXT) e [avisos de terceiros](licencas/microsoft.netcore.app.runtime.win-x64-8.0.32-THIRD-PARTY-NOTICES.TXT).
- [Windows Desktop Runtime — licença](licencas/microsoft.windowsdesktop.app.runtime.win-x64-8.0.32-LICENSE).
- [Microsoft.Diagnostics.NETCore.Client — MIT](licencas/Microsoft.Diagnostics.NETCore.Client-LICENSE.txt), versão `0.2.510501`, [revisão do fornecedor](https://github.com/dotnet/diagnostics/tree/8c08c89a0643d31db91e119b1adb463be3e0ffe5).
- [Microsoft.Diagnostics.Tracing.TraceEvent — MIT](licencas/TraceEvent-LICENSE.txt), versão `3.2.8`, [projeto PerfView](https://github.com/microsoft/perfview).

Os componentes Microsoft.Extensions e bibliotecas System adicionais mantêm os avisos Microsoft/.NET aplicáveis. As versões resolvidas estão no arquivo `ThinkExplode.deps.json` da instalação; os textos do runtime não substituem termos adicionais de componentes que expressem licença própria.

## Instalador e integrações

O instalador utiliza **NSIS 3.13**. Seus termos, incluindo os módulos de compressão, estão em [NSIS-LICENSE.txt](licencas/NSIS-LICENSE.txt).

ASUS Aura, Corsair iCUE, OpenRGB e Razer Chroma são integrações opcionais. As marcas pertencem aos respectivos titulares; nenhuma afiliação ou endosso é declarado. SDKs e serviços externos exigidos pelo hardware conservam seus próprios termos. O instalador do Think Monitor não inclui o Armoury Crate ou o iCUE.
