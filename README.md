# SMART ATIPC
### **S**istema de **M**anejo de **A**lexitimia **R**emoto e **T**ecnológico para Neuro**atípic**as

O **SMART ATIPC** é um projeto de tecnologia assistiva que funciona como um **"Exoesqueleto Mental"**. 

Desenvolvido em Python, o sistema foi projetado para ajudar pessoas neurodivergentes (especialmente aquelas com alexitimia) a traduzir telemetria biológica — sinais físicos e sensações — em emoções identificáveis e protocolos de manejo práticos.

---


##  Sobre o Projeto

Muitas vezes, o hardware (nosso corpo) envia sinais que o software (nossa consciência) não consegue processar ou nomear. 

O **SMART ATIPC** atua como essa camada intermediária de tradução. 

Ele não apenas identifica o "bug" emocional, mas oferece **indicações de manejos cabíveis** para estabilizar o sistema e evitar shutdowns ou sobrecargas.


###  Módulos do Sistema

* **`varredura_fisica.py`**: O Scanner de Hardware. Recebe inputs sobre sensações táteis, térmicas e motoras (ex: "estômago vazio", "mão suada", "luz incomodando").
  
* **`dicionario.py`**: O Banco de Dados de Memória. Um dicionário expansível que mapeia termos e aprende novas sensações conforme o uso.
  
* **`manejo.py`**: O Processador Central. Analisa a intensidade, o horário e o diagnóstico para entregar um relatório detalhado com instruções de autocuidado.
  
* **`sensor_hiperfoco.py`**: O Vigilante. Um loop de monitoramento que atua como um timer de manutenção preventiva, disparando alertas de pausa e hidratação a cada 2 horas de atividade interrupta.


---

##  Como o Sistema "Pensa" (Exemplos de Debug)

O sistema utiliza uma lógica de **Investigação de Bugs Humanos**:

> **Input:** *"Coração acelerado e mãos tremendo"*
> **Diagnóstico:** `Ansiedade / Modo de Fuga Ativado`
> **Ação de Manejo:** "FOCO NO HARDWARE: Toque em algo gelado. Respire contando até 4. Isso é uma descarga química, não é um fato real. VOCÊ ESTÁ SEGURO!"

> **Alerta Automático:** *"Status: 2 horas de atividade detectadas"*
> **Diagnóstico:** `Risco de Esgotamento de Hardware`
> **Ação de Manejo:** "Manutenção obrigatória: Beba água, alongue o pescoço e faça uma pausa de 5 minutos."

---


##  Instalação e Uso

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
* **Funcionamento diferente ainda é funcionamento:** Não buscamos a "correção" de um padrão, mas a otimização da nossa própria arquitetura.

---


##  Roadmap / Próximos Passos

- [x] Mapeamento inicial de 30 estados emocionais/físicos.
- [x] Sistema de relatório dinâmico por intensidade e horário.
- [x] Implementação de **Sensores de Hiperfoco** (vigilante de manutenção preventiva).
- [x] Integração total entre os módulos (Scanner, Dicionário, Manejo).
- [ ] Interface gráfica (GUI) customizada para redução de impacto sensorial.


---

**Desenvolvido por um cérebro atípico para auxiliar na autonomia de outros cérebros atípicos.** 🧩
