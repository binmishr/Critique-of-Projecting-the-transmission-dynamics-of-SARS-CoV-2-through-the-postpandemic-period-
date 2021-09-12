# Critique-of-Projecting-the-transmission-dynamics-of-SARS-CoV-2-through-the-postpandemic-period

The details of the codeset and plots are included in the attached Microsoft Word Document (.docx) file in this repository. 
You need to view the file in "Read Mode" to see the contents properly after downloading the same.

This is one of the papers referenced in my recent post on seasonality of COVID-19. The paper does several things that seem interesting:

    It looks at past incidence of “common cold” coronaviruses, estimating the viruses’ reproduction numbers (R) over time, and from that their degrees of cross-immunity and the seasonal effect on their transmission. It fits an ODE model for the two common cold betacoronaviruses, which are related to SARS-CoV-2 (the virus for COVID-19), using the same data.
    It then adds SARS-CoV-2 to this ODE model, and looks at various scenarios for the future, varying the duration of immunity for SARS-CoV-2, the degree of cross-immunity of SARS-CoV-2 and common cold betacoronaviruses, and the effect of season on SARS-CoV-2 transmission.

In future posts, I’ll discuss the substance of these contributions. In this post, I’ll talk about my efforts at reproducing the results in the paper from the code and data available, which is a prerequisite for examining why the results are as they are, and for looking at how the methods used might be improved.

I’ll also talk about an amusing / horrifying aspect of the R code used, which I encountered along the way, about CDC data sharing policy, and about the authors’ choices regarding some graphical presentations.
