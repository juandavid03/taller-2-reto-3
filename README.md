# taller-2-reto-3


    class Program
    
    {
    
        static void Main(string[] args)
        
        {
        
             int[] fibarray = new int[] { 4, 51, -7, 13, -99, 15, -8, 45, 90};
             
             foreach (int element in fibarray)
             
             {
             
                 int maximo = fibarray.Max();
                 
                 int minimo = fibarray.Min();
                 
                 Console.WriteLine("el numero maximo es {0} y el minimo es {1}", maximo, minimo);
                 
             }
             
             Console.ReadLine();
             
        }
        
    }
