# Домашнее задание
+ Взять стенд https://github.com/erlong15/vagrant-bind
+ Добавить еще один сервер client2
+ Завести в зоне dns.lab имена
+ web1 - смотрит на клиент1 
+ web2 смотрит на клиент2
+ Завести еще одну зону newdns.lab
+ Завести в ней запись
+ www - смотрит на обоих клиентов
+ Настроить split-dns
+ Клиент1 - видит обе зоны, но в зоне dns.lab только web1
+ Клиент2 видит только dns.lab
+ Настроить все без выключения selinux*
+ Формат сдачи ДЗ - vagrant + ansible

