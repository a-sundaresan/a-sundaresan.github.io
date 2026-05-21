---
layout: default
title: Projects
permalink: /projects/
---

<span class="eyebrow">Selected projects</span>

# What I've built

## AI & Agentic Workflows

<div class="card">
  <h3>AutoAnnotSC — Automated scRNA-seq Cell Type Annotation</h3>
  <p>An agentic pipeline that fully automates single-cell RNA-seq cell type annotation from a single command. Downloads data directly from Synapse or accepts local files, runs QC and preprocessing, annotates clusters using CellAnnotator and Claude Sonnet, and validates marker genes against PubMed literature. Outputs a complete analysis package including an annotated AnnData object, UMAP, JSON report, and plain-text summary.</p>
  <div class="tags">
    <span class="tag">Anthropic SDK</span>
    <span class="tag">Python</span>
    <span class="tag">Scanpy</span>
    <span class="tag">Synapse MCP</span>
    <span class="tag">PubMed MCP</span>
    <span class="tag">scRNA-seq</span>
  </div>
  <a href="https://github.com/a-sundaresan/AutoAnnotSC" target="_blank" rel="noopener">View code →</a>
</div>

<div class="card">
  <h3>BulkRNASeq Agent — Anthropic SDK Agentic Workflow <span class="tag" style="vertical-align:middle;">In Progress</span></h3>
  <p>An AI agent built with the Anthropic SDK that automates end-to-end bulk RNA-seq analysis. The agent orchestrates the full workflow — from raw data processing and quality control through alignment, quantification, differential expression, and pathway interpretation — reducing a multi-step manual pipeline to a single conversational interface.</p>
  <div class="tags">
    <span class="tag">Anthropic SDK</span>
    <span class="tag">Python</span>
    <span class="tag">DESeq2</span>
    <span class="tag">Nextflow</span>
  </div>
</div>

## Pipelines & Tools

<div class="card">
  <h3>Bulk RNA-seq DE Analysis — R Shiny App</h3>
  <p>A browser-based interactive tool for end-to-end differential expression analysis of bulk RNA-seq data. Upload your own count matrix and metadata, select comparison groups, and instantly get DESeq2 results alongside PCA, MA, and Volcano plots — no local R installation needed.</p>
  <div class="tags">
    <span class="tag">R</span>
    <span class="tag">Shiny</span>
    <span class="tag">DESeq2</span>
    <span class="tag">Bioconductor</span>
    <span class="tag">ggplot2</span>
  </div>
  <a href="https://a-sundaresan.shinyapps.io/BulkRNASeq_downstream_processing_after_quantification/" target="_blank" rel="noopener">Live app →</a>
  &nbsp;&nbsp;
  <a href="https://github.com/a-sundaresan/RShinyApps-BulkRNASeqDEAnalysis" target="_blank" rel="noopener">View code →</a>
</div>
