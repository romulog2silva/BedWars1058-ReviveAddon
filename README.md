# 🛏️ BedWars1058 ReviveAddon

Um addon inovador para **BedWars1058** que oferece a funcionalidade de reviver jogadores após a morte final, trazendo mais dinâmica e possibilidades estratégicas ao jogo.

## 📋 Descrição

O **BedWars1058 ReviveAddon** é um plugin que revive automaticamente qualquer jogador que morra durante a kill final da partida de BedWars. Com configuração totalmente traduzível no `config.yml`, você pode personalizar completamente a experiência do seu servidor.

### ✨ Características

- ✅ Revive jogadores após morte final
- ✅ Configuração totalmente traduzível
- ✅ Fácil integração com BedWars1058
- ✅ Compatível com servidores Spigot/Paper
- ✅ Suportes a mensagens personalizáveis

## 🚀 Instalação

1. **Faça o download** do arquivo `.jar` da última [release](../../releases)
2. **Coloque o arquivo** na pasta `plugins/` do seu servidor
3. **Reinicie o servidor** ou execute `/reload`
4. **Configure** o arquivo `plugins/BedWars1058ReviveAddon/config.yml` conforme necessário
5. **Reinicie novamente** para aplicar as alterações

RELOAD NÃO SUPORTADO!!!

## ⚙️ Configuração

Acesse o arquivo `plugins/BedWars1058ReviveAddon/config.yml` para personalizar o plugin:

```yaml
messages:
  no-permission: "&cVocê precisa ser OP para usar este comando."
  usage: "&cUso correto: /revive <jogador>"
  player-offline: "&cO jogador não está online."
  cannot-revive: "&cEste jogador não tem um histórico de final kill ativo para ser revivido."
  not-spectating: "&cO jogador não está no modo espectador em uma partida."
  success: "&aVocê reviveu o jogador %player% com sucesso!"
  revived: "&aVocê foi revivido pelos deuses do servidor e voltou à partida!"

  gui-only-players: "&cApenas jogadores dentro do jogo podem abrir o menu."
  gui-main-title: "&8Reviver: Espectadores"
  gui-head-name: "&e%player%"
  gui-player-offline: "&cEste jogador saiu do servidor."
  gui-not-spectating: "&cEste jogador não está mais espectando a partida."
  gui-teams-title: "&8Times de: &7%player%"
  gui-team-item: "%color%Time %team%"
  gui-internal-error: "&cOcorreu um erro interno ao tentar reviver."
  gui-revived-admin: "&aVocê reviveu %player% e forçou a entrada no %color%Time %team%&a!"
  gui-revived-target: "&aVocê foi salvo pelos deuses e colocado no %color%Time %team%&a!"
```

> 💡 **Dica:** Todas as mensagens suportam cores com `&`

## 🎮 Como Funciona

1. Quando um jogador morre durante a kill final
2. O addon detecta o evento e processa o revivo
3. O jogador pode ser revivio através do comando /revive ou /revivegui

## 📦 Requisitos

- **Servidor:** Spigot 1.20+
- **Plugin:** [BedWars1058](https://www.spigotmc.org/resources/bedwars1058-1-8-1-20-5.63714/)
- **Java:** Java 17 ou superior

## 🐛 Reportar Bugs

Se você encontrou um bug, abra uma [issue](../../issues) com:

- Versão do servidor
- Versão do BedWars1058
- Descrição detalhada do problema
- Arquivo `config.yml` (se relevante)

## 💡 Sugestões

Tem uma ideia de melhoria? Abra uma [discussion](../../discussions) ou uma [issue](../../issues) com a tag `enhancement`!

## 📝 Licença

Este projeto está disponível sob a licença MIT. Veja mais detalhes em [LICENSE](LICENSE).

## 👨‍💻 Autor

Desenvolvido por **[romulog2silva](https://github.com/romulog2silva)**

---

**Aproveite o plugin e divirta-se com seus amigos no BedWars! 🎯**
