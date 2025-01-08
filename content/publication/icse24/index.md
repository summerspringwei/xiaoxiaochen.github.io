---
title: "Combining Structured Static Code Information and Dynamic Symbolic Traces for Software Vulnerability Prediction"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - huanting-wang
  - zhanyong-tang
  - Shin Hwei Tan
  - chunwei-xia
  - zheng-wang

date: '2024-01-14T00:00:00Z'

doi: '10.1145/3597503.3639212'
# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-14T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "The 46th IEEE/ACM International Conference on Software Engineering, is the premier software engineering conference (ICSE) (**Artifacts Evaluated!**)"
publication_short: "ICSE'24"
publication_url: "https://conf.researchr.org/home/icse-2024"

url_pdf: "publications/icse24.pdf"
url_dataset: "https://github.com/HuantWang/CONCOCTION"
url_code: "https://github.com/HuantWang/CONCOCTION"

featured: false
selected_on_front: ["true"]
aeavailable: true
aereusable: true
aefunctional: true

abstract: Deep learning (DL) has emerged as a viable means for identifying software bugs and vulnerabilities. The success of DL relies on having a suitable representation of the problem domain. However, existing DL-based solutions for learning program representations have limitations - they either cannot capture the deep, precise program semantics or suffer from poor scalability. We present Concoction, the first DL system to learn program presentations by combining static source code information and dynamic program execution traces. Concoction employs unsupervised active learning techniques to determine a subset of important paths to collect dynamic symbolic execution traces. By implementing a focused symbolic execution solution, Concoction brings the benefits of static and dynamic code features while reducing the expensive symbolic execution overhead. We integrate Concoction with fuzzing techniques to detect function-level code vulnerabilities in C programs from 20 open-source projects. In 200 hours of automated concurrent test runs, Concoction has successfully uncovered vulnerabilities in all tested projects, identifying 54 unique vulnerabilities and yielding 37 new, unique CVE IDs. Concoction also significantly outperforms 16 prior methods by providing higher accuracy and lower false positive rates.

---
