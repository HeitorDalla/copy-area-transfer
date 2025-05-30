# Copiar para Área de Transferência
Este é um projeto simples que permite ao usuário copiar o conteúdo de um campo de texto para a área de transferência com um clique de botão, utilizando a API `Clipboard` do navegador.

## Tecnologias utilizadas
Este projeto foi desenvolvido utilizando as seguintes tecnologias:

- **HTML** – Estrutura básica da interface ([https://html.com](https://html.com))
- **CSS** – Estilização do campo de texto e botão ([https://css.com](https://css.com))
- **JavaScript** – Lógica de cópia para a área de transferência com a API Clipboard ([https://www.javascript.com](https://www.javascript.com))

## Visualização do Projeto
https://heitordalla.github.io/copy-area-transfer/

## Funcionalidades
- Campo de texto para entrada de qualquer conteúdo
- Botão para copiar automaticamente o valor do campo para a área de transferência
- Alerta visual informando que a cópia foi realizada com sucesso
- Limpa automaticamente o campo após a cópia

## Como Usar
1. Abra o arquivo `index.html` em seu navegador.
2. Digite qualquer texto no campo de entrada.
3. Clique no botão **“Copiar”**.
4. O texto será copiado para a área de transferência e o campo será esvaziado.

## Lógica de Funcionamento
Ao clicar no botão com o ID `#copia`, um `eventListener` captura o clique.  
A função `navigator.clipboard.writeText()` é utilizada para copiar o conteúdo do campo de entrada (`#input`).  
Após a cópia, um `alert()` exibe a mensagem **"Copiado!"** e o campo de entrada é limpo.

## Pré-requisitos
- Navegador moderno com suporte à API Clipboard (Chrome, Firefox, Edge, Safari, etc.)
- Permissão do navegador para utilizar a área de transferência (em alguns navegadores, isso exige HTTPS)

## Contribuindo
Este projeto é aberto a contribuições. Sinta-se à vontade para relatar bugs, propor melhorias ou enviar pull requests.

## Contato
- Criado por **Heitor Giussani Dalla Villa**  
- E-mail: [heitorvillavilla@gmail.com](mailto:heitorvillavilla@gmail.com)  
- LinkedIn: [https://www.linkedin.com/in/heitordallavilla](https://www.linkedin.com/in/heitordallavilla)

## Observações Finais
Este projeto utiliza a API `Clipboard` nativa do navegador.  
Caso seja executado em páginas locais (`file://`), a funcionalidade pode não funcionar em todos os navegadores.  
Para evitar problemas, recomenda-se testar o projeto em ambiente `localhost` ou hospedado via HTTPS.
