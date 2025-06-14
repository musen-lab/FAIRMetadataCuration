# FAIRMetadataCuration

Scientific metadata often suffer from incompleteness, inconsistency, and formatting errors, which hinder effective discovery and reuse of the associated data. We present a method that uses GPT-4 and the CEDAR metadata knowledge base to automatically standardize metadata and ensure compliance with established standards. Our standardization process corrects and refines metadata entries in bulk, resulting in significantly improved search performance and recall. Using the BioSample and GEO repositories, we demonstrate how metadata standardization enhances retrieval outcomes. The average recall increases from 17.65\% with the baseline raw metadata (in BioSample and GEO) to 62.87\% with the metadata corrected by our pipeline. These results underscore the transformative potential of combining advanced AI models with standardized metadata structures for more effective and reliable data retrieval.

## Code Usage
Some files require OpenAI API-key for running. We have recorded the prompts and other mechanisms for both making the metadata FAIR using LLMs and for recording the recall values. MetadataCorrection is the python notebook to perform metadata correction for your data. MetadatRefine is the code to calculate recall, precision and F1 if you have access to gold standard. The other files are pertinent to our deployment where Rules.ipynb was the notebook used to create the gold standard and GEODatasetCreator is the code we used to generate our GEO dataset.

# Citation
The paper is available [here](https://arxiv.org/abs/2504.05307). Please consider using the following BibTex for citation.
```
@misc{sundaram2025totalrecallenhancingfairness,
      title={Toward Total Recall: Enhancing FAIRness through AI-Driven Metadata Standardization}, 
      author={Sowmya S Sundaram and Mark A Musen},
      year={2025},
      eprint={2504.05307},
      archivePrefix={arXiv},
      primaryClass={cs.IR},
      url={https://arxiv.org/abs/2504.05307}, 
}
```

