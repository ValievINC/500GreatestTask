# 500 Величайших альбомов всех времён
### Ваня, в очередной раз исследуя просторы всемирной паутины, наткнулся на [список 500 лучших альбомов всех времён](https://www.rollingstone.com/music/music-lists/best-albums-of-all-time-1062063/), составленный уважаемой редакцией Rolling Stone. 
### Ване почему-то стало интересно: "А у кого больше всего упомнинаний в этом списке?"
На основе прикрепленного [xml-файла](https://github.com/ValievINC/500GreatestTask/blob/main/500Greatest.xml) составьте столбчатую диаграмму с топом самых упоминаемых групп, по типу этой:

![image](https://github.com/ValievINC/500GreatestTask/blob/main/Top11_Bands.png)
### "А какие жанры самые популярные?"
На основе того же прикрепленного файла сделайте круговую диаграмму с самыми популярными жанрами из списка (не поджанрами). Не засовывайте все жанры в ваш пирог, пусть какая-то часть будет помечена как "others":

![image](https://github.com/ValievINC/500GreatestTask/blob/main/genres_pie.png)

### Ванин друг любит такой поджанр, как "Альтернативный Рок".
Сделайте Ваниному другу подарок - составьте csv-таблицу со всеми группами и альбомами, играющими в этом поджанре:

![image](https://github.com/ValievINC/500GreatestTask/blob/main/exmple.png)

### Примечание: в решении вам помогут библиотеки [xml.etree.ElementTree](https://docs.python.org/3/library/xml.etree.elementtree.html), [pandas](https://pandas.pydata.org/docs/), [matplotlib](https://matplotlib.org/stable/index.html), [collections](https://docs.python.org/3/library/collections.html).
