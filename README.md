# TechTaste

TechTaste é um projeto desenvolvido como parte da **Imersão Mobile** da **Alura**, com o objetivo de criar uma experiência digital interativa e acessível para os apaixonados por tecnologia. O projeto foi criado utilizando **Flutter**, o framework da Google para desenvolvimento de apps móveis nativos.

Este repositório contém o código-fonte do aplicativo **TechTaste** e serve como exemplo para quem está aprendendo a construir aplicativos com Flutter.

## Créditos

O projeto foi desenvolvido durante a **Imersão Mobile** da [Alura](https://www.alura.com.br/). O objetivo da imersão foi ensinar as melhores práticas para o desenvolvimento de apps móveis com o Flutter. A Alura é uma plataforma de cursos online renomada, voltada para tecnologia, com uma metodologia prática e de alta qualidade.

## Tecnologias Utilizadas

- **Flutter**: Framework da Google para criar aplicativos móveis nativos para iOS e Android usando uma única base de código.
- **Dart**: Linguagem de programação utilizada pelo Flutter para desenvolvimento de aplicativos.
- **Git**: Sistema de controle de versão distribuído utilizado para gerenciar o código-fonte.
- **GitHub**: Plataforma de hospedagem de código-fonte e controle de versões.

## Instalação

Para rodar o projeto localmente, siga os passos abaixo:

1. **Clone este repositório**:

    ```bash
    git clone https://github.com/erickatilladev/TechTaste.git
    ```

2. **Acesse o diretório do projeto**:

    ```bash
    cd TechTaste
    ```

3. **Instale as dependências do Flutter**:

    Se você ainda não tem o Flutter instalado, siga as instruções na [documentação oficial do Flutter](https://flutter.dev/docs/get-started/install).

    Para instalar as dependências do projeto:

    ```bash
    flutter pub get
    ```

4. **Execute o aplicativo**:

    Se você tem um emulador Android ou iOS, pode rodar o app com o comando:

    ```bash
    flutter run
    ```

    Caso esteja utilizando um dispositivo físico, certifique-se de que o dispositivo está conectado e visível no Flutter. O comando irá compilar e rodar o app no dispositivo.

## Funcionalidades

- **Interface do usuário moderna e intuitiva** com o uso de Widgets do Flutter.
- **Responsividade**: O app se adapta bem a diferentes tamanhos de tela.
- **Tela inicial** com informações sobre o aplicativo.
- **Navegação** entre diferentes seções do app utilizando o **Navigator** do Flutter.
  
## Estrutura do Projeto

A estrutura do projeto é organizada da seguinte forma:

TechTaste/ ├── lib/ # Código-fonte principal │ ├── ui/ # Interfaces de usuário (screens, widgets) │ ├── models/ # Modelos de dados utilizados no app │ └── main.dart # Ponto de entrada do aplicativo ├── assets/ # Arquivos estáticos como imagens, fontes e ícones ├── test/ # Testes unitários e de integração ├── pubspec.yaml # Arquivo de configuração do projeto, onde as dependências são listadas ├── .gitignore # Arquivo para ignorar arquivos que não devem ser versionados ├── README.md # Este arquivo └── LICENSE # Licença do projeto


- **lib/**: Contém o código-fonte do aplicativo.
- **assets/**: Contém imagens, fontes e ícones utilizados no app.
- **test/**: Contém os testes unitários e de integração do app.
- **pubspec.yaml**: Arquivo responsável pelo gerenciamento de dependências do Flutter.
- **README.md**: Este arquivo de documentação.

## Como Contribuir

Se você quer contribuir para esse projeto, siga estas etapas:

1. **Faça um fork** deste repositório.
2. **Crie uma nova branch** para a sua feature:

    ```bash
    git checkout -b minha-feature
    ```

3. **Faça suas modificações** no código.
4. **Adicione e faça commit das alterações**:

    ```bash
    git add .
    git commit -m "Descrição da feature ou bug fix"
    ```

5. **Faça o push** da sua branch para o repositório remoto:

    ```bash
    git push origin minha-feature
    ```

6. **Abra um Pull Request** explicando as alterações que você fez e como elas melhoram o projeto.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Autor

Feito por **Erick Atilla** - [GitHub](https://github.com/erickatilladev)

---

Feito com 💻 e 💡 durante a **Imersão Mobile** da Alura.
