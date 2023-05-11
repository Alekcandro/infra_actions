# infra_actions
Учебный проект для изучения работы GitHub Actions (Яндекс Практикум)

Сделайте fork репозитория с проектом infra-actions — зайдите на его страницу и нажмите кнопку Fork:

В вашем аккаунте на GitHub появится новый репозиторий — infra_actions.
Клонируйте репозиторий на локальную машину. Для этого в терминале выполните такие команды:
# Перейти в папку, созданную для проекта
cd .../Dev/
# Клонировать репозиторий
... Dev/$ git clone git@github.com:<ваш_username>/infra_actions.git  
Создайте и активируйте виртуальное окружение, установите в него зависимости:
... Dev/$ cd infra_actions

# Для Windows
... Dev/infra_actions$ python -m venv venv && . venv/Scripts/activate
(venv) ... Dev/infra_actions$ pip install -r requirements.txt 