# motifexperiment


## Motif analysis and discovery software

- MEME
  - MEME Suite: http://meme-suite.org/
  - Based on Expectation Maximization: https://en.wikipedia.org/wiki/Multiple_EM_for_Motif_Elicitation
- Extreme: https://github.com/uci-cbcl/EXTREME
- HOMER
  - Perl code http://homer.ucsd.edu/homer/motif/
- Omics PNL:
  - Windows command line software for Protein Sequence Motif Extraction:
  - https://omics.pnl.gov/software/protein-sequence-motif-extractor
- Online tools:
  - Genome JP: http://www.genome.jp/tools/motif/
  - Scan Prosite: https://prosite.expasy.org/scanprosite/
    - It supports Uniprot accesions: https://www.uniprot.org/
   - My hits https://myhits.isb-sib.ch/cgi-bin/motif_scan#prf:UBIQUITIN_2
   - ELM http://elm.eu.org/  
   
## Motif data: 
  - This seems to be the main resource: http://meme-suite.org/db/motifs
  - Is there a way to download them?
    - Maybe from here: http://jaspar.genereg.net/downloads/
      - Detail page for one download: http://jaspar.genereg.net/matrix/MA0597.1/
      - Can download in MEME format: http://jaspar.genereg.net/downloads/
  - FAQ about data formats: http://jaspar.genereg.net/faq/#data-formats
    - It has detailed information about MEME format text files
  - REST API: http://jaspar.genereg.net/api/v1/matrix
    - API call example with meme format: http://jaspar.genereg.net/api/v1/matrix/MA0001.1/?format=meme
  - From Uniprot you can also BLAST the motif:
    - https://www.uniprot.org/uniprot/Q9FFX4#family_and_domains

## Using KEGG for Motifs
  - Starting URL:
    - http://www.kegg.jp/dbget-bin/www_bget?tng:GSTEN00013192G001
    - Clicking on Motif leads the user to a motif detail page:
      - http://www.kegg.jp/ssdb-bin/ssdb_motif?kid=tng:GSTEN00013192G001
        - Clicking on the Sequence button leads the user to the motif sequence but it does not generate a unique url. (The data here is from Genbank)
        - A very interesting feature here is the Search GENES with same motif button. It also leads the user to another page without unique url.
    - Can you do the same using the KEGG API? http://www.kegg.jp/kegg/rest/keggapi.html
    
 ## Protein databases and open data
 
-  https://pfam.xfam.org/
- Search with motif keyword on pfam http://pfam.xfam.org/search/keyword?query=motif
- Info on biostars https://www.biostars.org/p/199737/
- Motifs and sites on EBI http://www.ebi.ac.uk/pdbe-site/pdbemotif/
-  https://prosite.expasy.org/
-Protein data bank motifs https://www.rcsb.org/pdb/staticHelp.do?p=help/advancedsearch/sequenceMotif.html
 
 ## Algorithms and papers
 
 - A generic motif discovery algorithm for sequential data https://github.com/kljensen/Gemoda

 
 ## Cool educational info about MOTIFs
 
- DNA Motif Finding 2010: https://www.slideshare.net/Stewbacca/dna-motif-finding-2010
- Motif-based analysis of ChIP-seq data: https://www.slideshare.net/AustralianBioinformatics/motifbased-analysis-of
- Motif and pattern database: https://www.slideshare.net/tsucheta/motif-andpatterndatabase
- A generic motif discovery algorithm for diverse molecular data: https://www.slideshare.net/kljensen/gemoda


 ## Como hacer rular EXTREME en localhost
-  sudo pip install cython
-  cd src
- python setup.py build_ext --inplace
- PETA! memewrapper.c:566:10: fatal error: 'numpy/arrayobject.h' file not found


