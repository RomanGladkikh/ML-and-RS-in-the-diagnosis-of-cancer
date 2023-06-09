# Машинное обучение и Рамановская спектроскопия в диагностике опухолевых тканей
Данный проект выполнен в рамках Выпускной Квалификационной Работы студентом ПМИ ФКН ВШЭ Гладких Романом
# Aннотация

В настоящее время машинное обучение является одной из самых быстрорастущих областей науки, и оно уже продемонстрировало свой большой потенциал для использования в медицине. Рамановская спектроскопия — это спектроскопический метод исследования, используемый для определения колебательных состояний внутри образцов, однако, имеется мало сообщений о его применении в живых тканях. Вследствие чего на данный момент Рамановская спектроскопия является одним из наиболее перспективных методов диагностики опухолевых тканей на ранней стадии болезни, путем выявления характерных изменений в составе ткани при раке. Это позволяет диагностировать опухолевые ткани, используя только Рамановскую спектроскопию. 
  
В данной работе описывается процесс создания и исследования моделей для диагностики опухолевых тканей на базе алгоритмов классификации машинного обучения, основанных на моделях логистической регрессии, бустинга и случайного леса. Также в данной работе при помощи алгоритмов отбора признаков выявляются наиболее важные Рамановские сдвиги, с целью улучшения интерпретируемости модели и создания механизма поддержки врачебных решений.

# Результаты

1. На основе Random Forest и методов отбора признаков (EFS, RFI и PCA) удалось достичь улучшения основной метрики F1 меры в 2.5 раза относительно бейзлайна (рост качества F1 меры с 0.938 до 0.975) на предоставленном наборе спектроскопий пациентов.
2. Были произведен отбор наиболее важных Рамановских сдвигов. Качество F1 меры при применении алгоритмов EFS и RFI возросло на 0.5\% и на 0.9\% соответственно при условии сокращения количества признаков на 99,1\% (с 1015 до 9).
