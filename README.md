- 👋 Hi, I’m @Joacoflow
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Joacoflow/Joacoflow is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
namespace Ejercicio1
{
    internal class Program
    {
        static void Main(string[] args)
        {
            int cantidad;
            double precio, importe;
            Console.WriteLine("Ingrese el precio: S/. ");
            precio = double.Parse(Console.ReadLine());
            Console.WriteLine("Ingrese la cantidad: ");
            cantidad = int.Parse(Console.ReadLine());
            importe = precio * cantidad;
            Console.WriteLine("El importe es: S/. " + importe);
            Console.ReadKey();
        }
        
        public void Ejercicio2()

            {
            
            int m, c;
            Console.WriteLine("Ingrese metros: ");
            m=int.Parse(Console.ReadLine());
            c = m* 100;
            Console.WriteLine("Metros a centimetros es:"+c);
            Console.ReadKey();

            }

        public void Ejercicio3()
        {
            int s, h, c;
            Console.WriteLine("Ingrese las horas trabajas: ");
            h = int.Parse(Console.ReadLine());
            Console.WriteLine("Ingrese costo por hora: ");
            c = int.Parse(Console.ReadLine());

            s = h * c;
            Console.WriteLine("El sueldo es:" + s);
            Console.ReadKey();
        }

        public void Ejercicio4()
        {
            double P, p = 0, g = 0, h = 0;
            Console.WriteLine("Densidad: ");
            p = double.Parse(Console.ReadLine());
            Console.WriteLine("Gravedad: ");
            g = double.Parse(Console.ReadLine());
            Console.WriteLine("Altura: ");
            h = double.Parse(Console.ReadLine());

            P = p * g * h;
            Console.WriteLine("la presion atmosferica: " + P);
            Console.ReadKey();
        }

        public void Ejercicio5()
        {
            double sb, v1, v2, v3, comision, gm;
            Console.WriteLine("Ingrese su salario base: S/. ");
            sb = double.Parse(Console.ReadLine());
            Console.WriteLine("Ingrese el valor de la venta 1: S/. ");
            v1 = double.Parse(Console.ReadLine());
            Console.WriteLine("Ingrese el valor de la venta 2: S/. ");
            v2 = double.Parse(Console.ReadLine());
            Console.WriteLine("Ingrese el valor de la venta 3: S/. ");
            v3 = double.Parse(Console.ReadLine());
            comision = (v1 + v2 + v3) * 0.10;
            gm = (sb + comision);
            Console.WriteLine("Su ganancia mensual es: S/. " + gm);
            Console.ReadLine();

        }

        public void Ejercicio6()
        {
            int n, s;
            Console.WriteLine("Ingrese numero: ");
            n = int.Parse(Console.ReadLine());
            s = (n * (n + 1) / 2);
            Console.WriteLine("La suma es: " + s);
            Console.ReadKey();
        }

        public void Ejercicio7() 
        
        {

            const double PI = 3.14159;
            double a, p, r;
            Console.WriteLine("El radio: ");

            r = double.Parse(Console.ReadLine());

            a = PI * (r * r);
            p = 2 * PI * r;

            Console.WriteLine("\nArea: " + a);
            Console.WriteLine("\nPerimetro: " + p);
            Console.ReadKey();
        }

        
      
    }
    public class Node
    {

        private Object info;
        private Node next;

        public Node()
        {
            info = null;
            next = null;
        }

        public Node(Object o, Node n)
        {
            setInfo(o);
            setNext(n);
        }

        public void setInfo(Object o)
        {
            info = o;
        }

        public void setNext(Node n)
        {
            next = n;
        }

        public Object getInfo()
        {
            return info;
        }

        public Node getNext()
        {
            return next;
        }
    }

}





