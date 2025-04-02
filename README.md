# MOODLE
### **Configuración del Moodle**  

1 **Inicia sesión en Moodle como admin y haz estos cambios:**  

- **Cambia tu email, contraseña y foto de perfil** (avatar).  
   - Ve a tu perfil (arriba a la derecha), dale a **Editar** o entra en **Preferencias**.  
(Captura desde 2025-03-19 12-39-11.png)
- **Cambia el nombre del sitio (largo y corto) y oculta la página principal a los no registrados.**  
   - Ve a **Administración del sitio > Primera plana > Parámetros**.  

- **Asegúrate de que la zona horaria del sitio es la correcta.**  
   - Esto se cambia en **Administración del sitio > Ubicación > Parámetros**.  
   - Importante para que los plazos de entrega sean correctos.  

- **Cambia el idioma del Moodle.**  
   - Ve a **Administración del sitio > Idioma > Parámetros**.  
   - Activa la detección automática y elige el idioma por defecto.  
   - Si no está el idioma que quieres, primero tienes que instalarlo en **Administración del sitio > Idioma > Paquetes de idioma**.  

- **Modifica las reglas de contraseñas.**  
   - Pon que las nuevas contraseñas tengan mínimo 4 caracteres y al menos una mayúscula, una minúscula y un número.  
   - Cambia esto en **Administración del sitio > Seguridad > Normativas del sitio**.  

---

2 **Crea cursos en Moodle:**  
- **Curso A** con **3 temas**.  
- **Curso B** con **5 temas**.  
Se hace en **Administración del sitio > Gestiona cursos y categorías** o en **Navegación > Cursos > Añadir curso**.  

---

3 **Añade contenido a los cursos:**  
- Entra a un curso creado y sube algún material (por ejemplo, un **PDF**).  
- Cámbiale el título a algún tema.  
- Activa el **modo edición** y explora opciones.  

No vamos a ver todas las herramientas en detalle porque eso lo hace más el profe que el admin, pero viene bien conocerlas.  

---

4 **Crear usuarios y alumnos**  

- **Crea a mano un usuario llamado "Bob"** con autenticación manual.  
   - Se hace en **Administración del sitio > Usuarios > Cuentas > Añadir usuario**.  

- **Crea 10 alumnos y añádelos a los cursos A y B con un archivo CSV.**  
   - Sube el CSV en **Administración del sitio > Usuarios > Cuentas > Cargar usuarios**.  
   - Si no sabes cómo hacer el archivo CSV, revisa la sección de Usuarios más abajo.  

- **Elimina 2 alumnos de los 10 creados.**  
   - Usa **Administración del sitio > Usuarios > Acciones en bloque**.  

---

5 **Matricular usuarios en los cursos**  

- **Curso A:**  
   - No permitas inscripciones, solo acceso como visitante (será público sin usuarios registrados).  

- **Curso B:**  
   - Solo admin puede inscribir manualmente a los alumnos.  
   - Cambia esto en **Administración del curso > Usuarios > Métodos de inscripción**.  
   - Si no aparece la opción, actívala en **Administración del sitio > Conectores > Autenticación**.  

- **Asigna a "Bob" como profe del curso B y matricula a los alumnos creados.**  
   - Ve a **Administración del curso > Usuarios inscritos > Inscribir**.  

- **Comprueba que el curso A es público y que el curso B solo se ve con cuenta registrada.**  

---

6 **Cambia el diseño del Moodle**  

- Descarga y activa un **tema nuevo** (no uses los que vienen por defecto).  
- Cambia la **cabecera y el pie de página**.  
   - Ve a **Administración del sitio > Conectores > Instalar complemento**.  
   - Luego cambia el tema en **Administración del sitio > Apariencia > Temas > Selector de temas**.  
- Usa la opción **"Cambio de rol"** en el menú para ver cómo se ve el sitio como alumno o profe.  

---

7 **Asigna un profe y matricula alumnos en el curso A.**  

8 **Añade contenido en el curso A:**  
- Activa el **modo edición** y sube diferentes tipos de actividades.  
- Crea una **tarea con entrega de PDF** y ponle fecha límite.  

9 **Entra como alumno y comprueba que se puede entregar la tarea.**  

---

### **Contenidos**  

**En el curso A:**  
- Crea una **UF (Unidad Formativa)** con **2 NF (Núcleos Formativos)** dentro.  
- Agrega actividades (tanto **teóricas** como **evaluables**).  
   - Mínimo: **1 entrega y 1 cuestionario**.  
- Cambia el **formato del curso a "Temas"** en **Administración del Curso > Editar Curso > Formato del Curso**.  
- Usa **el Moodle del Puig** como referencia.  
- **Copia el curso A en el curso B** usando **Administración del Curso > Importar** desde el curso B.  

---

### **Notas y calificaciones**  

**En el curso A:**  
- Completa todas las tareas con un usuario alumno.  
- Corrige y pon notas con el usuario profesor.  
- Configura el **calificador** para que genere automáticamente la nota de la UF.  
   - Esto se hace en **Administración del Curso > Configuración de calificaciones**.  

- **Crea una insignia y asígnala a un alumno.**  
   - Se hace en **Administración del sitio > Insignias**.  

---

### **Cuestionarios**  

- **Crea un cuestionario** y añade preguntas desde el **banco de preguntas**.  
- Organiza el banco con **categorías** y mete preguntas en cada una.  
- Al hacer el cuestionario, selecciona preguntas del banco.  
- **Responde el cuestionario como alumno** y revisa las notas como profesor.  

---

**¡Listo! Ahora tienes Moodle configurado con cursos, alumnos, contenido y evaluaciones.**
