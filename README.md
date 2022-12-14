# Programming I Portfolio
## Midterm adventure Game
![title](https://user-images.githubusercontent.com/115731900/207738231-d2866ef9-3042-4426-887b-0b8ba0adff70.png)
A short and sweet farming simulator made in C#
![gameplay](https://user-images.githubusercontent.com/115731900/207738292-f3584077-9cb1-4054-b998-ff4e6ab52362.png)

### Code Ex.
```
  static void GameTitle()
        {
            string Title = @" ____   ___   __    __  ___    __ __      ____    ____  ____    ____    ___  ____  
|    \ /   \ |  |__|  ||   \  |  |  |    |    \  /    ||    \  /    |  /  _]|    \ 
|  D  )     ||  |  |  ||    \ |  |  |    |  D  )|  o  ||  _  ||   __| /  [_ |  D  )
|    /|  O  ||  |  |  ||  D  ||  ~  |    |    / |     ||  |  ||  |  ||    _]|    / 
|    \|     ||  `  '  ||     ||___, |    |    \ |  _  ||  |  ||  |_ ||   [_ |    \ 
|  .  \     | \      / |     ||     |    |  .  \|  |  ||  |  ||     ||     ||  .  \
|__|\_|\___/   \_/\_/  |_____||____/     |__|\_||__|__||__|__||___,_||_____||__|\_|
                                                                                   ";
            Console.Title = Title;
            Console.ForegroundColor = ConsoleColor.Red;
            Console.WriteLine(Title);
            Console.ResetColor();
            Console.WriteLine("press enter to start game");
            Console.ReadKey();
            Console.Clear();
        }
```


