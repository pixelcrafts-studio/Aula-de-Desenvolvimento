# Guia de Configuração de Servidor Minecraft

Este repositório contém um guia completo para estruturar e configurar um servidor de Minecraft, desde a escolha dos plugins até a personalização de mundos usando ferramentas como WorldEdit. Este guia é ideal tanto para iniciantes quanto para usuários intermediários que desejam criar seu próprio servidor de Minecraft.

## Sumário
- [Introdução](#introdução)
- [Hospedagem e Escolha da Versão](#hospedagem-e-escolha-da-versão)
- [Plugins Essenciais](#plugins-essenciais)
- [WorldEdit e Schematics](#worldedit-e-schematics)
- [Personalização do Jogo](#personalização-do-jogo)
- [Testando e Publicando](#testando-e-publicando)
- [Passos Práticos](#passos-práticos)
- [Próximos Passos](#próximos-passos)

---

## Introdução

Criar um servidor de Minecraft permite construir experiências de jogo personalizadas, seja para uso privado ou para compartilhar com uma comunidade. Neste guia, vamos abordar:
- Como configurar um servidor do zero
- Plugins essenciais para gestão e proteção do servidor
- Personalização do jogo com ferramentas como WorldEdit
- Boas práticas para lançamento e manutenção de um servidor público

---

## Hospedagem e Escolha da Versão

### Hospedagem
- Você pode escolher entre **hospedagem local** ou **serviços dedicados**. A hospedagem local é ideal para testes, enquanto serviços dedicados como **MagnoHost** ou **LunarHosting** oferecem melhor desempenho e tempo de atividade.

### Versão
- A escolha da versão correta é fundamental para a compatibilidade com os plugins. As versões mais comumente suportadas para servidores são **1.19.x** e **1.20.x**.
- Recomendamos o uso de **Paper** para otimização de desempenho e compatibilidade de plugins.

---

## Plugins Essenciais

Para um servidor bem estruturado, aqui estão alguns plugins fundamentais:

### Gestão do Servidor
- **EssentialsX**: Comandos básicos do servidor, como `/spawn`, `/home` e gestão de economia.
- **LuckPerms**: Gestão de permissões para configurar cargos e funções dos jogadores.
- **Vault**: Plugin que gerencia o sistema econômico e integra com outros plugins.

### Proteção do Mundo
- **WorldGuard**: Protege áreas específicas de serem editadas ou destruídas.
- **CoreProtect**: Log e rollback para prevenir destruições (griefing).

Você pode encontrar a lista completa de plugins recomendados [aqui](plugins/plugins-essenciais.md).

---

## WorldEdit e Schematics

WorldEdit é uma ferramenta essencial para construir e gerenciar grandes estruturas de forma rápida.

### Comandos Básicos:
- **Selecionar Áreas**: Use o machado de madeira para selecionar dois pontos.
- **Copiar e Colar**: Use `/copy`, `/paste` para mover grandes estruturas.
- **Substituir Blocos**: Substitua blocos em massa com `/replace <antigo> <novo>`.
- **Manipulação de Schematics**: Salve partes do mundo como schematics com `/schem save <nome>` e carregue-as com `/schem load <nome>`.

Mais comandos e dicas podem ser encontrados [aqui](worldedit/comandos.md).

---

## Personalização do Jogo

Você pode personalizar ainda mais o jogo utilizando plugins que expandem as mecânicas padrão:
- **Quests**: Adiciona linhas de missões para os jogadores.
- **DeluxeMenus**: Crie interfaces gráficas interativas.
- **Citizens**: Adicione NPCs com os quais os jogadores podem interagir.

Além disso, você pode adicionar lojas, cargos personalizados ou mobs únicos para experiências diferenciadas.

---

## Testando e Publicando

Antes de tornar o servidor público:
- **Teste localmente**: Use uma configuração local para simular a jogabilidade real.
- **Backups**: Configure backups automáticos para evitar perda de dados.
- **Monitoramento de desempenho**: Use ferramentas como **Timings** ou plugins de otimização.

---

## Passos Práticos

Aqui está um guia passo a passo para configurar um mundo customizado usando WorldEdit:

1. **Instale os Plugins Básicos**: Adicione EssentialsX, WorldEdit e LuckPerms na pasta `/plugins`.
2. **Configure o Mundo**: Use `/region define` com WorldGuard para proteger áreas de spawn.
3. **Use Schematics**: Importe construções personalizadas usando schematics do WorldEdit.
4. **Configure Cargos**: Defina cargos e permissões com LuckPerms.
5. **Teste Permissões**: Teste com contas não-administrativas para garantir que as permissões estão corretas.

---

## Próximos Passos

Depois de dominar os fundamentos de configurar um servidor Minecraft, aqui estão algumas ideias para expandir:
- Aprenda a criar **mini-jogos** ou eventos personalizados usando MythicMobs.
- Explore mods para jogabilidade avançada (por exemplo, **Pixelmon** ou **MMOItems**).
- Construa uma comunidade em torno do seu servidor com um site ou Discord.

Para dúvidas ou problemas, sinta-se à vontade para abrir uma issue ou contribuir com este repositório!
