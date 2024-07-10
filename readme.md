## Desafio de Frontend - Lista de psicologos

### Objetivo

Desenvolver uma aplicação utilizando Next.js 14 que consuma uma API de psicologos (exemplo em `psicologos.json`) e exiba uma lista de psicologos com a possibilidade de visualizar detalhes de cada psicologo, utilizando Server Components e estilização com Tailwind CSS.

**Utilize o projeto do Figma como base de layout:**

https://www.figma.com/design/NIN7Om6EKH4dAuRghWejak/Teste-Front-End-%7C-Psi-do-Futuro?node-id=0-1&m=dev

### Requisitos

- Página Principal:

  - Exibir uma lista de psicologos obtidos a partir de uma API REST (você pode simular um RestAPI com base em `psicologos.json`). Cada psicologo deve exibir: nome, preço e uma imagem. Ao clicar em um psicologo, o usuário deve ser redirecionado para a página de detalhes desse psicologo.

- Página de Detalhes (/psi/[id]):

  - Exibir informações detalhadas do psicologo selecionado, incluindo nome, preço, descrição, imagem e outras informações relevantes.
  - Utilizar Server Components para renderização dos detalhes do psicologo, aproveitando a capacidade de carregamento paralelo de dados.

- Integração com API:

  - Utilizar Server Components para buscar os dados dos psicologos de forma eficiente.

- Componentização e Estilização:
  - Componentizar a exibição de lista de psicologos e de detalhes de psicologo.
    Utilizar Tailwind CSS para estilização, aproveitando suas classes utilitárias para um desenvolvimento mais ágil e consistente.

### Boas Práticas:

- Tratamento de erros ao carregar dados da API.
- Responsividade para diferentes tamanhos de tela.
- Garantir acessibilidade na aplicação.

### Advanced (opcional):

- Implementar paginação dinamica na lista de psicologos usando virtualização (como react-window).

- Adicionar calendário para agendamento de sessão (vide exemplo no Figma)

- Implementar testes unitários.

### Avaliação

Durante a avaliação do teste, serão considerados os seguintes aspectos:

- Organização do Projeto: Estrutura de pastas e arquivos claros e bem definidos.

- Qualidade do Código: Legibilidade, boas práticas de programação e padrões de codificação.

- Integração com API utilizando Server Components: Eficiência no carregamento dos dados e aproveitamento dos recursos do Next.js 14.

- Componentização e Reutilização: Uso adequado de componentes para melhorar a modularidade e reutilização.
- Estilização com Tailwind CSS: Utilização eficiente das classes utilitárias do Tailwind para estilização responsiva e esteticamente agradável.

- Funcionalidades Extra: Implementação de funcionalidades opcionais demonstra capacidade de ir além do básico.
- Documentação: Comentários pertinentes e documentação clara, se necessário.

### Observações

Server Components do Next.js 14 oferecem uma nova abordagem para renderização eficiente e paralela de componentes, otimizando a performance da aplicação.

Tailwind CSS permite um desenvolvimento rápido e consistente de interfaces, aproveitando suas classes utilitárias.
Espero que este desafio ajustado atenda às suas expectativas, combinando Server Components com Tailwind CSS para uma solução moderna e eficiente!

**Ao terminar o projeto subir teste em alguma empresa de hospedagem gratuita (Vercel e etc), e enviar o código fonte para avaliação.**

### Fase Final

Após o envio chamaremos você para uma call onde você deverá apresentar seu projeto e as tomadas de decisões tomada em cada ponto, não existe certo e nem errado apenas para entender sua linha de pensamento.

Boa sorte!
