# Backward-From

## Introdução

A rastreabilidade "backward-from" é muito importante na engenharia de software e na gestão de requisitos. Essa prática é extremamente benéfica em projetos de desenvolvimento de software, pois permite uma compreensão clara da origem e do contexto de requisitos, componentes de software e alterações. Isso é fundamental para garantir a qualidade e a conformidade com os objetivos do projeto.

## Metodologia

Adotamos o meta-modelo de Toranzo, seus níveis e os principais elos de rastreabilidade.

Os principais níveis são:
> - Ambiental: Analisa fatores externos como mercado, regulamentações e condições econômicas que influenciam o sistema. 
> - Organizacional: São informações relacionadas a organização.
> - Gerencial: Envolve o planejamento, monitoramento e controle do projeto.
> - Desenvolvimento: Trata do design, codificação, teste e implementação técnica do sistema, em nosso projeto seriam os artefatos feitos.

Os principais elos de rastreabilidade são:

> - Satisfação: classe origem tem dependência de satisfação com a classe destino.
> - Recurso: classe origem tem dependência de recurso com a classe destino.
> - Responsabilidade: registra a participação, responsabilidade e ação de pessoas sobre artefatos.
> - Representação: captura a representação ou modelagem dos requisitos em outras linguagens.
> - Alocado: classe origem está relacionada à classe destino, que representa um subsistema.
> - Agregação: indica “composição” de elementos.

**Legendas:**

> - RF: Requisito Funcional
> - RNF: Requisito Não Funcional
> - ENT: Entrevista
> - IP: Introspecção
> - STO: Storytelling
> - AP: Analise de protocolo
> - AIU: Analise de Interface
> - DOC: Analise de documento
> - LX: Léxicos
> - UC: Casos de uso

**Tabela 1** - Requisitos funcionais elicitados

|ID| Elicitação | Origem | Status |
| ---- | ---- |---- |---- |
| RF01 | Logar pelo Gov | [AIU2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) , [IP2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/), [DOC10](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)| Implementado|
| RF02 | Buscar por veículo | [AIU4](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP4](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)| Implementado|
| RF03 | Informar dados do veículo | [AIU5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/), [DOC1](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)| Implementado|
| RF04 | Adicionar carro como roubado | [AIU6](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP6](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)| Implementado|
| RF05 | Listar pessoas desaparecidas| [AIU9](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP9](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)| Implementado|
| RF06 | Vincular ao desaparecido | [AIU11](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP11](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)| Implementado|
| RF07 | Vincular ao carro | [AIU12](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP12](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)| Implementado|
| RF08 | Buscar por mandados de prisão | [AIU13](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP13](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/), [DOC2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)| Implementado|
| RF09 | Fornecer informações sobre mandados de prisão | [AIU14](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP14](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/), [DOC2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)| Implementado|
| RF10 | Buscar por procurados | [AIU16](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/),  [IP16](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/), [DOC4](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)| Implementado|
| RF11 | Fornecer informações sobre procurados |[AIU17](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP17](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)| Implementado|
| RF12 | Sair do aplicativo | [AIU19](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/)| Implementado|
| RF13 | Anunciar perturbação da vizinhança | [AIU20](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP20](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)| Implementado|
| RF14 | Ler texto para deficientes visuais | [IP1](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)| Não Implementado|
| RF15 | Disponibilizar restrição |[AP2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [ENT2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/)| Implementado|
| RF16 | Visualizar informações institucionais | [AIU15](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) | Implementado|
| RF17 | Disponibilizar informação do tipo de veículo | [AP3](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [ENT3](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/), [STO2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/storytelling/)| Não Implementado|
| RF18 | Disponibilizar diversas opções de denúncia | [AP5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [ENT5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/), [DOC5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/), [DOC6](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/), [DOC7](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/), [DOC8](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/), [DOC9](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)| Implementado|
| RF19 | Tutorial de uso do aplicativo | [AP7](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [ENT7](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/)| Não Implementado|
| RF20 | Disponibilização de fotos do desaparecido | [AP8](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [ENT8](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/)| Não Implementado|
| RF21 | Disponibilização de informações detalhadas do desaparecido | [ENT9](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/) | Não Implementado|
| RF22 | Ligar para a polícia | [AIU7](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP7](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)| Implementado|
| RF23 | Visualizar vínculos |[AIU8](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/)| Implementado|
| RF24 | Requisitar ajuda | [AIU18](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) | Implementado|
| RF25 | Retornar ao início | [AIU21](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/)| Implementado|
| RF26 | Salvar histórico de busca | [AIU22](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP15](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)| Implementado|
| RF27 | Disponibilizar filtro de pesquisa | [AIU23](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) | Implementado|
| RF28 | Possibilitar compartilhamento das informações de placa | [AIU25](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) | Implementado|
| RF29 | Notificar sobre atualizações sobre vínculo | [IP8](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)| Não Implementado|
| RF30 | Adicionar novas informações sobre perturbação da vizinhança | [IP21](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)| Não Implementado|
| RF31 | Acesso a mapa da região | [IP22](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)| Não Implementado|
| RF32 | Fornecer feedback de periculosidade de áreas no mapa | [IP23](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)| Não Implementado|
| RF33 | Visualizar perfil  |[AIU1](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/)| Implementado|
| RF34 | Usar funcionalidades sem o cadastro do Gov | [ENT12](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/)| Não Implementado|
| RF35 | Editar perfil Gov |[AIU29](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/)|Implementado|
| RF36 | Buscar Por Pessoa Desaparecida |[DOC3](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)|Implementado|
| RF37 | Cadastrar o próprio veículo |[DOC11](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)|Implementado|
| RF38 | Registrar Furto ou Roubo de veículo |[DOC12](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)|Implementado|
| RF39 | Inserir foto do desaparecido | [DOC13](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)|Implementado|
| RF40 | Inserir localização do desaparecido | [DOC14](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)|Implementado|

_Autor:[Italo Bruno](https://github.com/ItaloBrunoM), [Flávio Melo](https://github.com/flavioovatsug), 2024._

**Tabela 2** - Requisitos não funcionais elicitados

| ID | Elicitação | Origem | Status |
| ---- | ---- |---- |---- |
| RNF01 | Rápida disponibilização de informações | [AIU27](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [AP1](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [ENT1](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/), [IP27](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)| Implementado|
| RNF02 | Sigilo relativo de informações | [AIU26](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) , [IP26](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)| Implementado|
| RNF03 | Banco de dados ser constantemente atualizado | [AP4](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [IP25](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/), [STO3](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/storytelling/)| Não Implementado|
| RNF04 | Ajudar o trabalho policial e a comunidade | [ENT11](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/)| Implementado|
| RNF05 | Interface simples | [AIU3](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP3](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/), [STO1](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/storytelling/)| Implementado|
| RNF06 | Instalação do aplicativo em diferentes sistemas | [AIU28](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/), [IP28](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/)| Implementado|
| RNF07 | Aplicativo deve ser constantemente divulgado | [AP6](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/), [STO4](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/storytelling/)| Não Implementado|

_Autor:[Italo Bruno](https://github.com/ItaloBrunoM), [Flávio Melo](https://github.com/flavioovatsug), 2024._

## Elos

Neste segmento, abordaremos os vínculos dos requisitos identificados nas tabelas 1 e 2. De acordo com a metodologia mencionada, todos os requisitos serão categorizados com base no tipo de vínculo. No entanto, é importante observar que todos esses requisitos identificados pertencem à categoria de Desenvolvimento. Eles derivam de artefatos criados durante o processo de desenvolvimento do trabalho, sem qualquer relação com a organização ou a gestão do projeto. A partir desses requisitos, compilamos a tabela 3, que apresenta todos os vínculos (elos) envolvidos.

**Tabela 3** - Elos funcionais

| ID | Requisito  | Tipo de Elo |
| :---: | :---: | :---: |
| ELO01| RF01 / AIU2, IP2, DOC10 | **Agregação:** [AIU2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) agrega [LX07](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/Lexico/) </br> **Agregação:** [IP2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) agrega [LX07](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/Lexico/)  </br> **Agregação:** [DOC10](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) agrega [LX07](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/Lexico/) |
| ELO02| RF02 / AIU4, IP4 | **Satisfação:** [AIU4](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) satisfaz [DOC1](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) </br> **Satisfação:** [IP4](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) satisfaz [DOC1](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)|
| ELO03| RF03 / AIU5, IP5, DOC1 | **Recurso:** [AIU5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) depende de [DOC11](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) </br> **Recurso:** [IP5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) depende de [DOC11](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) </br>  **Satisfação:** [DOC1](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) satisfaz [DOC12](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/)|
| ELO04| RF04 / AIU6, IP6 | **Satisfação:** [AIU6](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) satisfaz [DOC12](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) </br> **Satisfação:** [IP6](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) satisfaz [DOC12](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) | 
| ELO05| RF05 / AIU9, IP9 | **Alocado:** [AIU9](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) Alocado em [LX08](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/Lexico/) e [AIU23](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/)  </br> **Alocado:** [IP9](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) Alocado em [LX08](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/Lexico/) e [AIU23](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/)|
| ELO06| RF06 / AIU11, IP11 | **Alocado:** [AIU11](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) Alocado em [LX05](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/Lexico/) </br> **Alocado:** [IP11](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) Alocado em [LX05](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/Lexico/) |
| ELO07| RF07 / AIU12, IP12 | **Alocado:** [AIU12](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) Alocado em [LX05](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/Lexico/) </br> **Alocado:** [IP12](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) Alocado em [LX05](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/Lexico/) |
| ELO08| RF08 / AIU13, IP13 | **Agregação:** [AIU13](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) é composto por [DOC2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) </br> **Agregação:** [IP13](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) é composto por [DOC2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) |
| ELO09| RF09 / AIU14, IP14 | **Agregação:** [AIU14](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) é composto por [DOC2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) </br> **Agregação:** [IP14](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) é composto por [DOC2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) |
| ELO10| RF10 / AIU16, IP16 | **Alocado:** [AIU16](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) Alocado em [DOC4](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) </br> **Alocado:** [IP16](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) Alocado em [DOC4](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) |
| ELO11| RF11 / AIU17, IP17 | **Recurso:** [AIU17](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) depende de [AIU16](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) e [ENT9](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/) </br> **Recurso:** [IP17](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) depende de [IP16](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) |
| ELO12| RF12 / AIU19 | **Recurso:** [AIU19](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) depende de [LX01](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/Lexico/) |
| ELO13| RF13 / AIU20, IP20 | **Agregação:** [AIU20](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) é composto por [ENT5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/) </br> **Agregação:** [IP20](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) é composto por [ENT5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/) |
| ELO14| RF14 / IP1 | **Recurso:** [IP1](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) depende de [LX01](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/Lexico/) |
| ELO15| RF15 / AP2, ENT2 | **Agregação:** [AP2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/) é composto por [AP1](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/) </br>  **Agregação:** [ENT2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/) é composto por [AP1](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/) |
| ELO16| RF16 / RF16 | **Recurso:** [RF16](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao//Pós-Rastreabilidade/backward/) depende de [LX04](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/Lexico/) |
| ELO17| RF17 / AP3, ENT3 | **Agregação:** [AP3](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/) é composto por [ST02](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/storytelling/) </br>  **Agregação:** [ENT3](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/) é composto por [ST02](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/storytelling/) |
| ELO18| RF18 / AP5, ENT5, DOC5, DOC6, DOC7, DOC8, DOC9 | **Recurso:** [AP5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/) depende de [UC05](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/Casos_De_uso/) </br> **Recurso:** [ENT5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista) depende de [UC05](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/Casos_De_uso/) </br> **Recurso:** [DOC5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) depende de [UC05](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/Casos_De_uso/) </br> **Recurso:** [DOC6](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) depende de [UC05](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/Casos_De_uso/) </br> **Recurso:** [DOC7](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) depende de [UC05](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/Casos_De_uso/) </br> **Recurso:** [DOC8](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) depende de [UC05](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/Casos_De_uso/) </br> **Recurso:** [DOC9](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) depende de [UC05](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/Casos_De_uso/)|
| ELO19| RF19 / AP7, ENT7 | **Recurso:** [AP07](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/) depende de [LX03](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/Lexico/) </br> **Recurso:** [ENT7](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/) depende de [LX03](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/Lexico/)|
| ELO20| RF20 / AP8, ENT8 | **Recurso:** [AP08](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeProtocolo/) depende de [LX06](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/Lexico/) </br> **Recurso:** [ENT8](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/) depende de [LX06](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/Lexico/)|
| ELO21| RF21 / ENT9 | **Alocado:** [ENT9](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/) alocado [UC02](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/Casos_De_uso/) </br> **Agregação:** [ENT9]() agrega [DOC3]() |
| ELO22| RF22 / AIU7 | **Satisfação:** [AIU7](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) satisfaz [AIU18](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) </br> **Alocado:**[AIU7](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) Alocado em [ENT5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/) |
| ELO23| RF23 / AIU8 | **Agregação:** [AIU8](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) é composto por [IP11](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) e [IP12](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) |
| ELO24| RF24 / AIU18 | **Recurso:** [AIU18](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) depende [AIU7](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/)|
| ELO25| RF25 / AIU21 | **Satisfação:** [AIU21](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) satisfaz [ENT10](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/) |
| ELO26| RF26 / IP15 | **Agregação:** [IP15](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) agrega em [LX01](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/Lexico/) |
| ELO27| RF27 / AIU23 | **Agregação:** [AIU23](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) agrega em [LX01](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/Modelagem/Lexico/) |
| ELO28| RF28 / AIU25 | **Satisfação:** [AIU25](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) satisfaz [ENT12](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/) |
| ELO29| RF29 / IP8 | **Agregação:** [IP8](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) agrega em [AIU11](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) e [AIU12](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) |
| ELO30| RF30 / IP21 | **Recurso:** [IP21](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) depende de [AIU20](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) |
| ELO31| RF31 / IP22 | **Recurso:** [IP22](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) depende de [ENT04](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/) |
| ELO32| RF32 / IP23 | **Recurso:** [IP23](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) depende de [IP22](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) |
| ELO33| RF33 / AIU1 | **Recurso:** [AIU1](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) depende de [INT17](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) |
| ELO34| RF34 / ENT12 | **Alocado:** [ENT12](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Entrevista/) está alocado em [INT9](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) |
| ELO35| RF35 / AIU29 | **Recurso:** [AIU29](LINK_PLACEHOLDER) depende de [IP2](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) |
| ELO36| RF36 / DOC3 | **Agregação:** [DOC3](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) agrega em [AIU26](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) |
| ELO37| RF37 / DOC11 | **Agregação:** [DOC11](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) compõe em [IP5](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) |
| ELO38| RF38 / DOC12 | **Agregação:** [DOC12](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) é composto por [IP6](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) e [IP8](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/Introspeccao/) |
| ELO39| RF39 / DOC13 | **Agregação:** [DOC13](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) compõe [AIU9](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) |
| ELO40| RF40 / DOC14 | **Agregação:** [DOC14](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDeDocumento/) compõe [AIU10](https://requisitos-de-software.github.io/2024.1-Sinesp_Cidadao/elicitacao/tecnicas/AnaliseDaInterface/) |

_Autor:[Italo Bruno](https://github.com/ItaloBrunoM), [Flávio Melo](https://github.com/flavioovatsug), 2024._

**Tabela 4** - Elos não funcionais

| ID   | Requisito | Tipo de Elo|
| :---: | :---: | :---: |
| ELO41| RNF01 / AIU27, AP1, ENT1, IP27 | **Recurso:** [AIU27](LINK_PLACEHOLDER), [AP1](LINK_PLACEHOLDER), [ENT1](LINK_PLACEHOLDER), [IP27](LINK_PLACEHOLDER) |
| ELO42| RNF02 / AIU26, IP26 | **Recurso:** [AIU26](LINK_PLACEHOLDER), [IP26](LINK_PLACEHOLDER) |
| ELO43| RNF03 / AP4, IP25, STO3 | **Recurso:** [AP4](LINK_PLACEHOLDER), [IP25](LINK_PLACEHOLDER), [STO3](LINK_PLACEHOLDER) |
| ELO44| RNF04 / ENT11 | **Recurso:** [ENT11](LINK_PLACEHOLDER) |
| ELO45| RNF05 / AIU3, IP3, STO1 | **Recurso:** [AIU3](LINK_PLACEHOLDER), [IP3](LINK_PLACEHOLDER), [STO1](LINK_PLACEHOLDER) |
| ELO46| RNF06 / AIU28, IP28 | **Recurso:** [AIU28](LINK_PLACEHOLDER), [IP28](LINK_PLACEHOLDER) |
| ELO47| RNF07 / AP6, STO4 | **Recurso:** [AP6](LINK_PLACEHOLDER), [STO4](LINK_PLACEHOLDER) |

_Autor:[Italo Bruno](https://github.com/ItaloBrunoM), [Flávio Melo](https://github.com/flavioovatsug), 2024._

## Conclusão

Considerando o Meta-modelo de Toranzo como referência, este documento apresenta 30 elos de rastreabilidade que permitem avaliar a qualidade e a coerência dos requisitos elicitados para o projeto do aplicativo do Sinesp Cidadão. Esses elos abrangem as diferentes dimensões e níveis de abstração dos requisitos, bem como as relações entre eles. Assim, é possível verificar se os requisitos atendem às necessidades e expectativas dos stakeholders, se são consistentes e completos, e se estão alinhados com os objetivos do projeto.

## Referência Bibliografia

> - POHL, Klaus; RUPP, Chris. Requirements Engineering Fundamentals: A Study Guide for the Certified Professional for Requirements Engineering Exam.
> - Slides da Aula 26 da Professora Milene Serrano e do Professor Maurício Serrano.

## Histórico de Versão

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`| 14/06/2024 | Criação do documento |[Flávio Melo](https://github.com/flavioovatsug) e [Italo Bruno](https://github.com/Italobrunom) | [Christian Hirsch Santos](https://github.com/crstyhs) |
|`1.1`| 15/06/2024 | Adição dos elos funcionais 21 ao 40| [Italo Bruno](https://github.com/Italobrunom) | [Christian Hirsch Santos](https://github.com/crstyhs) |
