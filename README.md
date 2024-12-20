# DeribitOEMS
## A High-Performance Trading System for Deribit Test

A high-efficiency trading system implemented in C++ designed for Deribit Test. This solution supports real-time market data processing, order management, and low-latency WebSocket communication, making it ideal for trading in Spot, Futures, and Options markets.

---

## Key Features

### Core Functionalities

#### **Order Management**
- **Place Orders**: Submit buy or sell orders efficiently.
- **Cancel Orders**: Remove active orders with minimal latency.
- **Modify Orders**: Adjust existing order parameters seamlessly.
- **Retrieve Orderbook**: Access current market depth data.
- **View Current Positions**: Monitor active positions with detailed metrics.

#### **Real-Time Market Data Streaming**
- Built-in WebSocket server:
  - Manage client connections efficiently.
  - Enable subscriptions to specific symbols.
  - Stream continuous updates for orderbook data.

### Market Coverage
- **Supported Instruments**:
  - Spot Trading
  - Futures Contracts
  - Options Trading
- **Scope**: Includes all symbols supported by Deribit Test.

---

## Technical Overview

### Language and Performance
- **Programming Language**: C++
- **Performance**: Optimized for low-latency trading operations.

### Error Handling and Logging
- Implements comprehensive logging to track issues and system events.
- Robust error management ensures minimal downtime and high reliability.

### WebSocket Server Capabilities
- Efficient **connection management** for multiple clients.
- Dynamic **subscription handling** for specific symbols.
- High-speed **message broadcasting** for real-time updates.

---

## Advanced Features (Optional)

### Performance Analysis and Optimization
#### Latency Benchmarking:
- **Order Placement Latency**: Measure the time taken to place orders.
- **Market Data Processing Latency**: Evaluate the time required to process incoming data.
- **WebSocket Message Propagation Delay**: Assess the delay in broadcasting messages.
- **End-to-End Trading Loop Latency**: Benchmark the overall system efficiency.

#### Optimization Techniques:
- Enhanced memory management for smoother operations.
- Streamlined network communication protocols.
- Optimal selection of data structures for trading.
- Effective thread management to maximize CPU utilization.
- Comprehensive CPU optimization to reduce processing overhead.

### Documentation
- Detailed bottleneck analysis reports.
- Methodologies for benchmarking performance.
- Justification for optimization decisions based on empirical results.

---

## Installation Guide

### Prerequisites

#### Development Environment
- Visual Studio 2022 (or an equivalent IDE).

#### Dependencies
- **cURL library**: For handling HTTP requests.
- **WebSocket library** (e.g., `websocketpp`): For WebSocket communication.
- **vcpkg**: For managing project dependencies.

#### API Setup
1. Create an account on [Deribit Test](https://test.deribit.com/).
2. Generate API keys for authentication.

---

### Installation Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/Rachit2912/DeribitOEMS.git
   ```
2. Install dependencies using vcpkg:
   ```bash
   ./vcpkg install curl websocketpp
   ```
3. Build the project using Visual Studio or your preferred IDE.
4. Run the executable and start trading.

---

## Contribution Guidelines
- Fork the repository and create a new branch for your changes.
- Submit pull requests with clear descriptions of your modifications.
- Ensure the code adheres to the project’s coding standards.

---

## Future Enhancements
- Incorporate machine learning for predictive analytics.
- Add support for additional trading platforms.
- Introduce graphical visualization tools for orderbook data.

---

