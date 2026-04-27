
| Характеристика        | UrBackup                        | Veeam CE                                          |
| --------------------- | ------------------------------- | ------------------------------------------------- |
| Версия Windows Server | Windows Server 2016/2019/2022   | Windows Server 2016/2019/2022/2025                |
| CPU                   | minimum 2 cores                 | minimum 8 cores                                   |
| RAM                   | minimum 4 Gb                    | 16 GB RAM plus 500 MB RAM for each concurrent job |
| ROM                   | minimum  32 ГБ(нет  информации) | 5 ГБ + 4,5 ГБ (.NET)                              |
| Файловая система      | NTFS                            |                                                   |
| Сеть                  | 1 Гбит/с                        | 1 Гбит/с                                          |
Источники:
- https://helpcenter.veeam.com/docs/vbr/userguide/system_requirements_backup_server.html?ver=13 (тут насчет диска лучше у  Veeam посмотреть)
- https://vinfrastructure.it/2025/11/veeam-backup-replication-13-is-now-also-for-windows/
- https://forums.urbackup.org/t/what-are-the-minimum-requirements-hardware-and-software/10710
- https://www.urbackup.org/administration_manual.html#x1-160003.1 (документация 22 года, думаю, что по винсервер 25 года поддержки нет, как будто также urbackup  может делать резервные копии vhd)


| Характеристика | Windows Server  2022            |
| -------------- | ------------------------------- |
| RAM            | minumum 2Gb for GUI             |
| CPU            | minimum 4-8 cores(НЕ СЧИТАЯ ПО) |
| ROM            | minimum 32Gb                    |
| Network        | 1 Гбит/с                        |

## Порты
#### UrBackup
![](../images/Аппаратные%20требования%20для%20UrBackup,%20Veeam%20CE-27.04.2026-19_04.png)

![](../images/Аппаратные%20требования%20для%20UrBackup,%20Veeam%20CE-27.04.2026-19_04-1.png)
#### Veeam
https://helpcenter.veeam.com/docs/vbr/userguide/used_ports.html?ver=13 -  veeam