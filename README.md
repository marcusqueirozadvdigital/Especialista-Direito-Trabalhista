# ⚖️ Especialista Trabalhista & Calculista

Sistema de IA especializado em direito trabalhista brasileiro, com duas funcionalidades principais:

- **Calculista** — Chat para cálculos trabalhistas (rescisão, horas extras, reflexos, liquidação, atualização monetária, INSS, IRRF)
- **Peças Processuais** — Gerador de mais de 30 tipos de peças (reclamação, contestação, recursos, tutelas, embargos, etc.)

---

## 🚀 Como publicar no GitHub Pages

### 1. Crie um repositório no GitHub
- Acesse [github.com](https://github.com) e clique em **New repository**
- Nome sugerido: `especialista-trabalhista`
- Deixe como **Public**
- Clique em **Create repository**

### 2. Faça upload do arquivo
- Clique em **uploading an existing file**
- Arraste o arquivo `index.html` para a área de upload
- Clique em **Commit changes**

### 3. Ative o GitHub Pages
- Vá em **Settings** → **Pages** (menu lateral esquerdo)
- Em **Source**, selecione **Deploy from a branch**
- Em **Branch**, selecione `main` e pasta `/ (root)`
- Clique em **Save**

### 4. Acesse o sistema
- Em alguns minutos seu site estará disponível em:
  `https://SEU_USUARIO.github.io/especialista-trabalhista`

---

## 🔑 Chave da API Anthropic

O sistema usa a API da Anthropic (Claude). Você precisa de uma chave:

1. Acesse [console.anthropic.com](https://console.anthropic.com)
2. Crie uma conta ou faça login
3. Vá em **API Keys** → **Create Key**
4. Copie a chave (começa com `sk-ant-...`)
5. Cole no campo que aparece no topo do sistema ao acessar

> **Segurança:** A chave fica salva no `localStorage` do seu navegador e **não é enviada para nenhum servidor** além da API da Anthropic.

---

## ✨ Funcionalidades

### Calculista (chat)
- Cálculo de rescisão sem/com justa causa
- Horas extras e reflexos (DSR, férias, 13º, FGTS, aviso-prévio)
- Liquidação de sentença
- Atualização monetária (IPCA-E + SELIC, ADC 58/59)
- Insalubridade e periculosidade
- Impugnação aos cálculos
- Súmulas e OJs do TST
- INSS e IRRF trabalhista
- Diferenças salariais, comissões, reflexos

### Peças Processuais
**Ações Principais:** Reclamação Trabalhista, Consignação em Pagamento, Ação de Cumprimento, Inquérito para Apuração de Falta Grave, Dissídio Coletivo

**Liquidação & Execução:** Liquidação de Sentença, Execução Trabalhista, Embargos à Execução, Impugnação aos Cálculos, Embargos de Terceiro, Exceção de Pré-Executividade

**Tutelas & Cautelares:** Tutela de Urgência, Tutela de Evidência, Produção Antecipada de Provas, Protesto Judicial, Arresto/Sequestro

**Ações Constitucionais:** Mandado de Segurança, Reclamação Constitucional

**Ações Especiais:** Ação Rescisória, Ação Anulatória, Homologação de Acordo Extrajudicial, Ação Civil Pública

**Recursos:** Recurso Ordinário, Recurso de Revista, Agravo de Petição, Agravo de Instrumento, Embargos de Declaração

**Defesa do Reclamado:** Contestação, Contrarrazões, Parecer Técnico-Contábil

---

## 🛠️ Tecnologias

- HTML5 + CSS3 + JavaScript puro (sem frameworks)
- API Anthropic (Claude claude-sonnet-4-20250514)
- Tabler Icons
- 100% client-side — nenhum backend necessário

---

## 📄 Licença

Uso pessoal e profissional. Proibida a revenda.
