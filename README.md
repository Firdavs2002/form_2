comands:

    npm install -g serve

    serve -s dist

a) было расмотренно много различных вариантов и каждый из них был по своему интересен, перебрав

все возможные варианты, я выбрал для себя самый оптимальный

b) трудности были в самом фреймворке vue, т.к. новые обновлении вышли не давно, пришлось

сначало изучить документацию, и конечно не обошлось без подводных камней :)

c) его главный не достаток навероное в том, что он не умеет общаться с сервером,

были расмотренны множество варинтов, таких как прочесть json файл, обратиться

к json-placeholder (ссылку оставлю внизу), и многое другое, в общем было решено

имитировать JSON запрос на стороне клиента, т.к. под рукой у меня не было бэкенда

и это его главная достоинство, он прост как и в логике, так и визуально, (по моему скромному мнению )

d) можно долго тестить, добавить фичу общение с сервером путём API AXIOS если мы говорим о vue

ссылка: https://jsonplaceholder.typicode.com/

    # Все исходники vue-cli находятся в архиве public
