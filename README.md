# Лабораторный практикум 2

Для того, чтобы запустить, необходимо открыть файл в Jupyter ноутбуке или в коллабе

В начале я хотел просто прикрутить api openai, но из-за санкций это невозможно сделать бз VPN, затем я подумал в сторону ThebAI, как раз предыдущая ДЗ была по теме, но там необходимо внести деньги на счет, чтобы воспользоваться API, я попробовал, но русская карта заблокирована, попробовал через крипту, но там надо внести минимальный депозит в 20 долларов. С GigaChat вышла примерно такая же история, но там вообще не ясно где шлюз оплаты.

Поэтому я решил воспользоваться сервисом HuggingFace, там по сути можно размещать свои модели и хостить. Я взял бесплатную модель от google в качестве примера, но она не говорит по русски, только на английском, если с ней попробовать на русском, то она сходит с ума (подробнее описал в коде).

На самом сайте hugging можно поискать еще разные модели, которые наверняка говорят по-русски, но вероятнее всего они хуже обучены.

- Данный бот - это по сути маленький chatGPT, который может говорить только на английском.
- P.S не обращайте внимание на ошибку в файле, это просто когда бота вырубаешь он выкидывает
- Токены направил через LMS

Подготовил: Пономарев Артем
