# not-hesaplama
 Console.Write("notunuzu giriniz: ");
            int not = Convert.ToInt32(Console.ReadLine()); 

            if (not >= 0 && not <= 30)
            {
                Console.WriteLine("notunuz :FF");
            }
            else if(not > 30 && not <=50)
            {
                Console.WriteLine("notunuz: DD");
            }
            else if(not > 50 && not <= 70)
            {
                Console.WriteLine("notunuz BB");
            }
            else if(not>70 && not <= 100)
            {
                Console.WriteLine("notunuz AA");
            }
            else
            {
                Console.WriteLine("hatalı not girdiniz");
            }
                
                Console.ReadLine();
