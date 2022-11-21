---
publications:
  - 
    me: Landeros A
    otherauthors:
        - and Lange K
    title: "Algorithms for Sparse Support Vector Machines"
    date: 2022
    journal: Journal of Computational and Graphical Statistics
    image: img/paper_illustration.png
    citation: "@article{landeros2022algorithms,\n\t
                author = {Alfonso Landeros and Kenneth Lange},\n\t
                title = {Algorithms for Sparse Support Vector Machines},\n\t
                journal = {Journal of Computational and Graphical Statistics},\n\t
                pages = {1-25},\n\t
                year  = {2022},\n\t
                publisher = {Taylor & Francis},\n\t
                doi = {10.1080/10618600.2022.2146697},\n\t
                URL = {https://doi.org/10.1080/10618600.2022.2146697},\n\t
                eprint = {https://doi.org/10.1080/10618600.2022.2146697}\n
              }"
    pdf: ""
    links:
      -
        name: Main URL
        url: "https://www.tandfonline.com/doi/abs/10.1080/10618600.2022.2146697"
      -
        name: Code
        url: "https://github.com/alanderos91/SparseSVM.jl"
    description: Many problems in classification involve huge numbers of irrelevant features. Variable selection reveals the crucial features, reduces the dimensionality of feature space, and improves model interpretation. In the support vector machine literature, variable selection is typically achieved by lasso penalties. These convex relaxations seriously bias parameter estimates toward 0 and tend to admit too many irrelevant features. The current paper presents an alternative that replaces penalties by sparse-set constraints. We derive two closely related algorithms based on penalizing a L2 SVM loss with sparse-set distance penalties. Our simulated and real examples vividly demonstrate how the algorithms achieve better sparsity without loss of classification power.

  -
    me: Landeros, A,
    otherauthors:
        - Padilla OHM,
        - Zhou H, and
        - Lange K
    title: "Extensions to the Proximal Distance Method of Constrained Optimization"
    date: 2022
    journal: Journal of Machine Learning Research
    citation: "@article{landeros2022extensions,\n\t
                author  = {Alfonso Landeros and Oscar Hernan Madrid Padilla and Hua Zhou and Kenneth Lange},\n\t
                title   = {Extensions to the Proximal Distance Method of Constrained Optimization},\n\t
                journal = {Journal of Machine Learning Research},\n\t
                year    = {2022},\n\t
                volume  = {23},\n\t
                number  = {182},\n\t
                pages   = {1--45},\n\t
                url     = {http://jmlr.org/papers/v23/20-964.html}\n
              }"
    pdf: https://www.jmlr.org/papers/volume23/20-964/20-964.pdf
    links:
        - 
            name: Main URL
            url: "https://www.jmlr.org/papers/v23/20-964.html"
        - 
            name: Code
            url: "https://github.com/alanderos91/ProximalDistanceAlgorithms.jl"
    description: Distance majorization is a general technique which constructs regular surrogate functions by (1) folding (semi)algebraic constraints into an objective function with a distance-to-set penalty, and (2) majorizing the penalty by a Euclidean distance between a point and its projection onto the constraint set. Algorithm maps derived using this technique are often related to a proximal operator. If fusion constraints are involved, which couple parameters through a linear operator, then proximal maps no longer apply. In this paper, we demonstrate how the MM principle underlying distance majorization can be used to derive various algorithm maps in the fusion, nonlinear constraint setting. We also prove a few convergence results with special attention to sparsity constraints.

  -
    firstauthors:
      - Mester R,
    me: Landeros A,
    otherauthors:
        - Rackauckas C, and 
        - Lange K
    title: "Differential Methods for Assessing Sensitivity in Biological Models"
    date: 2022
    journal: PLoS Computational Biology
    citation: "@article{mester2022differential,\n\t
                doi = {10.1371/journal.pcbi.1009598},\n\t
                author = {Mester, Rachel AND Landeros, Alfonso AND Rackauckas, Chris AND Lange, Kenneth},\n\t
                journal = {PLOS Computational Biology},\n\t
                publisher = {Public Library of Science},\n\t
                title = {Differential methods for assessing sensitivity in biological models},\n\t
                year = {2022},\n\t
                month = {06},\n\t
                volume = {18},\n\t
                url = {https://doi.org/10.1371/journal.pcbi.1009598},\n\t
                pages = {1-30},\n
              }"
    pdf: https://journals.plos.org/ploscompbiol/article/file?id=10.1371/journal.pcbi.1009598&type=printable
    links:
        - 
            name: Main URL
            url: "https://doi.org/10.1371/journal.pcbi.1009598"
        - 
            name: Code
            url: "https://github.com/rachelmester/SensitivityAnalysis"
    description: "Differential sensitivity analysis is indispensable in fitting parameters, understanding uncertainty, and forecasting the results of both thought and lab experiments. Although there are many methods currently available for performing differential sensitivity analysis of biological models, it can be difficult to determine which method is best suited for a particular model. In this paper, we explain a variety of differential sensitivity methods and assess their value in some typical biological models. First, we explain the mathematical basis for three numerical methods: adjoint sensitivity analysis, complex perturbation sensitivity analysis, and forward mode sensitivity analysis. We then carry out four instructive case studies. (a) The CARRGO model for tumor-immune interaction highlights the additional information that differential sensitivity analysis provides beyond traditional naive sensitivity methods, (b) the deterministic SIR model demonstrates the value of using second-order sensitivity in refining model predictions, (c) the stochastic SIR model shows how differential sensitivity can be attacked in stochastic modeling, and (d) a discrete birth-death-migration model illustrates how the complex perturbation method of differential sensitivity can be generalized to a broader range of biological models. Finally, we compare the speed, accuracy, and ease of use of these methods. We find that forward mode automatic differentiation has the quickest computational time, while the complex perturbation method is the simplest to implement and the most generalizable."

  -
    me: Landeros A,
    otherauthors:
        - Ji X,
        - Lange K,
        - Stutz TC,
        - Xu J,
        - Sehl ME, and
        - Sinsheimer JS
    title: "An Examination of School Reopening Strategies during the SARS-CoV-2 Pandemic"
    date: 2021
    journal: PLOS ONE
    citation: "@article{landeros2021examination,\n\t
                doi = {10.1371/journal.pone.0251242},\n\t
                author = {Landeros, Alfonso AND Ji, Xiang AND Lange, Kenneth AND Stutz, Timothy C. AND Xu, Jason AND Sehl, Mary E. AND Sinsheimer, Janet S.},\n\t
                journal = {PLOS ONE},\n\t
                publisher = {Public Library of Science},\n\t
                title = {An examination of school reopening strategies during the SARS-CoV-2 pandemic},\n\t
                year = {2021},\n\t
                month = {05},\n\t
                volume = {16},\n\t
                url = {https://doi.org/10.1371/journal.pone.0251242},\n\t
                pages = {1-16},\n\t
                number = {5},\n
              }"
    pdf: https://journals.plos.org/plosone/article/file?id=10.1371/journal.pone.0251242&type=printable
    links:
        - 
            name: Main URL
            url: "https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0251242"
        - 
            name: Code
            url: "https://github.com/alanderos91/COVID19SchoolReopening"
    description: "The SARS-CoV-2 pandemic led to closure of nearly all K-12 schools in the United States of America in March 2020. Although reopening K-12 schools for in-person schooling is desirable for many reasons, officials understand that risk reduction strategies and detection of cases are imperative in creating a safe return to school. Furthermore, consequences of reclosing recently opened schools are substantial and impact teachers, parents, and ultimately educational experiences in children. To address competing interests in meeting educational needs with public safety, we compare the impact of physical separation through school cohorts on SARS-CoV-2 infections against policies acting at the level of individual contacts within classrooms. Using an age-stratified Susceptible-Exposed-Infected-Removed model, we explore influences of reduced class density, transmission mitigation, and viral detection on cumulative prevalence. We consider several scenarios over a 6-month period including (1) multiple rotating cohorts in which students cycle through in-person instruction on a weekly basis, (2) parallel cohorts with in-person and remote learning tracks, (3) the impact of a hypothetical testing program with ideal and imperfect detection, and (4) varying levels of aggregate transmission reduction. Our mathematical model predicts that reducing the number of contacts through cohorts produces a larger effect than diminishing transmission rates per contact. Specifically, the latter approach requires dramatic reduction in transmission rates in order to achieve a comparable effect in minimizing infections over time. Further, our model indicates that surveillance programs using less sensitive tests may be adequate in monitoring infections within a school community by both keeping infections low and allowing for a longer period of instruction. Lastly, we underscore the importance of factoring infection prevalence in deciding when a local outbreak of infection is serious enough to require reverting to remote learning."

  -
    firstauthors:
        - Stutz TC,
    me: Landeros A,
    otherauthors:
        - Xu J,
        - Sinsheimer JS,
        - Sehl ME, and
        - Lange K
    title: "Stochastic Simulation Algorithms for Interacting Particle Systems"
    date: 2021
    journal: PLOS ONE
    citation: "@article{stutz2021stochastic,\n\t
                doi = {10.1371/journal.pone.0247046},\n\t
                author = {Stutz, Timothy C. AND Landeros, Alfonso AND Xu, Jason AND Sinsheimer, Janet S. AND Sehl, Mary AND Lange, Kenneth},\n\t
                journal = {PLOS ONE},\n\t
                publisher = {Public Library of Science},\n\t
                title = {Stochastic simulation algorithms for Interacting Particle Systems},\n\t
                year = {2021},\n\t
                month = {03},\n\t
                volume = {16},\n\t
                url = {https://doi.org/10.1371/journal.pone.0247046},\n\t
                pages = {1-15},\n\t
                number = {3},\n
              }"
    pdf: https://journals.plos.org/plosone/article/file?id=10.1371/journal.pone.0247046&type=printable
    links:
        - 
            name: Main URL
            url: "https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0247046"
        - 
            name: Code
            url: "https://github.com/alanderos91/BioSimulator.jl"
    description: "Interacting Particle Systems (IPSs) are used to model spatio-temporal stochastic systems in many disparate areas of science. We design an algorithmic framework that reduces IPS simulation to simulation of well-mixed Chemical Reaction Networks (CRNs). This framework minimizes the number of associated reaction channels and decouples the computational cost of the simulations from the size of the lattice. Decoupling allows our software to make use of a wide class of techniques typically reserved for well-mixed CRNs. We implement the direct stochastic simulation algorithm in the open source programming language Julia. We also apply our algorithms to several complex spatial stochastic phenomena. including a rock-paper-scissors game, cancer growth in response to immunotherapy, and lipid oxidation dynamics. Our approach aids in standardizing mathematical models and in generating hypotheses based on concrete mechanistic behavior across a wide range of observed spatial phenomena."

  -
    me: Landeros A,
    otherauthors:
        - Stutz TC,
        - Keys KL,
        - Alekseyenko A,
        - Sinsheimer JS,
        - Lange K, and
        - Sehl ME
    title: "BioSimualtor.jl: Stochastic Simulation in Julia"
    date: 2018
    journal: Computer Methods and Programs in Biomedicine
    citation: "@article{landeros2018biosimulator,\n\t
                title = {{{BioSimulator}}.Jl: Stochastic Simulation in {{Julia}}},\n\t
                shorttitle = {{{BioSimulator}}.Jl},\n\t
                author = {Landeros, Alfonso and Stutz, Timothy and Keys, Kevin L. and Alekseyenko, Alexander and Sinsheimer, Janet S. and Lange, Kenneth and Sehl, Mary E.},\n\t
                year = {2018},\n\t
                journal = {Computer Methods and Programs in Biomedicine},\n\t
                volume = {167},\n\t
                pages = {23--35},\n\t
                issn = {0169-2607},\n\t
                doi = {10.1016/j.cmpb.2018.09.009},\n\t
                langid = {english}\n
              }"
    pdf: "https://arxiv.org/pdf/1811.12499.pdf"
    links:
        - 
            name: Main URL
            url: "https://www.sciencedirect.com/science/article/abs/pii/S0169260718301822?via%3Dihub"
        - 
            name: Code
            url: "https://github.com/alanderos91/BioSimulator.jl"
    description: Biological systems with intertwined feedback loops pose a challenge to mathematical modeling efforts. Moreover, rare events, such as mutation and extinction, complicate system dynamics. Stochastic simulation algorithms are useful in generating time-evolution trajectories for these systems because they can adequately capture the influence of random fluctuations and quantify rare events. We present a simple and flexible package, BioSimulator.jl, for implementing the Gillespie algorithm, $\tau$-leaping, and related stochastic simulation algorithms. The objective of this work is to provide scientists across domains with fast, user-friendly simulation tools.

  -
    firstauthors:
        - Sehl ME,
        - Shimada M
    me: Landeros A,
    otherauthors:
        - Lange K, and
        - Wicha MS
    title: "Modeling of Cancer Stem Cell State Transitions Predicts Therapeutic Response"
    date: 2015
    journal: PLOS ONE
    citation: "@article{sehl2015modeling,\n\t
                doi = {10.1371/journal.pone.0135797},\n\t
                author = {Sehl, Mary E. AND Shimada, Miki AND Landeros, Alfonso AND Lange, Kenneth AND Wicha, Max S.},\n\t
                journal = {PLOS ONE},\n\t
                publisher = {Public Library of Science},\n\t
                title = {Modeling of Cancer Stem Cell State Transitions Predicts Therapeutic Response},\n\t
                year = {2015},\n\t
                month = {09},\n\t
                volume = {10},\n\t
                url = {https://doi.org/10.1371/journal.pone.0135797},\n\t
                pages = {1-20},\n\t
                number = {9},\n
              }"
    pdf: https://journals.plos.org/plosone/article/file?id=10.1371/journal.pone.0135797&type=printable
    links:
        - 
            name: Main URL
            url: "https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0135797"

    description: Cancer stem cells (CSCs) possess capacity to both self-renew and generate all cells within a tumor, and are thought to drive tumor recurrence. Targeting the stem cell niche to eradicate CSCs represents an important area of therapeutic development. The complex nature of many interacting elements of the stem cell niche, including both intracellular signals and microenvironmental growth factors and cytokines, creates a challenge in choosing which elements to target, alone or in combination. We present a mathematical model of the breast cancer stem cell (BCSC) niche to predict population dynamics during carcinogenesis and in response to treatment. Using data from cell line and mouse xenograft experiments, we estimate rates of interconversion between mesenchymal and epithelial states in BCSCs and find that EMT/MET transitions occur frequently. We examine bulk tumor growth dynamics in response to alterations in the rate of symmetric self-renewal of BCSCs and find that small changes in BCSC behavior can give rise to the Gompertzian growth pattern observed in breast tumors. Finally, we examine stochastic reaction kinetic simulations in which elements of the breast cancer stem cell niche are inhibited individually and in combination.
preprints:
  -
    me: Landeros A,
    otherauthors:
        - Wu TT, and
        - Lange K
    title: "Sparse Vertex Discriminant Analysis: Feature Selection for Biomedical Classification Applications"
    date: 2022
    journal: TBD
    # citation: 
    # pdf: 
    # links:
    #     - 
    #         name: Main URL
    #         url: "https://www.jmlr.org/papers/v23/20-964.html"
    #     - 
    #         name: Code
    #         url: ""
    # description: TODO
  -
    me: Landeros A,
    otherauthors:
        - Liu W,
        - Sehl ME,
        - Tamori Y,
        - Deng W, and
        - Ji X
    title: "Lattice-based Mathematical Models of Cancer Cell Competition in Drosophila"
    date: 2022
    journal: TBD
    # citation: 
    # pdf: 
    # links:
    #     - 
    #         name: Main URL
    #         url: "https://www.jmlr.org/papers/v23/20-964.html"
    #     - 
    #         name: Code
    #         url: ""
    # description: TODO
  -
    me: Landeros A,
    otherauthors:
        - Padilla OHM,
        - Zhou H,
        - Zshou J, and
        - Lange K
    title: "Hierarchical Regression Modelling for Integrating Genomics Data"
    date: 2022
    journal: TBD
    # citation: 
    # pdf: 
    # links:
    #     - 
    #         name: Main URL
    #         url: "https://www.jmlr.org/papers/v23/20-964.html"
    #     - 
    #         name: Code
    #         url: ""
    # description: TODO
---

# Research Interests

I am broadly interested in mathematical modelling, optimization, and applications of quantitative skills to science.
I have a soft spot for stochastic models and enjoy learning about human genetics, immunology, and cancer immunobiology.

My preferred language for computing is [Julia](https://julialang.org/). Other programming languages are great and useful, too.