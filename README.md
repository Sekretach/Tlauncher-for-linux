<div align="center">

## Тлаунчер на Арч линукс
[![stars](https://img.shields.io/github/stars/Sekretach/tlauncher-on-arch-ru?color=7E9CD8&style=for-the-badge)](https://github.com/Sekretach/Tlauncher-on-arch-ru/stargazers)
[![issues](https://img.shields.io/github/issues/Sekretach/tlauncher-on-arch-ru?color=FF5D62&style=for-the-badge)](https://github.com/Sekretach/tlauncher-on-arch-ru/issues)
[![size](https://img.shields.io/github/repo-size/Sekretach/tlauncher-on-arch-ru?color=76946A&style=for-the-badge)](https://github.com/Sekretach/tlauncher-on-arch-ru)
[![license](https://img.shields.io/github/license/Sekretach/tlauncher-on-arch-ru?color=957FB8&style=for-the-badge)](https://github.com/Sekretach/Tlauncher-on-arch-ru/blob/main/LICENSE)

</div>

Это репозиторий, который я перевел: [оригинальный репозиторий](https://github.com/mttomaz/tlauncher-arch/) для установки TLauncher на Arch Linux напрямую с их сайта. [site](https://tlauncher.org/).

> [!warning]
> Этот скрипт — всего лишь инструмент для облегчения загрузки TLauncher.
> Использование TLauncher осуществляется исключительно на ваш страх и риск. Я не несу ответственности
> за любые проблемы, которые могут возникнуть при использовании TLauncher [this](https://github.com/Sekretach/Tlauncher-for-linux/issues/1#issue-3206354638) issue.

## Установка
Введите эту команду в терминал чтоб установить TLauncher:

```bash
curl -fsSl https://raw.githubusercontent.com/mttomaz/tlauncher-arch/master/install.sh | sh
```

## Запуск
После установки, Надо написать `tlauncher` в терминал чтоб запустить tlauncher.

Если хотите обновить напиши в терминал `tlauncher --update` или `tlauncher -u` для загрузки последней версии tlauncher _(Это не лучший способ, но на данный момент сойдет)_.
Если вы хотите удалить TLauncher из своей системы, введите `tlauncher --remove` или `tlauncher -r`, после чего файлы tlauncher будут удалены, и вы сможете удалить пакеты Java и/или $HOME/.tlauncher dir
