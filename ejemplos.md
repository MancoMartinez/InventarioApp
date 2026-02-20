int numeroGlobal = 100;

int MetodoA()
{
    int numeroLocal = 5;
    Console.WriteLine(numeroGlobal); // OK, puede acceder global
    Console.WriteLine(numeroLocal);  // OK, es suya
    return numeroLocal;
}

void MetodoB()
{
    numeroLocalB = MetodoA();
    Console.WriteLine(numeroGlobal); // OK, global existe
    // Console.WriteLine(numeroLocaB); // ERROR: numeroLocal no existe aquí
}

// Uso:
MetodoA();
MetodoB();