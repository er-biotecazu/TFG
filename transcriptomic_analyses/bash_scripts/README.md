# Detalle sobre la ejecución de los *scripts*

* [01_lablog_fastQC](https://github.com/er-biotecazu/TFG/blob/main/transcriptomic_analyses/bash_scripts/01_lablog_fastQC): análisis de calidad de las lecturas con la herramienta fastQC. 
* [01_lablog_fastp](https://github.com/er-biotecazu/TFG/blob/main/transcriptomic_analyses/bash_scripts/01_lablog_fastp): análisis de calidad de las lecturas, eliminación de los adaptadores y filtrado de calidad con la herramienta fastp.
* [02_lablog_trimmomatic](https://github.com/er-biotecazu/TFG/blob/main/transcriptomic_analyses/bash_scripts/02_lablog_trimmomatic): eliminación de los adaptadores con la herramienta Trimmomatic (no necesario si se emplea fastp).
* [03_lablog_post_fastQC](https://github.com/er-biotecazu/TFG/blob/main/transcriptomic_analyses/bash_scripts/03_lablog_post_fastQC): análisis de calidad de las lecturas sin los adaptadores con la herramienta fastQC (no necesario si se emplea fastp).
* [04_lablog_remove_host_reads](https://github.com/er-biotecazu/TFG/blob/main/transcriptomic_analyses/bash_scripts/04_lablog_remove_host_reads): eliminación de las lecturas de la planta huésped con Bowtie 2. Este paso no se realiza si las lecturas provienen del cultivo axénico.
* [05_lablog_STAR](https://github.com/er-biotecazu/TFG/blob/main/transcriptomic_analyses/bash_scripts/05_lablog_STAR): alineamiento de las lecturas al genoma de referencia utilizando el alineador STAR.
* [06_lablog_htseq-count](https://github.com/er-biotecazu/TFG/blob/main/transcriptomic_analyses/bash_scripts/06_lablog_htseq-count): recuento de las lecturas por gen del hongo utilizando htseq-count.
