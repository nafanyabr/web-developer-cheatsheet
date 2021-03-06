# PIP

- [Описание](#описание)
- [Установка](#установка)
- [Основные команды](#основные-команды)
- [Полезные ссылки](#полезные-ссылки)

## Описание

**pip** —  система управления пакетами, которая используется для установки и управления программными пакетами, написанными на  Python. Много пакетов можно найти в Python Package Index (PyPI).

Начиная с версии Python 2.7.9 и Python 3.4, они содержат пакет  **pip**  (или **pip3** для Python 3) по умолчанию.

Большинство дистрибутивов Python уже содержат **pip**. Если **pip** отсутствует, то его можно установить при помощи системы управления пакетами или через cURL, утилиту для загрузки через интернет: Одно из главных преимуществ **pip** это простота интерфейса командной строки, которая позволяет установить пакеты Python простой командой: Так же просто и удалять пакеты: Главное, что **pip** предоставляет возможность управлять всеми пакетами и их версиями. Это обычно делается с помощью файла `requirements.txt`. Что позволяет эффективно воспроизводить весь необходимый список пакетов в отдельном окружении (например, на другом компьютере) или в виртуальном окружении.



## Установка

```bash
curl https://bootstrap.pypa.io/get-pip.py | sudo python3.6
```



## Основные команды

```bash
# Помощь по доступным командам
pip help
# установка пакета
pip install package_name
# Обновление пакета
pip install -U package_name
# При обновлении, переустановить пакет, даже если он последней версии
pip install --force-reinstall package_name
# Установка из файла requirements
pip install -r requirements.txt
# Удаление пакета
pip uninstall package_name
# Список установленных пакетов
pip list
# Информация об установленном пакете
pip show package_name
# Поиск пакетов по имени
pip search package_name
# Использование с прокси
pip --proxy user:pass@proxy.server:port
```



## Полезные ссылки

- [Документация](https://pip.pypa.io/en/stable/)
- [Python Package Index](https://pypi.org/)