# 🖥️ Display Manager - Controle Multi-Monitor

<div align="center">

![Versão](https://img.shields.io/badge/versão-1.0.0-blue.svg)
![Python](https://img.shields.io/badge/python-3.8+-green.svg)
![Plataforma](https://img.shields.io/badge/plataforma-Windows-lightgrey.svg)
![Licença](https://img.shields.io/badge/licença-MIT-orange.svg)

**Gerenciamento profissional de múltiplos monitores para Windows**

[🚀 Download](#-download) • [📖 Funcionalidades](#-funcionalidades) • [🎯 Como Usar](INICIAR.md) • [🌍 Idiomas](#-idiomas)

![Display Manager Banner](https://img.shields.io/badge/Multi--Monitor-Control-blue?style=for-the-badge)

</div>

---

## 📋 Sobre o Projeto

**Display Manager** é uma solução completa e **100% gratuita** para gerenciamento avançado de múltiplos monitores no Windows. Se você trabalha com 2, 3, 4 ou mais monitores e está cansado de reconfigurar tudo manualmente toda vez que conecta/desconecta um monitor ou inicia um jogo, este é o software que você precisa!

### ✨ Por que usar o Display Manager?

- 🎮 **Gamers**: Configure perfis diferentes para cada jogo (ex: jogar em tela única, trabalhar com 3 monitores)
- 💼 **Profissionais**: Alterne entre configurações de trabalho e apresentação com apenas 1 clique
- 🏠 **Home Office**: Perfis diferentes para trabalho durante o dia e lazer à noite
- 🎬 **Criadores de Conteúdo**: Configurações específicas para streaming, edição de vídeo, gravação
- 🖼️ **Personalização Total**: Wallpapers diferentes em cada monitor com sistema de álbum de fotos
- ⚡ **Automação**: Lance jogos e aplique perfis automaticamente, inclusive Steam Big Picture

---

## 🚀 Funcionalidades

### 📋 **Perfis de Configuração**
- ✅ Salve configurações completas de monitores (posição, resolução, monitor primário)
- ⭐ Defina um perfil padrão para aplicar automaticamente ao iniciar o Windows
- 🔄 Alterne entre perfis com um único clique
- 💾 Exporte/importe perfis para backup ou compartilhar com amigos
- 🎵 Salve dispositivo de áudio padrão em cada perfil
- 🖼️ Wallpapers personalizados por monitor em cada perfil

### 🎮 **Launchers Inteligentes**
- 🚀 Aplique perfis automaticamente ao abrir jogos ou aplicativos
- 🖥️ **Steam Big Picture**: Monitore e aplique perfil específico quando Steam Big Picture iniciar
- 🔙 Retorne automaticamente ao perfil padrão ao fechar o aplicativo
- ⚙️ Dois métodos de detecção:
  - **BAT**: Cria um arquivo .bat que aplica o perfil e inicia o jogo
  - **Monitor**: Monitora processos do Windows e aplica quando detectar o executável

### 🖥️ **Gerenciamento Visual de Displays**
- 🎯 Visualização gráfica interativa e em tempo real dos seus monitores
- 🖱️ Arraste os monitores com o mouse para reposicionar
- 🔍 Zoom in/out na visualização para melhor precisão
- ⭐ Defina monitor primário com um clique
- 📐 Altere resolução e posição com facilidade
- 🔍 Identifique monitores fisicamente (mostra número na tela)
- 📊 Veja todas as informações: dispositivo, resolução, posição

### 🔊 **Controle de Áudio Integrado**
- 🎵 Salve dispositivo de áudio padrão em cada perfil
- 🔄 Troque automaticamente de dispositivo ao aplicar perfil
- 📋 Lista completa de todos os dispositivos de reprodução
- 🎧 Perfeito para alternar entre fones, caixas de som, headset

### 🎨 **Papel de Parede por Monitor**
- 🖼️ Defina wallpaper **diferente** para cada monitor
- 📁 **Modo álbum**: troca automática de imagens de uma pasta inteira
- 🎨 Cor sólida personalizada por monitor
- 🔄 Intervalo configurável para slideshow (5 a 3600 segundos)
- 🎲 Ordem aleatória de imagens no álbum
- 🖼️ Múltiplos estilos: Preencher, Ajustar, Esticar, Lado a lado, Centro, Expandir

### ⚙️ **Configurações Avançadas**
- 🌍 **Interface Multilíngue**: Português (Brasil) e English
- 🚀 Inicialização automática com Windows
- 📍 Minimizar para bandeja do sistema (System Tray)
- 🎯 Aplicar perfil padrão automaticamente ao iniciar
- 💾 Todas as configurações salvas automaticamente
- 🔧 Não precisa ser administrador (funciona em contas limitadas)

---

## 📥 Download

### 🎁 Versão Portátil (Recomendado)
**✨ Não requer instalação! Baixe, extraia e execute.**

1. 📦 Acesse a [página de Releases](../../releases)
2. ⬇️ Baixe `DisplayManager_Portable.zip`
3. 📂 Extraia para qualquer pasta (Desktop, Documentos, etc.)
4. ▶️ Execute `DisplayManager.exe`
5. 🎉 **Pronto! Está funcionando!**

### 📋 Requisitos do Sistema
- ✅ **Windows 10 ou 11** (64-bit)
- ✅ **Nenhum software adicional necessário**
  - Python **NÃO** precisa estar instalado
  - .NET Framework **NÃO** é necessário
  - Funciona "out of the box"
- ✅ ~20 MB de espaço em disco
- ✅ Suporta qualquer quantidade de monitores
- ✅ Funciona com AMD, NVIDIA e Intel Graphics

---

## 🎯 Como Usar

### 🚀 Início Rápido

Para um guia detalhado passo a passo, veja **[INICIAR.md](INICIAR.md)**

#### 1. **Criar um Perfil**
```
1. Abra a aba "Perfis"
2. Configure seus monitores, áudio e wallpapers como desejar
3. Clique em "💾 Salvar Perfil"
4. Digite um nome (ex: "Trabalho", "Gaming")
```

#### 2. **Aplicar um Perfil**
```
1. Selecione o perfil na lista
2. Clique em "✅ Aplicar Perfil"
3. Pronto! Tudo configurado instantaneamente
```

#### 3. **Perfil Padrão (Automático)**
```
1. Selecione um perfil
2. Clique em "⭐ Definir Padrão"
3. Será aplicado automaticamente ao iniciar o PC
```

#### 4. **Launcher para Jogos**
```
1. Vá na aba "Launchers"
2. Clique em "🆕 Novo Launcher"
3. Selecione o executável do jogo
4. Escolha o perfil a aplicar
5. O jogo aplicará o perfil automaticamente!
```

### 📖 Documentação Completa

- 📘 **[INICIAR.md](INICIAR.md)** - Guia completo em português
- 📗 **[QUICKSTART.md](QUICKSTART.md)** - Quick guide in English

---

## 🌍 Idiomas

Display Manager suporta **múltiplos idiomas** com tradução completa de toda a interface:

- 🇧🇷 **Português (Brasil)** - Idioma padrão
- 🇺🇸 **English (US)** - Full translation
- ➕ **Mais idiomas em breve!** (Espanhol, Francês, Alemão)

### Como trocar o idioma?

1. Abra a aba **"Configurações"** (ou "Settings")
2. Na seção **"🌍 Idioma / Language"**
3. Selecione o idioma desejado no dropdown
4. Clique em **"💾 Salvar Todas as Configurações"**
5. A interface muda **instantaneamente**!

---

## ❓ Perguntas Frequentes (FAQ)

<details>
<summary><b>❓ O Display Manager funciona com laptops?</b></summary>

**Sim!** Funciona perfeitamente com laptops que usam monitores externos. Você pode criar perfis para:
- Laptop sozinho (em viagem)
- Laptop + 1 monitor externo (home office)
- Laptop + 2 monitores externos (escritório)
- E qualquer combinação que imaginar!
</details>

<details>
<summary><b>❓ Preciso ter Python instalado?</b></summary>

**Não!** A versão portátil (`DisplayManager.exe`) é completamente standalone e **não requer Python** ou qualquer outra dependência. Baixe e execute!
</details>

<details>
<summary><b>❓ Funciona com placas de vídeo AMD e NVIDIA?</b></summary>

**Sim!** O Display Manager usa as **APIs nativas do Windows** (CCD - Connecting and Configuring Displays), então funciona com:
- ✅ NVIDIA GeForce
- ✅ AMD Radeon
- ✅ Intel HD Graphics / Iris
- ✅ Qualquer GPU que o Windows reconheça
</details>

<details>
<summary><b>❓ Meus perfis ficam salvos onde?</b></summary>

Na mesma pasta do programa, em arquivos JSON:
- `display_profiles.json` - Seus perfis de monitor
- `launchers.json` - Configurações de launchers
- `app_settings.json` - Configurações gerais do app

**Dica:** Faça backup desses arquivos para não perder suas configurações!
</details>

<details>
<summary><b>❓ É grátis mesmo? Tem versão paga?</b></summary>

**100% gratuito e open source!** Não tem versão paga, não tem anúncios, não tem telemetria. Use à vontade, compartilhe com amigos, modifique o código se quiser (licença MIT).
</details>

<details>
<summary><b>❓ Posso usar em ambiente corporativo/empresa?</b></summary>

**Sim!** A licença MIT permite uso comercial sem restrições. Pode instalar em todos os computadores da empresa sem problemas.
</details>

<details>
<summary><b>❓ Como reportar um bug ou sugerir funcionalidade?</b></summary>

Abra uma [Issue no GitHub](../../issues) com:
- 🐛 **Bug**: Descrição, passos para reproduzir, versão do Windows, screenshot
- 💡 **Sugestão**: Descreva a funcionalidade que gostaria de ver
</details>

<details>
<summary><b>❓ O programa consome muitos recursos?</b></summary>

**Não!** O Display Manager é extremamente leve:
- 💾 ~20 MB em disco
- 🧠 ~30-50 MB de RAM em uso
- ⚡ CPU próxima de 0% quando inativo
- Não afeta performance de jogos ou aplicativos
</details>

---

## 🎬 Casos de Uso Reais

### 🎮 Gamers
**Problema:** Jogo em tela única (monitor principal), mas trabalho com 3 monitores.

**Solução:**
1. Crie perfil "Trabalho" com 3 monitores ativos
2. Crie perfil "Gaming" com apenas 1 monitor ativo
3. Configure launcher para cada jogo aplicar perfil "Gaming"
4. Ao sair do jogo, volta automaticamente para "Trabalho"

### 💼 Profissionais
**Problema:** Apresentação em projetor requer configuração diferente.

**Solução:**
1. Perfil "Escritório" - Monitores normais
2. Perfil "Apresentação" - Monitor + projetor
3. Troca com 1 clique antes de reuniões

### 🏠 Home Office
**Problema:** Durante o dia trabalho, à noite jogo/assisto filmes.

**Solução:**
1. Perfil "Trabalho" - Dispositivo de áudio: Fone de ouvido
2. Perfil "Lazer" - Dispositivo de áudio: Caixas de som
3. Wallpapers diferentes para cada perfil

### 🎬 Streamers
**Problema:** Setup de streaming é diferente do setup de edição.

**Solução:**
1. Perfil "Stream" - Monitor de jogo + chat + OBS
2. Perfil "Edição" - Monitor principal + preview
3. Perfil "Gravação" - Configuração específica

---

## 🔒 Privacidade e Segurança

- ✅ **Nenhum dado é coletado** - Zero telemetria
- ✅ **Sem conexão com internet** - Funciona 100% offline
- ✅ **Código aberto** - Você pode auditar tudo
- ✅ **Sem instalação** - Não modifica registro (exceto se pedir início automático)
- ✅ **Portátil** - Leve em pendrive, use em qualquer PC

---

## 💝 Apoie o Projeto

Se o Display Manager te ajudou, considere:

- ⭐ Dar uma **estrela** no repositório
- 📢 **Compartilhar** com amigos que usam múltiplos monitores
- 🐛 **Reportar bugs** para melhorarmos o software
- 💡 **Sugerir funcionalidades** que gostaria de ver
- 🌍 **Traduzir** para outros idiomas

---

## 📄 Licença

Este projeto está sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para detalhes.

**TL;DR:** Você pode usar, copiar, modificar, distribuir e até vender este software. A única exigência é manter o aviso de copyright original.

---

## 👨‍💻 Créditos

Desenvolvido com ❤️ e ☕ para facilitar a vida de quem trabalha com múltiplos monitores.

**Tecnologias utilizadas:**
- Python 3.8+ (Linguagem)
- Tkinter (Interface gráfica)
- Windows CCD API (Controle de displays)
- PyInstaller (Compilação)

---

<div align="center">

### 🌟 Mostre seu Apoio

**Se este projeto te ajudou, dê uma ⭐ no repositório!**

**Compartilhe com seus amigos! 🚀**

---

**Display Manager** - *Gerenciamento profissional de múltiplos monitores*

[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github)](../../)

Made with 💻 and ☕ in Brazil 🇧🇷

</div>
