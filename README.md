# 🧅 Doutrinador de Fraudador ou Vendedor Chato

Um script de "doutrinação em massa" via WhatsApp Web. Ideal para lidar com tentativas de golpe, robôs de telemarketing ou aquele vendedor que não entende o que significa "não tenho interesse". 

O método? Um bombardeio pedagógico com o roteiro completo de **Shrek** (ou qualquer texto da sua escolha).

---

## ⚔️ Manual de Operações (Passo a Passo)

Se o alvo apareceu e merece a lição, siga estas coordenadas:

### 1. Preparar o Terreno
Abra o [WhatsApp Web](https://web.whatsapp.com) no seu navegador e **entre na conversa** do indivíduo que será doutrinado. O cursor deve estar pronto para digitar.

### 2. Abrir o Painel de Controle
Com a conversa aberta, acesse as ferramentas de desenvolvedor do navegador:
*   **Windows/Linux:** Pressione `F12` ou `Ctrl + Shift + I`.
*   **Mac:** Pressione `Cmd + Option + I`.

### 3. Invocando o Script
No painel que abriu (geralmente à direita), clique na aba **Console**. 
1. Copie o código do arquivo `script.js` deste repositório.
2. Cole no console.
3. Dê um **Enter** glorioso para iniciar o processo.

### 4. Manter a Guarda Alta
**Não mude de aba e não minimize o navegador** enquanto as frases estiverem sendo enviadas. O navegador precisa que a página esteja ativa para que o script continue o bombardeio.

---

## 🛡️ Regras de Engajamento

*   **Paciência de Ogro:** O script possui um *delay* (atraso) entre as frases. Isso é proposital para que o sistema do WhatsApp não te desconecte por comportamento robótico imediato.
*   **Alvo Único:** Certifique-se de que a conversa certa está selecionada. O script dispara no campo de texto que estiver focado no momento.
*   **Ética de Combate:** Este script foi criado para combater o mal (fraudes e spam invasivo). Use com sabedoria.

---

## 🛠️ Por que o script antigo parou de funcionar?
O WhatsApp Web atualizou sua estrutura (agora usa a biblioteca *Lexical*). Este script foi recalibrado para:
1.  **Simular Digitação:** Disparar o evento de `input` para que o botão de enviar "nasça" no código.
2.  **Busca por Ícone:** Encontrar o botão de envio pelo ID de teste (`data-testid="send"`) que é mais estável.
3.  **Fallback de Teclado:** Se o botão físico falhar, ele tenta forçar um "Enter" via sistema.

---

> *"As cebolas têm camadas. Os chatos também, mas a gente vai descascando uma por uma até eles desistirem."* 🧅⚔️
