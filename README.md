นายแทนคุณ ทันเขิม  
รหัสนักศึกษา:683450064-0


classDiagram
    class Program {
        +Main(string[] args)
    }

    class Tankun {
        -int water
        -int coffee
        -int milk
        -int chocolate
        +Tankun(int water, int coffee, int milk, int chocolate)
        +MakeDrink(int water, int coffee, int milk, int chocolate, string name)
        +ShowStock()
        +Refill(int water, int coffee, int milk, int chocolate)
    }

    Program --> Tankun
