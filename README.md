# PanelCC - Painel de Corrente Contínua

[![Licença](https://img.shields.io/github/license/Canela-san/PanelCC)](LICENSE)
[![Versão](https://img.shields.io/badge/versão-1.0-blue)](https://github.com/Canela-san/PanelCC/releases)

## Descrição

O **PanelCC** é um painel elétrico modular desenvolvido para aplicações de corrente contínua, fornecendo proteção e controle para diversos projetos. Ele integra um disjuntor e um contator de corrente contínua que podem ser facilmente conectados a sistemas existentes, garantindo uma proteção eficiente e simplificada. O objetivo deste painel é servir como uma solução prática para projetos que exigem proteção contra sobrecarga e curto-circuito, além de facilitar o gerenciamento de energia em microredes ou outras aplicações industriais.

Este projeto está sendo utilizado no contexto do **LabREI Microgrid**, mas pode ser adaptado para outros tipos de aplicação.

## Componentes Principais

- **Disjuntor 32A e 125A** - Proteção contra sobrecorrente.
- **Contator 32A e 100A** - Controle de alta corrente de forma segura.
- **Botão de Emergência** - Desligamento rápido em situações críticas.
- **Barramento e Trilho DIN** - Organização e montagem dos componentes.
- **LEDs Indicadores** - Sinalização visual de status operacional.

## Estrutura do Projeto

O projeto inclui os seguintes arquivos e diretórios principais:

- **Modelos 3D**: 
  - `3D Final.FCStd` - Modelo completo do painel.
  - `TechDraw.FCStd` - Desenho técnico do projeto.
  - Vários arquivos .FCStd e .stp para os componentes individuais do painel.
  
- **Esquemáticos**: 
  - `MainSchematic.qet` - Esquemático elétrico do painel.
  - Arquivos .dwg e .pdf dos furos para montagem do painel e stacks.
  
- **Partes**:
  - Arquivos .FCStd, .STEP e .SLDPRT de componentes individuais como disjuntores, contator, canaletas, trilhos DIN, LEDs, tomadas, etc.

## Requisitos

Para visualizar e modificar os arquivos deste projeto, você precisará dos seguintes softwares:

- [FreeCAD](https://www.freecadweb.org/) para abrir os arquivos `.FCStd` e realizar a modelagem 3D.
- [QElectroTech](https://qelectrotech.org/) para editar e visualizar o esquemático elétrico `.qet`.
- Software CAD compatível com arquivos `.dwg` para trabalhar com os esquemáticos de furação.

## Como Usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/SeuUsuario/PanelCC.git
Abra os arquivos no software correspondente:
Arquivos 3D e desenhos técnicos: Use o FreeCAD.
Esquemáticos elétricos: Abra com o QElectroTech.
Esquemáticos de furação: Use um visualizador de arquivos .dwg.
Licença
Este projeto está licenciado sob a Licença MIT.

Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests. Consulte o arquivo CONTRIBUTING.md para mais detalhes.

Contato
Para mais informações sobre este projeto, entre em contato com Seu Nome.

LabREI - Laboratório de Energias Renováveis e Inovações
Universidade X