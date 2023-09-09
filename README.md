namespace MonaresCalcProgram

{
    internal class Program
    {
        public static void Main(string[] args)
        {
            int x;
            x = int.Parse(Console.ReadLine());
            int y;
            y = int.Parse(Console.ReadLine());
            Console.Write("Choose an operation(+,-,*,/):");
            char ops;
            ops = Convert.ToChar(Console.ReadLine());

            var a = Sum(x, y);
            var b = Difference(x, y);
            var c = Multiply(x, y);
            var d = Divide(x, y);

            PrintResultSum(a);
            PrintResultDifference(b);
            PrintResultMultiply(c);
            PrintResultDivide(d);


        }
        private static int Sum(int x, int y)
        {
            return x + y;
        }
        private static int Difference(int x, int y)
        {
            return x - y;
        }
        private static int Multiply(int x, int y)
        {
            return x * y;
        }
        private static int Divide(int x, int y)
        {
            return x / y;
        }
        private static void PrintResultSum(int a)
        {
            Console.WriteLine(a);
        }
        private static void PrintResultDifference(int b)
        {
            Console.WriteLine(b);
        }
        private static void PrintResultMultiply(int c)
        {
            Console.WriteLine(c);
        }
        private static void PrintResultDivide(int d)
        {
            Console.WriteLine(d);
        }

    }

}


