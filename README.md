# Baby_Blockchain
Мой проект:
Блокчейн система для голосования, где каждый пользователь может проголосовать как на государственных выборах/голосования так и на частных голосованиях/выборах.

У каждого пользователя будет свой хеш-ключ, который хранит в себе информацию о пользователе(имя, фамилия, дата рождения и т.д.)

У идеальной хеш функции шанс выпадения коллизии очень мал. мал-следовательно каждый хеш будет уникальным, каждый голос уникальный и подделать голосование  представляется невозможным ,что предоставляет шанс получить честные выборы.

Каждый вариант голоса-стек, который будет  хранит хранить в себе хеш каждого пользователя, который проголосовал за этот вариант.

(проводил личное собственное при увеличении длины хеша идеальной хеш функции -вероятность коллизии стремится к 0 при большом количестве испытаний )


