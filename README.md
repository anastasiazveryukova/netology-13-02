# Домашнее задание к занятию "`Защита хоста`" - `Зверюкова Анастасия`


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

### Задание 1
Установите eCryptfs.
Добавьте пользователя cryptouser.
Зашифруйте домашний каталог пользователя с помощью eCryptfs.
В качестве ответа пришлите снимки экрана домашнего каталога пользователя с исходными и зашифрованными данными.

```
sudo apt update
sudo apt install ecryptfs-utils
sudo adduser --encrypt-home cryptouser
```
<img width="744" height="464" alt="Снимок экрана 2026-04-27 220945" src="https://github.com/user-attachments/assets/ba16e6e7-718b-4e72-896a-8107ea3fdfbd" />

<img width="1023" height="217" alt="Снимок экрана 2026-04-27 222812" src="https://github.com/user-attachments/assets/f4d17d3b-7aea-4736-8e7b-369ce3ec1bce" />


<img width="992" height="280" alt="Снимок экрана 2026-04-27 222852" src="https://github.com/user-attachments/assets/eef89a4f-34ca-405f-a4b6-59b20f2fbbad" />



<img width="983" height="506" alt="Снимок экрана 2026-04-27 221240" src="https://github.com/user-attachments/assets/9951834b-3245-4b52-b4fd-5dce9dec6c5f" />

Выполнила команды руководствуясь презентацией, получился не совсем тот результат, который ожидала.

### Задание 2
Установите поддержку LUKS.
Создайте небольшой раздел, например, 100 Мб.
Зашифруйте созданный раздел с помощью LUKS.
В качестве ответа пришлите снимки экрана с поэтапным выполнением задания.

<img width="1104" height="977" alt="Снимок экрана 2026-04-27 224723" src="https://github.com/user-attachments/assets/41df2201-4df2-4ba7-b0d7-0ff7a3a59ae5" />

<img width="1035" height="954" alt="Снимок экрана 2026-04-28 130345" src="https://github.com/user-attachments/assets/b79b2d0e-7d56-4f08-9dce-2cd914d7277d" />

<img width="1075" height="549" alt="Снимок экрана 2026-04-28 130643" src="https://github.com/user-attachments/assets/c149db8b-640f-48aa-8be5-267547c0e81d" />

<img width="1047" height="889" alt="Снимок экрана 2026-04-28 132455" src="https://github.com/user-attachments/assets/a5ca82c5-577b-4aa6-9c8f-d40723bf0749" />

<img width="1342" height="665" alt="Снимок экрана 2026-04-28 133430" src="https://github.com/user-attachments/assets/7c5fb7fc-0889-46dc-8e9b-522a59b01d3e" />

<img width="1324" height="527" alt="Снимок экрана 2026-04-28 133649" src="https://github.com/user-attachments/assets/ef6d89e4-4291-4f7e-9017-58da1411ec32" />


