# PromptCraft

PromptCraft is an open-source project designed to summarize complex scientific papers published in the Springer Nature database. Springer Nature is a leading global scientific publisher of books and journals, delivering quality content through innovative information products and services. With close to 500 academic and professional society journals and over 3,000 journals and 13,000 new books published each year, Springer Nature provides a vast amount of valuable scientific knowledge.

The goal of PromptCraft is to make scientific research more accessible by providing concise summaries of scientific papers. This can be particularly helpful for researchers, students, and professionals who want to quickly grasp the key findings and insights of a paper without having to read the entire document. By leveraging natural language processing techniques, PromptCraft aims to automate the process of summarizing scientific papers, saving time and effort for individuals seeking to stay updated with the latest research.

## Features

- **Paper Summarization:** PromptCraft utilizes advanced natural language processing algorithms to generate summaries of scientific papers. These summaries condense the main ideas, findings, and conclusions of the original research, allowing users to quickly understand the essence of a paper.

- **Springer Nature Integration:** PromptCraft leverages the extensive Springer Nature database, which contains a wide range of scientific papers across various disciplines. By tapping into this vast collection, PromptCraft can access a diverse set of research articles to summarize.

#### For Example, Turn this Abstract: 

Herein, we report the synthesis, characterization, and application of TiO2/ZnO and La-doped ZnO nanocomposites for the detection and degradation studies of Malachite Green (MG). TiO2/ZnO and La-doped ZnO nanocomposites were synthesized by reflux and hydrothermal methods, respectively, and characterized by UV–visible spectroscopy, X-ray diffraction, Fourier transform infrared spectroscopy, scanning electron microscopy, and energy-dispersive X-ray analysis. A glassy carbon electrode modified with COOH-fMWCNTs and TiO2/ZnO nanocomposite demonstrated high sensitivity characteristics for the sensing of MG up to 0.34 nM limit of detection. The application of a photocatalytic method using 2% La-doped ZnO led to 99% degradation of MG in 40 min. The photocatalytic breakdown of MG followed first-order kinetics as revealed from the spectroscopic and electrochemical monitoring of the degradation process. Color variation offered naked-eye evidence of MG degradation in the specified time. The experimental findings helped in proposing the degradation mechanism. To the best of our knowledge, the current work presents the first example of a novel photocatalyst for almost absolute degradation of MG. Moreover, the electrode modifier as well as the approach adopted is novel and efficient for minute-level detection of MG and monitoring of its photocatalytic degradation.

#### Into this Summary:

TiO2/ZnO and La-doped ZnO nanocomposites were synthesized and used for the detection and degradation of Malachite Green. The nanocomposites showed high sensitivity for sensing and almost complete degradation of MG in 40 minutes using a photocatalytic method. <ins>This could impact human life by providing a more efficient and effective way to detect and remove harmful pollutants from the environment.</ins>

## Getting Started

To get started with PromptCraft, follow these steps:

1. Clone the repository:

```shell
git clone https://github.com/your-username/promptcraft.git
```

2. Set up the Springer Nature API credentials. Obtain an API key from Springer Nature [https://dev.springernature.com/](https://dev.springernature.com/)

3. Set up the OpenAI API credentials [https://platform.openai.com/docs/api-reference](https://platform.openai.com/docs/api-reference)

4. Set the API keys in a local environment file and name them: 
'SPRINGER_NATURE_API_KEY' and 'OPENAI_API_KEY'

5. Run the 'summarize_nature_articles.ipynb' notebook

## Contributing

We welcome contributions from the community to make PromptCraft even better. If you'd like to contribute, please follow these guidelines:

1. Fork the repository and create your branch:

```shell
git clone https://github.com/your-username/promptcraft.git
cd promptcraft
git checkout -b my-feature
```

2. Make your changes and commit them:

```shell
git commit -m "Add new feature"
```

3. Push your changes to your forked repository:

```shell
git push origin my-feature
```

4. Open a pull request, explaining the changes you made and the rationale behind them.

## License

PromptCraft is released under the [MIT License](https://opensource.org/licenses/MIT).

## Contact

If you have any questions, suggestions, or feedback, feel free to reach out to the PromptCraft team at promptcraft@example.com. We value your input and are excited to hear from you!

---

*Disclaimer: PromptCraft is an independent project and is not affiliated with or endorsed by Springer Nature.*