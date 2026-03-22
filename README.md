# Homework_monitoring_Zabbix2

# Домашнее задание к занятию "`Мониторинг` Zabbix-2" - `Смирнов Максим`

### Задание 1

`Шаблон был создан для параметров CPU и RAM usage, используя, соответственно, ключи:`
```
proc.cpu.util
vm.memory.size[pused]
```
`Шаблон и два параметра мониторинга в нем`
![pics/zabbix-ass1.jpg](https://github.com/turboturtle-90/Homework_monitoring_Zabbix2/blob/2d2ecf8101e5f1f40669bad9a84b4b5f92fdadff/pics/zabbix-ass1.jpg)

---

### Задание 2-3

`Интересный комментарий: пробовал прописать в конфиге агента локальный IP сервера - обе виртуалки (и сервера и агента) находились в одной локальной сети. Однако так не сработало, в логе агент писал ошибку, что к нему стучится неизвестный сервер и указывал его внешний IP. Указание в конфиге внешнего IP собственно и решило проблему`

`К хостам SmirnovMV-1 и SmirnovMV-2 добавлен кастомный шаблон Assignment1 с двумя параметрами мониоринга`
![pics/zabbix-ass2-0.jpg](https://github.com/turboturtle-90/Homework_monitoring_Zabbix2/blob/2d2ecf8101e5f1f40669bad9a84b4b5f92fdadff/pics/zabbix-ass2-0.jpg)

`А теперь добавлен также и стандартный Linux by Zabbix agent`
![pics/zabbix-ass2-1.jpg](https://github.com/turboturtle-90/Homework_monitoring_Zabbix2/blob/2d2ecf8101e5f1f40669bad9a84b4b5f92fdadff/pics/zabbix-ass2-1.jpg)

`Данные пошли`
![pics/zabbix-ass2-2.jpg](https://github.com/turboturtle-90/Homework_monitoring_Zabbix2/blob/2d2ecf8101e5f1f40669bad9a84b4b5f92fdadff/pics/zabbix-ass2-2.jpg)

`Добавленные вручную Item'ы работают`
![pics/zabbix-ass2-3.jpg](https://github.com/turboturtle-90/Homework_monitoring_Zabbix2/blob/2d2ecf8101e5f1f40669bad9a84b4b5f92fdadff/pics/zabbix-ass2-3.jpg)


---
### Задание 4


`Кастомный dashboard`
![pics/zabbix-ass4.jpg](https://github.com/turboturtle-90/Homework_monitoring_Zabbix2/blob/2d2ecf8101e5f1f40669bad9a84b4b5f92fdadff/pics/zabbix-ass4.jpg)
