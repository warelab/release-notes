## Using the genes search interface {#search-interface}

Watch the [demo video on YouTube](https://www.youtube.com/watch?v=nnAEnA9qTMY&t=2s).

Searching for a gene given a gene id can be done in a couple of ways:
- Click the spyglass icon and type/paste `SORBI_3006G095600` it into the search box
- Link directly to [http://sorghumbase.org/genes?idList=SORBI_3006G095600](https://www.sorghumbase.org/genes?idList=SORBI_3006G095600)

If you don't know the gene id you can search by pathway and taxonomy [example](https://www.sorghumbase.org/genes?filters={%22status%22:%22init%22,%22operation%22:%22AND%22,%22negate%22:false,%22marked%22:false,%22leftIdx%22:0,%22rightIdx%22:5,%22children%22:[{%22fq_field%22:%22pathways__ancestors%22,%22fq_value%22:%221119332%22,%22name%22:%22Jasmonic%20acid%20biosynthesis%22,%22category%22:%22Plant%20Reactome%20Pathway%22,%22leftIdx%22:1,%22rightIdx%22:2,%22negate%22:false,%22showMenu%22:false,%22marked%22:false},{%22fq_field%22:%22taxonomy__ancestors%22,%22fq_value%22:%224558%22,%22name%22:%22Sorghum%20BTx623%22,%22category%22:%22Taxonomy%22,%22leftIdx%22:3,%22rightIdx%22:4,%22negate%22:false,%22showMenu%22:false,%22marked%22:true}],%22showMarked%22:true,%22showMenu%22:false,%22moveCopyMode%22:%22%22,%22searchOffset%22:0,%22rows%22:20}&genomes=):
1. In the search box, start typing `jasmonic acid biosynthesis` and choose the matching Plant Reactome Pathway term
2. To limit the search to genes in *Sorghum bicolor* BTx623, type `sorghum` in the search box and select the matching Taxonomy term

The search results page is organized into three areas:
1. A panel on the left side shows the status of the search
2. At the top is a visualization of the genomic locations of genes matching the search
3. Below this is a paginated list of genes

Each gene has a set of tabs that can be expanded to explore more details:
- Location - Lightweight genome browser showing gene structure
- Expression - Baseline gene expression viewer from [EBI-Expression Atlas](https://www.ebi.ac.uk/gxa)
- Homology - Gene family tree viewer (opens by default if only one gene is found)
- Pathways - Associated pathways in [Gramene’s Plant Reactome](https://plantreactome.gramene.org)
- Xrefs - Cross-references to other databases

![LOX3 ortholog](images/image13.png)
