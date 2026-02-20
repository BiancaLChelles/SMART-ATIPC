# SMART ATIPC
### **S**canner e **M**anejo de **A**lexitimia **R**emotamente **T**ratada para **P**essoas **N**euroatípicas

O **SMART ATIPC** é um projeto de tecnologia assistiva que funciona como um **"Exoesqueleto Mental"**. 
Desenvolvido em Python, o sistema foi projetado para ajudar pessoas neurodivergentes (especialmente aquelas com alexitimia) a traduzir telemetria biológica — sinais físicos e sensações — em emoções identificáveis e protocolos de manejo práticos.

---


##  Sobre o Projeto

Muitas vezes, o hardware (nosso corpo) envia sinais que o software (nossa consciência) não consegue processar ou nomear. 
O **SMART ATIPC** atua como essa camada intermediária de tradução. 

Ele não apenas identifica o "bug" emocional, mas oferece **indicações de manejos cabíveis** para estabilizar o sistema e evitar shutdowns ou sobrecargas.


### Módulos do Sistema

* **`varredura_fisica.py`**: O Scanner. Recebe inputs sobre sensações táteis, térmicas e motoras (ex: "estômago vazio", "mão suada", "luz incomodando").
* 
* **`dicionario.py`**: A Base de Dados. Um dicionário expansível que mapeia termos e aprende novas sensações conforme o uso.
* 
* **`manejo.py`**: O Processador Central. Analisa a intensidade, o horário e o diagnóstico para entregar um relatório detalhado com instruções de autocuidado.

---

## Como o Sistema "Pensa"

O sistema utiliza uma lógica de **Debug Humano**. Confira alguns exemplos de diagnóstico:

> **Input:** *"Coração acelerado e mãos tremendo"*

> **Diagnóstico:** `Ansiedade / Modo de Fuga Ativado`

> **Ação de Manejo:** "FOCO NO HARDWARE: Toque em algo gelado. Respire contando até 4. Isso é uma descarga química, não é um fato real. VOCÊ ESTÁ SEGURO!"

> **Input:** *"Não consigo sair do sofá mesmo querendo muito"*

> **Diagnóstico:** `Inércia Executiva / Falha na Inicialização`

> **Ação de Manejo:** "Dê um tranco manual no motor. Execute micro-tarefas de 30 segundos para quebrar a paralisia."


---

##  Instalação e Uso

1. **Requisitos:** Ter o Python 3.x instalado em sua máquina.
2. **Clone o repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/SMART-ATIPC.git](https://github.com/seu-usuario/SMART-ATIPC.git)

## ⚙️ Instalação e Uso

1. **Requisitos:** Ter o Python 3.x instalado.
2. **Clone o repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/SMART-ATIPC.git](https://github.com/seu-usuario/SMART-ATIPC.git)
3. **Execute o programa principal:**
   ```bash
   python manejo.py

 ##  Filosofia de Desenvolvimento

Este projeto une **Pedagogia**, **Investigação** e **Programação**. 

No SMART ATIPC, seguimos estas diretrizes:

* **Stimming não é bug**, é manutenção necessária do sistema nervoso.
* **O passado é um arquivo de "apenas leitura"**; pare de tentar rodar scripts de edição em logs que já foram fechados.
* **Descanso é upgrade de performance**, nunca uma falha de produtividade.
* **Erros de sintaxe na vida acontecem:** O importante é que, mesmo com pequenos erros, já estamos entendendo muito mais do que antes.

---

## 📈 Roadmap / Próximos Passos

- [x] Mapeamento inicial de 30 estados emocionais/físicos.
- [x] Sistema de relatório dinâmico por intensidade e horário.
- [ ] Implementação de **Sensores de Hiperfoco** (alarmes de manutenção preventiva).
- [ ] Interface gráfica (GUI) customizada para redução de impacto sensorial.
- [ ] Integração total entre os módulos de diagnóstico de "bugs" físicos e mentais.

---

**Desenvolvido por um cérebro atípico para auxiliar na autonomia de outros cérebros atípicos.** 🧩
