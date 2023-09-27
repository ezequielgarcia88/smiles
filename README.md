# Smiles
Consultar la API de Smiles buscando los vuelos más baratos con millas

### Como usarlo
- Descargar del último release el programa compatible con tu sistema operativo y arquitectura
- Ejecutar por línea de comando enviando parámetros: `Origen Destino FechaDeSalida FechaDeVuelta DíasCorridosAConsultar`
- - Ejemplo: `smiles CDG EZE 2023-12-11 - 1`

### Ejecutar directamente desde el código fuente
- Instalar Go
- Clonar el repositorio
- Configurar parámetros al comienzo de `main.go`
- `go run main.go CDG EZE 2023-12-11 - 1`
