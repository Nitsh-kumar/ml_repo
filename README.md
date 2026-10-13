# Machine Learning Practice Notebooks

A collection of Python experiments covering regression, classification, text embeddings, data exploration, and PDF question answering.

**Status:** learning workspace. Notebook completeness and dependency requirements vary. These are exercises, not production ML services.

## Notebook index

| Notebook | Contents | Status |
| --- | --- | --- |
| [Linear regression](Day_1%5BLinear_Regression_%5D_%2825_12_23%29.ipynb) | Regression notes and a SciPy example | Implemented learning example |
| [TensorFlow classification](tensorflow_practice_classification.ipynb) | MNIST classification and evaluation metrics | Implemented notebook |
| [PDF queries](PdfQueryLangchain.ipynb) | PDF extraction, embeddings, FAISS, and LangChain question answering | Historical API experiment; dependencies need reconciliation |
| [Dataset exploration](app.ipynb) | Kickstarter dataset download and pandas exploration | Small exploratory notebook |
| [Word2Vec experiment](.ipynb) | Gensim text-vector experiment | Substantive notebook with an unclear filename; needs cleanup |
| [KNN practice](KNN_practice.ipynb) | Placeholder | No substantive exercise yet |
| [Keras linear regression](Linear_regression_using_keras.ipynb) | Placeholder | No substantive exercise yet |

## How to explore

Open one notebook at a time in Jupyter or Colab. Read its imports, install that notebook's dependencies in an isolated environment, and run cells from a fresh session.

- Regression: SciPy and Matplotlib.
- MNIST: TensorFlow, NumPy, Matplotlib, and scikit-learn.
- Dataset exploration: KaggleHub, pandas, and Matplotlib.
- Word2Vec: Gensim and pandas.
- PDF queries: PyPDF2, FAISS, LangChain, and provider libraries referenced by the notebook.

There is no shared pinned environment. The PDF notebook uses older LangChain import paths; installing the latest packages is not a verified compatibility solution.

The Kickstarter experiment downloads `kemical/kickstarter-projects` through KaggleHub. Review dataset usage terms before redistributing it. Do not upload private PDFs or commit provider credentials or document-derived outputs.

## Next cleanup

Rename the Word2Vec notebook, repair its code issue, and provide notebook-specific tested environments. Finish or remove individual placeholders without discarding the useful examples. Preserve the existing [GPLv3 license](LICENSE).

See [project status](docs/PROJECT_STATUS.md).

## Validation

This documentation was checked against repository files on 13 October 2026. Notebooks, application runs, refreshes, and test suites were not executed during this documentation pass. Saved outputs are historical evidence, not a fresh run.
