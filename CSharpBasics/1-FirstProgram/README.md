# Dit første program

- Vi har en standart konsol app i C#, vi skal starte med at forstå programmet før vi kan skrive i det!

```c#
  namespace FirstProgram
  {
    public class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hej og velkommen til C#-bogen!");
        }
    }
  }
```

Først skal vi lige decode alle kodeordene som starter vores kode

#### 1. namespace

[Officiel Dokumentation - Namespaces](https://learn.microsoft.com/en-us/dotnet/csharp/fundamentals/types/namespaces)

Et namespace er brugt til at organisere jeres kode og separerer det. Det er i toppen af stort set alle jeres filer og kan indeholde klasser som vi lærer om senere og kan faktisk også indeholde nestet namespaces!

#### 2. Tuborg-klammer / curly braces -> {}

[Officiel Dokumentation - Formatting](https://learn.microsoft.com/en-us/dotnet/fundamentals/code-analysis/style-rules/csharp-formatting-options)

I kender nok "{}" fra andre sprog, nogle få bruger dem ikke normalt såsom Python. De definere hvornår jeres namespace, metode eller funktion starter og stopper.

#### 3. public

[Officiel Dokumentation - public](https://learn.microsoft.com/en-us/dotnet/csharp/language-reference/keywords/public)

Public betyder at den efterfølgende klasse eller variabel er offentlig tilgængelig. Altså at den kan tilgås uden for dens egen klasse eller namespace.
Vi dækker emnet omkring Public, Private osv. senere i forløbet!

#### 4. class

class er også et keyword som vi stifter meget mere bekendtskab med senere i forløbet. Vi har dedikeret en hel uge til OOP (Object Orienteret Programmering), så der skal vi nok få dækket det. Generelt bruger vi klasser til at holde på variabler (Attributes) og metoder, vi snakker i [kapitel 8](/CSharpBasics/8-Methods/) omkring objekter som hænger tæt sammen med klasser!

#### 5. static

vores Main metode skal altid have static kodeordet, det gør at vi kan kalde metoden uden at lave en instans af klassen.
Vi kommer ikke rigtig til at bruge kodeordet senere, så I behøver ikke dyb viden omkring det!

#### 6. void

void betyder at vores metode ikke retunere noget, hvis vi i løbet af metoden bruger kodeordet "return" er det vigtigt at skrive præcis hvilken type vi retunere i stedet for "void". Vi kommer til at bruge den her funktionalitet meget, senere i vores forløb og der kommer det til at give meget mere mening!

#### 7. Main(string[] args)

Main() er vores hovedmetode, det betyder at når vi starter programmet ser den automatisk efter en Main()-metode som starter vores program. Senere når vi har større projekter, bruger vi en fil kaldet program.cs til at gøre præcis det samme!

#### 8. Console

Console er en del af "System" pakken, det gør at vi har et sted at skrive tekst til. Udover det kan de også tage input som vi ser senere!
