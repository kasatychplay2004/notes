# Заметки
Конспекты по пути к специалисту по ИБ
Мои учебные заметки по программе «системное администрирование → информационная безопасность».
Пишу самое важное (теория+практика). Веду с июля 2026.

**Метод:** каждая тема разбирается по схеме Система → Атака → Защита → Обнаружение.

---

## Модуль 0. Фундамент

- [Системы счисления и кодировки](M0-fundamentals/01-encodings.md) — binary, hex, ASCII, Base64, URL-encoding, parser differential
- [Как ОС изолирует](M0-fundamentals/02-os-isolation.md) - Kernel space и user space, процессы и дерево процессов, виртуальная память

## Модуль 1. Сети через призму безопасности

- [Модель OSI, инкапсуляция, MTU](M1-networks/01-osi-encapsulation.md) - Семь уровней OSI, Модель TCP/IP, Инкапсуляция, MTU и фрагментация
- [TCP|UDP](M1-networks/02-tcp-udp-handshake.md) - TCP|UDP, SYN flood (атака+защита)
  
## Лабораторные работы
- [Лабораторная работа 1 - сети Wireshark](network-labs/wireshark-analysis/01-encapsulation.md) - Первое знакомство с Wireshark
- [Лабораторная работа 2 - сети Wireshark](network-labs/wireshark-analysis/01-handshake.md) - TCP флаги в Wireshark
