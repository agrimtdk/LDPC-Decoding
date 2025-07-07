# LDPC-Decoding

LDPC Decoding for 5G NR
This project implements Low-Density Parity-Check (LDPC) encoding and decoding algorithms used in 5G New Radio (NR). LDPC codes are linear error-correcting codes designed for high-performance communication over noisy channels with minimal latency.

📌 Features
Construction of LDPC Base Graphs (BG1/BG2) and expansion to H matrices

Encoding using structured parity equations

BPSK modulation and simulation over AWGN channel

Hard Decision Decoding using majority voting and XOR logic

Soft Decision Decoding using Min-Sum Approximation with Log-Likelihood Ratios (LLRs)

Comparison of Bit Error Rate (BER) across different code rates (1/4 to 4/5)

📈 Technologies
Python (NumPy, Matplotlib)

Monte Carlo simulations for BER estimation

Based on 3GPP-compliant base graphs

📊 Results
Demonstrated lower BER with soft decision decoding over hard decision decoding

Performance evaluated for various code rates using NR matrices

📚 References
CT216 Lectures by Prof. Yash Vasavada

NPTEL Lectures by Prof. Andrew Thangaraj

3GPP LDPC specifications for 5G NR
