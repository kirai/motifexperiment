# motifexperiment


## Motif discovery algorithms and data available for download

- MEME, based on Expectation Maximization: https://en.wikipedia.org/wiki/Multiple_EM_for_Motif_Elicitation
  - MEME Suite: http://meme-suite.org/
- HOMER Motif Analysis
  - Perl code.
  - http://homer.ucsd.edu/homer/motif/
- Windows command line software for Protein Sequence Motif Extraction:
  - https://omics.pnl.gov/software/protein-sequence-motif-extractor
- Online tools:
  - Genome JP: http://www.genome.jp/tools/motif/
  - Scan Prosite: https://prosite.expasy.org/scanprosite/
    - It supports Uniprot accesions: https://www.uniprot.org/
   - My hits https://myhits.isb-sib.ch/cgi-bin/motif_scan#prf:UBIQUITIN_2
   - ELM http://elm.eu.org/
   
   
## Motif databases: 
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
 
 
