please see https://github.com/openclimate-sg/whitepaper/wiki for the full whitepaper.

# Climate Action Tracking & Data Sharing
Open Climate Collabathon 2019 (Yale-NUS College, Singapore)

## Architecture
![](https://i.imgur.com/qHNWSL8.png)

### Blockchain for data availability + smart contract enforcement 
- data analysis smart contract
- encrypted emissions data (PoC: assume numerical and standard data format) 
- goal fulfilment smart contract
- publicly declared reductions goals
- stake deposit

### Trusted execution environment (TEE) for machine learning
- INPUT: encrypted data, ML weights
- COMPUTE: sentiment analysis for bad actor prediction, data cleaning, outlier detection
- OUTPUT: cleaned encrypted data, bad actors, updated ML weights

### Homomorphic statistical aggregation 
- INPUT: cleaned encrypted data
- COMPUTE: aggregate statistics on cleaned encrypted data
- OUTPUT: decrypted aggregate result, proof of decryption

### Incentives
- Reporting accurate data
- Making reduction commitments
- Fulfilling reduction commitments
