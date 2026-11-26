# Agendamento para barbearia 
Aplicação para agendar serviço da Barbearia, desenvolvimento front-end com dados em uma API

##Tema e campos 

**Tema:** Agendamento para barbearia 
**Recursos na API:** "agendamentos"

Campo | Tipo | Descrição 

| Campo | Tipo | Descrição |
| :--- | :--- | :--- |
| `id` | `String` | Identificador único do agendamento |
| `cliente` | `String` | Primeiro nome do cliente |
| `Servico` | `String` | Opções fixas: corte, barba, combo, acabamento *(Obrigatório)* |
| `barbeiro` | `String` | Nome do barbeiro responsável por atender |
| `valor` | `Number` | Valor do corte |
| `datahora` | `String` | Data e hora do atendimento *(Obrigatório)* |
| `Estilo` | `String` | Preferências do estilo ou detalhes opcionais |
