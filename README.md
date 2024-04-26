# Knowledge-Enhanced Language Models Are Not Bias-Proof

Analysis scripts and data from the paper "Knowledge-Enhanced Language Models Are Not Bias-Proof: Situated Knowledge and Epistemic Injustice in AI"
to be presented at FAccT 2024.


- Stereotype bias: We used [this](https://github.com/McGill-NLP/bias-bench) repo to run the stereotype analyses.
- Enhancement effect: The LAMA analyses were run with via [this fork](https://github.com/morioka/LAMA).
- TREx performance bias:
   - To analyze the TREx performance bias, we disaggregated the dataset linked in the LAMA repo by gender. We provide the gendered subsets in our `TREx_analysis` folder.
   - Run the LAMA analysis script on the disaggregated data to obtain the individual predictions and disaggregated mean P@1 scores.
   - `trex-bias-results.ipynb` implements additional bias evaluations on the individual predictions.
- KELM analysis: In the paper, we briefly mention our analysis of the KELM corpus. In the `KELM_analysis` folder, you may find the respective notebook and the data can be downloaded [here](https://drive.google.com/drive/folders/1diLInSDJHdKjo5_0Dizgog6FMyjnpWrw?usp=sharing).
