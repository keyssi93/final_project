![idata_eafit](readme_img/logos.png "idata_eafit")



<!-- ABOUT THE PROJECT -->
## About The Project

<!--[![Product Name Screen Shot][product-screenshot]](https://example.com)-->

![idata_eafit_diapo](readme_img/4_ps.PNG "idata_eafit_diapo")



Con este proyecto nosotros queremos agregar valor agregado que contribuya con el crecimiento de la empresa por medio de las nuevas tecnologias.


### Built With

* [Databricks](https://databricks.com/)
* [spacy](https://spacy.io/usage)
* [t-SNE](https://interactivechaos.com/es/manual/tutorial-de-machine-learning/t-sne)

### Team
* [Luis Felipe Bedoya Martinez](https://www.linkedin.com/in/felbed/)
* [Keyssi Margarita Arroyo Mendez](https://www.linkedin.com/in/keyssi-m-arroyo/)
* [Yoban Steban Nova Aranda](https://www.linkedin.com/in/yoban-nova-aranda-7a56ba1b2/)
* [Diego Alejandro Zapata Marin](https://www.linkedin.com/in/diegoaengineer/)
* [Faiber Andres Montes Gomez](https://www.linkedin.com/in/faiber-andres-montes/)


### Workflow

Dado que en nuestro caso nos enfocaremos en agrupar y sintetizar los requerimientos en las subcategorias recomendadas de acuerdo al historico de las mismas utlizaremos NLP para dicho objetivo, como se envidencia a continuacion estas son las caracteristicas de un Model de procesamiento de lenguaje natural 

![idata_eafit_nlpworkflow](readme_img/nlp_worflow.png "idata_eafit_nlpworkflow")

### Results and conclutions 
![idata_eafit_conjunto](readme_img/output_productos.png "idata_eafit_cojuntodedatos")

Al correr el model diseñado con la libreria spacy, especializada en NLP pudimos obtener estas metricas del modelo:


![idata_eafit_metrics](readme_img/mtrics.PNG "idata_eafit_metricas")


Al ver su funcionamiento en un escenario real, tenemos que los 0 son los no predichos correctamente:

![idata_eafit_metrics](readme_img/result.PNG "idata_eafit_metricas")

y aqui podemos observar algunos de ellos que no se predijeron bien, cabe resaltar que al parecer puede que en la muestre esten mal clasificados por lo que el algoritmo lo aprendio de esta forma, como no podemos concluir en este punto del modelo, como proximo paso se propone indagar dentro de los productos o servicios en que subcateoria estan para asi afianzar nuestro modelo 

![idata_eafit_resultados](readme_img/test.PNG "idata_eafit_resultados")

Estos resultados probablemente se den tambien por el desbalance en las Subcategorias

![idata_eafit_subcategoria](readme_img/subcategoria.PNG "idata_eafit_subcategoria")

![idata_eafit_resultado](readme_img/resultado.PNG "idata_eafit_resultado")

![idata_eafit_outpu](readme_img/output_modelo.PNG "idata_eafit_output")



**Proximos pasos**
* Recolección de más datos​
* Reentrenamiento  y afinamiento del modelo​
* Generacion de web en base a tecnología React para despliegue y uso del modelo 








