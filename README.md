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
4. **Configure** o arquivo `plugins/BedWars1058-ReviveAddon/config.yml` conforme necessário
5. **Reinicie novamente** para aplicar as alterações

## ⚙️ Configuração

Acesse o arquivo `plugins/BedWars1058-ReviveAddon/config.yml` para personalizar o plugin:

```yaml
# Ativar/Desativar o addon
enabled: true

# Mensagem ao reviver um jogador
revive-message: "§a&Player foi revivido!"

# Delay para reviver (em ticks)
revive-delay: 20

# Som ao reviver
sound:
  enabled: true
  type: "ENTITY_RESURRECT"
```

> 💡 **Dica:** Todas as mensagens suportam cores com `&` (ex: `&a` para verde, `&c` para vermelho)

## 🎮 Como Funciona

1. Quando um jogador morre durante a kill final
2. O addon detecta o evento e processa o revivo
3. O jogador é revivido automaticamente
4. Uma mensagem personalizável é exibida a todos

## 📦 Requisitos

- **Servidor:** Spigot 1.17.1+ ou Paper
- **Plugin:** [BedWars1058](https://www.spigotmc.org/resources/bedwars1058-1-8-1-20-5.63714/)
- **Java:** Java 11 ou superior

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