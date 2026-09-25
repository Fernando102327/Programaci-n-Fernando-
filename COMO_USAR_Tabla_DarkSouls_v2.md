# Tabla Dark Souls Remastered v2 (Cheat Engine)

Archivo: `Tabla_DarkSouls_v2.CT`. Solo para el modo **offline**: usar trucos en línea puede hacer que te baneen.

## Pasos

1. Abre el juego y **carga tu partida** (tu personaje tiene que estar en el mundo).
2. Abre Cheat Engine, selecciona el proceso `DarkSoulsRemastered.exe` y carga la tabla.
3. Activa **"0) ACTIVAR PRIMERO: Inicializar"**. Esto busca los punteros del juego y
   te dice en la ventana de Lua si los encontró.
4. Activa lo que quieras:

| Truco | Tecla | Qué hace |
|---|---|---|
| Vida Infinita | F1 | Mantiene tu HP al máximo |
| Estamina Infinita | F2 | Mantiene tu estamina al máximo |
| Almas Infinitas | F3 | Mantiene tus almas en 9,999,999 como mínimo |
| Matar de un Golpe | F4 | Mantiene el HP del enemigo en 1 (ver abajo) |
| Velocidad x0.5 / x1.5 / x2 / x3 | F5 / F6 / F7 / F8 | Speedhack de Cheat Engine. Al desactivarlo vuelve a x1 |

## Matar de un golpe

Aquí hay que poner la dirección a mano (igual que en tu primera tabla):

1. Pégale a un enemigo y busca su HP (First Scan con *Unknown initial value*,
   luego *Decreased value* cada vez que le pegues).
2. Cuando te quede la dirección, pégala en **"HP del Enemigo (manual)"**,
   dentro de *Direcciones manuales*.
3. Activa **Matar de un Golpe (F4)**. Ese enemigo queda con 1 de HP y cae al siguiente golpe.

## Si la inicialización falla

Si el juego se actualizó, puede que los patrones AOB ya no coincidan. En ese caso:
busca tu HP, estamina o almas con un escaneo normal y pega las direcciones en
*Direcciones manuales (plan B)*. Los trucos usan esas direcciones automáticamente.
