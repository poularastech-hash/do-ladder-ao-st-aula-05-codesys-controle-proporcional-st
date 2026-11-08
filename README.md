# 🚀 Do Ladder ao ST - Episódio 05: Controle Proporcional (P) no CODESYS e Factory I/O

Repositório oficial do código-fonte desenvolvido para o episódio **#05** da série **Do Ladder ao ST** do canal **PoularasTech**. 

Neste projeto, resolvemos o clássico problema de *overshoot* (ultrapassagem do setpoint) e o gotejamento de válvulas no enchimento de tanques, substituindo a lógica tradicional de "Liga/Desliga" por um **Controle Proporcional (Ação P do PID)** programado em **Structured Text (ST)** no **CODESYS** e integrado em tempo real com o **Factory I/O**.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas
* **PLC / CLP:** CODESYS V3.5 (Programação em ST - Structured Text).
* **Simulador 3D:** Factory I/O (Cenário de Nível de Tanque com Válvula Proporcional).
* **Linguagem:** IEC 61131-3 Ladder ao Structured Text.

---

🎯 O que você vai aprender com este projeto?
Eliminação de Overshoot: Como fazer a válvula desacelerar suavemente conforme o nível se aproxima do setpoint.
Sintonia de Ganho ($K_p$): Como ajustar a agressividade do controlador para a dinâmica da planta virtual
Análise de Perturbação: O comportamento da malha de controle frente a perturbações externas (como a abertura da válvula de descarga) e o surgimento do erro estático (offset).

📺 Assista à Aula Completa no canal do YouTube:
👉 https://youtu.be/9u2-9xksSE0

👨‍💻 Desenvolvido por PoularasTech Mecatrônica e Automação Industrial ⚙️
