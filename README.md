<div align="center">

# tlauncher-on-arch
[![stars](https://img.shields.io/github/stars/mttomaz/tlauncher-arch?color=7E9CD8&style=for-the-badge)](https://github.com/mttomaz/tlauncher-arch/stargazers)
[![issues](https://img.shields.io/github/issues/mttomaz/tlauncher-arch?color=FF5D62&style=for-the-badge)](https://github.com/mttomaz/tlauncher-arch/issues)
[![size](https://img.shields.io/github/repo-size/mttomaz/tlauncher-arch?color=76946A&style=for-the-badge)](https://github.com/mttomaz/tlauncher-arch)
[![license](https://img.shields.io/github/license/mttomaz/tlauncher-arch?color=957FB8&style=for-the-badge)](https://github.com/mttomaz/tlauncher-arch/blob/master/LICENSE)

</div>

Это репозиторий, который я создал для установки TLauncher на Arch Linux напрямую с их сайта. [site](https://tlauncher.org/).

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
