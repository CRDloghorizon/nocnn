# NN Noxim
Prerequest: SystemC 2.3.3
Go to ./bin, change the SystemC library in makefile.defs and then install using make
Run the simulator: change the SystemC library in the link_library file, source it
Then: ./noxim -dimx 3 -dimy 3 -dimz 1 -NNmodel model.txt -NNweight weight.txt -NNinput input.txt -mapping random -groupsize 100 -sim 10000


# nocnn
Performance/Energy estimation of NoC-based Deep Neural Network accelerators

Run this simulator, you need to make first.
Then, using the following command:
./nocnn cfg/alexnet.cfg cfg/noc-sample.cfg
