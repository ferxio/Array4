# Array4
 A set of array management tools in python and Julia
with functions to evaluate differential operators or
frontier conditions.
 The module is a set of functions to simplify the management
of arrays in problems related with Reaction-Difusion Systems
with constant Difusion Coefficient or with tensorial coefficient X_ as
                  div(X_ grad(u)).
A list fo functions there

export argmaxind
   export argminind
   export dij # distancia euclidiana entre dos SD's
   
   ### numericos
   #############

   export partial1
   export grad1
   export partial
   export grad
   export divXgrad
   export Lap_5
   export Lap_9

   ###  suma de vecinos AC
   #######################

   export Sum_4
   export Sum_8
   export Count_4
   export Count_8
   
########## STAT ##########
##########################

### HISTOGRAM
   export Histogram
   export Theta
   export r
   export r_list
   export s_
   export s
   export s_list
   export Hurst
   export miHurst
   export Pareto
   export Pareto
   export Pareto_array
   export ExpPareto
   export LinearFit

   export fill
   export fill!

########### EXTREMA ##########
##############################

### local maxima
   export FindLocalExtrema
   export FindLocalMaxima
   export FindLocalMinima

   ### frontier
   #############

   export Frontier!
   export FrontierZeroDeriv!
   export FrontierPeriodic!
   export FrontierZero!
   export FrontierConst!

   ### files
   ############
   
   export savearray
   export loadarray
   export savearraytab
   export savearray3d
   export loadarray3d
   export normalize
