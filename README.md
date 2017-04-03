# Platzom

Platzom es un idioma inventado para el [Curso de Fundamentos de Javascript](https://platzi.com/js) de [Platzi](https://platzi.com), el mejor lugar de educación online

## Descripción del idioma

- Si la palabra termina en "ar", se le quitan esos dos caracteres
- Si la palabra inicia con Z, se le añade "pe" al final
- Si la palabra traducida tiene 10 o más letras se debe partir por la mitad y unir con un guión en medio
- Si la palabra original es un palíndromo, ninguna regla anterior cuenta y se devuelve la misma palabra intercalando mayúsculas y minúsculas

## Instalacion

```
npm install vsplatzom
```

## Uso
```
import platzom from 'platzom'

platzom("Programar")	// Program
"Programar" 			// Program
"Zorro" 				// Zorrope
"Zarpar" 				// Zarppe
"abecedario" 			// abece-dario
"sometemos" 			// SoMeTeMoS
```

## Créditos
- [Vicente Soriano](https://twitter.com/Wicens)

## Licencia
[MIT](https://opensource.org/licenses/MIT)

