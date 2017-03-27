# binom_hourly
Почасовые графики для Binom


## Инструкция:
- скачать и разархивировать файлик index.html
- положить на свой сервер бинома, в папку `/var/www/binom/graph`
- зайти на свой трекер по адресу: `http://<адрес_трекера.ком>/graph/`
- Страничка попросит API ключ к биному. Введите ключ и нажмите энтер. Страничка немного подумает и выдаст графики Clicks и Profit.
- Дальше ваш ключ сохранится в урле как GET-параметр. Если страницу в таком виде сохранить в избранном, она больше не будет спрашивать ключ.

## О безопасности:
- страничка никуда не лезет, кроме как на апи вашего собственного сервера
- страничка ничего никуда не отправляет (см. код, он прозрачен)

## Проблемы:
- Не работает на айфоне. Не понимаю, почему. На десктопном хроме - работает отлично, а на айфоне -нет. Может, Mobile Safari как-то перехерачивает GET-параметры при запросе апи бинома; не понимаю. Если кто-то поможет допилить это под айфон - буду благодарен.
