# Formulário de Cadastro

Formulário de inscrição para envio de currículo, construído com HTML, CSS e JavaScript puros.

## Descrição do projeto

Este projeto apresenta um formulário de cadastro profissional que permite ao usuário preencher dados pessoais e anexar um arquivo de currículo. O formulário valida o preenchimento de todos os campos obrigatórios e exibe um modal de confirmação após o envio.

## Funcionalidades

- Campos obrigatórios para nome completo, email, telefone, LinkedIn, país e cidade
- Upload de currículo em formatos suportados: `.pdf`, `.doc` e `.docx`
- Botão de envio habilitado apenas quando todos os campos estiverem preenchidos e o arquivo for anexado
- Exibição do nome do arquivo selecionado
- Opção para remover o arquivo anexado antes do envio
- Modal de confirmação com mensagem de sucesso
- Reset do formulário ao fechar o modal

## Tecnologias usadas

- HTML5
- CSS3
- JavaScript (DOM e manipulação de eventos)

## Estrutura do projeto

- `index.html` - página principal contendo o formulário e o script inline
- `assets/css/style.css` - estilos visuais do formulário e do layout
- `assets/img/img-container.svg` - imagem decorativa usada na página

## Como usar localmente

1. Abra a pasta do projeto no seu editor ou explorador de arquivos.
2. Abra `index.html` em um navegador moderno.
3. Preencha todos os campos do formulário.
4. Anexe um currículo usando o botão `+ Anexar currículo`.
5. Clique em `Candidatar-se para a vaga` para abrir o modal de confirmação.

## Observações

- O formulário não envia dados para um servidor; a interação é feita apenas no cliente.
- O botão de envio permanece desabilitado até que todos os campos estejam preenchidos corretamente e um arquivo seja selecionado.
- O layout do projeto está preparado para ser hospedado diretamente no GitHub Pages usando a raiz do repositório.

## Melhorias possíveis

- adicionar validação de formato para email e telefone
- implementar suporte mobile aprimorado com media queries
- adicionar envio real para backend ou integração com serviço de formulário
- incluir mensagens de erro específicas para cada campo
