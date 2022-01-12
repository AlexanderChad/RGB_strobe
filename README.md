# Analog RGB stroboscope. Аналоговый RGB стробоскоп.  
![Template](https://github.com/AlexanderChad/RGB_strobe/blob/main/Photo/RGB_strobe_tp.jpg)  
В зависимости от частоты зажигаются с определенной яркостью определенные кристалы определенного цвета 🙃. 
Общий диаппазон: 3-7000 Гц. НЧ - красный цвет, СЧ - зеленый, ВЧ - синий. Диаппазоны цветов пересекаются, для большего разнообразия цветов.  
Для защиты кристалов от перегрузки по току в данной схеме использована ШИМ. Так же с помощью ШИМ задается яркость для разных частот.  
Схема имеет триггеры Шмитта для улучшения крутизны АЧХ фильтров (НЧ, СЧ, ВЧ), что позволило реализовать не плавное переключение цветов, 
а отдельные вспышки цветов (требуемый эффект стробоскопа).

Схема:  
![Схема](https://github.com/AlexanderChad/RGB_strobe/blob/main/Photo/RGB_strobe_scheme.png)  

Собранная схема:  
![pcb_top_view](https://github.com/AlexanderChad/RGB_strobe/blob/main/Photo/pcb_top_view.jpg)
![pcb_bottom_view](https://github.com/AlexanderChad/RGB_strobe/blob/main/Photo/pcb_bottom_view.jpg)
![RGB_LED+MIC](https://github.com/AlexanderChad/RGB_strobe/blob/main/Photo/RGB_LED%2BMIC.jpg)  

Тесты:  
![music_test1](https://github.com/AlexanderChad/RGB_strobe/blob/main/Photo/music_test1.jpg)  
