> **Warning**


```python

class IxKian(metaclass=ABCMeta):
    @abstractstaticmethod
    def contact():
        return ["discord", "telegram"]

    @abstractstaticmethod
    def life():
        return self.coding()

    @abstractstaticmethod
    def coding():
        pass


class Attributes(arused):
    @staticmethod
    def contact() -> tuple:
        discord: str = "^"
        telegram: str = "arused"

        return discord, telegram

    @staticmethod
    def life() -> tuple:
        langs = ("hebrew", "English")

        return langs

    @staticmethod
    def coding() -> tuple:
        text_editor = "vscode,pycharm"
        specialities = ["reverse engineering", "automation"]
        langs = {"engineering": "python", "c#": "go", "learning": "js"}
        return langs, specialities, text_editor
```
