# Quantum_BB84_Encryption

The idea is to encode the sender's text(secret message) using the concept of interference. The secret message is encoded based on the cover file(a text sentence in this case). An interactive working implementation is available here: [https://share.streamlit.io/shisheerkaushik24/quantum-stegaayzer/app.py](https://share.streamlit.io/shisheerkaushik24/quantum-stegaayzer/app.py). 

We have chosen our cover file and the secret message to be in text formats to make it easier for new learners to understand the concept of quantum steganography while also trying it out interactively in a console. 

## Project Idea

We have implemented Quantum Steganography using qiskit in this project.   

![q stegalyzer](Data/dat0.png)

We have chosen our cover file and the secret message to be in text formats to make it easier for new learners to understand the concept of quantum steganography while also trying it out interactively in a console. 

## Implementation Details

The encoder circuit is based on 7 qubits but our interactive application has an option to create circuits based on the number of qubits selected and view them instantaneously.  

Here are some steps to interactively play with our application:

1. Choose the number of qubits using the slider. We would suggest that you choose 7 for the encoding and decoding scheme to work flawlessly. You can also test out other number of qubits to view the generated circuit.  

![no_of_qubits](Data/img2.png)

2. Enter the Secret message and press enter. For instance, let us try a letter, NOTE: Enter only small letters [i.e f,h,l, etc ]

![secret_msg](Data/dat1.PNG)

![secret_msg](Data/dat2.PNG)

Here, you can also view the generated circuit.

Above is the transpilated circuit generated with respect to the secret key entered, using the special gates during Quantum Simulation  

![secret_msg](Data/dat3.PNG)

3. This graph shows the output generated with respect the secret key entered

4. Upload a sentence where you wish to hide your message and press enter. NOTE: Enter only small words [i.e family,hindrance,lanquage, etc ]

![encode](Data/dat4.PNG)

5. Click on encode to view the encoded message

![encode](Data/dat5.PNG)

6. Then click on decode to finally view your original secret message

![decode](Data/dat6.PNG)

All the simulation was done qiskit sdk: [Secret key used: Qiskit]

a] Simulator

![decode](Data/img7.PNG)

The fig(a) graph selected is the output generated from the Quantum Simulator [ qasm_simulator]

b] Quantum Cumpter [ibmq-melbourne]

![decode](Data/img6.PNG)

The fig(b) graph slected is the output generated from the Real Quantum Computer [ ibmq-melbourne]

Contributor:

- [Shisheer S Kaushik](https://www.linkedin.com/in/shisheerkaushik24/)
