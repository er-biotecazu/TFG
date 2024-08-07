# Repositorio TFG - Eric Torres
Este repositorio recoge algunos de los *scripts* desarrollados durante la realización de mi Trabajo Fin de Grado (TFG) para la obtención del título de Graduado en Biotecnología por la Universidad Politécnica de Madrid

El TFG lleva por título «Análisis genómico y transcriptómico del hongo endófito *Colletotrichum tofieldiae* en interacción con *Zea mays* y *Arabidopsis thaliana*» y ha sido tutorizado por la Dra. Soledad Sacristán Benayas y la Dra. Sandra Díaz González. 

## Abstract 
Endophytic fungi are ubiquitously distributed organisms that colonise internal plant tissues conferring several benefits including plant growth promotion and enhanced protection against biotic and abiotic stresses. In recent years, endophytic fungi have gained a lot of attention and advances in high-throughput sequencing technologies have shed light on the complexities of plant-endophyte interactions. However, many of these studies have primarily focused on the host plant, leaving the molecular mechanisms deployed by the fungus relatively unexplored. *Colletrotrichum tofieldiae* strain 0861 (*Ct*0861) is an endophytic fungus originally isolated from *Arabidopsis thaliana* surface-sterilised leaves. Different studies have shown that this fungus is able to colonise the roots of both *A. thaliana* and other agronomically valuable hosts, providing several fitness advantages to the plants.

In this study, the genome of *Ct*0861 has been characterised in five different functional categories typically involved in host plant colonisation and interaction: secreted CAZymes, secreted proteases, effectors, transporters and genes involved in secondary metabolite biosynthesis. An RNA-Seq experiment was conducted to obtain transcriptomic data of the fungus interacting with maize at two different timepoints. The results obtained were used to perform a differential gene expression analysis. Functional categories within the differentially expressed genes were examined and functional enrichment analyses using Gene Ontology (GO) terms were performed. The same pipeline was applied to a second host plant, *A. thaliana*, from previously published raw transcriptomic data, allowing the comparison between the findings obtained in both hosts.

Overall, this study demonstrates that the genome of *Ct*0861 encodes extensive repertoires of genes across the different functional categories examined. These genes play crucial roles during the interaction with both hosts, as evidenced by the transcriptomic analyses. However, not all of them participate at the same level in the interaction with the plant: some genes, such as those encoding secreted proteases and transporters are highly induced during host colonisation at different timepoints and hosts, while genes involved in secondary metabolite biosynthesis exhibit low expression levels in planta, despite the high biosynthetic capacity of *Ct*0861.

The comparative analyses of *Ct*0861 transcriptomes in both host plants and at different timepoints reveal distinct temporal dynamics and functions, suggesting divergent strategies for the colonisation and establishment of trophic interactions with different hosts. The results from the GO enrichment analysis also highlight the relevance of polysaccharides metabolism and transport in the interaction of *Ct*0861 with the different hosts and across various timepoints. The insights gained with this work pave the way to future research aimed at elucidating the molecular bases of endophytism.

<p align="center">
  <img width="500" height="290" src="https://github.com/er-biotecazu/TFG/assets/145058927/cf78138d-da9b-4e73-99c7-87640a7fcd2f">
</p>

## Guía del repositorio 
Este repositorio se divide en dos carpetas principales, en función de la naturaleza de los análisis. Por una parte, los *scripts* utilizados para la caracterización genómica de *Ct*0861 ([genomic_analyses](https://github.com/er-biotecazu/TFG/tree/main/genomic_analyses)). Los programas incluidos en esta carpeta están destinados a obtener información a nivel funcional con el objetivo de anotar el genoma en distintas categorías de genes potencialmente involucradas en la interacción planta-hongo. 

Por su parte, la carpeta con los análisis transcriptómicos ([transcriptomic_analyses](https://github.com/er-biotecazu/TFG/tree/main/transcriptomic_analyses)) contienen *scripts* con los que se procesan las lecturas generadas por distintos experimentos de RNA-Seq y se lleva a cabo un análisis de expresión diferencial de genes. Además, se presenta un análisis de componentes principales. 

Cada una de las subcarpetas contienen archivos README con información específica sobre la finalidad de los *scripts*. 
