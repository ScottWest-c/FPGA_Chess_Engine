# FPGA_Chess_Engine

This project is a hardware accelerator for the [PeSTO](https://www.chessprogramming.org/PeSTO%27s_Evaluation_Function) evaluation function. It is designed to communicate with a Python script on a computer through the serial port to play chess in the terminal. An Arty Z7, Zynq-7000 series SoC, is being used for this project. The ARM microcontroller receives the position in the [FEN](https://www.chessprogramming.org/Forsyth-Edwards_Notation) format and converts it into an array. Then the MCU performs a [Minimax](https://www.chessprogramming.org/Minimax) search to find the best move using the FPGA as the evaluation function. 




TODO: Add Signal for Completed Evaluation, Use a FIFO instead of BRAM and [En Passant](https://en.wikipedia.org/wiki/En_passant) 
