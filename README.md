# Relatorio POO
Marketplace Virtual de Placas Solares

Nosso projeto é um marketplace destinado a usuários e fornecedores de painéis solares.
O projeto foi desenvolvido usando em grande parte a IDE BlueJ para suporte ao ambiente de desenvolvimento integrado (IDE) usado para prototipagem e testes iniciais, com suporte para linguegem Java para a implementação da lógica de negócios e operações de CRUD. UML para a modelagem e design do sistema por meio do plant.txt. GIT DESKTOP este meio para criar algumas necessidade no GitHub. VSCODE foi usado mais como teste e curiosidade no seu funcionamento para desenvolvimento de código e visualização de códigos em formato fxml.

O objetivo é permitir que qualquer cliente acesse a plataforma e forneça suas especificações e requisitos desejados para um projeto. Essas informações são então apresentadas a fornecedores cadastrados, que respondem com propostas para avaliação dos clientes. Embora o projeto tenha um grande potencial, o resultado atual é um esqueleto com funcionalidades básicas, devido ao tempo limitado e à necessidade de aprendizado das ferramentas e da linguagem pelos desenvolvedores, que são novos em algumas dessas tecnologias.

O diagrama UML foi criado antes do início do projeto, em colaboração com o grupo, para orientar todos os membros sobre a direção a seguir. No decorrer do projeto, buscamos a melhor maneira de realizar os cálculos de modo mais simples e geral possível. Todas as classes foram desenvolvidas utilizando o BlueJ.

Rodrigo e Eduardo, ficaram responsáveis pela parte do banco de dados SolarOrcamentos que foi feita em linguagem MySQL, onde foi projetado para permitir uma expansão futura, com uma estrutura clara que facilita a adição de novas funcionalidades. Eu fiquei com afunção do front-end onde o profissional desenvolvedor front-end é o responsável por colocar em prática, através de códigos, o design de um site ou interface. Izadora ficoucom Back-end de modelos abstratos e interfaces, ela me orientou a seguir a narrativa que Eduardo na mesma linha de raciocínio, pois as atividades eram semelhantes, além de me orientar que o artigo postado deveria ser editado dando uma ideia mais concreta, onde cada aspecto era citado de forma instrutiva demais, me ajudou com a instalação, manutenção e manipulação do Github Desktop, GitLab e Visual Studio Code.

Foi projetado para gerenciar informações sobre os clientes, lojas parceiras e produtos em uma plataforma de orçamentos para painéis solares. Ele é composto por quatro tabelas principais de clientes que armazena informações sobre os clientes, incluindo nome, email, telefone e CPF. O email e o CPF são únicos para evitar duplicidades. Lojas parceiras que contém dados sobre lojas parceiras, como nome e CNPJ, que também é único, onde tem uma correlação com outra tabela (Produtos). Produtos com lista de produtos disponíveis nas lojas parceiras, com detalhes como nome, preço e descrição. Cada produto está vinculado a uma loja específica através de uma chave estrangeira. Orcamentos que registram os orçamentos realizados, associando cada um a um cliente e a uma loja parceira, com campos para valor total e data do orçamento. O banco de dados é estruturado para permitir fácil expansão e assegura a integridade referencial através do uso de chaves estrangeiras e restrições de unicidade. As restrições de unicidade nos campos de email, CPF e CNPJ garantem a integridade dos dados. O uso de chaves estrangeiras assegura a integridade referencial entre as tabelas. Com essa configuração, é possível gerenciar eficientemente as operações relacionadas aos orçamentos de painéis solares, garantindo um fluxo de dados consistente e confiável.

No decorrer do projeto, busquei a melhor maneira para criar uma interface gráfica e view em Java para o marketplace de placas fotovoltaicas descrito, onde podemos utilizar a biblioteca Swing, que é uma das mais comuns para interfaces gráficas em Java. Criei uma estrutura básica para a interface gráfica que inclui as principais funcionalidades descritas no projeto, como simulação de sistemas de placas solares, cadastro de usuários, busca de empresas e páginas de produtos. de modo mais simples e geral possível, para que os objetivos de representação visual da interface com base no projeto, descreva como seria o design dessa interface em Java Swing e, em seguida, fornecer um exemplo de código que pode usar para visualizar e testar a interface. A maior dificuldade enfrentada na construção do modelo de resolução foi o processo de construção. A estrutura do projeto teve, tela principal que apresenta o menu principal e acesso às funcionalidades do sistema. Tela de simulação que permite aos usuários simular sistemas de placas solares. Tela de cadastro de usuários que permite que os usuários se cadastrem e gerenciem suas informações. Tela de busca de empresas que permite que os usuários busquem e comparem empresas especializadas. Tela de página de produtos que exibe informações detalhadas sobre os produtos e um código exemplo de como você pode estruturar a interface gráfica usando Java Swing. Tivemos que consertar pequenos bugs e erros de compilação, no uso classes diferentes aos usuais para ajudar a consertar problemas de implementação, de classe que apenas deveriam determinar tipos de climas e ambientes, assim como pequenos problemas como a falta de variáveis que tinham no contrato, mas que ao escrever os códigos esquecemos, devido ao volume de classes e detalhes a serem lembrados para evitar alguns problemas acerca de compilação e sintaxe.

Os proximos passos de implementar lógica de backend seriam: 
Integrar com APIs de energia solar, sistemas de pagamento e banco de dados para armazenar e processar informações.
Melhorar a Interface: Adicionar funcionalidades avançadas, como gráficos de desempenho de energia, filtros de busca, e mais.
Testar e Refinar: Realizar testes rigorosos e ajustar a interface de acordo com o feedback dos usuários.
Este exemplo fornece uma base inicial, mas pode-se expandi-lo e personalizá-lo de acordo com as necessidades do projeto.

Para criar uma interface gráfica e view em Java que represente o marketplace de placas fotovoltaicas, fizemos uma representação visual da interface com base no projeto. Vou descrever como seria o design dessa interface em Java Swing que poderiase usar para visualizar e testar a interface.
Estrutura da Interface Gráfica
Tela Principal
Menu Principal com botões para navegar entre as principais funcionalidades: Simulação, Cadastro de Usuário, Busca de Empresas e Página de Produtos.
Tela de Simulação
Campos para entrada de dados: Localização, Área Disponível e Consumo de Energia.
Botão para calcular a simulação e exibir resultados.
Tela de Cadastro de Usuário
Campos para Nome, Email e Senha.
Botão para cadastrar usuário.
Tela de Busca de Empresas
Campo para buscar empresas por nome ou localização.
Botão para realizar a busca e mostrar resultados.
Tela de Página de Produtos
Área de Texto para exibir informações detalhadas sobre produtos.
Botão para obter mais informações sobre o produto.
Descrição Visual da Interface
Tela Principal
Botões dispostos verticalmente para cada funcionalidade.
Tela de Simulação
Labels e TextFields para inserir dados.
Botão para calcular.
Tela de Cadastro de Usuário
Labels e TextFields para informações do usuário.
Botão para realizar o cadastro.
Tela de Busca de Empresas
Label e TextField para buscar empresas.
Botão para buscar.
Tela de Página de Produtos
Label e TextArea para detalhes do produto.
Botão para mais informações.
Por fim o modelo ficou pronto e foram executados alguns testes com o intuito de validar os resultados, usando como base de comparação um simulador.
