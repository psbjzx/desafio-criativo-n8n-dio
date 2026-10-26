# 🎯 Desafio Criativo: Planejando Automações com N8N

Este repositório contém a resolução do "Desafio Criativo: Planejando Automações com N8N Usando Apenas Bons Prompts", proposto na plataforma DIO. O objetivo é criar um prompt estruturado para guiar a criação de um fluxo de automação.

## 📝 O Prompt Final

Abaixo está o prompt construído seguindo os passos de intenção, contexto e regras. Ele foi desenhado para ser enviado a uma IA, instruindo-a a criar um workflow de agendamento na área da Saúde Suplementar.

---

**Atue como um especialista em N8N.**
Crie uma automação para agendamento inteligente de consultas e exames na área de Saúde Suplementar, utilizando extração de palavras-chave.

**Público:**
Beneficiários e Clientes da clínica/plano de saúde.

**Ferramentas envolvidas:**
WhatsApp ou Telegram (para o chat), OpenAI (para interpretar a mensagem natural do cliente e extrair as palavras-chave como especialidade e horário) e Google Sheets ou Banco de Dados (para consultar e registrar a agenda).

**Fluxo:**
1. O cliente inicia a conversa no chat e o bot responde: "Olá! Como posso ajudar? Fale em poucas palavras."
2. O cliente descreve o que deseja (ex: "Marcar exame de raio x para às 13h" ou "Oftalmologista às 13h").
3. A automação interpreta a mensagem, extrai o serviço e o horário, e consulta a base de dados.
4. O bot retorna os horários disponíveis (ex: "Temos horários às 13h30, 14h e 15h") e pede confirmação com opções rápidas ("Sim", "Não" ou "Voltar").
5. Após o cliente confirmar, o sistema salva o agendamento e envia a mensagem de sucesso.

**Regras:**
- Se o serviço solicitado não existir na base, o bot deve informar o cliente e sugerir o serviço cadastrado mais próximo.
- Se o horário exato não estiver disponível, o sistema deve sugerir automaticamente os horários livres mais próximos daquele solicitado.

Explique quais nós do N8N devem ser utilizados e a lógica de funcionamento do workflow.

---

## 🛠️ Como utilizar
Este texto pode ser copiado e colado em ferramentas como ChatGPT, Claude ou Gemini para obter um guia passo a passo de como montar exatamente essa automação dentro do painel do n8n.
