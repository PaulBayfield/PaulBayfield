```python
class Paul:
    apprenticeship = MoëtHennessy("Data Engineering")
    study = ComputerScience()
    projects = [CROUStillant(), Better-IUT-RCC()]
    hobby = Bouldering()
    home = France("Paris")

    async def run(self, inputs: Union[Keyboard, Mouse, Screen]) -> None:
        while True:
            await self.apprenticeship.do(inputs)
            await self.study.do(inputs)
            [await project.do(inputs) for project in self.projects]

    def sleep(self):
        raise NotImplementedError
```
