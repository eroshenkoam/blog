# Почему у соседа трава зеленее?

Не знаю откуда я это знаю, но утверждаю, что человек мысли дельтами. 
Светка красивее чем Катя, BMW надежнее чем Лада, правая рука лучше левой. 

Это я к чему? Сегодня обсуждали тему того, как синхронизировать разработку тестов с разработкой продукта. 
Один из автоматизаторов предложил отводить на каждый бранч разработки бранч тестов и править тесты сразу. 

"Это не возможно" - ответил я. 
Во-первых, рузработчиков сильно больше чем тестироващиков. 
Во-вторых, еще чего-то. 
И в третьих, человек мыслит дельтами.

Лучше иметь зеленые тесты на релизной версии продукта. 
Если запускать эти тесты на каждом фиче-бранче, то можно будет увидеть то, что дельту: 
* либо мы найдем ошибку в регрессии - значит пофиксим ее в этом же PR
* либо мы найдем ошибку в тесте - значит эту функциональность легче проверить глазами/руками

Почему легче проверить галазми/руками? Потому что процесс разработки тестов - это в первую очередь процесс разработки. 
У нас для каждого нового набора тестов или исправлений отводится бранч по названию тикета и проводится код ревью. 

В общем, пока заметку написал, нужно еще будет причесать. 
