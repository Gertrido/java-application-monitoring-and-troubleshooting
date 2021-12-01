# Hardware
## CPU
1. Процессорная загрузка в %
2. Средняя загрузка за 5/10/15 секунд

## RAM
1. Потребление, %
2. % от свободной RAM
3. swap memory

## HDD
1. Свободное место, %
2. swap

## LAN
1. Загрузка сети, mb
2. IO per seconds

# OS

## Contrainer support
1. ???

## Process managment

1. Health check перенести на уровень приложения

## Thread management

1. Кол-во hardware-статистики по каждому потоку процесса
2. Deadlock-метрика
3. Информация по доступности потоков

## Filesystem I/O

1. Кол-во операций I/O
2. Буферизация

## Network I/O

1. Кол-во операций
2. Буферизация

# Containter

## Network virtualization

## Port mapping
1. Список открытых портов и их маппинг на внутренние

## Overlay fs

## disk image
1.  Кол-во hardware-статистики по каждому image-у

# JVM-process
## Class loading
1. Кол-во загруженные и выгруженных классов. Влияет на память

## Memory management + GC
1. Кол-во затраченной памяти
2. Heap size
3. Off-heap memory
4. Метрики GC

## Filesystem IO api
1. Native buffers

## Network I/O api

## Monitoring API
1. JMX

## Profiling API

## Debug API
1. Remote/locale debug

# Servlet Container
## App configuration context managment
1. Текущая конфигурация контейнера
2. Кол-во загруженных тредов

## Framework modules management
1. Загруженные в контейнер модули

# Application framework
## App configuration handing
## App config profiles support
## App components management
## Common scopes management
## User-defined thread pools management
## Logging management
1.  Сбор логов и отправка их в спец.движок

# Web/SOAP/REST framework
## http protocol api
1. Веб-сессии
## request routing
1. Метрики запросов и интенсивность на них
## http scopes management
## monitoring endpoint

# application
