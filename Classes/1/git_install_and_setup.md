Если у вас Windows, то Git можно скачать с этой страницы (для других систем есть варианты проще, см. ниже):

https://git-scm.com/downloads

Надо нажать на Windows  прямо под большой надписью Downloads (тут же можно выбрать Mac Os X и Linux/unix, если это понадобилось, а способ ниже не помог.)

Если у вас MacOs, то пишите в терминал команду git, и система начнет сама ее устанавливать.

Если y вас Linux и git не был установлен с системой, то можно его установить с помощью пакетного менеджера:
`sudo apt-get install git (для Ubuntu и Debian)`

В случае установки на Windows после запуска приложения нажать на странице лицензии "Next", в окошке с галочками, чтобы вы не выбрали, это не повлияет на изучение нашего курса, посмотрите, что вам удобнее (если любите называть/писать на русском языке, то поставьте галочку возле TrueType fonts (это внизу списка)).

Далее будет окно выбора текстового редактора:

Notepad++, возможно придется самому установить;

Nano - консольный текстовый редактор, проще vim, там подписаны действия (^? - это одновременное нажатие клавиш Сtrl и ?);

Vim – сложный, но предалагается по умолчанию (а на mac os x и linux выбрать иное не дают), да и на компьютерах на Старой Басманной он используется;

Возможно еще что-то будет предложено, но ничего сказать про это не могу.

В следующем окне выбирайте "Use Git from Windows Command Prompt", а затем в окне далее "Use OpenSSH", потом "Use the OpenSSL library", затем "Checkout as-is, commit Unix-style line endings", после "Use Windows' default console window".

В онке с тремя квадратиками советую выбрать все на всякий случай, а далее "Install".

После установки git необходимо его настроить, это делается с помощью двух команд:

`git config --global user.name "ваш логин на github"`

`git config --global user.email "почту, которую указали при регистрации на GitHub.com"`

Теперь можно переходить к работе с репозиториями.
