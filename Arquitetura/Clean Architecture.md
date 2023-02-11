Clean Architecture é uma abordagem de design de software que visa separar as preocupações de uma aplicação em camadas, com o objetivo de torná-la mais fácil de manter, testar e evoluir. É uma forma de implementar o princípio "Keep it simple, stupid" (KISS) em arquitetura de software.

As camadas são organizadas em torno do núcleo da aplicação, sendo as camadas externas dependentes das camadas internas. A camada mais interna é composta por entidades de negócios, regras de negócios e casos de uso. As camadas subsequentes incluem a interface de usuário, a camada de apresentação, a camada de dados e, finalmente, as camadas de infraestrutura.

![[Uncle_Bob_Clean_Architecture.jpg]]


Isso significa que a lógica de negócios é protegida de mudanças em outras partes da aplicação, tornando-a mais fácil de manter e evoluir ao longo do tempo. Além disso, a separação clara das camadas permite que você teste cada camada separadamente, o que é uma vantagem significativa sobre outros métodos de arquitetura de software.

Em resumo, a Clean Architecture é uma forma de organizar o código de uma aplicação de maneira clara e coesa, tornando-a mais fácil de manter, testar e evoluir.

Ela é baseada em alguns princípios, incluindo:

- Independente de tecnologias: a camada mais interna do aplicativo, onde se encontra a lógica de negócios, deve ser independente de qualquer tecnologia externa, como bancos de dados ou frameworks de interface de usuário.

- Camadas concêntricas: as camadas de um aplicativo são organizadas em camadas concêntricas, com a camada mais interna sendo a mais importante e a camada mais externa sendo a menos importante.

- Dependências invertidas: as camadas externas devem depender das camadas internas e não o contrário. Isso garante que a lógica de negócios esteja sempre protegida e isolada.

- Interfaces claras: as camadas devem interagir através de interfaces claras e bem definidas, permitindo que as camadas internas possam ser substituídas ou alteradas sem afetar as camadas externas.

A Clean Architecture é uma abordagem útil para o desenvolvimento de aplicativos robustos e escaláveis, mas também pode ser um pouco complexa de se implementar. É importante ter uma compreensão clara dos princípios por trás dela e dos padrões de projeto relacionados, como o SOLID, antes de começar a aplicá-la em seus projetos.

![[Hapijs_Clean_Architecture.svg]]