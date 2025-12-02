## 1. Feedbacks recebidos (exemplos, adapte com o real)

- **Feedback 1 – Simplicidade da interface**
  - O representante considerou a interface simples e fácil de entender.
  - Sugeriu manter os formulários com poucos campos obrigatórios para agilizar o registro das entregas.

- **Feedback 2 – Necessidade de relatório por período**
  - Foi sugerida a possibilidade de gerar um relatório mensal com total de kg reciclados para cada tipo de resíduo.

- **Feedback 3 – Impressão dos dados**
  - Sugeriu ser útil ter opção de exportar ou imprimir o histórico de entregas para levar em reuniões com parceiros.

- **Feedback 4 – Controle de acesso**
  - Sugeriu que apenas pessoas autorizadas pudessem cadastrar pontos de coleta, enquanto outros só poderiam registrar entregas.

---

## 2. Ajustes realizados após a validação

- Implementado **dashboard** com resumo de:
  - total de usuários
  - total de pontos
  - total de entregas 
  - total de kg reciclados
  - distribuição de kg por tipo de resíduo.
- Proteção de rotas através de **login com JWT**, garantindo que apenas usuários autenticados acessem funcionalidades críticas.
- Estrutura preparada para futura exportação/relatórios (ex.: botão de exportar na página de Entregas).
