# CONNECTED WRITER — Protótipo

Protótipo web de um app para escritores com design sofisticado e ferramentas iniciais.

Recursos incluídos no protótipo:
- Editor rico (contentEditable) com barra de formatação
- Modo foco
- Contador de palavras e timer de escrita
- Exportar HTML
- Gerenciamento simples de projetos (localStorage)
- Design com glassmorphism e paleta escura

Pré-requisitos:
- Node.js >= 18

Como rodar:

```powershell
cd c:\Users\Aluno\Pictures\Screenshots\PAULO
npm install
npm run dev
```

Observações e próximos passos sugeridos:
- Integrar um editor mais completo (TipTap ou ProseMirror)
- Adicionar versões e histórico de documentos
- Implementar templates, análise de estilo e integração com IA
- Empacotar com Electron para desktop

Se quiser, eu continuo e:
- adiciono mais templates prontos e painel de personagens com CRUD
- integro um editor avançado (TipTap/ProseMirror) para recursos ricos
- adiciono versionamento mais robusto e diff visual de versões
- empacoto como app desktop (Electron) e configuro builds

Novas funcionalidades adicionadas neste protótipo:
 - Painel de templates aplicáveis diretamente no editor
 - Snapshots/Versões do documento (salvar/ restaurar)
 - Exportação rápida para HTML e Markdown
 - Painel lateral para personagens (visível no protótipo)

Como rodar em desenvolvimento (Windows PowerShell):

```powershell
cd c:\Users\Aluno\Pictures\Screenshots\PAULO
npm install
npm run dev
```

Para testar com Electron (após `npm install`):

```powershell
npm run start:electron
```

Observação: empacotamento e integração com TipTap exigirão instalar dependências adicionais e ajustes; posso cuidar disso no próximo passo.

 Como subir rápido (StackBlitz / CodeSandbox)
 - Opção A — Abrir o protótipo standalone (recomendado / mais rápido):
	 1. Use o arquivo `connected-writer-standalone.html` — ele roda sem Node.js.
	 2. No StackBlitz, escolha "Create Project" → "Static" → arraste e solte `connected-writer-standalone.html` ou cole o conteúdo em um `index.html`.
	 3. No CodeSandbox, escolha "Create Sandbox" → "Static" e faça o upload do arquivo.

 - Opção B — Subir o projeto completo (para testar com Vite online):
	 1. Faça upload do arquivo `connected-writer.zip` (contendo todo o repositório) em StackBlitz (opção "Upload Project") ou CodeSandbox (Upload Files).
	 2. StackBlitz pode executar o projeto automaticamente, ou você pode abrir o shell dentro do ambiente para rodar `npm install` / `npm run dev` se o ambiente suportar.

 Observações sobre importação:
 - O arquivo `connected-writer-standalone.html` é a forma mais direta de testar a interface e as ferramentas sem instalar dependências.
 - O ZIP (`connected-writer.zip`) contém o código-fonte completo (`src/`, `package.json`, etc.) para uso em ambientes que oferecem suporte a Node/Vite.

 Se quiser, eu já reembalei o projeto em `connected-writer.zip` para upload — o arquivo está no mesmo diretório do projeto.

