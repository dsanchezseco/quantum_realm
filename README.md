# Me learning Quantum Computing

## Install & Setup
```
brew install anaconda
echo "export PATH=\"/usr/local/anaconda3/bin:$PATH\"" >> ~/.zshrc
source ~/.zshrc

pip install qiskit
```

### IBMQ token for QComputer access

```
from qiskit import IBMQ
IBMQ.save_account('<API TOKEN>') # from https://quantum-computing.ibm.com/

IBMQ.load_account() # check everything is correcT
```

## Usage
```
jupyter notebooK
```
