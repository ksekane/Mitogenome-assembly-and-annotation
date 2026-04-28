#Mitogenome assembly and annotation, and phylegenetic tree construction

#Description
This project involved the assembly and annotation of the mitochondrial genome of Poroderma africanum, a catshark species endemic to southern Africa. Raw sequencing data were processed to generate a complete mitogenome, which was then annotated to identify key genomic features, including protein-coding genes, ribosomal RNAs, transfer RNAs, and control regions.

To investigate evolutionary relationships, the annotated mitogenome was incorporated into a comparative dataset comprising mitochondrial genomes from 59 shark species. Multiple sequence alignment and phylogenetic analyses were performed to construct a phylogenomic tree, providing insights into species divergence and evolutionary patterns within elasmobranchs. The resulting tree highlights the phylogenetic placement of P. africanum and contributes to a broader understanding of shark evolutionary history.

#Objectives
-To assemble the complete mitochondrial genome of Poroderma africanum from raw sequencing data.
-To accurately annotate the mitogenome by identifying protein-coding genes, rRNAs, tRNAs, and regulatory regions.
-To compile a comparative dataset of mitochondrial genomes from 59 shark species.
-To perform multiple sequence alignment of mitogenomic data for phylogenetic analysis.
-To construct a robust phylogenomic tree to infer evolutionary relationships among shark species.
-To determine the phylogenetic placement of P. africanum within the broader elasmobranch lineage.
-To contribute to the understanding of shark evolution and mitochondrial genome diversity.

#Tools & Technologies
- Minimap
- Flye
- MitoHifi
- MitoAnnotator
- SeqKit
- Mafft
- MrBayes
- iTOL

#Project Structure
- scripts/ → code files
- results/ → outputs

#How to Run
1. Clone the repository
git clone https://github.com/ksekane/Mitogenome-assembly-and-annotation.git
cd Mitogenome-assembly-and-annotation

2. Install dependencies
Minimap (map sewuencing reads to reference mitogenome)
Flye(assembly into contigs)
MitoHifi (assembly into mitogenome)
MitoAnnotator (annotation)
Seqkit (removing tRNA, rRNA, and control regions and keeping protein coding genes)
MAFFT (alignment)
MrBayes (tree construction)

3. Map raw reads to reference mitogenome
4. Assemble mitogenome
5. Annotate mitogenome
6. Remove tRNA, rRNA, and control regions
7. Align 59 protein coding sequences
8. Construct phylogenomic tree
9. Visualise using tools such as ITOL

#Results
The retrieved mitogenome of the pyjama shark was 16 692 bp with 13 protein coding genes, 2 rRNAs, 22 tRNAs and a GC content of 39%. As expected, pyjama sharks clustered in the order Carcharhiniformes within the Scyliorhinidae family, and was sister-species to Poroderma pantherinum. The pyjama shark mitogenome along with the reconstruction of its evolutionary relationships, and the estimation of its divergence time, may be used as a molecular tool in conjunction with its nuclear data and ecological data to investigate population structure within the different populations of the pyjama shark. This will aid in assessing the pyjama shark populations’ risk of extinction and their ability to adapt in the face of rapid oceanographic climate change and the threat of fisheries. This study produced the first mitogenome sequence for this species, contributing to the continued management and conservation of this endemic catshark.

#Author
Lehlohonolo Karabo Sekane
   





