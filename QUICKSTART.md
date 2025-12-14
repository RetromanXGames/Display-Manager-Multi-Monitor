# 🚀 Display Manager - Guia de Início Rápido

> **Guia completo passo a passo para usar o Display Manager pela primeira vez**

---

## 📑 Índice

1. [🎯 Primeiro Uso](#-primeiro-uso)
2. [📋 Gerenciando Perfis](#-gerenciando-perfis)
3. [🎮 Configurando Launchers](#-configurando-launchers)
4. [🖥️ Ajustando Displays](#️-ajustando-displays)
5. [🔊 Configurando Áudio](#-configurando-áudio)
6. [🎨 Personalizando Wallpapers](#-personalizando-wallpapers)
7. [⚙️ Configurações Avançadas](#️-configurações-avançadas)
8. [💡 Dicas e Truques](#-dicas-e-truques)

---

## 🎯 Primeiro Uso

### 1. Baixando e Executando

1. **Baixe o arquivo** `DisplayManager_Portable.zip` da [página de Releases](../../releases)
2. **Extraia** para qualquer pasta (ex: `C:\Apps\DisplayManager\`)
3. **Execute** `DisplayManager.exe`
4. **Pronto!** A interface abrirá automaticamente

> 💡 **Dica:** Não precisa instalar nada. O programa roda direto do executável!

### 2. Interface Principal

Ao abrir, você verá **6 abas** na parte superior:

- 📋 **Perfis** - Salvar e aplicar configurações
- 🚀 **Launchers** - Automação de perfis para jogos
- 🖥️ **Displays** - Configurar monitores
- 🔊 **Áudio** - Dispositivos de reprodução
- 🎨 **Papel de Parede** - Wallpapers por monitor
- ⚙️ **Configurações** - Opções gerais e idioma

---

## 📋 Gerenciando Perfis

### 🆕 Criar seu Primeiro Perfil

#### Passo 1: Configure como Deseja
1. Vá na aba **"Displays"** e configure seus monitores
2. Vá na aba **"Áudio"** e selecione dispositivo de saída
3. *Opcional:* Vá na aba **"Papel de Parede"** e personalize cada monitor

#### Passo 2: Salve o Perfil
1. **Clique no botão** `💾 Salvar Perfil` (topo da janela)
2. **Digite um nome** descritivo:
   - ✅ Bom: "Trabalho", "Gaming", "Netflix", "Apresentação"
   - ❌ Evite: "Perfil1", "Teste", "aaa"
3. **Clique em OK**
4. 🎉 **Perfil criado!** Aparecerá na lista da aba "Perfis"

### ✅ Aplicar um Perfil

**Método 1: Manual**
1. Abra a aba **"Perfis"**
2. **Clique no perfil** que deseja aplicar (ex: "Gaming")
3. **Clique no botão** `✅ Aplicar Perfil`
4. Aguarde 2-3 segundos
5. ✨ **Pronto!** Configuração aplicada

**Método 2: Perfil Padrão (Automático)**
1. **Selecione um perfil** na lista
2. **Clique no botão** `⭐ Definir Padrão`
3. **Confirme** a ação
4. 🔄 Este perfil será aplicado automaticamente:
   - Ao **iniciar** o Display Manager
   - Ao **sair** de jogos (se configurado em Launchers)

### ✏️ Renomear um Perfil

1. **Selecione o perfil** na lista
2. **Clique em** `✏️ Renomear`
3. **Digite o novo nome**
4. **OK**

### 🔄 Atualizar um Perfil

Se você alterou a configuração de monitores e quer **salvar no perfil existente**:

1. **Configure** monitores/áudio como deseja
2. **Selecione o perfil** na lista
3. **Clique em** `🔄 Atualizar`
4. **Confirme**
5. ✅ Perfil atualizado com as novas configurações!

### 🗑️ Excluir um Perfil

1. **Selecione o perfil** na lista
2. **Clique em** `🗑️ Excluir`
3. **Confirme** a exclusão
4. ⚠️ **Cuidado:** Ação irreversível!

---

## 🎮 Configurando Launchers

**Launchers** aplicam perfis **automaticamente** ao abrir jogos ou aplicativos.

### 🎯 Caso de Uso Exemplo

**Situação:** Você trabalha com 3 monitores, mas joga em tela única.

**Solução:**
1. Crie perfil "Trabalho" (3 monitores)
2. Crie perfil "Gaming" (1 monitor)
3. Configure launcher para o jogo usar perfil "Gaming"
4. Ao abrir o jogo → aplica "Gaming" automaticamente
5. Ao fechar o jogo → volta para "Trabalho" automaticamente

### 🆕 Criar um Launcher

1. **Abra a aba** "Launchers"
2. **Clique em** `🆕 Novo Launcher`
3. **Preencha o formulário:**

   **Nome:**
   ```
   Digite um nome para identificar (ex: "Elden Ring", "Cyberpunk 2077")
   ```

   **Executável:**
   ```
   Clique em "📂 Procurar" e selecione o .exe do jogo
   Exemplo: C:\Games\EldenRing\Game\eldenring.exe
   ```

   **Perfil:**
   ```
   Selecione qual perfil aplicar (ex: "Gaming")
   ```

   **Método:**
   - **BAT (Recomendado para Steam/Epic/GOG):**
     - Cria um arquivo `.bat` que você executa no lugar do jogo
     - Aplica perfil → Abre jogo → Aguarda fechar → Volta ao perfil padrão
   
   - **Monitor (Recomendado para atalhos/lançadores):**
     - Monitora processos do Windows
     - Quando detecta o `.exe`, aplica o perfil automaticamente
     - Não precisa executar pelo .bat

4. **Clique em** `💾 Salvar`

### 📝 Exemplo Prático: Configurar Elden Ring

```
Nome: Elden Ring
Executável: C:\Program Files (x86)\Steam\steamapps\common\ELDEN RING\Game\eldenring.exe
Perfil: Gaming
Método: BAT
```

**Como usar:**
1. Launcher criará: `Elden Ring.bat` na pasta do Display Manager
2. Execute `Elden Ring.bat` em vez de abrir pelo Steam
3. Perfil "Gaming" será aplicado automaticamente
4. Jogo abrirá
5. Ao fechar, volta ao perfil padrão

### 🖥️ Steam Big Picture

**Para aplicar perfil automaticamente quando Steam Big Picture abrir:**

1. **Vá na seção** "🎮 Steam Big Picture Monitor"
2. **Selecione um perfil** no dropdown (ex: "TV Mode")
3. **Clique em** `💾 Salvar`
4. **Clique em** `▶️ Iniciar Monitor`
5. **Status mudará para** "🟢 Ativo"

**Pronto!** Sempre que Steam Big Picture abrir, o perfil será aplicado automaticamente.

Para desativar:
- Clique em `⏸️ Parar Monitor`

---

## 🖥️ Ajustando Displays

### 📊 Visualização Gráfica

A aba **"Displays"** mostra seus monitores em tempo real:

- 🖱️ **Arraste** monitores para reposicionar
- 🔍 **Scroll** para zoom in/out
- 🎯 **Clique** em um monitor para selecioná-lo

### ⭐ Definir Monitor Primário

1. **Selecione o monitor** na lista OU na visualização gráfica
2. **Clique em** `⭐ Definir como Principal`
3. ✅ Monitor marcado como primário (barra de tarefas aparecerá nele)

### 📐 Alterar Resolução

1. **Selecione o monitor** na lista
2. **Clique em** `🎯 Alterar Resolução`
3. **Escolha a resolução** desejada (ex: 1920x1080, 2560x1440)
4. **OK**
5. **Confirme** para manter a nova resolução

### 📍 Alterar Posição

**Método 1: Visual (Recomendado)**
1. **Arraste o monitor** na visualização gráfica
2. **Solte** na posição desejada
3. **Confirme** para aplicar

**Método 2: Manual**
1. **Selecione o monitor**
2. **Clique em** `📍 Alterar Posição`
3. **Digite X e Y** (coordenadas)
4. **OK**

### 🔍 Identificar Monitores

Se você não sabe qual é o "Monitor 1", "Monitor 2", etc:

1. **Clique em** `🔍 Identificar Monitores`
2. **Número grande** aparecerá em cada tela física
3. Agora você sabe qual é qual!

---

## 🔊 Configurando Áudio

### 🎵 Trocar Dispositivo de Áudio Padrão

1. **Abra a aba** "Áudio"
2. **Lista mostrará** todos os dispositivos de reprodução:
   - Fones de ouvido
   - Caixas de som
   - Headset USB
   - Saída HDMI de monitores
   - Etc.
3. **Selecione o dispositivo** desejado
4. **Clique em** `⭐ Definir como Padrão`
5. ✅ Dispositivo configurado!

### 🎧 Salvar Áudio em Perfis

**Os perfis salvam automaticamente o dispositivo de áudio ativo no momento!**

**Exemplo:**
```
1. Selecione "Fones de ouvido" como padrão
2. Salve perfil "Trabalho"
   → Perfil salva: Monitores + Fones de ouvido

3. Selecione "Caixas de som" como padrão
4. Salve perfil "Lazer"
   → Perfil salva: Monitores + Caixas de som

Ao aplicar "Trabalho" → Troca para fones
Ao aplicar "Lazer" → Troca para caixas de som
```

---

## 🎨 Personalizando Wallpapers

### 🖼️ Modo: Imagem Única

**Para definir uma imagem fixa em um monitor:**

1. **Selecione o monitor** na lista esquerda
2. **Escolha modo** `🖼️ Imagem`
3. **Clique em** `📂 Procurar`
4. **Selecione a imagem** (JPG, PNG, BMP)
5. **Escolha o estilo:**
   - **Preencher** - Cobre tela inteira (pode cortar)
   - **Ajustar** - Cabe inteira na tela (pode ter barras)
   - **Esticar** - Estica para caber (pode distorcer)
   - **Lado a lado** - Repete em mosaico
   - **Centro** - Centraliza sem redimensionar
6. **Clique em** `✅ Aplicar`

### 📁 Modo: Álbum (Slideshow)

**Para trocar imagens automaticamente de uma pasta:**

1. **Selecione o monitor**
2. **Escolha modo** `📁 Álbum (Slideshow)`
3. **Clique em** `📁 Procurar` (Pasta)
4. **Selecione a pasta** com suas fotos
5. **Defina o intervalo** (ex: 30 segundos, 5 minutos)
6. **Marque** `🔀 Ordem aleatória` se quiser embaralhar
7. **Escolha o estilo** (Preencher, Ajustar, etc.)
8. **Clique em** `✅ Aplicar`

### 🎨 Modo: Cor Sólida

**Para definir uma cor pura no monitor:**

1. **Selecione o monitor**
2. **Escolha modo** `🎨 Cor Sólida`
3. **Clique no seletor de cor**
4. **Escolha a cor** desejada
5. **OK**
6. **Clique em** `✅ Aplicar`

### 💾 Salvar Configuração de Wallpapers

**Para salvar wallpapers no perfil ativo:**

1. Configure wallpapers de todos os monitores
2. **Clique em** `💾 Salvar Configuração`
3. Wallpapers salvos no perfil atual!

Agora ao aplicar este perfil, os wallpapers também serão aplicados!

### 🔄 Restaurar Padrão

**Para voltar ao wallpaper padrão do Windows:**

1. **Clique em** `🔄 Restaurar Padrão`
2. **Confirme**
3. Voltará ao wallpaper que estava antes do Display Manager

---

## ⚙️ Configurações Avançadas

### 🌍 Trocar Idioma

1. **Abra a aba** "Configurações" (ou "Settings")
2. **Seção** "🌍 Idioma / Language"
3. **Selecione:**
   - **Português** - Interface completa em português
   - **English** - Full interface in English
4. **Clique em** `💾 Salvar Todas as Configurações`
5. ✨ Interface muda instantaneamente!

### 🚀 Iniciar com Windows

**Para o Display Manager abrir automaticamente ao ligar o PC:**

1. **Marque** `Iniciar automaticamente com o Windows`
2. **Clique em** `💾 Salvar Todas as Configurações`
3. ✅ Configurado! Aparecerá no registro do Windows

**Para desativar:**
- **Desmarque** a opção
- **Salve** as configurações

### 📍 Minimizar para Bandeja (System Tray)

**Para o app ficar na bandeja do relógio quando minimizado:**

1. **Marque** `Minimizar para bandeja do sistema (System Tray)`
2. **Salve** as configurações

**Opções adicionais:**
- `Iniciar minimizado na bandeja` - App inicia escondido
- `Minimizar para bandeja ao fechar` - Clicar X minimiza (não fecha)

### 🎯 Aplicar Perfil Padrão ao Iniciar

**Para aplicar perfil padrão automaticamente ao abrir o app:**

1. **Marque** `Aplicar perfil padrão ao iniciar o app`
2. **Salve** as configurações
3. Certifique-se de ter um perfil marcado com ⭐ (definido como padrão)

---

## 💡 Dicas e Truques

### 🎯 Perfil para cada Situação

**Crie perfis específicos:**
```
📋 Trabalho        → 3 monitores, fones, wallpaper produtivo
🎮 Gaming          → 1 monitor, headset, wallpaper do jogo
📺 Netflix/Filmes  → TV como principal, caixas de som
🎬 Streaming       → Monitor de jogo + chat + OBS
✈️ Portátil        → Apenas tela do laptop
```

### 🔄 Workflow Recomendado

1. **Configure** como sempre usa (trabalho padrão)
2. **Salve** como perfil "Principal"
3. **Marque como padrão** (⭐)
4. **Crie perfis específicos** para casos especiais
5. **Configure launchers** para jogos

### 🎮 Dica para Gamers

**Se você joga vários jogos:**
1. Crie perfil "Gaming Fullscreen" (1 monitor)
2. Crie perfil "Gaming Windowed" (múltiplos monitores)
3. Configure launcher para cada jogo

**Exemplo:**
```
FPS (CS:GO, Valorant) → Gaming Fullscreen
MMO (WoW, FF14)       → Gaming Windowed (para ver Discord)
RPG (Elden Ring)      → Gaming Fullscreen
```

### 💼 Dica para Profissionais

**Home Office + Escritório:**
```
🏠 Home Office → 2 monitores externos + laptop
🏢 Escritório  → 3 monitores + docking station
☕ Café        → Apenas laptop
```

Troque com 1 clique ao mudar de ambiente!

### 🖼️ Dica para Wallpapers

**Organize suas pastas:**
```
C:\Wallpapers\
  ├── Trabalho\     (imagens inspiradoras)
  ├── Gaming\       (artes de jogos)
  ├── Natureza\     (paisagens relaxantes)
  └── Anime\        (wallpapers de anime)
```

Cada perfil pode ter pasta diferente em slideshow!

### ⌨️ Atalho Rápido

**Crie atalho na área de trabalho:**
1. Botão direito em `DisplayManager.exe`
2. **Enviar para** → **Área de trabalho (criar atalho)**
3. Renomeie para "Display Manager"

**Ou fixe na barra de tarefas:**
1. Arraste `DisplayManager.exe` para barra de tarefas
2. Acesso com 1 clique!

### 🔧 Backup de Configurações

**IMPORTANTE:** Faça backup dos arquivos JSON!

```
Copie estes arquivos para local seguro:
- display_profiles.json  (seus perfis)
- launchers.json         (seus launchers)
- app_settings.json      (configurações)
```

Se formatar o PC ou trocar de computador, copie de volta!

---

## 🆘 Solução de Problemas

### ❓ Perfil não está aplicando

**Verifique:**
1. Monitores estão conectados?
2. Drivers de vídeo atualizados?
3. Windows reconhece os monitores? (Configurações do Windows)

### ❓ Launcher não está funcionando

**Método BAT:**
- Execute o arquivo `.bat` criado
- Não execute o jogo direto

**Método Monitor:**
- Verifique se o caminho do executável está correto
- Inicie o monitor antes de abrir o jogo

### ❓ Wallpaper não muda

**Verifique:**
1. Caminho da imagem/pasta está correto?
2. Arquivo é JPG, PNG ou BMP?
3. Você tem permissão para ler o arquivo?

### ❓ Áudio não troca

**Verifique:**
1. Dispositivo está conectado e funcionando?
2. Windows reconhece o dispositivo?
3. Perfil foi salvo com o dispositivo correto?

---

## 📞 Precisa de Ajuda?

- 📖 Leia o [LEIA-ME.md](LEIA-ME.md) completo
- 🐛 [Reporte bugs no GitHub](../../issues)
- 💡 [Sugira funcionalidades](../../issues)
- ❓ Veja as [Perguntas Frequentes](LEIA-ME.md#-perguntas-frequentes-faq)

---

<div align="center">

**🎉 Agora você domina o Display Manager!**

**Aproveite seus múltiplos monitores ao máximo! 🖥️🖥️🖥️**

---

[⬅️ Voltar para LEIA-ME](LEIA-ME.md)

</div>
