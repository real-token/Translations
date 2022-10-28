# Translations

The public repository allows our community to participate in the translation of the texts of the various apps that RealT creates for the ecosystem

# File translation

The language files are in [JSON format](https://fr.wikipedia.org/wiki/JavaScript_Object_Notation)

the translation must be exclusively done on the right part (value) the left part is a key, it must be modified only by the project dev

# Create support for a new language

In the appropriate project folder, e.g. for the "Realtoken YAM" ./YAM/locales/

modify the file "index.ts" to add the path to the language you create, for example for Portuguese :

original file:

    import  en  from  './en';
    import  es  from  './es';
    import  fr  from  './fr';

    export  const  resources = { en, es, fr };

file modify to add PT:

        import  en  from  './en';
        import  es  from  './es';
        import  fr  from  './fr';
        import  pt  from  './pt';

        export  const  resources = { en, es, fr, pt };

create a sub-folder with the 2-letter code of the language, example for Portuguese "PT".

Then copy the files and file contents of the EN version (always copy this reference version) into the new folder "PT".

Modify the values to perform the translation
