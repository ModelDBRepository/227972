Contributed by Daniel Jercog.


This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details (http://www.gnu.org/licenses/).


Contains both rate and spiking network model implementations from the paper Jercog et al 2017. Both models generate the time courses for E & I population rates and adaptation presented. In addition, the Spiking network generates individual spiking activity in rasters. A complete description of the model is provided in the methods of the paper.

+ Rate model (compiled in Matlab 2009 - Linux).
  Include following files in a separated folder:
  -singleSimEIModel.m: main function (also plots the output traces).
  -eiModelParams.m: model parameters.
  -eiModel.mexa64: Compiled MEX-function from source eiModel.cpp (Unix).
  -eiModel.cpp: c++ mex-function source.
  -rate_readme.txt: description.

+ Spiking Model (compiled in g++ 6.4.3 - Linux):
  Include following files in a separated folder:
  -main.cpp: main function, generate output bin files.
  -functions.h:   auxiliar functions.
  -functions.cpp: auxiliar functions.
  -spiking_readme.txt: description.

Further instructions for usage of each model in their corresponding readme-files.
