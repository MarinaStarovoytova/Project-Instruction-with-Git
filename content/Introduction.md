[//]: # ( Введение в Git )

[< Назад](/readme.md)

# Git

В 2005 году, Линус Торвальдс разработал GIT для управления версиями ядра Linux, однако, чуть позднее его поддержкой занялся другой человек, японский инженер-программист — Джунио Хамано. На сегодняшний день, GIT — это одна из самых известных систем контроля версий с открытым исходным кодом, на которую полагаются миллионы проектов по всем миру (включая как коммерческие, так и бесплатные проекты). GIT — это полностью бесплатное программное обеспечение, поддерживающее множество ОС, таких как Mac, Linux, Windows. Вот несколько функций GIT достойных упоминания:

1. Распределенная система управления версиями, GIT следует принципу одноранговой сети — peer to peer (равный к равному) в отличии от других систем вроде Subversion (SVN), которая основана на модели client-server (клиент-сервер).

2. GIT позволяет разработчикам иметь множество совершенно независимых веток кода. Создание, удаление и объединение этих веток происходит без каких-либо проблем и больших затрат времени.

3. В GIT все операции атомарны; это означает, что любое действие может быть полностью удачным или провалиться (без каких-либо изменений). Это действительно важно, так как в некоторых системах контроля версий (вроде CVS), где действия не атомарны, некоторые повисшие операции по всему хранилищу, могут оставить его в нестабильном состоянии.

4. В отличии от других VCS, таких как SVN или CVS где метаданные хранятся в скрытых папках (.cvs, .svn, и т.д.), в GIT все данные расположены в каталогах .git.

5. Он использует модель данных, которая помогает обеспечить криптографическую целостность всего, что присутствует в репозитории. Каждый раз когда файлы добавляются или коммитятся, генерируются их контрольные суммы; аналогичный процесс происходит при их извлечении.

6. Еще одна превосходная функция, присутствующая в GIT — это его индекс. В пределах индекса, разработчики могут форматировать коммиты и просматривать их до фактического применения.

Он довольно прост в использовании. Для начала, вы можете либо создать новое хранилище, либо добавить существующее. После установки, команда `git init` поможет вам с настройкой нового хранилища, или команда `git clone` поможет настроить пользователя для работающей копии локального хранилища.
