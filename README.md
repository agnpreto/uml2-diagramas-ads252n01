# UML 2 – Catálogo de Diagramas · Turma ADS252N01

Repositório colaborativo da turma **ADS252N01**.
Prof. Aguinaldo Neto.

Em aula estudamos os diagramas de **Caso de Uso**, **Classe** e **Sequência**. Cada grupo apresentou um dos outros diagramas da UML 2. Agora cada grupo vai **publicar o seu trabalho aqui**, para que este repositório se torne um catálogo completo dos diagramas da UML, construído pela turma.

## Grupos e diagramas

| # | Diagrama | Grupo | Situação |
|---|---|---|---|
| 1 | [Diagrama de Atividades](01-diagrama-de-atividades/) | Rêmulo, Eduardo, Yasmim e Renan | ⏳ pendente |
| 2 | [Diagrama de Estados (Máquina de Estados)](02-diagrama-de-estados/) | Thomas, Luiz, Bruno e Bruno | ⏳ pendente |
| 3 | [Diagrama de Componentes](03-diagrama-de-componentes/) | Jany, Jamili e Ruan | ⏳ pendente |
| 4 | [Diagrama de Implantação (Deployment)](04-diagrama-de-implantacao/) | Pedro, Genesis, Kelvin e Erbeson | ⏳ pendente |
| 5 | [Diagrama de Objetos](05-diagrama-de-objetos/) | Gabriel, Gabriel, Luiz e Adília | ⏳ pendente |
| 6 | [Diagrama de Pacotes](06-diagrama-de-pacotes/) | João, Sidney, Jully e Gabriella | ⏳ pendente |
| 7 | [Diagrama de Comunicação (Colaboração)](07-diagrama-de-comunicacao/) | Walter, Mayara e Luana | ⏳ pendente |
| 8 | [Diagrama de Visão Geral de Interação](08-diagrama-de-visao-geral-de-interacao/) | Paulo, Augusto e Lucas | ⏳ pendente |

> Clique no nome do diagrama para abrir a pasta do grupo.

## O que cada grupo entrega

Dentro da **pasta do seu grupo** (e somente nela):

| Arquivo | Conteúdo |
|---|---|
| `README.md` | Já existe um modelo na pasta: preencha todas as seções. |
| `apresentacao.pdf` | A apresentação feita em sala, exportada em PDF. |
| `diagrama.png` | O exemplo prático do grupo, em imagem. |

Regras:

- **Cada integrante faz pelo menos 1 commit** com a própria conta do GitHub. O histórico mostra a participação de cada um.
- Mensagens de commit claras, por exemplo: `Adiciona definição e quando usar`, `Inclui exemplo prático`.
- Não altere arquivos de outros grupos nem o README principal.
- A entrega é feita por **Pull Request**. Só o professor faz o merge.

## Passo a passo

### 1. Fork (só um integrante do grupo)

1. Entre neste repositório e clique em **Fork** (canto superior direito) → **Create fork**.
   Uma cópia do repositório é criada na sua conta.
2. No seu fork, vá em **Settings → Collaborators → Add people** e adicione os colegas do grupo pelo nome de usuário do GitHub.
   Cada colega precisa aceitar o convite que chega por e-mail.

### 2. Adicionar os arquivos (todos os integrantes)

**Pelo navegador (mais simples):**

1. No fork, abra a pasta do seu grupo.
2. Para enviar arquivos: **Add file → Upload files**, arraste o PDF ou a imagem, escreva a mensagem do commit e clique em **Commit changes**.
3. Para editar o README: abra o arquivo, clique no ícone de lápis, preencha, escreva a mensagem do commit e clique em **Commit changes**.

**Pelo terminal:**

```bash
git clone https://github.com/SEU-USUARIO/uml2-diagramas-ads252n01.git
cd uml2-diagramas-ads252n01/0X-pasta-do-grupo
# coloque os arquivos e edite o README.md
git add .
git commit -m "Adiciona exemplo prático do diagrama"
git pull      # traz os commits dos colegas antes de enviar
git push
```

### 3. Pull Request (um integrante, quando tudo estiver pronto)

1. No fork, clique em **Contribute → Open pull request**.
2. Título: `Grupo X – Nome do diagrama` (exemplo: `Grupo 3 – Diagrama de Componentes`).
3. Preencha o checklist que aparece na descrição e clique em **Create pull request**.
4. Acompanhe os comentários do professor. Se ele pedir ajustes, faça novos commits no fork: eles entram automaticamente no mesmo Pull Request.

## Avaliação

| Critério | O que será observado |
|---|---|
| Conteúdo | README completo: definição, quando usar, notação, exemplo e comparação |
| Exemplo prático | Diagrama autoral, legível, com a notação correta |
| Uso do Git | Commits de todos os integrantes, mensagens claras, só a pasta do grupo alterada |
| Pull Request | Título no padrão e checklist preenchido |
