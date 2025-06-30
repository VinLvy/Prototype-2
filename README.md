# Decentralized Payout Tracker

This project is currently **under development**.

## Project Overview

[cite_start]The Decentralized Payout Tracker is a simple application designed to allow users to record payments received or made to specific blockchain addresses[cite: 1]. [cite_start]These payment records are stored on the blockchain, either as events or contract data, and a user-friendly frontend will display them[cite: 2].

[cite_start]This project serves as an excellent learning experience for those interested in Rust and Web3 development, offering insights into fundamental blockchain interactions, Rust backend development, and core Web3 concepts[cite: 3, 4, 6].

## Core Components:

* [cite_start]**Solana Program (Smart Contract):** A Rust-based Solana Program will be used to store and manage payment logs on the Solana Devnet[cite: 9, 11, 20].
* [cite_start]**Rust Backend:** Written in Rust, this component will handle requests from the frontend, prepare blockchain transactions, and send them to the Solana network[cite: 4, 12, 22]. [cite_start]It will utilize frameworks like `actix-web` or `rocket` [cite: 13] [cite_start]and blockchain libraries such as `solana_sdk` or `anchor-lang`[cite: 14].
* [cite_start]**Next.js Frontend:** The user interface will be built using Next.js (React), interacting with the Rust backend and potentially leveraging `solana-web3.js` for direct blockchain interactions or wallet connectivity[cite: 16, 17].

## Current Status

We are actively working on implementing the core functionalities across all three major components: the Solana program, the Rust backend API, and the Next.js frontend. Progress will be updated regularly.

## Learning Outcomes

Upon completion, this project aims to provide strong practical knowledge in:
* [cite_start]Rust Fundamentals (ownership, borrowing, error handling, async/await) [cite: 27]
* [cite_start]Building REST APIs with Rust [cite: 29]
* [cite_start]Connecting to and interacting with Solana blockchain nodes [cite: 31]
* [cite_start]Reading and writing on-chain data [cite: 32]
* [cite_start]Core Web3 concepts (addresses, private keys, transactions, on-chain data) [cite: 6]

Thank you for your interest!