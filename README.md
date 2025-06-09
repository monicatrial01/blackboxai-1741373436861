# blackboxai-1741373436861
Built by https://www.blackbox.ai

## Agendamento de sobrancelhas

Este repositório possui um pequeno app web para agendamento de atendimentos em uma empresa de designer de sobrancelhas.

Abra o arquivo `index.html` em um navegador e utilize o formulário para registrar novos agendamentos (nome, data e hora). Os agendamentos são salvos no `localStorage` do navegador e aparecerão listados na página, podendo ser removidos pelo botão **Excluir**.

## Servidor HTTP simples

Para acessar a página externamente, rode o servidor embutido em Python:

```bash
python3 serve.py
```

Isso iniciará o serviço em `http://localhost:8080`, onde o arquivo `index.html` poderá ser acessado em qualquer navegador.
