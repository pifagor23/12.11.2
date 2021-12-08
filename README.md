# 12.11.2
namespace qwe
{
    class Program
    {
        static void Main()
        {
            int[] mas = { 1, 2, 3, -4, -5,-45,5,36,7,45,32,36,865,3,4,-52,346,-234,4,-567,76,87,95, };
            for (int i = 1; i < mas.Length-1; i++)
            {
                if (mas[i] > 0)
                {
                    Console.WriteLine(mas[i]);
                }
            }
            

        }
    }
}
