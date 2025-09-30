🛠️ OTCustom – Editores e Ferramentas do Servidor

Bem-vindo ao OTCustom, um conjunto de editores e ferramentas criados para facilitar o desenvolvimento, manutenção e personalização do seu servidor OpenTibia.
Este repositório reúne scripts, configurações e utilitários essenciais para criar um servidor totalmente customizado e estável.

<img width="809" height="370" alt="image" src="https://github.com/user-attachments/assets/ecedeb04-15c4-4dd7-9dcd-3d8d3d8a321d" />


⚙️ Requisitos

Antes de começar, verifique se você possui:

✅ TFS (The Forgotten Server)
 compatível (versão 1.3+ recomendada)

✅ Cliente Tibia compatível com a versão do seu servidor

✅ RME – Remere’s Map Editor
 para edição de mapas

✅ Visual Studio Code
 ou outro editor de scripts

✅ Pacote de editores do OTCustom incluído neste repositório

🚀 Como Usar os Editores
🪄 1. Item Editor

Caminho: tools/ItemEditor/

Função: Criar, editar e organizar todos os itens do servidor.

Arquivos editados:

data/items/items.xml

data/items/items.otb

🔮 2. Spell Editor

Caminho: tools/SpellEditor/

Função: Criar e modificar magias (spells) facilmente.

Arquivos editados:

data/spells/scripts/*.lua

data/spells/spells.xml

👹 3. Monster Editor

Caminho: tools/MonsterEditor/

Função: Criar novos monstros e bosses, ajustar loot, skills e comportamentos.

Arquivos editados:

data/monster/*.xml

🗺️ 4. Map Editor (RME)

Caminho: tools/MapEditor/

Função: Editar mapas, spawns, casas e regiões do mundo.

Arquivos editados:

data/world/*.otbm

🧥 5. Outfit Editor

Caminho: tools/OutfitEditor/

Função: Criar e editar novas outfits, addons e aparências exclusivas.

Arquivos editados:

data/XML/outfits.xml

🧪 Dicas Importantes

Sempre faça backup dos arquivos antes de editar.

Após alterações em items.xml, spells.xml ou outfits.xml, reinicie o servidor.

Para testar rapidamente NPCs e scripts, use o comando !reload dentro do jogo.

Tenha cuidado ao editar IDs de itens e monstros – IDs duplicados podem causar crash no servidor.

🐛 Solução de Problemas
Erro	Possível causa	Solução
Item not found	ID duplicado ou inválido	Verifique items.xml e items.otb
Spell not loading	Erro de sintaxe no script	Revise a função e verifique parênteses e vírgulas
Map corrupted	Arquivo salvo incorretamente	Reabra no RME e salve novamente
NPC não responde	Script não carregado	Confirme o nome no npc.xml e no script
🤝 Contribuindo

Quer ajudar a melhorar o OTCustom?

Faça um fork deste repositório

Crie uma branch para sua modificação

Envie um pull request com suas alterações

📜 Créditos

mantido por Gabriel Vieira
📍 Lages - SC - Brasil
📧 Contato: gabrielsc.dev@gmail.com

🌐 GitHub: https://github.com/lageano

📄 Licença

Este projeto é distribuído sob a licença MIT.
Você pode usar, modificar e distribuir livremente, desde que mantenha os créditos originais.
