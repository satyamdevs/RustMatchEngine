🦀 Rust Matching Engine 

A minimal matching engine prototype written in Rust.
It includes a simple orderbook, price levels, limit orders, and basic matching logic.

 Features

Bids & asks stored in separate price-level maps

Add limit orders to the orderbook

Market order filling (partial & multi-order)

MatchingEngine supporting multiple trading pairs

Example usage in main.rs

Unit tests for order matching

📁 Structure
src/
 ├── main.rs
 └── matching_engine/
       ├── mod.rs
       ├── engine.rs
       └── orderbook.rs

▶️ Run
cargo run

🧪 Tests
cargo test
