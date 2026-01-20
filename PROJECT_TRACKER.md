# MatrixCBot Project Tracker

## Project Overview
This document tracks the progress and tasks for the MatrixCBot algorithmic forex trading project.

**Project Goal:** Develop a sophisticated algorithmic forex trading bot with AI integration, multi-pair correlation analysis, and advanced risk management.

**Version:** 0.1.0  
**Last Updated:** 2025-01-20

---

## Development Phases

### Phase 1: Core Infrastructure (In Progress)
- [x] Setup GitHub repository with template structure
- [x] Configure `pyproject.toml` with dependencies
- [x] Setup Python package structure (`matrixcbot/`)
- [x] Configure development tools (pytest, black, mypy, flake8)
- [ ] Implement logging system
- [ ] Setup configuration management (from `.env`)

### Phase 2: Trading Filters & Indicators
- [ ] Implement EMA (Exponential Moving Average) filter
- [ ] Implement MACD (Moving Average Convergence Divergence)
- [ ] Implement RSI (Relative Strength Index)
- [ ] Implement Stochastic Oscillator
- [ ] Add correlation analysis between trading pairs
- [ ] Supply & Demand zone detection

### Phase 3: AI Integration
- [ ] Setup AI model endpoint (Mistral/Claude/Ollama)
- [ ] Implement signal prediction using AI
- [ ] Create training pipeline for ML models
- [ ] Backtesting framework

### Phase 4: cTrader Integration
- [ ] Connect to cTrader API
- [ ] Implement position sizing logic
- [ ] Add trade execution with risk limits
- [ ] Position management & TP/SL automation
- [ ] Real-time signal monitoring

### Phase 5: Risk Management & Optimization
- [ ] Risk blocks implementation
- [ ] Drawdown limits
- [ ] Daily loss limits
- [ ] Portfolio rebalancing
- [ ] Performance optimization

---

## Current Tasks

### High Priority
1. **Setup CI/CD Pipeline** - GitHub Actions for automated testing
   - [ ] Create `.github/workflows/test.yml`
   - [ ] Run pytest on every push
   - [ ] Add coverage reporting

2. **Implement Core Filters**
   - [ ] EMA filter module
   - [ ] RSI filter module
   - [ ] Basic unit tests

### Medium Priority
3. **Documentation**
   - [ ] README setup instructions
   - [ ] API documentation
   - [ ] Configuration guide

4. **Database Setup** (if needed)
   - [ ] PostgreSQL schema
   - [ ] Trade history logging

### Low Priority
5. **Optimization**
   - [ ] Performance profiling
   - [ ] Memory optimization

---

## Technical Stack

- **Language:** Python 3.9+
- **Trading Platform:** cTrader
- **Main Libraries:** requests, python-dotenv, pytest, numpy, pandas
- **AI Models:** Mistral, Claude, Ollama
- **Testing:** pytest, pytest-cov
- **Code Quality:** black, flake8, mypy

---

## Dependencies

See `pyproject.toml` for the complete list:

**Runtime:**
- requests>=2.28.0
- python-dotenv>=0.20.0

**Development:**
- pytest>=7.0
- pytest-cov>=4.0
- black>=23.0
- flake8>=6.0
- mypy>=1.0

---

## Notes & Ideas

- Multi-timeframe analysis (1H, 4H, Daily)
- Telegram notifications for trade signals
- Web dashboard for monitoring
- Docker containerization for server deployment
- Automatic restart on errors

---

## Contact & Contributing

**Project Lead:** zalizman  
**Repository:** https://github.com/zalizman/matrixcbot  
**Issues:** https://github.com/zalizman/matrixcbot/issues
