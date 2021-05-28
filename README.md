# ApproxFlow

>* ApproxFlow is a toolbox for the evaluation of approximate multiliers on DNNs. 

## How to

>* Download the code. 
>>* Dependencies: cmake, g++, openmp

>* mkdir build

>* cd build

>* cmake ..

>* make

>* ./approxflow

>* Run different tests by modifying main.cpp and probably Tests/TestQuantArray0.h. 

## Note

>* You can run testMNIST / testFashionMNIST / testCIFAR10AlexNet functions with various look-up tables of approximate multipliers. 

>* The look-up tables are put in the Utils folder: 

|  Multiplier | File Name  |
|  ----  | ----  |
| Wallace Tree | accurate.csv |
| HEAM         | LUT_ours.txt |
| KMap\[1\]         | approximate.csv |
| AC\[2\]           | LUT_AC.txt |
| CR(C.6)\[3\]      | LUT_CR(C.6).txt |
| CR(C.7)      | LUT_CR(C.7).txt |
| OU(L.1)\[4\]      | LUT_OU(L.1).txt |
| OU(L.3)      | LUT_OU(L.3).txt |
| SDLC\[5\]         | LUT_SDLC.txt |

## Reference

\[1\] P. Kulkarni, P. Gupta, and M. Ercegovac. Trading Accuracy for Power with an Underdesigned Multiplier Architecture. 2011 24th Internatioal Conference on VLSI Design, 2011. 

\[2\] A. Momeni, J. Han, P. Montuschi, and F. Lombardi. Design and Analysis of Approximate Compressors for Multiplication. IEEE Transactions on Computers, 2015. 

\[3\] C. Liu, J. Han, and F. Lombardi. A low-power, high-performance approximate multiplier with configurable partial error recovery. Design, Automation and Test in Europe Conference and Exhibition (DATE), 2014. 

\[4\] C. Chen et al. Optimally Approximated and Unbiased Floating-Point Multiplier with Runtime Configurability. Proceedings of the 39th International Conference on Computer-Aided Desig. 2020. 

\[5\] I. Qiqieh, R. Shafik, G. Tarawneh, D. Sokolov, and A. Yakovlev, "Energy-efficient approximate multiplier design using bit significance-driven logic compression," in Design, Automation and Test
  in Europe Conference Exhibition (DATE), 2017.
