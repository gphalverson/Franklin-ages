# Franklin-ages
Simple Bayesian updating model applied to updating the ages of crosscutting Franklin dykes and sills

This model is adapted to R from the "Barebones" model presented in Johnstone et al. (2019), which was written in Python. It is provided here as an R notebook that should be able to run without any modification. Note that while we use a simple Metropolis-Hastings MCMC algorithm, the same results can be generated via a Monte Carlo approach. The Barebones model is used both to update the ages of the Franklin dykes and sills in the Fury and Hecla and Thule basins presented in Dufour et al. (2023) and to update U-Pb ages bracketing the base of the Sturtian Eagle Creek Formation in the Ogilvie Mountains of Yukon (Macdonald et al., 2010; 2018). The latter ages are then used to estimate the Sturtian onset age, which can easily be adapted based on new or other age constraints. 

References

Dufour, F., Davies, J.H.F.L., Greenman, J.W., Skulski, T., Halverson, G.P., in review. New U-Pb CA-ID TIMS zircon ages implicate the Franklin LIP as the proximal trigger for the Sturtian Snowball Earth event. Earth Plan. Sci. Lett. 
Johnstone, S.A., Schwartz, T.M. Holm-Denoma, C.S., 2019. A stratigraphic approach to inferring depositional ages from detrital geochronology data. Front. Earth Sci. 7, 57.
Macdonald, F.A., Schmitz, M.D., Crowley, J.L., Roots, C.F., Jones, D.S., Maloof, A.C., Strauss, J.V., Cohen, P.A., Johnston, D.T., Schrag, D.P., 2010. Calibrating the cryogenian. science 327, 1241–1243.
Macdonald, F.A., Schmitz, M.D., Strauss, J.V., Halverson, G.P., Gibson, T.M., Eyster, A., Cox, G., Mamrol, P., Crowley, J.L., 2018. Cryogenian of Yukon. Precambrian Res. 319, 114–143.
