<div align="center">

![ouija logo](https://github.com/blackdreamai/ouija-ai/assets/17468438/caf539fa-f17a-42db-8331-fd142789b348)

# Ouija : God View for your Brain

<h3>

[Homepage](https://github.com/blackdreamai/ouija-ai) | [Documentation](/docs) | [Examples](/examples) | [Showcase](/docs/showcase.md)

</h3>

[![GitHub Repo stars](https://img.shields.io/github/stars/blackdreamai/ouija-ai)](https://github.com/blackdreamai/ouija-ai/stargazers)
[![Lines of code](https://img.shields.io/tokei/lines/github/blackdreamai/ouija-ai)](https://github.com/blackdreamai/ouija-ai)

</div>

---

**Ouija** is a proposed platform purposed towards democratizing access to personal neurological health. 

This will be done by aggregating diverse sets of data, including various high-fidelity neural scans, relevant medical reports, and real-time EEG monitoring via a non-invasive brain-computer interface to actualize a high-fiedlity "God View" of the users neurology, so that they can comprehend + proactively monitor their brain activity, functioning, integrity and any pertubations due to aging / damage.

I (Eros, bd.ai founder) will be the initial test case for this initaitve and my actual neurological and health data will open-sourced for use in this project. The gif at the top of this README is an axial MRI scan of my brain taken @ Stanford.

---

## Table of Contents
- Overview
- Core Features
- Technological Stack
- Data Sources
- Installation
- Dependencies
- Contributing
- License
- Contact & Support

## Core Features
- **Multi-Modal Data Integration**: Seamless integration of MRIs, PET scans, neurology reports, and more.
- **Real-Time Brain Monitoring**: Direct interfacing with OpenBCIs MarkIV BCI for instantaneous data capture and visualization.
- **Deep Analytics**: Dive deep into your data with our advanced machine learning algorithms and AI-powered insights.
- **Security & Privacy**: With HIPAA-compliant storage and GDPR adherence, rest assured your data is in safe hands.

## Stack
### Frontend
- React
- D3.js

### Backend
- Python Flask
- FastAPI

### Machine Learning
- PyTorch
- Scikit-learn

## Data Management
- PostgreSQL (HIPAA-compliant relational database)
- WebSocket (for handling real-time data streams from OpenBCIs MarkIV)

## Security
- HTTPS
- JWT

## Data Sources
- Brain / Cranial MRI Scans
- SPECT / PET Scans
- CW-NIRS Scans
- Neurologist Reports
- OpenBCIs MarkIV BCI headset (wet + dry electrodes)
- Historical Medical Data
  
## Installation
```py
# Navigate into the directory
cd Ouija

# Install backend dependencies
pip install -r requirements.txt

# Navigate to frontend directory
cd frontend

# Install frontend dependencies
npm install

# Run the backend and frontend as per the individual READMEs in their directories.
```

## Contributing
We highly value any and all adjacent expertise in:
- **Computational Neuroscience**: To refine our analytical models and make sense of complex neurological data.
- **Neurotech**: To enhance our real-time brain monitoring capabilities.
- **Deep Learning**: For advancing our data analytics and prediction systems.
- If you're passionate about these fields and wish to make a meaningful impact, please see our CONTRIBUTING.md for guidelines.

## License
**Ouija** is under the MIT License. Check out LICENSE.md for more details.

## Contact & Support
For inquiries, support, or collaborations, feel free to contact eros@blackdream.ai
