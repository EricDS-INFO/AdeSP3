# ADMINISTRACIÓN DE SISTEMAS | PRÁCTICA 3

**Gestión de usuarios y recusros en Windows 2012 - Dominio Raíz**

![Imagen de portada con el logo de Active Directory](./images/portada.png "Active directory logo")

> Por: Éric Dürr Sierra ( [alu0101027005](alu0101027005@ull.edu.es) )


El siguiente documento pretende **recopilar todo el proceso** llevado a cabo para el desarrollo
de la práctica del bloque de administración de sistemas en **Windows**. Concretamente se expone el desarrollo del servidor raíz **( CD1ASXT09 | astxt09.local )**.

Se detallarán más en 
profundidad aquellos aspectos que sean pertinentes al volumen teórico de la asignatura al igual 
que se resumirán aquellos aspectos más secundarios o que puedan resultar obvios.

<br>
<br>
<br>
<br>
<br>
<br>

***

**Índice**

1. [Introducción](#id1)
2. [Situación de la organización](#id2) 
3. [Diseño de la estructura de la organización](#id3)
4. [Creación y adecuación del dominio raíz (CD1ASXT09)](#id4)
5. [Contenido](#id5)
    - [Administración de las directivas](#id5_1)
    - [Administración de los empleados](#id5_2)
    - [Administración de los grupos](#id5_3)  
    - [Administración de los prtoyectos](#id5_4)
    - [Administración de los recursos](#id5_5)

6. [Script de automatización de nuevos usuarios (parte opcional)](#id6)
7. [Problemas encontrados](#id7)
8. [Conclusión](#id8)
9. [Bibliografía y referencias](#id9)

***



<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<div id="id1"\>

## 1. Introducción

Principalmente se abordará la creación de un entorno basado en Windows 2012 que deberá soportar un número determinado de usuarios, grupos globales, grupos locales y directorios a fin de organizar cuatro proyectos. dos de ellos hospedados en el dominio raíz y los otros dos sencillamente considerados a través de los grupos globales, ya que se encuentran en otro dominio.

Los proyectos que residen en este dominio (el raíz) son el de Auditorio y el de Aeropuerto, además de los cinco de diez empleados ( 1, 2, 3, 7, 8) que participarán y dirigirán los mismos.

Algunas palabras claves con las que vincular este proyecto son:

+ Directorio Activo
+ Windows Server 
+ Escritorio remoto
+ Administrador del servidor
+ Herramientas del servidor
+ DNS
+ Directivas
+ Propiedades
+ Powershell
+ Grupos globales
+ Grupos locales
+ Dominios
+ Unidades Organizativas


<br>
<br>
<div id="id2"\>

## 2. Situación de la organización


<br>
<br>
<div id="id3"\>

## 3. Diseño de la estructura de la organización


<br>
<br>
<div id="id4"\>

## 4. Creación y adecuación del dominio raíz (CD1ASXT09)


<br>
<br>
<div id="id5"\>

## 5. Desarrollo de los requisitos de la organización

<br>
<div id="id5_1"\>

### 5.1. Administración de las directivas

<br>
<div id="id5_2"\>

### 5.2. Administración de los empleados

<br>
<div id="id5_3"\>

### 5.3. Administración de los grupos 

<br>
<div id="id5_4"\>

### 5.4. Administración de los proyectos

<br>
<div id="id5_5"\>

### 5.5. Administración de los recursos


<br>
<br>
<div id="id6"\>

## 6. Script de automatización de nuevos usuarios (parte opcional)


<br>
<br>
<div id="id7"\>

## 7. Problemas encontrados


<br>
<br>
<div id="id8"\>

## 8. Conclusión


<br>
<br>
<div id="id9"\>

## 9. Bibliografía y referencias

- [Documentio de instalación AD-IAAS](https://docs.google.com/document/d/15JZq7p0MvTtbSuf2MSbrIWJU1r4rQ4hbt6SVHWZztfA/edit#heading=h.gjdgxs)
- [Documento de instalación de Máquina windows en el IAAS](https://docs.google.com/document/d/1a5MTotTzvvbbTr_sxEkYUZFSHWXny6aEAc_uIWfCs3E/edit)
- [Manual de Active Directory](https://activedirectoryenwindows.blogspot.com/)
- [Documentación de Windows 10 y Windows Server 2016 para PowerShell](https://docs.microsoft.com/en-us/powershell/windows/get-started?view=win10-ps)
- [Tutorial de creación de usuarios en AD mediante PowerShell](https://blog.netwrix.com/2018/06/07/how-to-create-new-active-directory-users-with-powershell/)
- [Uso de CVS en PowerShell | Documentación de Microsoft](https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.utility/import-csv?view=powershell-7)