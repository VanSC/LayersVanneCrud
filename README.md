## para busqueda de productos

var result = product.Where(x => x.name.IndexOf(name, StringComparison.OrdinalIgnoreCase) >= 0).ToList();

