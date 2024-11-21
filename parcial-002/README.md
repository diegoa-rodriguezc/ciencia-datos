# Universidad de los Andes
## MINE-4101: Ciencia de Datos Aplicada
### Parcial 2: Clínica de los Alpes
  
**Integrante:**  
- Diego Alberto Rodríguez Cruz
  
**Contexto:**

Contexto: Clínica de los Alpes
La Clínica de los Alpes es una IPS colombiana con varios años de operación en la capital. Esta institución posee varias unidades de cuidado especializado para pacientes con diferentes tipos de patologías y necesidades de atención.

Sin embargo, al igual que muchas entidades de las mismas características, uno de los mayores problemas que enfrenta la Clínica es el de los reingresos médicos. Un reingreso médico ocurre cuando un paciente que se ha dado de alta debe ser nuevamente admitido por complicaciones relacionadas con su ingreso original en plazos de 30 días, 90 días o hasta un año, de acuerdo con las definiciones de la OMS.

Los reingresos son problemáticos porque aumentan la carga financiera sobre la clínica, añadiendo costos acumulativos de cuidado, bloqueando el uso eficiente de recursos para atender a otros pacientes, generando en sobrecostos para las facturas médicas que deben pagar los pacientes, causando impactos físicos y emocionales; y en últimas ocasionando pérdida de confianza en la institución de salud.

Por esta razón la Clínica de los Alpes ha financiado un proyecto de Inteligencia Artificial con el propósito de detectar cuando un paciente que está a punto de ser dado de alta tiene un riesgo considerable de reingreso y por lo tanto requiere atención adicional. En la fase inicial del desarrollo de una herramienta de detección de riesgos de reingresos, la clínica ha decidido concentrarse en los pacientes con diabetes, una de las condiciones de salud de pacientes que se ve asociada con un mayor riesgo a ser reingresado por complicaciones. El equipo de desarrollo ha decidido emplear un conjunto de datos de pacientes con esta enfermedad.
  
**Dependencias:**  

- `pip install pandas`
- `pip install numpy`
- `pip install scikit-learn`
- `pip install matplotlib`
  
**Estructura:**  

```plaintext
parcial-002/
├── data/
│   └── diabetes_data_complete.csv
├── doc/
│   ├── Data_dictionary.xlsx
│   └── Parcial 2 - Enunciado Inicial.pdf
├── img/
│   └── uni_facultad.png
├── .gitignore              
├── parcial-002.ipynb
└── README.md
```
