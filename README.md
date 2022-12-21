# 201222
C# 101 dersleri deneme kodları
internal class Program
{
    private static void Main(string[] args)
    {
        //Tür dönüşüm örnekleri

        byte a = 10;

        short b = 20;

        sbyte c = 30;

        int d = a + b + c ;//örnek bir tür dönüşümü (bilinçsiz)

        string e = "İBB Project 100 KY ";

        char f = 'A';

        object g = e + " " + f + " " + d ;//farklı tiplerin obje tipine aktarılması

        long h = d;

        float i = h;

        double j = i;

        double k = 26.6f;

        Console.WriteLine("birinci durum: " + d.ToString());
        Console.WriteLine("ikinci durum: " + g.ToString());
        Console.WriteLine("üçüncü durum: " + h + k);

        // Bilinçsiz dönüşüm olayında ilginç bir durum

        char l = 'H';

        int m = l;

        Console.WriteLine("dördüncü durum: " + m);

        Console.WriteLine(""); //bir satır boşluk bırakma.

        Console.WriteLine("\n\t"); //bir satır boşluk bırakma.


        //tür dönüşüm örnekleri - bilinçsiz

        int r = 15;

        byte s = (byte)r;

        Console.WriteLine("beşinci durum: "+ (s + r));

        Console.WriteLine()

        Console.ReadKey();
    }
}
