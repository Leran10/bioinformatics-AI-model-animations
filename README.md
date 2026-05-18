# BioAI Animations

Interactive animated explanations of popular and state-of-the-art AI models used in bioinformatics and computational biology.

## Goal

Provide an accessible, visual platform for researchers, students, and practitioners to understand how AI/ML models in bioinformatics work — from input to output, layer by layer — through step-by-step animations.

## Live Demo

Open `index.html` in your browser to access the platform. No dependencies or build steps required.

## Models Covered

### Genomics / DNA
| Model | Status |
|-------|--------|
| **Evo 2** (StripedHyena-2, 40B, 1M context) | Interactive |
| DNABERT-2 (BPE tokenizer, multi-species) | Coming soon |
| Nucleotide Transformer (2.5B, 6-mer) | Coming soon |
| Enformer (conv + transformer, 200kb) | Coming soon |
| Caduceus (Mamba SSM, bidirectional) | Coming soon |

### Protein
| Model | Status |
|-------|--------|
| AlphaFold 2 (Evoformer + IPA) | Coming soon |
| AlphaFold 3 (Pairformer + diffusion) | Coming soon |
| ESM-2 / ESMFold (15B protein LM) | Coming soon |
| ESM3 (multimodal generative) | Coming soon |
| RFdiffusion (diffusion protein design) | Coming soon |
| ProteinMPNN (inverse folding GNN) | Coming soon |
| AlphaMissense (variant pathogenicity) | Coming soon |
| Boltz-1 (open-source AF3-level) | Coming soon |
| SaProt (structure-aware LM) | Coming soon |

### Single-Cell
| Model | Status |
|-------|--------|
| scGPT (33M cells, multi-omics) | Coming soon |
| scFoundation (50M cells) | Coming soon |
| Geneformer (rank-value encoding) | Coming soon |
| scVI (VAE, count data) | Coming soon |

### Drug Discovery
| Model | Status |
|-------|--------|
| MolBERT / ChemBERTa (SMILES LM) | Coming soon |
| DiffDock (diffusion docking) | Coming soon |
| GROVER (graph transformer) | Coming soon |

## Features

- Searchable model catalog with category filters
- Each animation is a self-contained HTML file with interactive controls
- Step-by-step progression with detailed explanations at each stage
- No dependencies — just open in a browser

## Contributing

Have a model you'd like to see animated? Open an issue or submit a PR. Animations should be:
- Self-contained HTML (no external dependencies)
- Interactive with step-by-step progression
- Accompanied by clear explanations of each processing stage

## License

MIT
