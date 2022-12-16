# protein-seq-contact-sites

We aim to use ESM-2 a transformer based model to detect similarities in protein sequences. 

We are currently working on implementing statistical analysis that will determine similarity in protein sequences through homologous pairs in contact sites. 

To do so, we are using clusters of orthologous groups (COGs). COGs consist of orthologues (homologous genes that have diverged in different species from a common ancestral gene, along with the divergence of the species). The COGs are used to construct a distribution of homologous pair counts in protein sequences across different classes of organisms. 

So far, we created a list of 500,000 COG pairs across different organism classes. We are now working to create a phylogeny of virus orthologus groups (VOGs) to detect contact sites in virus proteins. 

 
