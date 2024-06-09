<form action="/enviar-contato" method="post">
  <label for="nome">Nome:</label><br>
  <input type="text" id="nome" name="nome" required><br><br>

  <label for="email">E-mail:</label><br>
  <input type="email" id="email" name="email" required><br><br>

  <label for="telefone">Telefone:</label><br>
  <input type="tel" id="telefone" name="telefone"><br><br>

  <label for="assunto">Assunto:</label><br>
  <select id="assunto" name="assunto" required>
    <option value="">Selecione...</option>
    <option value="reserva">Reserva</option>
    <option value="duvida">Dúvida</option>
    <option value="sugestao">Sugestão</option>
    <option value="reclamacao">Reclamação</option>
  </select><br><br>

  <label for="mensagem">Mensagem:</label><br>
  <textarea id="mensagem" name="mensagem" rows="4" required></textarea><br><br>
