
# 🧠 MultiChain Wallet Balance Checker

**Versión gratuita de código cerrado para uso experimental**  
Escanea frases semilla al azar y comprueba saldos en múltiples redes como Ethereum, BSC, Polygon, Arbitrum y Avalanche.

---

## ⚠️ AVISO IMPORTANTE DE DESCARGA DE RESPONSABILIDAD

> ⚠️ **Este software se proporciona solo con fines educativos y experimentales.**
>
> Ni su autor ni colaboradores se hacen responsables por el uso que se le dé a esta herramienta.
>
> **El uso de esta aplicación es bajo tu propio riesgo.**  
> Puedes comprobar su funcionamiento con frases semilla reales.
> Si encuantra una frase semilla con saldo por favor se responsable con su uso y nunca la hagas publica.
> Otra persona podria darle un mal uso o reutilizar sus fondos  
> **úsalo con precaución**.

---

## 🧩 ¿Qué hace esta app?

- Genera **frases mnemotécnicas** (BIP39) aleatorias.
- Deriva la dirección Ethereum/BSC/Polygon.
- Consulta automáticamente los saldos usando endpoints públicos.
- Permite comprobar frases o direcciones manualmente.
- Muestra logs, estadísticas y guarda los hallazgos en `wallets_con_saldo.txt` dentro de la carpeta documentos.

---

## 🧪 ¿Puedo encontrar una billetera con saldo?

**Es muy improbable.**  
La posibilidad de encontrar una cartera real con saldo por fuerza bruta es **muy dificil**, puedes tener suerte y encontrar una billetera o utilizar el programa durante mucho tiempo sin encontrar ninguna, es cuestion de suerte, el programa es GRATUITO y **funciona correctamente** y podría servir con fines educativos, demostrativos o como parte de un estudio teórico.

---

## 🛠 Requisitos

- Windows 7 o superior
- No requiere instalación de Python (es un `.exe`)
- No necesitas claves ni registrarte

---

## 📦 Configuración recomendada

| Opción                         | Valor Recomendado |
|----------------------------------------|-------------------|
| Palabras por frase semilla             | `24`              |
| Tiempo entre escaneos (ms)             | `200`             |
| Número de hilos para RPC               | `2`               |
| Número de workers simultáneos          | `2`               |
| Reiniciar workers cada (N wallets):    | `2000`            |


> Puedes modificar estos parámetros en la pestaña `Configuración`.

---

## 🔗 Endpoints

Los endpoints RPC son las conexiones con las redes. Puedes usar:

- `https://ethereum.publicnode.com`
- `https://bsc-dataseed.binance.org/`
- `https://polygon-rpc.com`
- `https://arb1.arbitrum.io/rpc`
- `https://mainnet.optimism.io`
- `https://api.avax.network/ext/bc/C/rpc`

> Asegúrate de que estén activos. Puedes desactivar alguno si no lo necesitas.

---

## 📷 Capturas

### ✅ Ventana principal
![Principal](images/PRINCIPAL.jpg)

### ⚙️ Configuración
![Configuración](images/CONFIGURACION.jpg)

---

## 📥 Descarga

El ejecutable se encuentra en la sección de Releases o en tu carpeta de instalación personalizada. Puedes copiar la carpeta completa a otra máquina.

> No es necesario instalar nada adicional.

---

## 🧼 Recomendaciones

- Ejecuta como usuario normal (no administrador).
- No compartas el ejecutable, compártelo empaquetado con esta documentación.
- Algunos antivirus podrían marcarlo como sospechoso por usar PyInstaller y escaneo de red: **esto es un falso positivo**.

---

## ✅ Estado de detección (Jotti)

Revisión antivirus:  
1/13 antivirus lo marcó, la mayoría lo considera **seguro**.
