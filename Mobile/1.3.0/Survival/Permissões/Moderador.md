() = Opcional
<> = Obrigatório
[] = Opcional

[Moderador] <parent: Terrariano>
**(Internos)**
/comandos | /cmds = Mostra todos os comandos disponíveis para você no servidor.
/regras = Mostra as regras de jogo do servidor.
/login <senha> = Efetua login de forma manual caso preciso.
/sair = Usado para deslogar de uma conta.
/senha <senha-atual> <nova-senha> = Usado para alterar a senha atual da conta em que está logado.
/expulsar | /kick = Usado para expulsar um jogador do servidor.
/ban = Usado para banir um jogador.
/warp = Comando para uso e gerenciamento de atalhos.
/userinfo | /ui = Usado para ver informações sobre usuários cadastrados.
/online | /jogando = Usado para ver os jogadores online no servidor.
/buff = Usado para ativar um buff em si mesmo.
/darbuff = Usado para ativar um buff em outro jogador.
*permissão para ignorar o dano* **sim**;
*permissão para ignorar a quantidade de HP/MP* **sim**;
/item = Usado para criar itens para si mesmo.
/daritem = Usado para dar itens a outros jogadores.
*permissão para usar itens bloqueados* **não**;
/invocarboss = Usado para invocar Bosses via comando no servidor.
/spawnmob = Usado para invocar Mobs via comando no servidor.
/butcher = Usado para matar todos os NPCs inimigos ou um NPC específico no servidor.
/tp = Usado para teleportar-se a outro jogador de forma imediata.
/tptrazer | /tptr = Usado para teleportar outro jogador até si de forma imediata.
/pos = Usado para ver sua posição atual no mapa.
/pos <jogador> = Usado para ver a posição atual de outro jogador no mapa.
/spawn = Usado para teleportar-se até seu ponto de spawn pessoal.
/mapspawn = Usado para teleportar-se até o ponto de spawn do mapa.
*permissão para editar construções do servidor* **sim**;
/bloodmoon = Usado para forçar a Lua de Sangue.
/hora = Usado para definir a hora do servidor.
/plantar = Usado para plantar árvores na sua posição atual.
*permissão para mover NPCs* **sim**;
/eclipse = Usado para iniciar o evento 'Eclipse' no servidor.
/luacheia = Usado para iniciar o evento 'Lua Cheia' no servidor.
/chuva [slime] <iniciar/parar>= Usado para inciar ou para a chuva no servidor.
/vento = Usado para alterar a velocidade do vendo no servidor.
/clear <item/npc/projectile> [área] = Usado para limpar certos tipo de coisas do servidor. (útil caso haja muitos itens no chão ou algum NPC apresente bug)
/pv = Usado para enviar uma mensagem privada a outro jogador.
/responder | /r = Usado para responder uma mensagme privada recebida de outro jogador.
/me = Usado para enviar uma mensagem em terceira pessoa á todos no servidor.
/godmode [jogador] = Usado para ativar o godmode em si mesmo ou em outro jogador.
*permissão para usar blocos bloqueados* **sim**;
*permissão para criar projéteis bloqueados* **sim**;
*permissão para usar itens bloqueados* **sim**;
*permissão para acessar os servidores Hardmode e Pré-Hardmode a qualquer momento* **sim**;
*permissão para compartilhamento de Construções e Objetos no servidor 'Porta 770\*'* **sim**;
*permissão parar modificar blocos e paredes protegidas* **sim**;
-----------------------------------------------------------------------------------------------------------------------
**(Estatísticas)**
/stats [jogador] = Usado para ver as suas estatísticas de jogo ou de um outro jogador.
/uic [jogador] = Usado para ver informações sobre seu usuário ou algum outro usuário.
**(TerraBank)**
-----------------------------------------------------------------------------------------------------------------------
/banco = Mostra todos os comandos bancários disponíveis.
/banco saldo (jogador) = Usado para ver o saldo bancário disponível em uma conta bancária.
/banco add|del = Usado para adicionar ou remover saldo de contas bancárias.
*perde porcentagem de dinheiro do banco ao morrer* **não**;
*ignora tempos de espera* **sim**;
*Crédito* R$5 bi = Valor de crédito para compras **loan** quando o saldo disponível for menor que o valor da compra. 
-----------------------------------------------------------------------------------------------------------------------
**(TPA)**
/tpa = Usado para teleportar-se a outro jogador.
/tpaceito | /tpac = Usado para aceitar uma solicitação de teleporte.
/tparejeito | /tpar = Usado para recusar uma solicitação de teleporte.
/tpatrazer | /tpatr = Usado para teleportar outro jogador até si mesmo.
/tpautorej = Usado para recusar solicitações de teleporte automaticamente. 
-----------------------------------------------------------------------------------------------------------------------
**(PermaBuff)**
/permabuff = Usado para adicionar um buff ao seu personagem permanentemente.
/buffcheck = Lista os permabuffs ativos no jogador específico.
/bpermabuff = Concede um permabuff ao jogador específico.
/clearbuffs = Remove todos os permabuffs.
-----------------------------------------------------------------------------------------------------------------------
**(CustomItem)**
/customitem | /citem = Usado para criar itens com valores modificados, dano, cor, etc.
/gcustomitem | /gcitem = Usado para dar itens com valores modificados, dano, cor, etc.
-----------------------------------------------------------------------------------------------------------------------
**(History)**
/historico [usuário] [tempo] [área] = Usado para visualizar o histórico de modificações feitas em um bloco ou por um jogador, no geral, ou em X tempo, em uma área proxima ou geral.
/desfazer <usuário> <tempo> [área] = Usado para desfazer modificações feitas em uma determinada área por um jogador no tempo especificado.
/refazer = Usado para desfazer as alterações da ação **/refazer**.
-----------------------------------------------------------------------------------------------------------------------
**(Proteção de Construções)**
/casa = Mostra informações sobre a proteção de casas.
/casa comandos = Mostra todos os comandos de proteção disponíveis para casas e construções.
*limite de casas* **sem limite** = Limite máximo de casas que você pode proteger por mapa.
*limite de tamanho máximo por proteção (Altura x largura)* **sem limite** = Casas que ultrapassem esse limite podem ser protegidas mais de uma vez.
-----------------------------------------------------------------------------------------------------------------------
**(Proteção de Objetos (Baús, Camas, Ferramentas Elétricas, etc))**
/protector = Mostra informações sobre a proteção de objetos.
/protector comandos = Mostra todos os comandos de proteção disponíveis para objetos.
/proteger | /pt = Usado para proteger objetos.
/desproteger | /dp = Usado para desproteger objetos.
/pinfo | /pi = Usado para ver informações sobre um objeto protegido.
/compartilhar = Usado para **compartilhar** um objeto protegido.
/descompartilhar = Usado para **descompartilhar** um objeto protegido.
/compartilharpublic = Usado para **compartilhar de forma pública** um objeto protegido.
/descompartilharpublic = Usado para **descompartilhar** um objeto **compartilhado publicamente**.
/scanbaus = Usado para procurar um ou vários itens em todos os baús do mapa.
/tpbau = Usado para teleportar-se até um dos baús encontrados por **/scanbaus**.
*limite de proteções* **sem limite** = Limite máximo de objetos que você pode proteger por mapa.
-----------------------------------------------------------------------------------------------------------------------
**(Summon Limit)**
*limite de minions* 11;
-----------------------------------------------------------------------------------------------------------------------
**(TerraStore)**
*tempo de espera* **não**;
*permissão para criar* **não**;
*permissão para editar* **não**;
*permissão para ignorar >private* **sim**;
*permissão para ignorar >espera* **sim**;
-----------------------------------------------------------------------------------------------------------------------
**(InvSee)**
/invsee = Usado para ver o inventário de um jogador. 
            Executa /invsee novamente para restaurar seu inventário.
            Executa /invsee -save para salvar as alterações feitas no inventário do jogador.
-----------------------------------------------------------------------------------------------------------------------
[Permissões-Moderador]
maxloan.5000000000, seconomy.world.bypassdeathpenalty, aliascmd.bypasscooldown, stats.others, pb.check, pb.give, pb.use, customitem, customitem.give, history.get, history.rollback, history.rollback, houseregions.housingmaster, prot.viewall, prot.nolimits, prot.useeverything, prot.scanchests, essentials.signs.nocd, essentials.signs.readall, invsee.main, invsee.save, invsee.user, tshock.admin.viewlogs, tshock.admin.kick, tshock.admin.ban, tshock.admin.warp, tshock.admin.mute, tshock.admin.seeplayerids, tshock.admin.userinfo, tshock.buff.self, tshock.buff.others, tshock.ignore.damage, tshock.ignore.hp, tshock.ignore.mp, tshock.item.give, tshock.item.spawn, tshock.npc.invade, tshock.npc.hurttown, tshock.npc.spawnmob, tshock.npc.spawnboss, tshock.npc.butcher, tshock.tp.allothers, tshock.tp.self, tshock.tp.others, tshock.tp.pos, tshock.tp.getpos, tshock.tp.npc, tshock.tp.spawn, tshock.world.time.bloodmoon, tshock.world.editregion, tshock.world.time.set, tshock.world.grow, tshock.world.movenpc, tshock.world.time.eclipse, tshock.world.time.fullmoon, tshock.world.rain, tshock.world.wind, tshock.item.usebanned, tshock.others.hardmodeallow, tshock.others.ignorebuildserver, tshock.others.bypasstw