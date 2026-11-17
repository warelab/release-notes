_Last updated: November 17, 2026_

**Ask the Maize PanGenome questions with an AI assistant**

You can ask questions about the Gramene Maize PanGenome in plain language and let an AI assistant look up the answers: genes and their function, orthologs and gene trees, presence and absence across the maize genomes, transcription factor families, expression, and lines that carry loss-of-function alleles. This server holds Maize PanGenome release 6, with 56 _Zea_ genomes (B73, the NAM founders, other inbreds and teosintes) plus sorghum, rice, Arabidopsis and other reference species.

The connection uses the Model Context Protocol (MCP), an open standard that lets an AI assistant call tools on a remote server. The Maize PanGenome MCP server is free and read-only, and it needs no account or sign-in with us. This guide uses Claude because it supports MCP servers on its free plan; other assistants are covered [further down](#other-ai-tools).

- [1. Get an assistant](#1-get-an-assistant)
- [2. Add the Maize PanGenome connector](#2-add-the-maize-pangenome-connector)
- [3. Turn it on in a chat](#3-turn-it-on-in-a-chat)
- [4. Example questions](#4-example-questions)
- [5. Browse a gene tree](#5-browse-a-gene-tree)
- [Tips](#tips)
- [Other AI tools](#other-ai-tools)
- [What the assistant can do](#what-the-assistant-can-do)
- [Privacy](#privacy)

---

## 1. Get an assistant

1. Create an account at [claude.ai](https://claude.ai). The free plan is enough to try this.
2. Use Claude in your browser, or install the desktop app for macOS or Windows.

Free plans limit how many custom connectors you can add and how many messages you can send in a few hours. A question that needs many lookups uses that allowance faster than an ordinary chat.

## 2. Add the Maize PanGenome connector

The server address is:

```
https://data.gramene.org/mcp/maize_v6
```

1. In Claude, open **Settings** and choose **Connectors**.
2. Choose **Add custom connector**.
3. Enter a name, for example `Gramene Maize`, and paste the address above.
4. Leave the sign-in (OAuth) fields empty and choose **Add**.

On a Team or Enterprise plan, an organization owner may need to add the connector once before members can switch it on.

## 3. Turn it on in a chat

Start a new chat, open the tools menu below the message box, and switch **Gramene Maize** on. The first time Claude uses one of the tools it asks for permission; you can allow it once or for the whole chat.

Gramene runs a separate server for each of its sites, and they all offer the same tools. Keep only the one you need switched on in a chat, so the assistant does not mix data from two releases.

## 4. Example questions

Copy a question, paste it into the chat, and change the gene, region or trait to your own. The line under each question says what the answer draws on.

### Genes and IDs

```
What is the maize gene tb1? Give its B73 v5 ID, location and what is known about its function.
```
Gene record: location, description, protein domains, GO terms and pathways.

```
What is the B73 v5 ID for the v4 gene Zm00001d033673?
```
Maps an identifier from an earlier B73 annotation to the current one.

```
List the B73 v5 genes whose name starts with "wx" or whose description mentions waxy.
```
Search by name and description within one genome.

### Regions

```
List the B73 v5 genes on chromosome 9 between 25.0 and 25.25 Mb, with a short description of each.
```
Genes in an interval of the reference genome; the interval contains wx1.

```
What are the ten genes on either side of Zm00001eb054440?
```
Genomic neighbourhood of one gene.

### Orthologs and gene families

```
What are the sorghum, rice and Arabidopsis orthologs of tb1 (Zm00001eb054440)?
```
Orthologs from the Compara gene trees, by species.

```
Does opaque2 (Zm00001eb301570) have paralogs in B73 v5?
```
Within-genome duplicates, including those from the maize whole-genome duplication.

### Across the maize genomes

```
Among the maize genomes included in the gene trees, which have no ortholog of tb1 (Zm00001eb054440), and which have more than one?
```
Presence/absence and copy number across the assembly panel.

```
How many protein-coding genes in B73 v5 have no ortholog in Mo17?
```
A count across two genomes; ask for a sample of the genes if you want examples.

```
How many copies of the wx1 (Zm00001eb378140) family does each of the NAM founder genomes carry?
```
Copy counts per genome for one gene family.

### Transcription factors

```
How many bZIP transcription factors does B73 v5 have, and how does that compare with sorghum?
```
Grassius transcription factor family membership, by genome.

```
Which transcription factor family does lg1 (Zm00001eb067740) belong to, and what are its paralogs in B73 v5?
```
Family assignment plus paralogs.

### Expression

```
In which tissues is tb1 (Zm00001eb054440) most highly expressed? Name the experiments.
```
Baseline expression from curated RNA-seq experiments, by tissue.

```
Which B73 v5 genes in the starch biosynthesis pathway are highly expressed in the endosperm but not in the leaf?
```
Combines a pathway gene set with per-organ expression calls.

### Germplasm

```
Which maize lines carry predicted loss-of-function alleles of wx1 (Zm00001eb378140)? Group them by the type of variant.
```
Lines with stop-gain, frameshift or splice variants, by consequence and zygosity.

### Pathways and literature

```
Which B73 v5 genes are in the starch biosynthesis pathway?
```
Plant Reactome pathway membership.

```
What has been published on tb1 (Zm00001eb054440)? Give PubMed IDs.
```
Curated literature references for a gene.

### Sequences

```
Give me the protein sequence of Zm00001eb378140 in FASTA format.
```
Sequences of the gene's transcripts; genomic, cDNA and CDS are also available.

**Not on this site:** maize QTL and variant (rsID) lookups. The QTL records here describe rice and sorghum, so a trait question returns QTL in those species.

## 5. Browse a gene tree

Ask to *see* a gene tree and the assistant opens an interactive viewer in the conversation instead of describing the tree in text:

```
Show me the gene tree for the maize gene tb1 (Zm00001eb054440).
```

![The gene tree viewer opened by the assistant](images/ai-guide-gene-tree.png)

The viewer shows the phylogeny with speciation and duplication nodes, gene labels and the protein alignment with its domains. You can collapse or prune clades, search for a gene, add the gene-neighbourhood and gene-structure panels from the **Zones** menu, and switch to full screen. Clicking a gene offers **Ask about this gene**, which sends that gene back to the chat as your next question.

The viewer appears in assistants that support MCP Apps, which include Claude on the web and the desktop app. Elsewhere you get a short text summary of the tree.

## Tips

- **Give stable IDs when you have them.** `Zm00001eb054440` is unambiguous; a gene symbol may match several genes, or genes in other species.
- **Name the genome.** Gene IDs and coordinates differ between assemblies. Say "in B73 v5" for the reference, or name the line (Mo17, CML247, a teosinte) when you mean another genome. B73 v3 and v4 gene models are here too.
- **Be specific.** Name the organ ("inflorescence", "root") and say how to rank or filter. "Rank by root expression and ortholog function" gives a more repeatable answer than "find the best candidates".
- **Ask for counts before lists.** "How many genes…" is quick; a list of several thousand genes is long and will be cut short.
- **Ask for links.** The assistant can give the Maize PanGenome site links for the genes it reports, so you can check them in the browser.
- **Say what you want back.** A table, a ranked shortlist, FASTA, or a file to download.
- **Check before you act.** AI answers can be wrong. Confirm gene IDs, positions and germplasm names on [the Maize PanGenome site](https://maize-pangenome.gramene.org) before ordering seed or designing an experiment.

## Other AI tools

Any assistant or client that supports remote MCP servers over streamable HTTP can use the same address. In Claude Code:

```
claude mcp add --transport http gramene-maize https://data.gramene.org/mcp/maize_v6
```

Setup instructions for VS Code, Cursor and other clients are in the [gramene-mcp README](https://github.com/warelab/gramene-mcp#connecting-to-mcp-clients).

## What the assistant can do

You do not need to name these tools; the assistant picks them. The table is here so you know what is possible.

| Tool | What it does |
|---|---|
| `solr_suggest` | Turns a word or phrase (a gene name, trait, pathway, protein domain, species) into the matching search terms |
| `gene_search`, `solr_search`, `solr_search_bool` | Find genes by any combination of filters, and count or summarize them |
| `resolve_gene_ids` | Maps older or alternative gene IDs to current ones |
| `genes_in_region` | Lists the genes in a chromosome interval |
| `expand_gene_set` | Orthologs, paralogs, whole gene families and neighbouring genes |
| `gene_tree_view` | Opens the interactive gene tree viewer |
| `expression_for_genes` | Expression by tissue and condition from curated RNA-seq experiments |
| `vep_for_gene` | Germplasm carrying predicted loss-of-function alleles of a gene |
| `pubmed_for_genes` | Publications linked to genes |
| `gene_sequence` | Genomic, cDNA, CDS or protein sequence |
| `mongo_find`, `mongo_lookup_by_ids` | Full records for genes, gene trees, genomes, ontology terms, pathways and QTL |

## Privacy

Your questions go to the AI provider you chose, under that provider's terms. Our server receives only the tool requests the assistant makes on your behalf, such as "genes in this region", and keeps a log of those requests, as any web server does. It never sees the rest of your conversation.

Questions or problems? Use the feedback link on [the Maize PanGenome site](https://maize-pangenome.gramene.org).
