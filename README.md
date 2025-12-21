# APIGuard

Intelligent API gateway with ML-powered rate limiting and threat detection.

## Overview

APIGuard is a smart API gateway that learns traffic patterns and automatically adjusts rate limits based on observed behavior. It provides real-time threat detection, request validation, and comprehensive analytics dashboards.

## Features

- **Adaptive Rate Limiting**: ML-based rate limit adjustments based on traffic patterns
- **Anomaly Detection**: Identifies unusual request patterns and potential attacks
- **Request Validation**: Schema-based validation for incoming requests
- **Threat Dashboard**: Real-time visualization of security events
- **Traffic Analysis**: Deep insights into API usage patterns
- **Auto-Scaling Limits**: Dynamic threshold adjustment during peak loads

## Tech Stack

### Languages
- **HTML** (1 file) - Static demo page with embedded JavaScript/CSS

### Demonstration Tech
This is a static HTML demo showcasing the concept. A production implementation would use:
- **Go** - High-performance gateway core
- **Redis** - Rate limit counters and caching
- **TensorFlow.js** - Pattern recognition models
- **PostgreSQL** - Analytics and audit logging
- **Grafana** - Metrics visualization

## Key Algorithms

- **Token Bucket**: Base rate limiting with burst allowance
- **Sliding Window**: Smoothed request counting
- **ARIMA Models**: Traffic pattern prediction
- **Isolation Forest**: Anomaly detection in request features

## Metrics Tracked

- Request rate per endpoint
- Latency percentiles (p50, p95, p99)
- Error rates by type
- Geographic distribution
- Client fingerprinting

## Demo

View the live demo at: https://danielminton.github.io/APIGuard/

## Author

Daniel Minton