# multilevel-balance
Jupyter code for multi-level evaluation of balance in directed signed graphs incluidng the binary linear programming model for computing the frustration index of directed signed graphs as described in the paper:
Aref, S., Dinh, L., Rezapour, R. et al. Multilevel structural evaluation of signed directed social networks based on balance theory. Sci Rep 10, 15228 (2020). https://doi.org/10.1038/s41598-020-71838-6

This algorithm is developed in Python 3.7 based on the computational methods for multilevel evaluation of balanced including computing the exact value of frustration index discussed in the above article.

Jupyter code written by Samin Aref, Rezvaneh Rezapour, and Ly Dinh in 2020

Creative common license: Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)

Using this code for non-commercial purposes is permitted to all given that the three following publications are cited:

1. Aref, S., Dinh, L., Rezapour, R. et al. Multilevel structural evaluation of signed directed social networks based on balance theory. Sci Rep 10, 15228 (2020). https://doi.org/10.1038/s41598-020-71838-6

2. Aref, S., Mason, A. J., & Wilson, M. C. (2020). A modeling and computational study of the frustration index in signed networks. Networks, 75(1), 95-110. url: https://doi.org/10.1002/net.21907

3. Aref, S., Mason, A. J., and Wilson, M. C. Computing the line index of balance using integer programming optimisation. In Optimization Problems in Graph Theory, B. Goldengorin, Ed. Springer, 2018, pp. 65-84. https://doi.org/10.1007/978-3-319-94830-0_3

Related datasets:

Aref, S., Dinh, L., and Rezapour, R. : Dataset of directed signed networks from social domain. figshare data repository, 2020, https://doi.org/10.6084/m9.figshare.12152628

The following steps outline the process for installing the required software on your computer to be able to run the code:

1-Download and install Anaconda (Python 3.7 version) which allows you to run a Jupyter code. It can be downloaded from https://www.anaconda.com/distribution/. Note that you must select your operating system first and download the corresponding installer.

2-Register for an account on https://www.gurobi.com/registration-general-reg/ to get a free academic license for using Gurobi. Note that Gurobi is a commercial software, but it can be registered with a free academic license if the user is affiliated with a recognized degree-granting academic institution. This involves creating an account on Gurobi website to be able to request a free academic license in step 5.

3-Download and install Gurobi Optimizer (Latest version recommended) which can be downloaded from https://www.gurobi.com/downloads/gurobi-optimizer-eula/ after reading and agreeing to Gurobi's End User License Agreement.

4-Install Gurobi into Anaconda. You do this by first adding the Gurobi channel to your Anaconda channels and then installing the Gurobi package from this channel.

From a terminal window issue the following command to add the Gurobi channel to your default search list

conda config --add channels http://conda.anaconda.org/gurobi

Now issue the following command to install the Gurobi package

conda install gurobi

5-Request an academic license from https://www.gurobi.com/downloads/end-user-license-agreement-academic/ and install the license on your computer following the instructions given on Gurobi license page.

Completing these steps is explained in the following links (for version 9.0):

for windows https://www.gurobi.com/documentation/9.0/quickstart_windows/ins_the_anaconda_python_di.html

for Linux https://www.gurobi.com/documentation/9.0/quickstart_linux/ins_the_anaconda_python_di.html

for Mac OSX https://www.gurobi.com/documentation/9.0/quickstart_mac/ins_the_anaconda_python_di.html

After following the instructions above, open Jupyter Notebook which takes you to an environment (a new tab on your browser pops up on your screen) where you can open the main code (which is a file with .ipynb extension).
