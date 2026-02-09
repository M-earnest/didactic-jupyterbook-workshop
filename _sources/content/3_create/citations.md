# Adding Citations and Bibliographies

To include citations in your course website, begin by creating a BibTeX file to store your references. Then, check the `_config.yml` file to ensure that the file is linked correctly. Once set up, you can easily add citations and generate a bibliography to enhance your course content.

## Create a Bibliography

Create a new file in your repository and save it with the `.bib` extension to create a BibTeX file. 

![Image of how to name the bibtex file](../../static/bib-file-name.jpg)

Then, add your references to the file and click on "Commit changes".

![Image of the newly created bibtex file with one example reference.](../../static/bib-file.png)


## Check the Config File

Open the `_config.yml` file and ensure that the linked BibTeX file is correct. By default, its name is "references.bib". 

![Image of the config.yml file, in which the BibTeX file is included as described.](../../static/config_bibtex.png)

```{note}
If the file is located in a different folder, make sure to include the correct path.
```

## Add a Citation
Now, you can include your citations into your text with help of the `{cite}` role. Here is an example:

```
{cite}`munafo2017manifesto`
```

Result:
{cite}`munafo2017manifesto`

## Add a Bibliography 

To add a bibliography, you need to use the `{bibliography}` directive at the end of your page: 
````
```{bibliography}
```
````
At the end of this page, you will see an example bibliography.


## Next Section:
In the next section, you will learn how to adapt the Table of Content file in order to structure your online course.

----

**References**
```{bibliography} 
```

