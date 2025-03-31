
<p align="center">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://avatars.githubusercontent.com/u/106863939?s=400&u=40a83beff43c48fd9e32db17621f40e129bdf9c8&v=4">
<img src="https://avatars.githubusercontent.com/u/106863939?s=400&u=40a83beff43c48fd9e32db17621f40e129bdf9c8&v=4" width=100 lt="N2O.DEV">
</picture>
</p>

<p align="center"><strong>Sokhatsky Commander, Binary Editor, TeX Processor</strong></p>

<P><b>Sokhatsky Commander</b></p>

<p>Є цілий клас файлових менеджеріву, серед яких Norton Commander, Volkov Commander (Всеволода Волкова), Demos Commander (Серія Вакуленко), Dos Navigator, Total Commander. Такі програми зручно використовати для навігації по файловій системі і впорядкуванню бібліотек. Фактично це воно (!), але:</p>

<p>
— Без залежностей, потрібно тільки C99/POSIX які є стандартом<br>
— Без використання ncurses та S-Lang, тільки termios<br>
— Модальність редагування HEX і редактор BE: Binary Editor<br>
— Маленький розмір (бінарі 35KB, рядків 1KLOC, 5 С файлів на 64KB)<br>
— Історія команд
</p>

<P><b>Binary Editor</b></p>

<p>Є цілий клас бінарних редакторів, серед яких 010 Editor, beye, hiew, Binary Ninja, WinHex, що мають окрім HEX режиму — режим дизасемблера.
Такі програми зручно використовати для дослідження ROM файлів, прошивок дронів, телефонів, BIOS, у якості систем накладання патчів,
створення map-файлу бінарного образу за допомогою текстових анотацій, а також для візуального аналізу об`єктного коду. Фактично це objdump,
але з можливістю зберігання та візуального редагування. У цій статті презентується концепт сучасного нового представника цієї когорти
редакторів — BE (Binary Editor) InfoSec Hex Editor with Disassemblers, який має наступні характеристики:</p>

<p>
— Без залежностей, потрібно тільки C99/POSIX які є стандартом <br>
— Без використання ncurses та S-Lang, тільки termios <br>
— Модальність редагування HEX з варіативною довжиною рядка <br>
— Модальність редагування ASM об`єктного коду з відображенням дизасемблера <br>
— 16, 32, 64, 128 бітні режими процесора <br>
— Маркування редагованих байтів перед збереженням, анотація регіонів <br>
— Пошук байтової послідовності, побітове редагування <br>
— Редагування секторів дисків (LBA) <br>
— Створення та накладення патчів з анотованих регіонів <br>
— Повна підтримка x86 архітектури та її розширень у дизасемблері <br>
— vi-подібна система команд та режимів <br>
— Компактне ядро з підтримкою Maс та Linux <br>
— Підтримка контейнерів обʼєктного коду ELF, Mach-O, PE/COFF <br>
— Перша лінія дизасемблерів: EM64T, RISC-V, AArch64 <br>
— Друга лінія дизасемблерів: M68K, PowerPC, MIPS, SuperH <br>
— Третя лінія дизасемблерів: PDP-11, 8080/8085/Z80/MSX, 6502/C64/Atari, HC08/HC11<br>
— Четверта лінія дизасемблерів: CLR, JVM, BEAM, EFI Byte Code</p>

Note: The development of this project and all subprojects are for learning purposes only and cannot be used for any commercial purposes. 

<P><b>Публікації</b></p>

<p>[1]. <a href="https://5ht.co/be/">Домашня сторінка проекту</a><br>
   [2]. <a href="https://tonpa.guru/stream/2020/2020-10-10 FPGA археологія.htm">FPGA археологія</a><br>
   [2]. <a href="https://tonpa.guru/stream/2022/2022-06-07 8086 XT дизасемблер.htm">XT: 8086 Дизасемблер</a><br>
   [3]. <a href="https://tonpa.guru/stream/2022/2022-06-11 A64 Disassembler.htm">ARM64: Armv9.2 Дизасемблер</a><br>
   [4]. <a href="https://tonpa.guru/stream/2020/2020-09-13 Процесори Intel.htm">Процесори Intel</a><br>
   [5]. <a href="https://game.5ht.co">Ретроконсолі</a><br>
   [6]. <a href="https://retro.5ht.co">Ретрокомпіки</a><br>
   [7]. <a href="https://top.5ht.co">Компіки Сохацького</a><br>
</p>
