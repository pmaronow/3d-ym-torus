# The continuum limit of three-dimensional SU(2) lattice Yang–Mills theory on a torus

P. M. Aronow and Patrick Lopatto

[Read the manuscript](3d-ym-torus.pdf) · [LaTeX source](source/)

With the exception of this note, the entire document is machine-written. We have taken care to supervise this writing to ensure that the proofs meet a minimum standard of readability and that previous literature is appropriately cited.

The manuscript began as an attempt to pursue the program of Magnen, Rivasseau, and Sénéor [132] using large language models. Our hope was that understanding the problem on the torus might offer some insight into the general case. The construction that resulted from this starting point is three-dimensional and lattice-based, and draws extensively on Bałaban’s renormalization group methods.

As we were verifying these results, we learned that Sussman and Alpöge announced that YM4 has been done, following Bałaban’s program (https://github.com/ethanwsussman/Yang--Mills-LLM-experiment). We are thrilled and look forward to learning more about these exciting developments. We hope that this manuscript nonetheless contributes to understanding constructive approaches to three-dimensional Yang–Mills theory. We did not inspect and, to the best of our knowledge, the LLMs we used did not access the ongoing work of Sussman and Alpöge.

Although we have done extensive machine auditing of these proofs, including adversarial passes with multiple models, the proof is too complex for either (i) Lean autoformalization given the authors’ resources or (ii) our own understanding of the results. Thus we are less confident in correctness than we are in our other work. We welcome suggestions concerning mathematical corrections, omitted citations, and attribution of ideas.

P. L. was partially supported by NSF grant DMS-2450004.

To build the manuscript, run `latexmk -pdf main.tex` from the `source/` directory.
