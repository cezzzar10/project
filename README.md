# qanday qilib ishlatish kerak?

1. Clone qilasiz.
2. .env dagi MO ga ulanish sozlamasini to'g'riligini tekshirasiz (Kompyuteringizdagi Ombor bilan chalkashib ketmasligini ko'ring)
3. composer install
4. bin/console doctrine:database:create (yoki bin/console d:d:c).
5. bin/console doctrine:migrations:migrate (Yoki bin/console d:m:m) 
6. Keyin loyihani yurgazib ko'rasiz agar xampp bo'lsa php -S localhost:<port-raqami> -t public
