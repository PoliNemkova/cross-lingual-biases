# Cross-Lingual Biases

This project investigates cross-lingual biases in large language models (LLMs) for human rights-related classification tasks. The experiments evaluate model performance across multiple languages to identify potential biases in multilingual settings.

## Tasks

### HRV (Human Rights Violation)
Detection of human rights violations mentioned in social media posts, including killing of civilians, destruction of civil objects, rape, torture, and executions.

**Languages:**
- English
- Ukrainian
- Russian
- Chinese
- Lingala
- Burmese

### HRD (Human Rights Defenders)
Detection of attacks, threats, kidnapping, harassment, or intimidation targeting human rights defenders such as journalists, activists, lawyers, and whistleblowers.

**Languages:**
- English
- Hindi
- Chinese
- Arabic
- Russian
- Lingala
- Burmese

## Project Structure

```
cross-lingual-biases/
├── datasets/
│   ├── hrv/
│   └── hrd/
├── prompts/
│   ├── Arabic/
│   ├── Burmese/
│   ├── Chinese/
│   ├── English/
│   ├── Hindi/
│   ├── Lingala/
│   ├── Russian/
│   └── Ukrainian/
└── experiments/
    ├── hrv_experiment.ipynb
    └── hrd_experiment.ipynb
```
