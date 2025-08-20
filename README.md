O arquivo activity_main.xml funciona como o menu inicial da aplicação, reunindo botões que levam o usuário para cada tela de exemplo. Ele serve como ponto de partida para explorar os diferentes tipos de layouts disponíveis no Android.

O frame_layout_example.xml demonstra o uso do FrameLayout, um tipo de layout que empilha os elementos, permitindo que um fique sobre o outro. Esse recurso é especialmente útil em cenários em que se deseja colocar uma imagem de fundo com textos ou ícones sobrepostos.

Já o linear_layout_example.xml apresenta o LinearLayout, responsável por organizar os componentes de forma linear, seja vertical ou horizontalmente. Esse tipo de layout é bastante prático para formulários simples, menus básicos ou listas pequenas em que os elementos devem aparecer em sequência.

O relative_layout_example.xml mostra o RelativeLayout, que possibilita posicionar cada elemento em relação a outro ou ao próprio contêiner. Esse tipo de organização oferece maior flexibilidade e é útil em casos em que se precisa alinhar itens de forma dinâmica, como posicionar um botão à direita de um texto ou centralizar um elemento em relação à tela.

Por sua vez, o constraint_layout_example.xml demonstra o ConstraintLayout, considerado o mais moderno e eficiente. Ele permite a criação de interfaces complexas com menos níveis de hierarquia, pois cada elemento é posicionado por meio de restrições em relação a outros componentes ou às bordas do layout. Isso torna o aplicativo mais otimizado e é a escolha recomendada para novos projetos.

Por fim, o recycler_view_example.xml apresenta a RecyclerView, que não é apenas um layout, mas um componente avançado usado para exibir listas ou grades de dados de forma eficiente. Diferente de listas comuns, a RecyclerView recicla os elementos que saem da tela, economizando memória e garantindo melhor desempenho, sendo ideal para listas grandes como feeds de redes sociais.

A MainActivity conecta todos esses layouts, funcionando como o controlador da navegação entre as telas. Ela gerencia os cliques nos botões do menu principal e abre cada exemplo de layout em sua respectiva atividade, garantindo a interação do usuário com a aplicação.
