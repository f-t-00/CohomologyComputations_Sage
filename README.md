# CohomologyComputations_Sage

We include here the Sage code used to compute the dimension of the Lie algebra cohomology in degree 2 of the following 16-dimensional Lie algebra g.

The Lie algebra can be endowed with a 3-step stratification g=V_1\oplus V_2\oplus V_3 with 

V_1=span{X_1,X_2,X_3,X_4,X_5,X_6,X_7,X_8},

V_2=span{T_1,T_2,T_3,T_4} and V_3=span{W_1,W_2,W_3,W_4}

The only non trivial brackets of the Lie algebra are the following: 

[X_1,X_2]=[X_3,X_4]=T_1 , [X_2,X_3]=[X_4,X_5]=T_2, [X_3,X_5]=[X_4,X_6]=T_3, [X_1,X_3]=[X_2,X_4]=[X_5,X_6]=T_4

[X_1,T_1]=-[X_5,T_3]=-[X_4,T_4]=W_1, [X_3,T_2]=[X_4,T_3]=W_2, [X_3,T_4]=-[X_6,T_3]=W_3, [X_4,T_2]=W_3-[X_2,T_1]=W_4

The Sage programme computes the dimension of the Lie algebra cohomology in degree 2, which is equal to 24.

Since H^2(g) contains at least the 24-dimensional space of Lie algebra cohomology in weight 2 (this follows from the fact that the space of 2-forms of weight 2 is 28=8!/(2!6!) while the image of d_0 from 1-forms of weight 2 is 4-dimensional), this directly implies that the Lie algebra cohomology in degree 2 and weight greater than 2 must be 0.
