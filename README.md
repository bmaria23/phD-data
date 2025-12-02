# phD-data

This dataset accompanies the phD thesis 'Nonperturbative properties of QCD vertices and their connection to dynamical mass generation'. Two sets of data are included in this dataset.

1) Data from the article: https://doi.org/10.1140/epjc/s10052-023-12058-w [Preprint version: https://arxiv.org/abs/2306.16283].

This dataset consists of data for the residue function associated with the pole structure of the three-gluon vertex. Using both the STI and the SDE for this vertex, we compute the residue function of the pole associated with a structure following a double pole of the vertex. To numerically determine this residue function, we solve the SDE for the form factor $A_3^p(q)$ of the ghost-gluon scattering kernel. These two sets of data constitute the contributions of this article.

The data generated in this article are contained in two files: 'A3p.dat' and 'V9.dat'. The first file contains the data for the form factor $A_3^p(q)$ of the ghost-gluon scattering kernel as a function of the momentum $q$. The second file contains the data for the residue function $V_9(q)$ as a function of the momentum $q$, computed via the STI result using the SDE result for $A_3^p(q)$, and via the SDE with $A_3^p(q)=0$.

The figures in the article use the data as follows:

Fig. 9 (right panel) data are contained in the 'A3p.dat' file. 

Fig. 10 displays the data in the file 'V9.dat'.

2) Data from the article: https://doi.org/10.1140/epjc/s10052-024-13605-9 [Preprint version: https://arxiv.org/abs/2408.15370].

Consists on data for the eight form factors of the transversally projected quark-gluon vertex through its 3PI SDE, in the Landau gauge, with two degenerate light quarks, using as external inputs the gluon and quark propagators and three-gluon vertex as lattice data fits. 

The data for the eight form factors, $\lambda_i$, with i=1,...,8, in the form of arrays Lambdai(nx,nx,nth) with nx=30 and nth=10, is containned in the file 'formfactors.dat'.

The figures in the article use the files as follows:

Figs. 5 and 6 show $\lambda_1$ in general kinematics, in the fourth column of the file 'formfactors.dat'.

Figs. 7, 8, and 9 contain $\lambda_i$ with $i = 2,\dots,8$ in general kinematics, from columns five to eleven of the file 'formfactors.dat'.

Fig. 10 uses the same $\lambda_1$ data as in Figs. 5 and 6. The other form factors are taken from Figs. 7–9. This data, combined with the fits of the gluon and quark propagators using Eq. (5.1), produces Fig. 10.

Fig. 11 also uses the same $\lambda_1$ data as in Figs. 5 and 6, and combined with the propagators via Eq. (5.1), yields Fig. 11.

Figs. 12, 13, and 15 include the solid black curve corresponding to the soft-gluon limit of $\lambda_1$, obtained by selecting the relevant points from $\lambda_1$: those with the same momenta and minimal $\theta$.

Fig. 14 presents the SDE results from the file 'formfactors.dat' for $\lambda_6$ and $\lambda_2$, again selecting the points with the same momenta and minimal $\theta$ to extract the soft-gluon limit.

For more information, feel free to contact: bianca.mso23@gmail.com.
