# SadykovSergey

SadykovSergey - это класс, который представляет информацию о Сергее Садыкове, включая его навыки, интересы, текущие учебные проекты и контактные данные.

    
    Class SadykovSergey:
    
      def __init__(self):
      self.name = 'Sergey Sadykov'
      
      self.skillz = ['Pyhton','CSV','JSON','cv2','numpy',
                    'matplotlib','Pandas','BeautifulSoup']
      
      def interested(self):
        interest = "Music, Backend, Life"
            return interest
  
      def currently_learning(self):
        print("Django")

      def reach_me(self):
        telegram = @ggbee
        mail = 'g.bee@bk.ru'
        return telegram, mail




## Описание функций

### Класс `SadykovSergey`
Класс содержит основные методы для отображения информации о Сергее Садыкове.

#### Метод `__init__(self)`
Инициализирует атрибуты `name` и `skillz`.

##### Атрибуты
- `self.name` (str): Имя Сергея Садыкова.
- `self.skillz` (list): Список навыков.

```python
class SadykovSergey:

  def __init__(self):
    self.name = 'Sergey Sadykov'
    self.skillz = ['Python', 'CSV', 'JSON', 'cv2', 'numpy', 'matplotlib', 'Pandas', 'BeautifulSoup']
```

#### Метод `interested(self)`
Возвращает строку с интересами Сергея.

##### Возвращаемое значение
- `interest` (str): Строка с интересами.

```python
  def interested(self):
    interest = "Music, Backend, Life"
    return interest
```

#### Метод `currently_learning(self)`
Печатает, что Сергей в настоящее время изучает Django.

##### Возвращаемое значение
- None

```python
  def currently_learning(self):
    print("Django")
```

#### Метод `reach_me(self)`
Возвращает контактные данные Сергея: Telegram и email.

##### Возвращаемое значение
- `telegram` (str): Логин в Telegram.
- `mail` (str): Email адрес.

```python
  def reach_me(self):
    telegram = '@ggbee'
    mail = 'g.bee@bk.ru'
    return telegram, mail
```

### Основной блок
Создает экземпляр класса `SadykovSergey` и вызывает методы для отображения информации.

```python
if __name__ == '__main__':
    sergey = SadykovSergey()
    print(sergey.name)
    print(sergey.skillz)
    print(sergey.interested())
    sergey.currently_learning()
    print(sergey.reach_me())
```

<!---
SergeySadykovN/SergeySadykovN is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->







