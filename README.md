#  Exercicios de escrever

1. São metodos que não é preciso instaciar para ser utilizado.

2. Ele define o que vai ser utilizado para determinada tarefa

3. UITableViewDataSource e UITableViewDelegate

4. numberOfRowsInSection o número de linhas na seção e cellForRowAt faz a mudança de uma celula.

5. a var e let são so utilizadas dentro do metodo e na class/struct podem ser acessadas passando elas para uma variavel externa e tipando ela com o nome da tua struct.

6.

7. São todas as partes que a view passa, antes de carregar, carregada, depois de carregada.

8. Esse método carrega ou cria uma exibição e a atribui a uma view, a View Controller chama esse método quando sua view é solicitada, mas atualmente é nil. É executado uma vez, Não é recomendado usar quando ela ja existe.

9. É chamado quando todas as Views são carregadas. É carregada uma vez no ciclo de vida da View Controller. Podemos definir layouts para view e adicionar metodos.

10. Esse método é chamado toda vez antes que a view fique visível e antes de qualquer animação ser configurada. o intuito é avisar que vai adicinar uma view.

11. Ela avisa que vai acontecer uma modificação no layout.

12. Esse método é chamado depois que o viewController se ajusta à sua subvisualização após uma alteração em seu limite. a diferença é que na viewWillLayoutSubviews ela avisa que vai ter modificação e a viewDidLayoutSubviews fez a modificação.

13. Este método é chamado após a view presente na tela, inicia a animação ou começar a reproduzir um vídeo ou som

14. Esse método é chamado antes que a exibição seja removida da hierarquia de exibição. Adicione código aqui para lidar com temporizadores e ocultar o teclado.

15. Este método é chamado depois que a View do View Controller foi removida da hierarquia, este métodos serve para parar de ouvir notificações ou sensores do dispositivo.

16. Antes de uma view controller ser removido da memória, ele é desinicializado. Enquanto o init inicializa o deinit desinicializa.

17. Quando a memória começa a ficar cheia, ele imite um aviso que você tem que limpar alguns dados da memoria para não ultrapassar o limite para que não ocorra o fechamento do app.

18. loadView, viewDidLoad, viewWillAppear, viewDidAppear

19. é importante para entedermos quais metodos terão que ser utilizados para fazer as alterações nos lugares corretos para que não tenha excesso de memoria.
