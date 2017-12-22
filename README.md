# kokotimeApp
Public files of the Kokotime App, not the source code of the app itself but the shared files like string resources etc...
Feel free to add and push translations of the strings.xml file and they will be added to support multiple languages in the app.
Any officialy publicly shared files will later be added here.

## Creating translations

To create a translation for Kokotime simply copy and paste the `strings.xml` file and translate **Only the values** of each tag not the name. 
You can then rename the file `strings-lc.xml` where `lc` is the two letter language code of your translation.

For example :

`<string name="extra_options">More</string>` in `strings.xml`

will be :

`<string name="extra_options">Plus</string>` in `strings-fr.xml`



## Correcting errors is string files

You can also correct any translations by reading the files and correcting any spelling or grammar issues if you are certain of these corrections this will help to get the best translations.
