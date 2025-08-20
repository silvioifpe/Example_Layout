Android Layouts Examples

Este projeto apresenta exemplos práticos de diferentes tipos de layouts do Android: FrameLayout, LinearLayout, RelativeLayout, ConstraintLayout e RecyclerView. O objetivo é demonstrar visualmente como cada layout funciona e para que cenários é mais útil.

📌 Estrutura do Projeto

MainActivity – Menu principal que permite navegar para cada exemplo de layout.

FrameLayoutActivity – Exemplo de FrameLayout.

LinearLayoutActivity – Exemplo de LinearLayout.

RelativeLayoutActivity – Exemplo de RelativeLayout.

ConstraintLayoutActivity – Exemplo de ConstraintLayout.

RecyclerViewActivity – Exemplo de RecyclerView com lista de itens simples.

Cada Activity possui seu próprio XML de layout, organizado na pasta res/layout/.

📌 Descrição dos Layouts

O arquivo activity_main.xml funciona como o menu inicial da aplicação, reunindo botões que levam o usuário para cada tela de exemplo. Ele serve como ponto de partida para explorar os diferentes tipos de layouts disponíveis no Android.

O FrameLayout demonstra como empilhar elementos, permitindo que um fique sobre o outro. Esse layout é útil quando se deseja colocar uma imagem de fundo com textos ou ícones sobrepostos.

O LinearLayout organiza os componentes de forma linear, vertical ou horizontal, sendo prático para formulários simples, menus básicos ou listas pequenas, em que os elementos devem aparecer em sequência.

O RelativeLayout possibilita posicionar cada elemento em relação a outro ou ao contêiner pai, oferecendo flexibilidade para alinhar itens dinamicamente, como centralizar um botão abaixo de um texto.

O ConstraintLayout permite criar interfaces complexas com menos hierarquia, posicionando elementos por meio de restrições em relação a outros componentes ou às bordas do layout, sendo ideal para projetos modernos e otimizados.

A RecyclerView exibe listas ou grades de dados de forma eficiente, reciclando elementos que saem da tela para economizar memória, sendo indicada para listas grandes, como feeds de redes sociais.

📌 MainActivity

A MainActivity conecta todos esses layouts, funcionando como o controlador da navegação entre as telas. Ela gerencia os cliques nos botões do menu principal e abre cada exemplo de layout em sua respectiva atividade, garantindo a interação do usuário com a aplicação.

📌 Como Rodar

Clone o repositório:

git clone https://github.com/seu-usuario/android-layouts-examples.git


Abra o projeto no Android Studio.

Construa e rode o aplicativo em um emulador ou dispositivo físico.

Na tela principal, clique nos botões para visualizar cada layout.
