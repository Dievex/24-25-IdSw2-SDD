[![](https://img.shields.io/badge/-Inicio-FFF?style=flat&logo=Emlakjet&logoColor=black)](/README.md) [![](https://img.shields.io/badge/-Entrega_1-FFF?style=flat&logo=openstreetmap&logoColor=black)](https://github.com/oscarsantasanchez/24-25-IdSw2-SDD/blob/main/documentos/entregas.d.md) [![](https://img.shields.io/badge/-Entrega_2-FFF?style=flat&logo=openstreetmap&logoColor=black)](https://github.com/oscarsantasanchez/24-25-IdSw2-SDD/blob/main/documentos/entregas.dM.md)  [![](https://img.shields.io/badge/-Entrega_3-FFF?style=flat&logo=openstreetmap&logoColor=black)](https://github.com/oscarsantasanchez/24-25-IdSw2-SDD/blob/entrega3/documentos/entregas.dOO.md)  [![](https://img.shields.io/badge/-Entrega_4-FFF?style=flat&logo=openstreetmap&logoColor=black)]()


# 🧬 Diseño Orientado a Objetos 

## 1. Principios Aplicados

| Principio | Aplicación en el Proyecto | Ejemplo |
|-----------|---------------------------|---------|
| **Abstracción** | `ComponenteHoja` como clase abstracta | Define métodos comunes para todas las componentes |
| **Encapsulación** | Atributos privados con métodos accesores | `Celda` oculta implementación de formato interno |
| **Herencia** | Jerarquía de clases base y especializadas | `ComponenteHoja` → Clases concretas |
| **Polimorfismo** | Métodos con implementaciones específicas | `mostrarContenido()` en diferentes contextos |



| Diseño orientado a objetos|
|-|
|![Jerarquizacion](/images/modelosUML/DiseñoObjetos.svg)

## 2. 🔗 Relaciones entre Clases

| Tipo | Clases Involucradas | Diagrama |
|------|---------------------|----------|
| **Herencia** | `ComponenteHoja` → Clases hijas | ![Herencia](/images/modelosUML/DiagramaHerencia.svg) |
| **Composición** | `Matriz` → `Celda` | ![Composicion](/images/modelosUML/DiagramaComposicion.svg) |
| **Agregación** | `HojaCalculo` → `Matriz` | ![Agregacion](/images/modelosUML/DiagramaAgregacion.svg) |

## 3. 🛠️ Patrones de Diseño

| Patrón | Aplicación | Beneficio |
|--------|------------|-----------|
| **Singleton** | `Teclado` (una única instancia) | Control centralizado de entrada |
| **Observer** | Actualización de la vista al modificar celdas | Sincronización modelo-vista |
| **Factory** | Creación de celdas con diferentes formatos | Extensibilidad de tipos |

## 4. ✅ Cumplimiento de Principios 

| Principio | Cumplimiento | Ejemplo |
|-----------|--------------|---------|
| **SOLID** | 🟢 85% | S: Clases con única responsabilidad |
| **DRY** | 🟡 70% | Algo de código repetido en validaciones |
| **Ley de Demeter** | 🟢 90% | Bajo acoplamiento entre componentes |

<div align=center>


</div>
