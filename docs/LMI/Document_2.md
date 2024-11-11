# Identificació dels espais de noms en documents (AndroidManifest.xml). Aquest article es podria combinar amb l'anterior.

* Esquema sobre Espais de Noms en AndroidManifest.xml

    1. __Definició d'espais de noms en XML__

        * Permeten organitzar i diferenciar etiquetes/atributs.

        * Eviten conflictes entre elements amb el mateix nom.

    2.  __Espais de noms principals en AndroidManifest.xml__
        
        * xmlns<br>
        <br>
        Associat a les funcions i atributs del sistema Android.
        
           <br> ``` Exemples: android:versionCode,android:versionName ```
          

        * Espais de noms personalitzats: <br>
        <br>
        Per a biblioteques externes.

            <br> ```Exemples: xmlns:tools per a eines de desenvolupament. ```<br>
            <br> 

    3. __Relació amb el desenvolupament d'aplicacions__
        Aplicacions natives: Utilitzat per definir permisos i components.
        Aplicacions híbrides: També present en frameworks com React Native o Flutter.

    4. __Conflictes d'espais de noms__
        Eviten conflictes entre atributs de diferents components o llibreries.

    5. __Resum combinat__
        Els espais de noms són clau per gestionar atributs i evitar conflictes en aplicacions Android, tant nadiues com híbrides.


