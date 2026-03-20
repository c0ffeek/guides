# Инструкция iPhone (iOS) Happ

1) **Скачать Happ** из App Store.

Открываем **страницу подписки** remnavawe, которую вам скинул админ, в браузере **Safari** на iPhone.

Пример ссылки: `https://webhooks.techbridge-net.com/ваш_код`

> ⚠️ **Подписка рассчитана на 5 устройств.** Добавить её на шестое устройство не получится. Если нужно больше — обратитесь к админу.

В разделе **«Установка»** убедитесь, что выбрана платформа **iOS** и вкладка **Happ**.

![](attachment/7d37c7bf4bcbd906d0c79cd603ebf889.png)

Нажмите **«App Store (RU)»** или **«App Store (Global)»** — в зависимости от того, какой регион у вашего Apple ID.

Установите приложение из App Store.

2) Запускаем **Happ**.

При первом запуске появится запрос на разрешение VPN‑конфигурации:

- Нажмите **«Allow» (Разрешить)**
- Введите **пароль устройства** (или подтвердите через Face ID / Touch ID)

> **Важно!** Без этого разрешения приложение работать не будет. Обязательно нажмите «Allow».

3) Теперь нужно добавить подписку.

Возвращаемся на **страницу подписки** remnavawe в Safari.

Находим раздел **«Добавление подписки»** и жмём **«+ Добавить подписку»**.

Happ откроется, и подписка добавится **автоматически**.

> Если Happ не открылся — убедитесь, что он установлен. Попробуйте ещё раз.


> **Альтернативный способ:** скопируйте ссылку-подписку и в приложении Happ нажмите **«Из буфера»**. Либо можно отсканировать **QR‑код** кнопкой **«QR-Код»**.

![](attachment/5c366e2b5391a3ea63a7f6c95f478457.png)


4) Добавятся конфиги — список серверов.

Вы увидите подключения по разным странам и протоколам, например:
- **[Автовыбор]** — сам выбирает лучший сервер, а если связь пропадёт — автоматически переключится на другую рабочую ноду
- **[FR] Reality**, **[FR] WS**, **[FR] XHTTP** — серверы во Франции
- **[SW] Reality**, **[SW] WS**, **[SW] XHTTP** — серверы в Швеции
- и другие

![](attachment/2bd0074aded25f8e458a7d2c6886f0b6.png)

**Рекомендуем использовать [Автовыбор]** — вам не придётся вручную менять сервер, всё работает само.

5) Выбираем нужный конфиг и нажимаем большую **кнопку включения** в центре экрана.

![](attachment/6639a72d323ae45bd1199281aa8ea5c0.png)

Начнётся подключение. Статус на кнопке сменится на **«Подключён»**.

Не забудьте выбрать сервер в **списке серверов** — при необходимости можно переключиться на другой.

6) Проверяем, что VPN работает: заходим в Safari на [https://www.whatismyip.com/](https://www.whatismyip.com/) — страна должна быть **не Россия** (Франция, Швеция, Германия и т.д.).

7) Чтобы **отключить VPN** — нажимаем на большую кнопку ещё раз.

---
## Можно сразу настроить маршрутизацию, чтоб ру-сайты, открывались напрямую:

**Функция экспериментальная, попробуйте, если не будет работать - просто отключите.**

1) Открываем правила маршрутизации:

![](attachment/c1fcda305b9898b93f59321032fdcc07.png) ![](attachment/a86ac025299a2c02458e834079f904ba.png)

2) Копируем на выбор одну из строк ниже.

**Только ру сайты напрямую:**
happ://routing/add/ewogICAgIkJsb2NrSXAiOiBbXSwKICAgICJCbG9ja1NpdGVzIjogW10sCiAgICAiRGlyZWN0SXAiOiBbCiAgICAgICAgImdlb2lwOnJ1IiwKICAgICAgICAiMTAuMC4wLjAvOCIsCiAgICAgICAgIjE3Mi4xNi4wLjAvMTIiLAogICAgICAgICIxOTIuMTY4LjAuMC8xNiIsCiAgICAgICAgIjE2OS4yNTQuMC4wLzE2IiwKICAgICAgICAiMjI0LjAuMC4wLzQiLAogICAgICAgICIyNTUuMjU1LjI1NS4yNTUiCiAgICBdLAogICAgIkRuc0hvc3RzIjogewogICAgICAgICJjbG91ZGZsYXJlLWRucy5jb20iOiAiMS4xLjEuMSIKICAgIH0sCiAgICAiRG9tYWluU3RyYXRlZ3kiOiAiSVBJZk5vbk1hdGNoIiwKICAgICJEb21lc3RpY0ROU0RvbWFpbiI6ICJodHRwczovL2Rucy5nb29nbGUvZG5zLXF1ZXJ5IiwKICAgICJEb21lc3RpY0ROU0lQIjogIjc3Ljg4LjguOCIsCiAgICAiRG9tZXN0aWNETlNUeXBlIjogIkRvVSIsCiAgICAiRmFrZUROUyI6ICJmYWxzZSIsCiAgICAiR2VvaXB1cmwiOiAiaHR0cHM6Ly9naXRodWIuY29tL0xveWFsc29sZGllci92MnJheS1ydWxlcy1kYXQvcmVsZWFzZXMvbGF0ZXN0L2Rvd25sb2FkL2dlb2lwLmRhdCIsCiAgICAiR2Vvc2l0ZXVybCI6ICJodHRwczovL2dpdGh1Yi5jb20vTG95YWxzb2xkaWVyL3YycmF5LXJ1bGVzLWRhdC9yZWxlYXNlcy9sYXRlc3QvZG93bmxvYWQvZ2Vvc2l0ZS5kYXQiLAogICAgIkdsb2JhbFByb3h5IjogInRydWUiLAogICAgIkxhc3RVcGRhdGVkIjogMTc2NDMyMDc0MywKICAgICJQcm94eUlwIjogW10sCiAgICAiUHJveHlTaXRlcyI6IFtdLAogICAgIlJlbW90ZUROU0RvbWFpbiI6ICJodHRwczovL2Nsb3VkZmxhcmUtZG5zLmNvbS9kbnMtcXVlcnkiLAogICAgIlJlbW90ZUROU0lQIjogIjEuMS4xLjEiLAogICAgIlJlbW90ZUROU1R5cGUiOiAiRG9IIiwKICAgICJSb3V0ZU9yZGVyIjogImJsb2NrLWRpcmVjdC1wcm94eSIsCiAgICAiTmFtZSI6ICJEaXJlY3QtUlUiLAogICAgIkRpcmVjdFNpdGVzIjogWwogICAgICAgICJnZW9zaXRlOnByaXZhdGUiLAogICAgICAgICJnZW9zaXRlOnlhbmRleCIsCiAgICAgICAgImdlb3NpdGU6bWFpbHJ1IiwKICAgICAgICAiZ2Vvc2l0ZTp2ayIsCiAgICAgICAgImRvbWFpbjpydSIsCiAgICAgICAgImRvbWFpbjp4bi0tcDFhaSIsCiAgICAgICAgImRvbWFpbjpzdSIsCiAgICAgICAgImRvbWFpbjp1ZmFuZXQudHYiCiAgICBdCn0=

**Ру сайты и гугл напрямую:**
happ://routing/add/ewogICAgIkJsb2NrSXAiOiBbXSwKICAgICJCbG9ja1NpdGVzIjogW10sCiAgICAiRGlyZWN0SXAiOiBbCiAgICAgICAgImdlb2lwOnJ1IiwKICAgICAgICAiMTAuMC4wLjAvOCIsCiAgICAgICAgIjE3Mi4xNi4wLjAvMTIiLAogICAgICAgICIxOTIuMTY4LjAuMC8xNiIsCiAgICAgICAgIjE2OS4yNTQuMC4wLzE2IiwKICAgICAgICAiMjI0LjAuMC4wLzQiLAogICAgICAgICIyNTUuMjU1LjI1NS4yNTUiCiAgICBdLAogICAgIkRuc0hvc3RzIjogewogICAgICAgICJjbG91ZGZsYXJlLWRucy5jb20iOiAiMS4xLjEuMSIKICAgIH0sCiAgICAiRG9tYWluU3RyYXRlZ3kiOiAiSVBJZk5vbk1hdGNoIiwKICAgICJEb21lc3RpY0ROU0RvbWFpbiI6ICJodHRwczovL2Rucy5nb29nbGUvZG5zLXF1ZXJ5IiwKICAgICJEb21lc3RpY0ROU0lQIjogIjc3Ljg4LjguOCIsCiAgICAiRG9tZXN0aWNETlNUeXBlIjogIkRvVSIsCiAgICAiRmFrZUROUyI6ICJmYWxzZSIsCiAgICAiR2VvaXB1cmwiOiAiaHR0cHM6Ly9naXRodWIuY29tL0xveWFsc29sZGllci92MnJheS1ydWxlcy1kYXQvcmVsZWFzZXMvbGF0ZXN0L2Rvd25sb2FkL2dlb2lwLmRhdCIsCiAgICAiR2Vvc2l0ZXVybCI6ICJodHRwczovL2dpdGh1Yi5jb20vTG95YWxzb2xkaWVyL3YycmF5LXJ1bGVzLWRhdC9yZWxlYXNlcy9sYXRlc3QvZG93bmxvYWQvZ2Vvc2l0ZS5kYXQiLAogICAgIkdsb2JhbFByb3h5IjogInRydWUiLAogICAgIkxhc3RVcGRhdGVkIjogMTc2NDMyMDc0MywKICAgICJQcm94eUlwIjogW10sCiAgICAiUHJveHlTaXRlcyI6IFtdLAogICAgIlJlbW90ZUROU0RvbWFpbiI6ICJodHRwczovL2Nsb3VkZmxhcmUtZG5zLmNvbS9kbnMtcXVlcnkiLAogICAgIlJlbW90ZUROU0lQIjogIjEuMS4xLjEiLAogICAgIlJlbW90ZUROU1R5cGUiOiAiRG9IIiwKICAgICJSb3V0ZU9yZGVyIjogImJsb2NrLWRpcmVjdC1wcm94eSIsCiAgICAiTmFtZSI6ICJEaXJlY3QtUlUrRyIsCiAgICAiRGlyZWN0U2l0ZXMiOiBbCiAgICAgICAgImdlb3NpdGU6cHJpdmF0ZSIsCiAgICAgICAgImdlb3NpdGU6eWFuZGV4IiwKICAgICAgICAiZ2Vvc2l0ZTptYWlscnUiLAogICAgICAgICJnZW9zaXRlOnZrIiwKICAgICAgICAiZG9tYWluOnJ1IiwKICAgICAgICAiZG9tYWluOnhuLS1wMWFpIiwKICAgICAgICAiZG9tYWluOnN1IiwKICAgICAgICAiZG9tYWluOnVmYW5ldC50diIsCiAgICAgICAgImdlb3NpdGU6Z29vZ2xlIgogICAgXQp9

3) После копирования нажимаем на три точки вот сюда и импортируем:

![](attachment/1e483b4cb00d6da8ee6312a7796e4764.png)![](attachment/ef0095fd4d57219a5690efc1d84345dd.png)

4) Далее включаем флажок, всё готово.

![](attachment/98bb0cb76fd825f955a0563e0989d720.png)

---
## Обновление подписки

Если админ сообщил, что на сервере что-то поменялось и подписку нужно обновить:

В списке серверов нажмите на иконку **«Обновить»** (🔄).

После обновления все конфиги восстановятся, даже если вы какие-то раньше удаляли.

---

🚫 **НЕ КАЧАТЬ ТОРРЕНТЫ СО ВКЛЮЧЁННЫМ VPN!**

🚫 **НЕЛЬЗЯ!** Вы будете нагружать канал!

🚫 **НЕЛЬЗЯ!** Вы будете нарушать закон об авторском праве!
