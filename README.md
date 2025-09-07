# 🎮 Game Design Document (GDD)  
## 🐱 Desvia, Gato!  

Documento de organização da proposta do jogo.  

---

## 1️⃣ Como vai ser  

- Jogo **2D**, estilo **hypercasual**, onde o jogador controla um gato que deve:  
  - **Esquivar de objetos**.  
  - **Coletar petiscos** para progredir de fase.  

- A gameplay se passa em **uma única tela com câmera fixa**.  

- Estrutura de fases: cada nível representa um cômodo da casa.  
  - **Nível 1** → Sala de Estar.  
  - **Nível 2** → Quarto.  
  - **Nível 3** → Banheiro.  

- Elementos em cena:  
  - Player (o gato).  
  - Objetos caindo do topo.  
  - Objetos horizontais que se movem pelo chão.  
  - Cenário de fundo indicando o cômodo (fase atual).  

---

## 2️⃣ Interface  

### 🏠 Menu Inicial  
- **3 botões**:  
  - Iniciar.  
  - Loja.  
  - Configurações.  

### 🎮 UI de Gameplay  
- **Parte inferior central**:  
  - 3 botões de movimento:  
    - Esquerda.  
    - Pular.  
    - Direita.  

- **Parte superior**:  
  - Nível atual.  
  - Vidas (3 corações vermelhos → ficam pretos ao perder).  
  - Contador de petiscos: **0/5 até 5/5**.  

- **Centro da tela**:  
  - Barra de progresso da fase (quando completa → avança para o próximo nível).  

---

## 3️⃣ Mecânicas  

- **Colisão com objetos** → causa **1 de dano** ao player.  
- **Objetos horizontais (chão)** → também causam dano.  
  - Exemplos: aspirador de pó, carrinho de controle remoto, patinho surfando.  

- **Petiscos** → caem junto aos objetos e podem ser coletados.  
- **Power-ups** → aparecem a cada **5 petiscos coletados**.  
  - (Ainda em definição: se será apenas 1 tipo ou vários).  

- **Fim da run** (derrota ou conclusão da fase):  
  - O jogador recebe **moedinhas** baseadas no progresso.  
  - Moedas são usadas para comprar **skins na loja**.  

- **Objetos únicos por fase**:  
  - Cada cômodo (fase) terá obstáculos próprios e característicos.  

---

📌 Esse documento é um rascunho da proposta inicial e pode ser expandido com:  
- Lista completa de power-ups.  
- Tipos de skins e progressão na loja.  
- Expansão de fases além dos 3 cômodos.  
- Sistema de ranking (local/online).  
