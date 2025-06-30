# Decentralized Payout Tracker

This project is currently **under development**.

## Project Overview

The Decentralized Payout Tracker is a simple application designed to allow users to record payments received or made to specific blockchain addresses. These payment records are stored on the blockchain, either as events or contract data, and a user-friendly frontend will display them.

This project serves as an excellent learning experience for those interested in Rust and Web3 development, offering insights into fundamental blockchain interactions, Rust backend development, and core Web3 concepts.

## Core Components:

* **Solana Program (Smart Contract):** A Rust-based Solana Program will be used to store and manage payment logs on the Solana Devnet.
* **Rust Backend:** Written in Rust, this component will handle requests from the frontend, prepare blockchain transactions, and send them to the Solana network. It will utilize frameworks like `actix-web` or `rocket` and blockchain libraries such as `solana_sdk` or `anchor-lang`.
* **Next.js Frontend:** The user interface will be built using Next.js (React), interacting with the Rust backend and potentially leveraging `solana-web3.js` for direct blockchain interactions or wallet connectivity.

## Current Status

We are actively working on implementing the core functionalities across all three major components: the Solana program, the Rust backend API, and the Next.js frontend. Progress will be updated regularly.

## Learning Outcomes

Upon completion, this project aims to provide strong practical knowledge in:
* Rust Fundamentals (ownership, borrowing, error handling, async/await) 
* Building REST APIs with Rust 
* Connecting to and interacting with Solana blockchain nodes 
* Reading and writing on-chain data 
* Core Web3 concepts (addresses, private keys, transactions, on-chain data)

Thank you for your interest!