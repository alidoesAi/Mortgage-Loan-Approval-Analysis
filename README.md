# Mortgage loan approval analysis - legacy coursework

This repository preserves a 2018 Seattle University econometrics project about
the association between race and mortgage approval in a historical Boston
sample. It contains a companion exploratory notebook authored by **Afsar Ali**
(Ali), the classroom data subset, a generated HTML report, and the final team
paper.

This is a historical course project, not current lending guidance, a production
model, or a causal finding that can be generalized beyond the studied sample.

## Project context

The final paper identifies:

- Seattle University, Albers School of Business and Economics;
- `ECON 5300`;
- March 14, 2018;
- team members Afsar Ali, Patrick Hoye, and Stefan Rijkaart; and
- instructor Bridget Hiedemann.

### Contribution record

The paper's final page assigns the work as follows:

- Afsar Ali created the prototypical-individual tables and focused on the
  Introduction, Model and Estimation Method, and Conclusion.
- Patrick Hoye generated the probit/logit models.
- Stefan Rijkaart created the descriptive-statistics and estimated-model tables
  and completed final proofreading and adjustments.
- All three members shared writing and discussion.

The separate R Markdown EDA names Afsar Ali as its author. Repository commit
history alone should not be used to erase the team attribution recorded in the
paper.

## Evidence map

| Artifact | File |
| --- | --- |
| Ali-authored exploratory analysis source | [Mortgage Loan Approval Analysis EDA.Rmd](./Mortgage%20Loan%20Approval%20Analysis%20EDA.Rmd) |
| Historical classroom data subset | [MLD Data File.csv](./MLD%20Data%20File.csv) |
| Preserved generated notebook output | [Mortgage_Loan_Approval_Analysis_EDA.html](./Mortgage_Loan_Approval_Analysis_EDA.html) |
| Final team paper and contribution record | [Mortgage Loan Approval Analysis Final.pdf](./Mortgage%20Loan%20Approval%20Analysis%20Final.pdf) |

## Data context and limitations

`MLD Data File.csv` has 1,989 rows and eight fields covering marital status,
credit-guideline status, obligations ratio, Black and Hispanic indicators,
gender, approval outcome, and loan-to-price ratio. It contains no direct name,
address, email, phone, or account identifier, but protected-class and lending
outcome fields are still sensitive.

The paper describes a sample of 1990 Boston mortgage decisions associated with
Home Mortgage Disclosure Act-era research. Official historical context is
available from the
[Federal Reserve Bank of Boston](https://www.bostonfed.org/publications/research-department-working-paper/1992/mortgage-lending-in-boston-interpreting-hmda-data.aspx).
This repository does not document the exact extraction, filtering, classroom
distribution, or redistribution license for its eight-column CSV.

The final paper explicitly notes sample-size, representation, omitted-variable,
place, and time limitations. Its results should be described as an association
in this historical sample, not as a present-day or universally causal estimate.

## Reproducibility

The notebook calls `tidyverse`, `GGally`, `plotly`, `car`, `ggplot2`,
`stargazer`, `sandwich`, `lmtest`, `psych`, `aod`, `Rcpp`, `Hmisc`, `pastecs`,
`popbio`, `rms`, `kableExtra`, and `broom`.

The input, source notebook, generated HTML, and final PDF are preserved.
However, there is no recorded R version, package lockfile, environment setup,
test suite, or CI workflow. The current audit did not re-run the notebook, and
the notebook is not proven to be the single generation pipeline for the final
team paper.

## Evidence-supported career statement

> Co-authored a Seattle University econometrics project examining associations
> between race and mortgage approval in a historical Boston sample; created the
> prototypical-applicant tables and focused on the introduction, model and
> estimation method, and conclusion.

## License

No repository license is present. Public visibility does not grant permission
to reuse the code, paper, or dataset.
