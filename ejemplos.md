- List: var lista = new List<Producto>(); lista.Add("Manzana"); lista[0] //acceso por numero. 
  
  lista.Add("Manzana");
  lista.Add("Manzana"); 
  lista.Add("Pera"); 


- Dictionary: var inventario = new Dictionary<string, int>;  
  
  inventario["Ana"] = 25; 
  inventario["Luis"] = 30;

  
- HashSet: var colores = new HashSet<string>();
  
  colores.Add("Rojo");
  colores.Add("Rojo"); // ignorado, no permite duplicados 
  colores.Add("Azul"); // ["Rojo", "Azul"]  

