# Задача 1

Реализовать  функции  вычисления  площади  под  графиком  функции _y  =  sin(x)_  на  произвольном отрезке _[a, b]_, где _0 <= a < b <= Pi_
- используя метод средних прямоугольников
- по составной формуле Симпсона

Реализовать  функцию,  которая  будет  принимать  на  вход  массив  целых  чисел,  являющихся количеством  прямоугольников  в  каждом  из  экспериментов  и  возвращающую  массив  строк  вида: “кол-во  значение1  значение2”.

При  этом  значения  площадей  округлить  до  пяти  знаков  после запятой.
Вызвать  указанную  функцию  из  main()  с  параметром  [5,  10,  20,  100,  500,  1000]  и  вывести получившиеся значения на консоль.
Снимок экрана с результатом работы программы приложить к пулреквесту в ветку main.

### Памятка по работе с Git и GitHub:
1. Склонировать репозиторий на компьютер
    `$ git clone ...`
    `cd ...`
1. Создать и перейти в ветку, в которой будете работать, например,  *work*
    либо `$ git switch -c work`
    либо `$ git branch work` и `$ git switch work`
1. Добавить свой код в папку `src/`
1. Зафиксировать изменения
    `$ git add ...` и `$ git commit`
1. Отправить изменения в удалённый репозиторий
    `$ git push ...`
    После этого во вкладке Actions в GitHub можно увидеть статус выполнения открытых тестов
1. Выпонить Pull Request из ветки *work* в ветку *main*
    Если открытые тесты выполнились успешо, заголовок Pull Request'а не содержит *WIP*, не выставлена метка *wip*, описание непусто (т.е все проверки прошли успешно), ваша ветка не конфликтует с *main*, Вы **самостоятельно** выполняете merge этого Pull Request'а.
1. После добавления Ваших изменений в *main*, будет выполнен запуск закрытых тестов. Статус выполнения ваших тестов можно посмотреть в [тестирующей системе](https://github.com/spbu-coding-2023/1-grading-system) в соответствующем Вашему репозиторию Pull Request'е.
    > Важно: этот Pull Request появляется не сразу.
1. После прохождения скрытых тестов в Вашем репозитории в комментариях к Pull Request *Feedback* преподаватель оставит комментарии по Вашему решению.
