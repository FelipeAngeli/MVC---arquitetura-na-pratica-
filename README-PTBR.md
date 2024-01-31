# README - Projeto de Arquitetura MVC (Swift)


## 🚀 Sobre o Projeto

Este projeto demonstra a implementação da arquitetura Model-View-Controller (MVC) em Swift para desenvolvimento iOS. MVC é um padrão arquitetural amplamente utilizado que separa os objetos em três tipos distintos: Modelos, Visualizações e Controladores. Esta separação ajuda na gestão de aplicações complexas e aumenta a reusabilidade e escalabilidade.


## 🚀 Estrutura do Projeto

O projeto segue a estrutura padrão MVC, dividida da seguinte forma:

*  **Model**:  Representa os dados e a lógica de negócios da aplicação. É responsável por buscar, armazenar e manipular dados, frequentemente interagindo com o banco de dados ou outras fontes de dados.
*  **View**: Camada de interface do usuário. Apresenta os dados ao usuário e envia as interações do usuário para o Controller para serem processadas.
*  **Controller**: Atua como um intermediário entre o Model e a View, controlando o fluxo de dados entre eles e gerenciando as regras de negócios.


### 📋 Requisitos

*  **iOS 13.0+**
*  **Xcode 11.0+**
*  **Swift 5.0+**



### ⚙️ Configuração

Para executar este projeto, clone o repositório e abra o arquivo .xcodeproj no Xcode:

```
git clone https://github.com/FelipeAngeli/MVC---arquitetura-na-pratica-
cd SwiftArquitetura
open SwiftArquiteturas.xcodeproj

```


## ⌨️ Como Usar

1. **Modelos**: Defina seus modelos de dados na pasta Models. Eles devem encapsular a lógica de negócios e o acesso aos dados.

2. **Visualizações**:  Crie e gerencie suas interfaces de usuário na pasta Views. A visualização deve ser passiva, apenas exibindo os dados fornecidos pelo Controller.

3. **Controladores**: Implemente a lógica de controle e comunicação entre Modelos e Visualizações na pasta Controllers.

4. **Navegação**: A navegação entre as telas é geralmente gerenciada pelos Controladores.

3. **Testes**: Escreva testes unitários para cada componente para garantir a qualidade e a estabilidade do código.



## 📄 Licença

Este projeto está sob a licença (Felipe Angeli) - veja o arquivo [LICENSE.md](https://github.com/FelipeAngeli/VipCleanSwift) para detalhes.



---
