# wallter
Все примеры с переменной int coin
1. Обнуление Валюты: coin=wallter.zero;
2. Инкрементирование валюты: coin=wallet.ink(coin);
3. Сохранение валюты через PlayerPrefs: wallter.SavePP("coin",coin);
4. Загрузка валюты через PlayerPrefs: wallter.loadPP("coin");
5. Сохранение валюты в файл: wallter.SaveInF(new int[]{coin}); //Обязательно запомните в какой последовательности Вы сохраняли валюты (если их больше одной) (отсчёт начинается с нуля)
6. Загрузка валюты из файла: coin=wallter.LoadInF()[0]; //В [] указываем порядковый номер валюты, начиная с нуля
7. Сохранение валюты в файл в бинарном виде: wallter.SaveInFB(new int[]{coin}); //так же запоминаем номер, как и в случае 5
8. Загрузка валюты из бинарного файла: coin=wallter.LoadInFB()[0];//так же указываем номер, как и в случае 6
