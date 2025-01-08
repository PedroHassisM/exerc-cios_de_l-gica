# exercicios_de_logica
exercícios para praticar a lógica de programação.
Primeiro exercicio Saber em que ano terá 100 ou mais anos 
Console.Write("quantos anos você tem ?");
int idade = int.Parse(Console.ReadLine());
int anoAtual = DateTime.Now.Year;
int AnosPara100 = 120 - idade;
int Anode100 = anoAtual + AnosPara100;
Console.WriteLine($"Você terá 100 anos em {Anode100}");
