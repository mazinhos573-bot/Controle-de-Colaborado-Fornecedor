# Controle-de-Colaborado-Fornecedor
# Sistema de Cadastro – Controle Interno

Sistema simples de cadastro de colaboradores com foto facial (selfie), armazenamento local no navegador e painel administrativo básico.

**Tecnologias utilizadas:** HTML5, CSS3, JavaScript puro, Bootstrap 5.3, Font Awesome, localStorage

**Não utiliza backend / banco de dados / servidor** — tudo roda 100% no navegador do usuário.

## Funcionalidades Principais

- Cadastro de novos colaboradores com campos obrigatórios:
  - Nome completo
  - Foto facial (capturada pela câmera — **obrigatória**)
  - CPF, chave PIX, data de nascimento, e-mail, telefone/WhatsApp
- Validação simples de campos obrigatórios
- Painel administrativo protegido por senha
- Listagem de todos os cadastros salvos
- Visualização detalhada de cada registro (com foto ampliada)
- Alteração de setor (CDC / RDC / Insumo)
- Inativação de registros selecionados
- Exclusão individual ou de todos os registros
- Geração de relatório textual
- Envio direto do relatório por WhatsApp (abre o app/site)
- Interface responsiva e moderna

## Capturas de Tela

*(Adicione aqui imagens do sistema quando possível — tela de cadastro, painel admin, modal de detalhes, etc.)*

Exemplo de como ficaria:

<!-- ![Tela de Cadastro](screenshots/cadastro.png) -->
<!-- ![Painel Administrativo](screenshots/admin.png) -->

## Como Usar

1. **Baixe ou clone** este repositório
2. Abra o arquivo **`index.html`** diretamente no navegador (Chrome, Edge, Firefox, etc.)
   - Pode ser aberto via `file://` ou servido por qualquer servidor simples
3. Na aba **"Novo Cadastro"**:
   - Preencha os dados
   - Clique em **Iniciar Câmera** → **Capturar** (selfie obrigatória)
   - Clique em **Finalizar Cadastro**
4. Para acessar o painel administrativo:
   - Clique na aba **Administração**
   - Digite a senha padrão: **`admin123`**
   - **IMPORTANTE:** Altere a senha no código antes de usar em produção!

```javascript
const ADMIN_SENHA = "admin123";  // ← MUDE EM PRODUÇÃO!
