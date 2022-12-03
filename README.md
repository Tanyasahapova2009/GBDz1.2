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
