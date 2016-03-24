# SoftUni

using System;


namespace _14CurrentDateAndTime
{
    class currentDateAndTime
    {
        static void Main()
        {
            DateTime dt = DateTime.Now;
            String.Format("{0:d/M/yyyy HH:mm:ss}", dt);            
            Console.WriteLine(dt); 
        }
    }
}
