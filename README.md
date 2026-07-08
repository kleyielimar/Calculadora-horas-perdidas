# Calculadora de Horas Perdidas

Mini herramienta interactiva de Kleyi Elimar para estimar cuanto tiempo y dinero puede estar perdiendo un negocio por desorden operativo, seguimiento manual e informacion dispersa.

## Publicacion

Esta pagina esta preparada para GitHub Pages.

## Supabase

El archivo `supabase-setup.sql` crea la tabla `calculadora_horas_leads` y las politicas necesarias para permitir inserciones anonimas desde la calculadora sin permitir lectura publica de los datos.

No uses la `service_role key` en el codigo publico. Solo se debe usar la `anon public key`.
