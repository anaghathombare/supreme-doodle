# supreme-doodle
SafeLearn/
├── README.md
├── LICENSE
├── .gitignore
├── docs/
│   └── research-paper.pdf
├── data/
│   ├── raw_prompts.csv
│   ├── injected_examples.csv
│   └── clean_prompts.csv
├── models/
│   └── intent_classifier_roberta.pkl
├── app/
│   ├── main.py
│   ├── prompt_filter.py
│   ├── response_checker.py
│   ├── utils.py
│   └── config.py
├── dashboard/
│   ├── app.py  # Streamlit UI
│   ├── pages/
│   │   └── analysis.py
│   └── assets/
│       └── logo.png
├── requirements.txt
└── tests/
    ├── test_filter.py
    └── test_classifier.py
