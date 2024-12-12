# Malicious URLs API

## Overview
The Malicious URLs API provides access to a dataset of malicious and benign URLs. This dataset is curated to aid in the development of machine learning models to identify and block malicious URLs, thus preventing cybersecurity threats such as phishing, malware distribution, and defacement. 

The dataset includes over 650,000 URLs categorized as benign, defacement, phishing, or malware. It is a valuable resource for researchers, developers, and cybersecurity professionals working on URL threat detection and prevention.

---

## Content
The dataset includes:
- **Benign URLs**: 428,103 URLs that are safe and pose no threat.
- **Defacement URLs**: 96,457 URLs used for website defacement.
- **Phishing URLs**: 94,111 URLs designed for phishing attacks.
- **Malware URLs**: 32,520 URLs used for malware distribution.

### Data Sources
The dataset is compiled from multiple trusted sources:
1. **ISCX-URL-2016 Dataset**
2. **Malware Domain Blacklist Dataset**
3. **Faizan Git Repository**
4. **Phishtank Dataset**
5. **PhishStorm Dataset**

---

## Analysis Ideas
- **URL Classification**: Build machine learning models to classify URLs as malicious or benign.
- **Threat Analysis**: Study the distribution of different types of malicious URLs.
- **Source Insights**: Analyze trends in malicious URLs from specific sources.
- **Real-Time Detection**: Develop APIs or systems to identify and block malicious URLs in real-time.

---

## How to Access the API

### Prerequisites
- A RapidAPI account
- An API token (available through RapidAPI)

### Steps to Get Started

1. **Sign Up on RapidAPI**
   - Visit [RapidAPI](https://rapidapi.com/robotfa-robotfa-default/api/malicious-urls1) and create an account if you don’t already have one.

2. **Subscribe to the API**
   - Search for the "Malicious URLs API" and subscribe to it.

3. **Get Your API Token**
   - After subscribing, navigate to the API's "Endpoints" section and copy your unique API token.

4. **Integrate the API**
   - Use the token to authenticate your requests. Here’s an example in cURL:
     ```bash
     curl -X GET "https://malicious-urls1.p.rapidapi.com/list/1" \
     -H "X-RapidAPI-Key: YOUR_API_KEY" \
     -H "X-RapidAPI-Host: malicious-urls1.p.rapidapi.com"
     ```

---

## Example Endpoints

### 1. URL List
Retrieve detailed information about a specific URL:
```bash
GET /list/{page}
```


---

## Contribution
If you have suggestions or would like to contribute to this project, feel free to open an issue or submit a pull request.

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

