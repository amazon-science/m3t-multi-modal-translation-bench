# M3T: A New Benchmark Dataset for Multi-Modal Document-Level Machine Translation

Document translation poses a challenge for Neural Machine Translation (NMT) systems. Most document-level NMT systems rely on meticulously curated sentence-level parallel data, assuming flawless extraction of text from documents along with their precise reading order. These systems also tend to disregard additional visual cues such as the document layout, deeming it irrelevant. However, real-world documents often possess intricate text layouts that defy these assumptions. Extracting information from Optical Character Recognition (OCR) or heuristic rules can result in errors, and the layout (e.g., paragraphs, headers) may convey relationships between distant sections of text. This complexity is particularly evident in widely used PDF documents, which represent information visually. This paper addresses this gap by introducing M3T , a novel benchmark dataset tailored to evaluate NMT systems on the comprehensive task of translating semi-structured documents. This dataset aims to bridge the evaluation gap in document-level NMT systems, acknowledging the challenges posed by rich text layouts in real-world applications.

For further details see our [paper](http://arxiv.org/abs/2406.08255).

## Examples

![image](images/example_doclaynet_annotations.svg)

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This dataset is licensed under the CC-BY-4.0 License. See the LICENSE file.

## Citation

If using our dataset, please consider citing our paper:

```
@misc{hsu2024m3t,
      title={M3T: A New Benchmark Dataset for Multi-Modal Document-Level Machine Translation}, 
      author={Benjamin Hsu and Xiaoyu Liu and Huayang Li and Yoshinari Fujinuma and Maria Nadejde and Xing Niu and Yair Kittenplon and Ron Litman and Raghavendra Pappagari},
      year={2024},
      eprint={2406.08255},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```

In addition, please cite the original datasets as well:
```
@inproceedings{pfitzmann-et-al,
author = {Pfitzmann, Birgit and Auer, Christoph and Dolfi, Michele and Nassar, Ahmed S. and Staar, Peter},
title = {DocLayNet: A Large Human-Annotated Dataset for Document-Layout Segmentation},
year = {2022},
isbn = {9781450393850},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3534678.3539043},
doi = {10.1145/3534678.3539043},
}

@inproceedings{harley-et-al,
  author={Harley, Adam W. and Ufkes, Alex and Derpanis, Konstantinos G.},
  booktitle={2015 13th International Conference on Document Analysis and Recognition (ICDAR)}, 
  title={Evaluation of deep convolutional nets for document image classification and retrieval}, 
  year={2015},
  volume={},
  number={},
  pages={991-995},
  doi={10.1109/ICDAR.2015.7333910}
}
```