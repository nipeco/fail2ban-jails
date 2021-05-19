# fail2ban Filters and Jails

## Introduction
I love to secure my servers with fail2ban. It's an easy way to block most brute force attacks. Among standard usecases you can even protect web applications or whatever writes logs with it. I often use nginx as webserver so paths and logs will refer to it.

This repo is a collection of jails for services I used to protect in the past. Feel free to contribute.

## List of available jails
I will only list services that are **not** included in the official package.

- WordPress [jail](jail.d/wordpress.conf) | [filter](filter.d/wordpress.conf)
- Matomo [jail](jail.d/matomo.conf) | [filter](filter.d/matomo.conf)

## License
This repo is open source software licensed under the [MIT License](LICENSE).
