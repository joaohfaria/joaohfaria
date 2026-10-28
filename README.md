# João Henrique

Estou aprendendo desenvolvimento de software com foco em Python e back-end, construindo projetos para firmar os fundamentos de programação.

## Estudando no momento

- Fundamentos de Python
- Desenvolvimento web com Flask (rotas, templates, sessões)
- SQL e SQLite
- Autenticação e hash de senhas
- Git e GitHub
- Organização de código e boas práticas

## Projetos

### Oficina — Sistema de Agendamento Online

Aplicação web que permite ao cliente de uma oficina mecânica agendar um serviço pela internet, no lugar do agendamento por telefone anotado à mão.

Feito com Python, Flask, SQLite e HTML. O cliente escolhe o serviço e um horário disponível, e o servidor valida o pedido antes de salvar: não aceita data passada, atende apenas em horário comercial (segunda a sexta, com intervalo de almoço), não permite dois agendamentos no mesmo horário e recusa serviço que a oficina não oferece. O funcionário entra com login e senha para ver a agenda, com as senhas guardadas como hash.

Os horários disponíveis são gerados a partir do horário de funcionamento da oficina, então mudar a agenda não exige mexer no código.

Estou construindo para a oficina onde trabalho, então as regras vêm de como o negócio funciona de verdade.

Em desenvolvimento.

### DevManager

Gerenciador de tarefas em linha de comando, feito em Python.

As tarefas têm ID, título, descrição, prioridade e status, e ficam salvas num arquivo JSON para não se perderem entre uma execução e outra. Tem validação de entrada e tratamento de erros para dados inválidos e arquivo ausente.

O projeto começou guardando tudo apenas na memória. Depois de perceber que as tarefas sumiam ao fechar o programa, implementei a persistência em JSON — e foi assim que aprendi manipulação de arquivos e tratamento de erros na prática.

## Próximos passos

- Deploy
- APIs REST e endpoints em JSON
- Testes automatizados com pytest
- JavaScript no front-end
