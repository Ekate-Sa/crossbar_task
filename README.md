# crossbar_task
Проект представляет собой кроссбар на 2 master и 2 slave устройства. Арбитраж запросов выполнен по алгоритму "round-robin".
Исходники представляют собой описание модулей устройства и тестбенчи для каждого модуля, включая crossbar_top.
# sources:
- crossbar_top 
- m_block
- rr_ack_arbiter
- rr_req_arbiter
- data_seeker
