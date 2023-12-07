# CleverFIT

Первым делом необходимо **установить Node Version Manager (NVM)**, если он у вас еще не установлен, на вашу машину. Если он уже есть, пропускайте данный шаг.

**Для установки NVM** на **Windows** переходите по этой **[ссылке](https://github.com/coreybutler/nvm-windows/releases)**. Установите .exe-файл последней версии.

![Alt text](/public/nvm.png)

Откройте терминал и убедитесь, что установка прошла успешно.

`nvm -v`

**Для установки NVM** на **Linux и Mac** откройте терминал.

`curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh`

`export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")" [ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"`

`source ~/.bashrc`

Убедитесь, что установка прошла успешно.

`nvm -v`

|Установка и запуска проекта  |
|-----------------------------|
|nvm install 20.10.0          |
|nvm use 20.10.0              |
|yarn install                 |
|yarn start                   |

|Основные команды  |Описание                               |
|------------------|---------------------------------------|
|yarn start        |`Запуск проекта`                       |
|yarn build        |`Сборка проекта`                       |
|yarn lint         |`Запуск eslint для ts(x)/js(x) файлов` |
|yarn test         |`Запуск unit тестов vitest`                 |
|yarn cy:e2e       |`Запуск e2e тестов cypress`            |
