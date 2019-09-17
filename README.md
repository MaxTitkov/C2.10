# C2.10

Сервер реализован на waitress. Он прописан в my_config.conf
В базовых настройках без my_config.conf сервер стоит auto

Описание директорий:

1. backend Содержит сервер и обработчики
2. views Содержит templates длы server
3. SSE  Отдельно лежат HTML для SSE подключений. Они не связаны с сервером. В for-sse.html имеются два progress-bar. Один для внутреннего сервера, второй для удаленного сервера https://sf-pyw.mosyag.in/sse/vote/stats


В Slack я Maxim. Если что пишите.
