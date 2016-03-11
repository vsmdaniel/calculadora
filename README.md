# calculadora
calculadora usando IF ELSE e background.
 
 int result;
            
           
            Console.WriteLine("Digite um número: ");
            string tmp = Console.ReadLine();
            int num1 = int.Parse(tmp);

            Console.WriteLine("Escolha a operação");
            string tmpp = Console.ReadLine();
            char opp = char.Parse(tmpp);

            Console.WriteLine("Digite outro número: ");
            string tmppp = Console.ReadLine();
            int num2 = int.Parse(tmppp);
 
            if (opp == '+')
            {
                Console.BackgroundColor = ConsoleColor.DarkBlue;
                result = num1 + num2;
                Console.WriteLine("O resultado da operação é: " + result);
            } 
            else
                if (opp == '-')
                {
                    
                }
            
