**Basics of Lists, Keyboard Control, Pong**

chr number of charcater to => string
http://www.codeskulptor.org/#examples-keyboard_echo.py

example of changing position with keys incrementally 
http://www.codeskulptor.org/#examples-position_control.py
example of changing position with timer 
http://www.codeskulptor.org/#examples-motion_explicit.py
task to change direction, change speed 

view motion slides
example of changing position with draw handler without timer 
http://www.codeskulptor.org/#examples-motion_implicit.py

view points slides
http://www.codeskulptor.org/#examples-collisions_and_reflections.py
task make the ball bounce off the right wall

we have to hit the keys a lot at the 
http://www.codeskulptor.org/#examples-collisions_and_reflections.py

new version update velocity with keys
http://www.codeskulptor.org/#examples-velocity_control.py
task make undo velocity at the keyUP handler

**Lists**

http://www.codeskulptor.org/viz/#examples_lists_mutation.py
http://www.codeskulptor.org/#examples-tips4.py

Additional material

__Когда вы выполняете присвоение, например x = 1000, создается запись словаря, которая отображает строку "x" в текущем пространстве имен на указатель на целочисленный объект, содержащий тысячу.
Когда вы обновляете "x" с помощью x = 2000, создается новый целочисленный объект, и словарь обновляется, чтобы указать на новый объект. Старая тысяча объектов не изменяется (и может быть или не быть живым в зависимости от того, ссылается ли что-нибудь еще на объект).
Когда вы выполняете новое задание, например y = x, создается новая запись слова "y" , которая указывает на тот же объект, что и запись для "x" .
Объекты, такие как строки и целые числа, неизменяемы. Это просто означает, что нет методов, которые могут изменить объект после его создания. Например, как только будет создан целочисленный объект тысяча, он никогда не изменится. Математика выполняется путем создания новых целых объектов.
Объекты, подобные спискам, изменяемы. Это означает, что содержимое объекта может быть изменено любым, что указывает на объект. Например, x = []; y = x; x.append(10); print y будет печатать [10]. Пустой список был создан. Оба "x" и "y" указывают на один и тот же список. Метод append мутирует (обновляет) объект списка (например, добавляет запись в базу данных), и результат отображается как "x" , так и "y" (так же, как обновление базы данных будет видимым для каждого подключения к этой базе данных).__



https://www.python-course.eu/passing_arguments.php
https://www.python-course.eu/python3_global_vs_local_variables.php
https://stackoverflow.com/questions/43612118/function-mutating-global-variables
https://devman.org/qna/26/v-pitone-peremennye-peredajutsja-po-ssylke-ili-po-znacheniju-est-podvodnye-kamni/
https://jeffknupp.com/blog/2012/11/13/is-python-callbyvalue-or-callbyreference-neither/


Homework template

http://www.codeskulptor.org/#examples-pong_template.py