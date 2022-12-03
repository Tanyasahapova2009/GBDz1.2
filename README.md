Console.WriteLine("Введите трехзначное число");
int n = int.Parse(Console.ReadLine());
int m = n % 10;
Console.WriteLine(m);

Console.WriteLine("Введите а=");
int numbera = Convert.ToInt32(Console.ReadLine());
Console.WriteLine("Введите в=");
int numberb = Convert.ToInt32(Console.ReadLine());
if ( numbera > numberb ) 

{
    Console.WriteLine("max="); Console.WriteLine(numbera);
    Console.WriteLine("min="); Console.WriteLine(numberb);

}
else
{
    Console.WriteLine("max="); Console.WriteLine(numberb);
    Console.WriteLine("min="); Console.WriteLine(numbera);
}
