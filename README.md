# 🗺️ Mapa ProITEC (`mod_mapaproitec`)

O **Mapa ProITEC** é um módulo de atividade para o Moodle desenvolvido especialmente para o curso autoinstrucional ProITEC do Instituto Federal do Rio Grande do Norte (IFRN).

---

## 🌐 Documentação Interativa HTML (`docs/`)

Acesse a documentação técnica rica completa em HTML com o mapa vetorial SVG interativo do RN e ilustrações:
👉 [**Documentação Técnica em HTML (`docs/index.html`)**](docs/index.html)

---

## 🚀 Funcionalidades

- **Mapa Interativo da Jornada**: Apresenta ao estudante o mapa estilizado do estado/regiões de atuação do IFRN.
- **Status Ativo/Inativo**: Permite ativar ou desativar o acesso ao mapa de acordo com o calendário pedagógico.
- **Rastreamento de Progresso**: Monitora e exibe graficamente quais pontos do mapa o aluno já visitou e quais concluiu.
- **Integração com a Gamificação**: Conecta o progresso do estudante à liberação de novos recursos no curso ProITEC.

---

## 🎨 Recursos Visuais (`pix/`)

- `mapa_ativo.svg`: Visualização completa e interativa do mapa quando liberado.
- `mapa_inativo.svg`: Estado bloqueado/inativo do mapa antes da liberação.
- `mesorregioes.png`: Ilustração das mesorregiões do Rio Grande do Norte e distribuição dos campi.

---

## 📥 Instalação

### Opção 1: Via Interface de Administração do Moodle
1. Faça o download do arquivo `.zip` da release do plugin.
2. No Moodle, acesse **Administração do site → Plugins → Instalar plugins**.
3. Envie o arquivo `.zip` e siga as instruções na tela.

### Opção 2: Instalação Manual no Servidor
1. Extraia o conteúdo deste repositório na pasta `mod/mapaproitec` da sua instalação Moodle:
   ```bash
   cd /caminho/do/seu/moodle/mod
   git clone git@github.com:proitec-moodle-suite/moodle-mod_mapaproitec.git mapaproitec
   ```
2. Acesse **Administração do site → Notificações** (ou execute `php admin/cli/upgrade.php`) para finalizar a instalação no banco de dados.

---

## 👥 Autores e Contribuidores

- **Kelson da Costa Medeiros** (<kelson.medeiros@ifrn.edu.br> / <kelsoncm@gmail.com>)
- **Matheus Mathias Rocha Lúcio de Moraes** (<mathias.matheus76@gmail.com>)

---

## 📜 Licença

Este plugin é software livre distribuído sob os termos da **GNU General Public License v3.0** (GPL-3.0). Veja o arquivo [LICENSE.md](LICENSE.md) para mais detalhes.
