# CLADE - Chat Log Analyzer for Digital Evidence



[![GitHub release](https://img.shields.io/github/release/yourusername/clade)](https://github.com/yourusername/clade/releases)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/yourusername/clade/blob/main/LICENSE)
[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)
[![Downloads](https://img.shields.io/github/downloads/yourusername/clade/total)](https://github.com/yourusername/clade/releases)

CLADE is a professional forensic analysis tool designed to help investigators, law enforcement, and security professionals analyze chat logs from various messaging platforms.

## Features

### Core Functionality
- **Multi-Platform Support**:
  - WhatsApp: Parses `.txt` files exported from chats
  - Telegram: Analyzes `.json` format from Telegram Data Export
- **Advanced Log Parsing**:
  - Extracts timestamps, sender information, and message content
- **Comprehensive Visualization**:
  - Timeline view showing communication patterns
  - Frequency analysis of participants
  - Word clouds highlighting most common terms

### Investigative Tools
- **Keyword Detection**:
  - Predefined lists for crime-related terms
  - Custom keyword lists for case-specific analysis
- **Relationship Mapping**:
  - Network graphs showing communication patterns
- **Sentiment Analysis**:
  - Emotional tone detection (positive/negative/neutral)

## Installation

### Prerequisites
- Python 3.8+
- pip package manager


Supported Input Formats
Platform	Format	Sample Input
WhatsApp	Text	24/04/2023, 14:30 - John: Message
Telegram	JSON	{"date": "2023-04-24T14:30:00", "from": "John", "text": "Message"}

